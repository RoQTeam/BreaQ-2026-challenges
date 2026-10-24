# BreaQ 2026 — Challenge 2: The Treacherous Transpiler

Unzip this entire directory and keep the notebook, `team_instance.json`, and
`breaq_ch2/` together. Challenge 1 is not a prerequisite.

Use Python 3.10–3.13; exact tested versions are recorded in the organizer release validation.
Create a clean environment to avoid conflicting Qiskit generations:

```bash
python -m venv .venv
# Linux/macOS:
source .venv/bin/activate
# Windows PowerShell instead: .venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m jupyter lab
```

Open `02_treacherous_transpiler.ipynb` in this directory and select the environment's Python kernel.
All execution is local; no account, Aer installation, or API token is needed.
Internet is needed for initial installation unless organizers provide a wheel cache.
The Qiskit version is deliberately pinned; other dependency ranges are not a complete lockfile.

All scaffold cells execute before completion; an unfinished notebook is not a solution.
The final export is opt-in and checks that required answers are present.
Reading local source is permitted. Demonstration, generalization, and oral defense are still required.
`team_instance.json` is public instance configuration, not a signed policy or a secret.
