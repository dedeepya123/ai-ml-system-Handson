Phase 1 — PyTorch and neural network fundamentals
Current phase
Weeks 1–2 · Build the foundation
Implement:
- Linear Layer
- Activations and Softmax
- Cross-entropy loss
- LayerNorm and RMSNorm
- Dropout, residual connections and embeddings
- Backpropagation and gradient flow
Outcome: Explain how each component works, implement it in PyTorch, and test it against PyTorch's reference implementation.

Phase 2 — Transformer from scratch
Weeks 3–5 · Connect the components
Implement:
- Token embeddings and positional information
- Self-attention: Q, K and V
- Causal masking
- Multi-head attention
- Feed-forward network
- Transformer block and decoder
Outcome: Understand the complete data flow through a transformer and explain every major operation in code.
Phase 3 — Build a tiny language model
Weeks 6–7 · Train and generate
Implement:
- Tokenization and training data
- Next-token prediction
- Training loop, loss and optimizer
- Evaluation and checkpointing
- Autoregressive text generation
- Sampling: greedy, temperature and top-k
Outcome: Train a small decoder-only language model and generate text from it.
Phase 4 — Build an LLM inference engine
Weeks 8–10 · Your main specialization
Implement:
- Prefill versus decode
- KV cache and cache updates
- Cached versus uncached generation
- Attention masks and sequence lengths
- Batch inference
- Latency and throughput benchmarks
Outcome: Understand how inference works beyond the model's forward pass, including why caching matters for performance.
Phase 5 — Model optimization and performance
Weeks 11–13 · Measure and improve
Implement and investigate:
- Profiling and bottleneck identification
- Memory usage and compute cost
- FP32, FP16/BF16 and INT8 quantization concepts
- Numerical error and accuracy comparisons
- Operator-level and inference benchmarks
- Optimization trade-offs
Outcome: Demonstrate measured improvements and explain the trade-offs between latency, throughput, memory, and accuracy

Phase 6 — ML systems and deployment
Weeks 14–16 · Connect to production systems
Explore:
- Exporting PyTorch models to ONNX
- Inspecting and transforming computational graphs
- Runtime execution and operator compatibility
- CPU/GPU/NPU execution constraints
- Quantization and deployment pipelines
- Scheduling, batching and inference serving
Outcome: Connect model-level knowledge to the runtime and hardware challenges you encounter in edge AI.
