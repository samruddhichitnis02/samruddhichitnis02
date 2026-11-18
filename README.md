## Hi, I'm Samruddhi

**ML Systems / Inference Engineer** · Master's student at San José State University · San Jose, CA

I like finding out where the milliseconds go when a model runs on a GPU.

Most of my projects start with a simple question and end with a profiler open:

- **How much can one RTX 4090 actually serve?** About 6,300 tokens/s with vLLM, 106x a plain Hugging Face pipeline. Under heavy load the GPU wasn't the bottleneck; the Python API layer was. ([squeeze-the-4090](https://github.com/samruddhichitnis02/squeeze-the-4090))
- **Can I write a matrix multiply that gets close to cuBLAS?** 66% of it, after four versions and a lot of Nsight Compute. ([cuda-gemm-optimization-lab](https://github.com/samruddhichitnis02/cuda-gemm-optimization-lab))
- **Does hand-fusing a BERT graph beat TensorRT?** Not really. I cut the graph from 1,231 nodes to 599, and TensorRT was already doing most of it. ([FuseRT](https://github.com/samruddhichitnis02/FuseRT))
- **How far can a training step go with my own kernels?** From 12% to 64% MFU on a Llama-style model, using Triton, CUDA C++ and FP8. ([llm-training-performance](https://github.com/samruddhichitnis02/llm-training-performance))

Right now, for my master's capstone, I'm comparing five recent KV-cache compression methods on Llama-3.1-8B at the same memory budget, to see which ones still hold up on long documents. ([298a-kv-cache-compression](https://github.com/samruddhichitnis02/298a-kv-cache-compression))

I'm looking for Inference Engineer and ML Systems roles. Reach me at [samruddhichitnis02@gmail.com](mailto:samruddhichitnis02@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/samruddhi-chitnis/).

### Skills

**Languages:** Python, CUDA C++, C++, SQL, JavaScript/TypeScript

**Inference & GPU:** vLLM, TensorRT, TensorRT-LLM, ONNX / ONNX Runtime, Triton, CUDA, FP8 / INT4 / NVFP4 quantization, KV-cache compression, Nsight Systems & Compute, roofline analysis

**ML / Deep Learning:** PyTorch, Hugging Face Transformers, PEFT / LoRA, torch.compile, Diffusion models, Vision Transformers, JAX

**LLM Applications:** LangGraph, LangChain, RAG, FAISS, ChromaDB, cross-encoder reranking, Claude API, Ollama

**Frameworks & Data:** FastAPI, React, Gradio, PostgreSQL, MySQL, Hadoop MapReduce

**Hardware:** NVIDIA RTX 5090 (Blackwell), RTX 4090 (Ada), RTX 3060 (Ampere)
