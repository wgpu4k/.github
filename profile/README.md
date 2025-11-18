# wgpu4k: Foundational WebGPU Libraries for the Future

[![GitHub License](https://img.shields.io/badge/Licence-MIT-blue?style=plastic)]([LICENSE](https://en.wikipedia.org/wiki/MIT_License))
[![GitHub Stars](https://img.shields.io/github/stars/wgpu4k?style=social)](https://github.com/wgpu4k)

**wgpu4k** is an open-source organization dedicated to building **foundational libraries** and tools around **WebGPU**, the next-generation graphics and compute API for the web and native platforms. Our mission is to simplify GPU programming, unify access to WebGPU implementations (such as **[wgpu](https://github.com/gfx-rs/wgpu)** and **[Dawn](https://dawn.googlesource.com/dawn)**), and empower developers to harness the full potential of modern GPUs—whether for **graphics, machine learning, scientific computing, or beyond**.

---

## 🌟 Vision

### Why WebGPU?
WebGPU is a **low-level, high-performance API** designed for modern GPUs. It enables:
- **Cross-platform compatibility**: Run the same code on web browsers, desktop, and mobile devices.
- **Performance**: Direct access to GPU features for graphics and compute workloads.
- **Future-proofing**: Built to evolve with hardware and industry standards.

### Our Goal
At **wgpu4k**, we aim to:
1. **Democratize GPU programming**: Provide intuitive, high-level APIs that abstract the complexity of WebGPU.
2. **Unify the ecosystem**: Bridge the gap between WebGPU implementations (e.g., `wgpu`, `Dawn`) and platforms (JVM, Android, iOS, WASM).
3. **Enable diverse use cases**: From real-time rendering to GPU-accelerated machine learning, our libraries are designed to be versatile and powerful.
4. **Foster collaboration**: Build a community-driven ecosystem where developers, researchers, and engine maintainers can contribute and innovate.

---

## 🏗️ Projects

### Core Libraries
| Project               | Description                                                                                     | Platforms                     |
|-----------------------|-------------------------------------------------------------------------------------------------|-------------------------------|
| **[wgpu4k](https://github.com/wgpu4k/wgpu4k)** | High-level, Kotlin-friendly WebGPU API for graphics and compute. Ideal for application developers. | JVM, Android, iOS, WASM, Native |
| **[wgpu4k-native](https://github.com/wgpu4k/wgpu4k-native)** | Low-level Kotlin wrapper for **[wgpu-native](https://github.com/gfx-rs/wgpu-native)**. Designed for engine maintainers and advanced users. | JVM (FFM), Android (JNI), iOS (C interop) |

### Experimental & Community Projects
- **Cross-platform engines**: Integrations with game engines and frameworks (e.g., [KorGE](https://github.com/korlibs/korge)).
- **Machine learning toolkits**: GPU-accelerated layers and utilities for Kotlin/ML.
- **Build tools**: Plugins for automated binding generation (e.g., JNI, Panama).

---

## 🚀 Use Cases

### Graphics
- **Game development**: Build cross-platform 2D/3D engines with WebGPU as the backend.
- **Interactive media**: Real-time visualizations, VR/AR, and creative coding.

### Compute
- **Machine learning**: Accelerate inference and training with WebGPU compute shaders.
- **Scientific computing**: Offload simulations and data processing to the GPU.

### Cross-Platform Development
- **Write once, deploy anywhere**: Target desktop, mobile, and web from a single Kotlin codebase.

---

## 🛠️ Get Involved

### For Developers
- **Start coding**: Explore our [repositories](#projects) and check out the examples.
- **Contribute**: Submit issues, suggest features, or open pull requests.
- **Join the discussion**: Share ideas and ask questions in [GitHub Discussions](https://github.com/wgpu4k/wgpu4k/discussions).

### For Engine Maintainers
- **Integrate wgpu4k-native**: Use our low-level bindings to add WebGPU support to your engine.
- **Collaborate**: Partner with us to improve cross-platform compatibility.

### For Researchers
- **Experiment**: Leverage WebGPU for GPU-accelerated research in ML, physics, or data science.
- **Publish**: Share your findings and tools with the community.

---

## 💡 Why Join wgpu4k?
WebGPU is the future of GPU programming. **wgpu4k** makes it **accessible, portable, and powerful**—so you can focus on building the next generation of applications, games, and tools.

🔗 **Explore our projects** → [wgpu4k/wgpu4k](https://github.com/wgpu4k/wgpu4k) | [wgpu4k/wgpu4k-native](https://github.com/wgpu4k/wgpu4k-native)
💬 **Join the conversation** → [GitHub Discussions](https://github.com/wgpu4k/wgpu4k/discussions)

---
*Let’s build the future of GPU programming—together.*
