# AEPL Logger

AEPL Logger is a lightweight Tkinter-based serial logging tool with macro execution and validation support.

## Requirements
- Python 3.8+ (3.10+ recommended)
- `pyserial` (listed in `requirements.txt`)

## Setup
1. Create and activate a virtual environment:
   - Windows PowerShell:
     `python -m venv .venv`
     `.\.venv\Scripts\Activate.ps1`
2. Install dependencies:
   `python -m pip install -r requirements.txt`

## Run
- `python .\main.py`

## Project Layout
- `ui.py`: Tkinter UI and main window logic
- `serial_handler.py`: Serial port monitoring and log capture
- `macro_executor.py`: Macro runner and validation
- `Assets/`: Icons and device config
- `Macro_files/`: Sample TTL macro files
- `logs/`: Auto-generated log files (created at runtime)

## Notes
- Log files are stored under `logs/YYYY-MM-DD/`.
- `Assets/device.json` is used to validate responses during macro execution.
