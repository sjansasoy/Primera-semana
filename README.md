# Semana 1 — Python Avanzado (VS Code + .venv)

Proyecto de práctica para configurar entorno de trabajo en **Windows + VS Code** usando **Python 3.12.10** y **entorno virtual (.venv)**.

## Requisitos
- Python 3.12.10
- VS Code con extensiones: Python, Jupyter

## Configuración rápida (Windows, PowerShell)
```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt