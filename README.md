# tilekit-preview

Technical preview of Tilekit.

- A node graph compute engine that powers the compute using [WebGPU](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API) with [rust-gpu](https://github.com/EmbarkStudios/rust-gpu), a compiler backend to generate compute shaders from Rust source code.
- [WebAssembly](https://webassembly.org/) is used both as a sandboxed runtime for the nodes, and as a way to run the entire runtime.
- Local LLMs on nodes with [WONNX](https://github.com/webonnx/wonnx),  a GPU-accelerated ONNX inference run-time for web.

