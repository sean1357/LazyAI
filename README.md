# LazyAI
Graphical user interface (GUI) designed to streamline local AI model execution.


Software Name: 
Ollama Engine Switcher (OES)
Product Overview 
Ollama Engine Switcher is a lightweight, intuitive graphical user interface (GUI) designed to streamline local AI model execution. It acts as a control center for the background Ollama service, eliminating the need for command-line interactions. The software is built specifically for developers, researchers, and creators who manage multi-GPU systems and need precise control over their hardware allocation.

Key Features
  Background Service Management: Start, stop, and restart the core Ollama background daemon with a single click. A persistent system tray icon provides real-time status updates (Active, Idle, or Stopped) without cluttering the taskbar.
  
  Dynamic GPU Selection: The standout feature is an interactive hardware mapper. The GUI automatically detects all installed graphics cards (NVIDIA CUDA or AMD ROCm). Users can assign a specific GPU to run a model or distribute layers across multiple cards using a simple dropdown or checkbox menu.
  
  VRAM & Performance Monitoring: Includes live telemetry displays showing video memory (VRAM) usage, core temperature, and compute load for each available GPU. This prevents out-of-memory errors before launching large language models (LLMs).
  
  One-Click Model Library: Browse, download, and delete official Ollama models (such as Llama, Mistral, or Phi) directly within the interface. It displays download progress bars and disk space requirements.
  
  Context Control Panel: Easily configure runtime parameters like context window size, temperature, and system prompts through a visual settings tab before deploying the background service.
  
  Target AudienceThis utility is perfect for users running workstation setups with multiple GPUs (e.g., an integrated GPU alongside dedicated cards, or dual-RTX setups) who want to isolate their AI workloads from their primary display or gaming hardware.
