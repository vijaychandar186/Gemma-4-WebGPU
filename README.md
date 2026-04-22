# Gemma 4 WebGPU

An in-browser multimodal AI application powered by Gemma 4. This project runs directly in your web browser leveraging WebGPU for accelerated local inference, ensuring high performance without the need for external APIs or server-side processing.

## Features

- **Local Execution:** Runs entirely in your browser using WebGPU. No data leaves your machine.
- **Multimodal Capabilities:** Supports text and multimodal interactions powered by the Gemma 4 architecture.
- **Fast and Responsive:** Achieves low-latency inference by utilizing your device's native GPU processing power.

## Getting Started

Since this is a fully static web application, you can run it using any local web server.

### Prerequisites

- A modern web browser with WebGPU support (e.g., latest Chrome, Edge, or Firefox Nightly).
- WebGPU may need to be explicitly enabled in your browser flags depending on your version (`chrome://flags/#enable-unsafe-webgpu`).

### Running the App

This project consists of pre-built static files. You just need to serve them.

1. Navigate to the project directory:
   ```bash
   cd Gemma-4-WebGPU
   ```
2. Start a local web server. For example, using Python:
   ```bash
   python -m http.server 8000
   ```
   Or using node `serve`:
   ```bash
   npx serve .
   ```
3. Open your browser and navigate to `http://localhost:8000` (or the port specified by your web server).

## Technologies Built With

- WebGPU 
- Vite 
- React / JavaScript (Compiled)
- KaTeX (for mathematical formulas)

## Privacy

Because the model runs entirely locally in your browser, your data and conversations are completely private and never sent to a remote server. 

## Attribution

This project is originally based on [webml-community/Gemma-4-WebGPU](http://huggingface.co/spaces/webml-community/Gemma-4-WebGPU) from Hugging Face Spaces.