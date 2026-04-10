\# Technical Decision Log



\## Why FastAPI + Jinja?



\- Faster MVP

\- Better SEO (server-rendered)

\- One language (Python)



\## Why SQLite for Development?



\- Zero config

\- Easy reset

\- PostgreSQL for production



\## Why Session Auth Instead of JWT?



\- HttpOnly cookies = lower XSS risk

\- Instant revocation

\- Simpler implementation



\## Why Demo/Live Separation?



Flag-based filtering keeps demo data for dev while showing only real providers publicly.



\## Why Booking Confirmation Tokens?



Numeric IDs in URLs allowed anyone to view any booking. Token + role checks fixed this.

