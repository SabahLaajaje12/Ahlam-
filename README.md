\# Ahlamé



Women-only beauty booking marketplace.



\[!\[Status](https://img.shields.io/badge/status-local%20MVP-yellow)](https://github.com/SabahLaajaje12/Ahlam-)

\[!\[DevLog](https://img.shields.io/badge/devlog-6%20phases-blue)](./devlog/)



\## Features



\- Multi-provider marketplace

\- Full booking flow

\- Provider and admin dashboards

\- Session-based authentication

\- RBAC (Customer, Provider, Admin)



\## Tech Stack



| Layer | Technology |

|-------|------------|

| Backend | FastAPI |

| Templates | Jinja2 |

| Database | SQLite |

| Auth | Session-based |



\## DevLog



\[→ Read the Development Journal](./devlog/README.md)



\## Run Locally



```bash

git clone https://github.com/SabahLaajaje12/Ahlam-.git

cd Ahlam-

python -m venv venv

venv\\Scripts\\activate

pip install -r requirements.txt

python -m app.migrations

uvicorn app.main:app --reload

