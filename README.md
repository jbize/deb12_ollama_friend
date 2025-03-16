# deb12_ollama_friend
# AI Friend Project

Welcome to the AI Friend Project! This setup deploys PyTorch, Ollama, and CUDA on Debian 12 to bring "Amy" to life. Optimized for a GTX 750 Ti, it’s portable across any Debian 12 box with the same GPU.

## Features
- **PyTorch 2.3.1+cu121**: GPU-accelerated ML with CUDA 12.3.
- **Ollama 0.6.1**: Runs `phi:latest` for local LLM chats.
- **Scripts**: `PyTorch_small.py` (GPU test), `friend.py` (Amy’s voice).
- **Hardware**: Tested on i7-4770, GTX 750 Ti, 16GB RAM, 1TB SSD.

## Prerequisites
- Debian 12 (fresh install).
- Internet access.
- Sudo privileges.

## Installation
1. **Prepare Files**:
   - Copy `install_py_ollama_deb12.sh` to your home dir.
   - `chmod +x install_py_ollama_deb12.sh`.

2. **Install**:
   ```bash
   sudo ./install_py_ollama_deb12.sh --install
   source ~/.bashrc

