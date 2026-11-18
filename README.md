## Hi, I'm Samruddhi

**ML Systems / Inference Engineer** · Master's student at San José State University · San Jose, CA

I make LLMs run faster, cheaper and in less GPU memory, and I back every claim with numbers measured on real hardware.

- Pushed **6,272 tokens/s** out of a single RTX 4090 with vLLM, **106x** a plain Hugging Face pipeline → [squeeze-the-4090](https://github.com/samruddhichitnis02/squeeze-the-4090)
- Took a Llama-style model from **12% to 64% MFU** with hand-written Triton/CUDA kernels and FP8 → [llm-training-performance](https://github.com/samruddhichitnis02/llm-training-performance)
- Wrote a CUDA matrix-multiply kernel from scratch that reaches **66% of cuBLAS** → [cuda-gemm-optimization-lab](https://github.com/samruddhichitnis02/cuda-gemm-optimization-lab)
- Cut BERT's inference graph **in half (1,231 → 599 nodes)** with custom ONNX fusion passes, checked against TensorRT → [FuseRT](https://github.com/samruddhichitnis02/FuseRT)
- Now: shrinking the **KV cache** of Llama-3.1-8B for long-context inference (master's capstone) → [298a-kv-cache-compression](https://github.com/samruddhichitnis02/298a-kv-cache-compression)
- Open to Inference Engineer, ML Systems and AI Engineer roles
- Reach me: [samruddhichitnis02@gmail.com](mailto:samruddhichitnis02@gmail.com) · [LinkedIn](https://www.linkedin.com/in/samruddhi-chitnis/)

### Skills

**Languages:** Python, CUDA C++, C++, SQL, JavaScript/TypeScript

**Inference & GPU:** vLLM, TensorRT, TensorRT-LLM, ONNX / ONNX Runtime, Triton, CUDA, FP8 / INT4 / NVFP4 quantization, KV-cache compression, Nsight Systems & Compute, roofline analysis

**ML / Deep Learning:** PyTorch, Hugging Face Transformers, PEFT / LoRA, torch.compile, Diffusion models, Vision Transformers, JAX

**LLM Applications:** LangGraph, LangChain, RAG, FAISS, ChromaDB, cross-encoder reranking, Claude API, Ollama

**Frameworks & Data:** FastAPI, React, Gradio, PostgreSQL, MySQL, Hadoop MapReduce

**Hardware:** NVIDIA RTX 5090 (Blackwell), RTX 4090 (Ada), RTX 3060 (Ampere)
