## Hi, I'm Samruddhi

I wrote my first machine learning code back in 2019: small Python programs, a chatbot, and image tricks like edge detection with OpenCV. For years my goal was always the same: get the model to work.

Then I started building with large language models, the kind behind ChatGPT, and a different question kept bothering me. Why are these models so slow and so expensive to run? When millions of people use one, every extra half-second and every extra graphics card turns into real money.

So I went one layer down, to the graphics card (GPU), the chip that does all of the math. That is what I work on now: making AI models run faster and cheaper on the hardware they already have.

I'm a Master's student at San José State University in San Jose, CA, looking for **Inference Engineer** and **ML Systems** roles.

### What I've built

**How many people can one graphics card serve?**
I took a single gaming GPU and tested different ways of running an AI model on it. With the right setup it produced about **100 times more text per second** than the standard approach. The surprise: under heavy traffic the GPU wasn't the problem. The software handing it the requests was.
[squeeze-the-4090](https://github.com/samruddhichitnis02/squeeze-the-4090)

**Can I beat the experts at their own math?**
Almost everything an AI model does comes down to multiplying huge grids of numbers. NVIDIA has a library for this that its own engineers hand-tuned for years. I wrote my own version from scratch and rewrote it four times. It ended up **5 times faster** than my first try and reached **two-thirds of NVIDIA's speed**.
[cuda-gemm-optimization-lab](https://github.com/samruddhichitnis02/cuda-gemm-optimization-lab)

**What if a model had fewer steps?**
A model runs as a long chain of small steps. I wrote a tool that merges steps together and cut one model from **1,231 steps to 599**. Then I learned something useful: NVIDIA's own compiler was already doing most of this. So I measured what it still left slow, which is where custom code can actually help.
[FuseRT](https://github.com/samruddhichitnis02/FuseRT)

**Why is the GPU sitting idle?**
While training a small ChatGPT-style model, I found the GPU was doing useful work only **12% of the time**. By writing my own code for the slowest parts and using smaller number formats, I got it to **64%**, making each training step **5 times faster**.
[llm-training-performance](https://github.com/samruddhichitnis02/llm-training-performance)

**Now: helping AI read long documents without running out of memory**
When a chatbot reads a long document, it keeps notes on every word, and those notes quickly fill up the GPU's memory. For my master's capstone, I'm comparing five brand-new ways of shrinking those notes, to find out which ones still give the right answers.
[298a-kv-cache-compression](https://github.com/samruddhichitnis02/298a-kv-cache-compression)

### Tools I use

**Inference & GPU:** CUDA C++, Triton, vLLM, TensorRT / TensorRT-LLM, ONNX Runtime, FP8 / INT4 quantization, Nsight Systems & Compute

**ML:** PyTorch, torch.compile, Hugging Face Transformers, PEFT / LoRA, JAX

**LLM apps:** LangGraph, LangChain, RAG, FAISS, ChromaDB, FastAPI

**Languages:** Python, C++, SQL, TypeScript

### Say hello

[samruddhichitnis02@gmail.com](mailto:samruddhichitnis02@gmail.com) · [LinkedIn](https://www.linkedin.com/in/samruddhi-chitnis/)
