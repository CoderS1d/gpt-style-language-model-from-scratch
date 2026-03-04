# gpt-style-language-model-from-scratch
 What This Project Includes

- **Character-level tokenizer** (stoi/itos, encode/decode)
- Tiny Shakespeare data loading + train/val split
- GPT-style architecture:
  - Token + positional embeddings
  - Multi-head self-attention (causal masking)
  - Feed-forward network (MLP)
  - Residual connections + LayerNorm
  - Stacked Transformer blocks
- Training loop with evaluation + loss tracking
- Text generation from a trained model

---

## 🧠 Model + Training Details (from the starter notebook)

Default hyperparameters (may be tuned depending on your implementation):
- `batch_size = 64`
- `block_size = 256` (context length)
- `n_embd = 128` (embedding size)
- `n_head = 4` (attention heads)
- `n_layer = 4` (Transformer blocks)
- `dropout = 0.1`
- `learning_rate = 3e-4`

Dataset:
- **Tiny Shakespeare** (downloaded automatically in the notebook)
