## Eigengram Protocol

Persistent, cross-session, cross-model KV cache semantic fingerprinting
for large language models.

The Eigengram Protocol defines a compact binary format (.eng) for storing
Fourier-decomposed fingerprints of LLM KV cache states, enabling:

- **Persistent memory** across LLM sessions
- **Cross-model retrieval** (99.5% recall, Llama/Qwen validated)
- **O(log N) search** via HNSW approximate nearest-neighbor indexing
- **Confidence-scored results** (HIGH/MEDIUM/LOW) for uncertainty-aware retrieval

### Repositories
| Repo | Description |
|------|-------------|
| [eigengram](https://github.com/eigengram-org/eigengram) | Core protocol |
| [eigengram-python](https://github.com/eigengram-org/eigengram-python) | Python SDK |
| [eigengram-js](https://github.com/eigengram-org/eigengram-js) | JS/TS SDK |
| [eigengram-spec](https://github.com/eigengram-org/eigengram-spec) | Format spec |

**Status:** Pre-release · Apache 2.0
