# tilekit-preview

Technical preview of Tilekit.

- A node graph compute engine that powers the compute using [WebGPU](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API) with [rust-gpu](https://github.com/EmbarkStudios/rust-gpu), a compiler backend to generate compute shaders from Rust source code, and multicore CPU fallback using Rayon, a data parallelism library.
- [WebAssembly](https://webassembly.org/) is used both as a sandboxed runtime for the nodes and as a way to run the entire runtime.
- Local LLMs on nodes with [WONNX](https://github.com/webonnx/wonnx),  a GPU-accelerated ONNX inference run-time for web.

# Status

## Milestone 1

> Coming early 2024.

- [ ]  Node graph engine with executor interface
- [ ]  Tilekit CLI toolkit
- [ ]  Multithreaded Wasm executor as CPU fallback
- [ ]  Experimental GPGPU executor

## Milestone 2
- [ ] Performance profiler for compute
- [ ]  WONNX runtime integration with node graph engine for Local LLMs deployment

## Milestone 3
- [ ] Cross platform interoperable layer for the engine
---

# **Powered by Rust, WASM & WebGPU**

![image](https://github.com/feynon/tilekit-preview/assets/41825871/89648d1d-9652-4694-9307-0a7d87e8e274)
![image](https://github.com/feynon/tilekit-preview/assets/41825871/6af9d073-ffb0-4f46-8b12-43488c2d0263)
