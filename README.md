# Vehicle Insurance MLOps

End-to-end, production-minded Machine Learning pipeline for **Vehicle Insurance purchase prediction**. The project demonstrates how to go from raw data → reproducible training → packaged model → containerized app, with optional CI/CD and deployment hooks.

---

## Project Structure
  Vehicle_Insurance_MLOps/
  ├─ config/ # Config files (paths, params, secrets placeholders)
  ├─ notebook/ # EDA, experiments, and training notebooks
  ├─ src/ # Modular Python package: pipelines & utilities
  ├─ app.py # App entry point (CLI / Streamlit / Flask/FastAPI)
  ├─ demo.py # Quick demo script for pipeline execution
  ├─ template.py # Scaffolder to generate project structure
  ├─ requirements.txt # Python dependencies
  ├─ setup.py # Editable install entrypoint
  ├─ pyproject.toml # Packaging metadata (PEP 621)
  ├─ Dockerfile # Container definition
  ├─ .dockerignore
  ├─ .gitignore
  ├─ LICENSE # MIT License
  └─ README.md

---

## Quickstart

```bash
  git clone https://github.com/Tushar7012/Vehicle_Insurance_MLOps.git
  cd Vehicle_Insurance_MLOps
  
  # Using virtual environment
  python -m venv .venv
  # Windows:
  .venv\Scripts\activate
  # macOS/Linux:
  # source .venv/bin/activate
  
  pip install --upgrade pip
  pip install -r requirements.txt
  pip install -e .







