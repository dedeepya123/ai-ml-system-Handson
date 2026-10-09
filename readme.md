# AI & ML Systems Lab

A hands-on  into deep learning, Transformer models, LLM inference, and ML systems through practical implementations and experiments.

The goal is to understand not just how to use machine learning frameworks, but how models work internally, how inference is executed, and how performance can be measured and improved.

## Goals

- Build strong practical skills with PyTorch.
- Implement fundamental deep learning components and understand their internals.
- Build a decoder-only Transformer and a small language model.
- Develop a simplified LLM inference engine.
- Explore KV caching, decoding, memory usage, and inference performance.
- Experiment with quantization, profiling, and model optimization.
- Understand model export, ONNX graphs, runtimes, and hardware constraints.
- Document experiments and lessons learned through technical blogs.

## Roadmap

### 01. PyTorch Fundamentals
Tensors, autograd, `nn.Module`, training loops, optimizers, and model debugging.

### 02. Deep Learning Components
Linear layers, activations, loss functions, normalization, embeddings, and residual connections.

### 03. Transformer from Scratch
Attention, causal masking, positional encoding, RoPE, GQA, RMSNorm, and Transformer blocks.

### 04. Tiny Language Model
Tokenization, training, next-token prediction, and text generation.

### 05. LLM Inference Engine
Prefill, decode, KV cache, sampling, and token-by-token generation.

### 06. Model Optimization
Profiling, memory and compute analysis, precision, quantization, and performance benchmarking.

### 07. Runtime and ML Systems
ONNX export, graph transformations, runtime execution, batching, and inference system design.

## Engineering Principles

- Implement before writing extensive notes.
- Understand the reasoning behind each implementation.
- Test against reference implementations where possible.
- Measure performance instead of assuming an optimization works.
- Record experiments, limitations, and lessons learned.
- Keep the code readable, reproducible, and well documented.

## Project Structure

The repository will evolve as implementations are added.

```text
ai-ml-systems-lab/
├── 01-pytorch-fundamentals/
├── 02-deep-learning-components/
├── 03-transformer-from-scratch/
├── 04-tiny-llm/
├── 05-llm-inference-engine/
├── 06-model-optimization/
├── 07-ml-systems/
└── README.md
```

## Learning Notes and Blogs

Technical articles will grow out of actual implementations, experiments, and debugging sessions. Each article should connect the underlying concepts to code and measured results.

## Status

Currently setting up the repository and beginning the PyTorch implementation track.

This is an ongoing learning and engineering project. Implementations and results will be added incrementally.
