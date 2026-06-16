# openclaw-ug

> A ready-to-use Uyghur AI control center—no need for high-end GPU.
   Built on [OpenClaw](https://github.com/openclaw/openclaw), providing a truly native Uyghur language LLM experience.

## News
After extensive testing and feedback, openclaw_ug now stable and reliable! The code has been released in [Release]([https://github.com/TaresaPerre/openclaw-ug/releases/]). Please download and install it. After extracting the folder, use the following command for one-click installation:
```powershell
powershell -ExecutionPolicy Bypass -File openclaw-install.ps1
```
For detailed installation instructions, please refer to OpenClaw Installation Guide.pdf.


## **Want to try it first?**

If you'd like to download, please contact me via the email below. I'll provide you with a ready-to-run installer—one-click install and use.

📧  **Contact**  

[Taresa_Perre@outlook.com](mailto:Taresa_Perre@outlook.com)

Explanation

    We hope to gather user feedback and refine the application on a small scale before releasing the public download link. We welcome your active participation and feedback!

## What is OpenClaw?

OpenClaw is a powerful local AI assistant framework with complex tool orchestration and workflow integration capabilities. This project provides a specially optimized **native Windows build**, with a key focus on Uyghur language —complete UI localization and deeply tuned prompt engineering, rather than simple surface-level translation.

## Features

- **Zero-config deployment**: All dependencies statically packaged—download, extract, and run.
- **Native Uyghur language support**: Complete UI translation, backend optimized for Uyghur language logic.
- **Full OpenClaw features**: Natural language tool calling, local file access, Telegram API integration, etc.
- **Complete privacy protection**: Fully offline operation—your data never leaves your device.

## System Requirements

A lightweight architecture that separates computing from local hardware, running smoothly on standard office equipment:

- **Operating System**: Windows 10 / 11 (64bit)
- **Memory**: ≥ 4GB
- **Storage**: ≥ 10GB available space
- **Network**: Internet connection required for LLM API requests
- *macOS and Linux versions coming soon.*

## Quick Start (3 minutes)

No coding required.
### Step 1: Download and Extract

Extract the downloaded file to a local directory.

> **Note**: Avoid spaces in the extraction path (e.g., `D:\OpenClaw\` is fine; `D:\My Folder\Open Claw\` is not).

### Step 2: Initialize

Open PowerShell in the extraction directory and run:
```powershell

powershell -ExecutionPolicy Bypass -File openclaw-install.ps1

```

`Bypass` simply allows Windows to run the installation script—this is standard practice and perfectly safe.

### Step 3: Configure and Launch

The web interface will automatically open at `http://127.0.0.1:18789/chat`.

1. **Get an API key**: Register for free at [NVIDIA NIM](https://build.nvidia.com/settings/api-keys) and get credits to use.
2. **Enter the key**: Paste the key into the configuration panel.
3. **Start chatting**: Uyghur language mode is enabled by default.

If you have a local model, select the corresponding vLLM or Ollama framework name in the model provider, use your local URL port number , and API key for sk-any.

> **Local Model (Optional)**  
> If you have already deployed a model locally, select the corresponding framework under "Model Provider" and fill in the relevant information. For example, for a model deployed using the vLLM framework:  
> - **vLLM**: Select `vLLM`, enter your local service address (e.g., `http://127.0.0.1:8000/v1`) in the **URL**, and enter any placeholder (e.g., `sk-any`) for the **API Key**.

For complete documentation, please refer to the accompanying "OpenClaw Usage Tutorial.pdf".

## License

MIT License—free to use, modify, and distribute.

## Acknowledgements

- [OpenClaw](https://github.com/openclaw/openclaw) — Elegant, powerful open-source AI assistant platform
- [Peter Steinberger](https://github.com/steipete) — OpenClaw founder
## Feedback & Contributions

Found translation issues, bugs, or have other feedback? Please submit [Issue](your-issues-link) to my email [Taresa_Perre@outlook.com](mailto:Taresa_Perre@outlook.com), and attach screenshots if possible.
