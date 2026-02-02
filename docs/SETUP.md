# Setup Guide

## Prerequisites
- Python 3.10+

## Development Setup
```bash
git clone https://github.com/vindicta-platform/WARScribe-CLI.git
cd WARScribe-CLI
python -m venv .venv
.venv\Scripts\activate
pip install -e ".[dev]"
```

## Running Tests
```powershell
pytest tests/ -v
```
