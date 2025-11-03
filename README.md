[README.md](https://github.com/user-attachments/files/23298759/README.md)
STEChecker Offline Starter (minimal)

- Offline, CPU-only ASD-STE100 analyzer & rewriter.
- Rule-based; optional local LLM (llama-cpp-python + GGUF).
- CLI: src\main_cli.py  |  GUI: src\gui.py
- Build: build.ps1

Quick start (dev):
  python -m venv .venv
  . .venv\Scripts\Activate.ps1
  pip install --upgrade pip
  pip install pyinstaller
  python src\main_cli.py --sentence "Identifying the module the part may be assigned to."
