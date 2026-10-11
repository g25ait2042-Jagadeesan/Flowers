G25AIT2042 flowers — Tokenization & Vectorization

This notebook is the original *flowers* neural network, rebuilt so that:

1. **Tokenization** — each flower is stored as a text record (e.g. `"length: 3 width: 1.5 type: red"`) and split into tokens.
2. **Vocabulary & encoding** — tokens are mapped to integer IDs, and labels (`red`/`blue`) are encoded as 1/0.
3. **Vectorization** — the tokens become a NumPy feature matrix `X` and label vector `y`, and every loop in the original code (cost, training, decision-boundary grid) is replaced with vectorized NumPy matrix operations.



