# tilekit-preview

The scope is to simplify running high-performance compute use cases locally on the web with Rust by leveraging WASM and WebGPU, without the need to learn any shader language.

# Status

## Milestone 0
> Communicate the project's vision, scope, and ongoing roadmap
- [ ] Design a layered landing page

## Milestone 1
> Make multicore CPU work with experimental GPU support.

- [ ]  Node graph engine with executor interface
- [ ]  Multithreaded Wasm executor for CPU compute
- [ ]  Experimental GPU executor
- [ ]  Profiler
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

---

# Contributor guide

The repository will be open to contributors after Milestone 1 is shipped with new documentation. Until then, we have a couple of listed resources for people who are new to familiarize themselves with WASM and WebGPU.

## Learning WebAssembly

- https://www.neversaw.us/2023/05/10/understanding-wasm/part1/virtualization/
- https://evilmartians.com/chronicles/hands-on-webassembly-try-the-basics
- https://rsms.me/wasm-intro
- https://juejin.cn/post/7013286944553566215
- https://rustwasm.github.io/book/
- https://github.com/EmNudge/watlings
- https://hacks.mozilla.org/2017/02/a-cartoon-intro-to-webassembly/
- https://hacks.mozilla.org/2017/07/creating-a-webassembly-module-instance-with-javascript/
- https://hacks.mozilla.org/2018/10/webassemblys-post-mvp-future/

## Learning WebGPU

- https://surma.dev/things/webgpu/
- https://developer.chrome.com/articles/gpu-compute/
- https://codelabs.developers.google.com/your-first-webgpu-app#7
- https://webgpufundamentals.org/webgpu/lessons/webgpu-fundamentals.html
- https://webgpufundamentals.org/webgpu/lessons/webgpu-compute-shaders.html
- https://developer.chrome.com/blog/webgpu-cross-platform/
- https://doc.babylonjs.com/features/featuresDeepDive/materials/shaders/computeShader
- https://cohost.org/mcc/post/1406157-i-want-to-talk-about
- https://sotrh.github.io/learn-wgpu/
