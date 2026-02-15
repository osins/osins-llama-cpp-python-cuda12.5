# llama-cpp-python

This repository is currently customized for RTX 3060 graphics card.
This repository is currently targeted for Windows 11 operating system.

## Compilation Environment Setup

To successfully build and compile, you must install the following software in order:

1. **Visual Studio 2022 Community Edition** - Install this development environment first
2. **CUDA 12.5** - Install after Visual Studio
3. **Nsight Visual Studio Edition** - Install nsight_visual_studio_edition-windows-x86_64-2024.2.1.24155_34374119.msi
4. **Python 3.11.9** - Install the specified Python version

## Packaging and Installation

To build and install this package on your local machine, run the following command:

```bash
pip install . --no-build-isolation --config-settings=cmake.args="-DGGML_CUDA=ON"
```

This project is a Python binding implementation for `llama.cpp`. For detailed usage instructions and complete documentation about `llama-cpp-python`, please visit the original repository:

**Original Repository**: [https://github.com/abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python)

We do not provide specific instructions on how to use `llama-cpp-python` here.