## Hi, I'm Samruddhi

**ML Systems / Inference Engineer** · Master's student at San José State University · San Jose, CA

- Making LLMs faster and cheaper to serve: GPU kernels, quantization, KV-cache compression and serving engines
- Working with vLLM, TensorRT / TensorRT-LLM, Triton, CUDA C++, FP8/INT4 and Nsight profiling
- Every result I publish is measured, logged and reproducible, from a single RTX 4090 up to an RTX 5090
- Open to Inference Engineer, ML Systems and AI Engineer roles
- Reach me: [samruddhichitnis02@gmail.com](mailto:samruddhichitnis02@gmail.com) · [LinkedIn](https://www.linkedin.com/in/samruddhi-chitnis/)


### Featured work

| Project | What it shows |
|---|---|
| [squeeze-the-4090](https://github.com/samruddhichitnis02/squeeze-the-4090) | LLM serving on one RTX 4090: HF vs vLLM vs TensorRT-LLM, FP8/INT4, load tests. vLLM reaches 6,272 tok/s at batch 32 (106x the HF baseline) |
| [FuseRT](https://github.com/samruddhichitnis02/FuseRT) | ONNX graph optimizer for BERT inference: custom fusion passes (1,231 → 599 nodes), validated against TensorRT and profiled with Nsight |
| [298a-kv-cache-compression](https://github.com/samruddhichitnis02/298a-kv-cache-compression) | Five 2026 KV-cache compression methods compared at equal memory on Llama-3.1-8B (LongBench, RULER) |
| [cuda-gemm-optimization-lab](https://github.com/samruddhichitnis02/cuda-gemm-optimization-lab) | Hand-written CUDA GEMM, 5.2x faster than naive and 66% of cuBLAS; fused Triton kernel 1.56x faster than PyTorch |
| [llm-training-performance](https://github.com/samruddhichitnis02/llm-training-performance) | Llama-style model from 12% to 64% MFU on Blackwell with fused Triton/CUDA kernels and FP8; roofline model within 4.6% error |

### Skills

**Languages:** Python, CUDA C++, C++, SQL, JavaScript/TypeScript

**Inference & GPU:** vLLM, TensorRT, TensorRT-LLM, ONNX / ONNX Runtime, Triton, CUDA, FP8 / INT4 / NVFP4 quantization, KV-cache compression, Nsight Systems & Compute, roofline analysis

**ML / Deep Learning:** PyTorch, Hugging Face Transformers, PEFT / LoRA, torch.compile, Diffusion models, Vision Transformers, JAX

**LLM Applications:** LangGraph, LangChain, RAG, FAISS, ChromaDB, cross-encoder reranking, Claude API, Ollama

**Frameworks & Data:** FastAPI, React, Gradio, PostgreSQL, MySQL, Hadoop MapReduce

**Hardware:** NVIDIA RTX 5090 (Blackwell), RTX 4090 (Ada), RTX 3060 (Ampere)
