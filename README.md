# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

requisites: Python 3.10+, Git.
 git clone git@github.com:<you>/lab01-starter.git
 cd lab01-starter
 python -m venv .venv
 source .venv/bin/activate # Windows: .venv\Scripts\Activate.ps1
 pip install -r requirements.txt
 pip install -e .


## Run

```powershell
python -m assistant "where is the IT helpdesk?"
```
Expected output: 'IT Helpdesk: room E.005, open Mon-Fri 08:00-17:00.'
## Test

```powershell
pytest -q
```
Expected output:'....      [100%]                                                                         
4 passed in 0.01s'
## Project structure

- `src/` - the assistant's source code
- `tests/` - pytest tests
- `data/` - data files (e.g. offices)
- `scripts/` - helper scripts (`check_env.py` checks your setup)
- `docs/` - documentation and worksheets
- `ui/` - user interface code
- `pyproject.toml` - package configuration
- `requirements.txt` - dependencies
