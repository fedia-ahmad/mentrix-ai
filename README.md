# MENTRIX AI

## Project Overview
MENTRIX AI is an AI-assisted teaching assistant project designed to support attendance management, quiz generation, AI-assisted grading, and student data management.

## Environment
- Python 3.12 (64-bit)
- PyTorch with CUDA support
- JupyterLab

## Setup
1. Create a virtual environment: `python -m venv .venv`
2. Activate it on Windows: `.venv\Scripts\activate`
3. Install dependencies:
   `python -m pip install -r requirements.txt --extra-index-url https://download.pytorch.org/whl/cu126`
4. Verify dependencies: `python -m pip check`
5. Launch JupyterLab: `python -m jupyterlab`
6. Open `notebooks/00_environment_check.ipynb` and select the project Python kernel.

Note: This environment was tested on Windows 10 with Python 3.12 and an NVIDIA GPU supporting CUDA.

## Project Structure
- `notebooks/`: Experiments and environment tests
- `src/`: Source code
- `configs/`: Model settings
- `results/`: Test results

## Notes
Do not commit API keys, student data, or local model files to Git.