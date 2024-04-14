# APTMoE Predictor

Collecting the results of the expert gating process by hacking the `transformers` library.

Modified files:

- `./transformers/src/transformers/models/mixtral/modeling_mixtral.py`
- `./transformers/src/transformers/models/nllb_moe/modeling_nllb_moe.py`

## Usage

```bash
pip install ./transformers

# Making data (Get model weights and data before)
python mkdata_mixtral.py
# or
python mkdata_nllb.py

# Training
python pregate_mixtral.py
# or
python pregate_nllb.py
```
