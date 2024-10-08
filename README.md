# WebLLM Chatbot

A web-based chatbot application utilizing the WebLLM inference engine to run large language models directly in the browser with hardware acceleration. This chatbot operates entirely within your browser, requiring no server support, and is accelerated using WebGPU.

## Features

- **In-Browser Inference**: Runs language model inference directly in the browser, eliminating the need for server-side processing. Powered by WebLLM and WebGPU for high-performance computation.
- **Streaming & Real-Time Interactions**: Supports streaming chat completions, providing real-time responses for interactive applications like chatbots and virtual assistants.
- **User-Friendly Interface**: Features a modern chat interface with a responsive design, suitable for both desktop and mobile devices.
- **Interactive Background**: Includes an engaging Particle.js background for an enhanced user experience.

## How It Works

WebLLM is a high-performance in-browser LLM inference engine that brings language model inference directly onto web browsers with hardware acceleration. Everything runs inside the browser with no server support and is accelerated with WebGPU.

### Model Loading

Upon first use, the model files are fetched and cached within your browser. This process might take some time depending on your internet connection. Subsequent uses will be faster due to caching.

### MLC Engine

The application uses the MLC engine to execute the language model efficiently within the browser environment.

## Getting Started

### Prerequisites

- A modern web browser with WebGPU support (e.g., the latest version of Chrome, Edge, or Firefox Nightly).
- An active internet connection for initial model loading.

### Installation

#### Clone the Repository
```bash
git clone https://github.com/nullpwn/webllm-chatbot.git](https://github.com/nullpwn/MLC-Chat.git
