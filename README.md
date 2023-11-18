# tilekit-preview

The scope is to simplify running high-performance compute use cases locally on the web with Rust by leveraging WASM and WebGPU, without the need to learn any shader language.

# Status

## Milestone 1
> Make multicore CPU work with experimental GPU support.

- [ ]  Node graph engine with executor interface
- [ ]  Multithreaded Wasm executor for CPU compute
- [ ]  Experimental GPU executor
- [ ]  CLI toolkit with Vite bundler plugin

## Milestone 2
> Node graph API interface for sharing compute operations portably.
- [ ]  Node graph API reference documentation

## Milestone 3
> Local LLM story.
- [ ]  Burn framework backends' integration with node graph engine for Local LLMs deployment

## Milestone 4
> Support for native targets
- [ ] Cross-platform interoperable layer for the engine
      
## Milestone 5
> Hosting support for larger models with Cloudflare AI
- [ ]  Cloudflare AI deployment for larger LLM models through a fork to Burn's import ONNX model crate


---

# Architecture

<img width="867" alt="tilekit-arch (4)" src="https://github.com/feynon/tilekit-preview/assets/41825871/129ae26f-baa4-4f35-af66-31cb928669d6">


## Powered by Rust, WASM & WebGPU

![image](https://github.com/feynon/tilekit-preview/assets/41825871/89648d1d-9652-4694-9307-0a7d87e8e274)
![image](https://github.com/feynon/tilekit-preview/assets/41825871/6af9d073-ffb0-4f46-8b12-43488c2d0263)
