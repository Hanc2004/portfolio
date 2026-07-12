# Hellena Nzellu — Portfolio

Live site: [hanc2004.github.io/portfolio](https://hanc2004.github.io/portfolio/)

A personal portfolio site for Hellena Nzellu, BSc Computer Systems and Networks student at Ardhi University, showcasing projects across backend development, frontend engineering, data pipelines, and field/IoT work.

## Overview

The site presents four projects as a "network topology," reflecting a Computer Systems and Networks background:

- **auth-api** — Node.js/Express authentication service with JWT, Google OAuth, PostgreSQL, Docker, and a GitHub Actions CI/CD pipeline. [Repo](https://github.com/Hanc2004/auth-api)
- **task-manager-frontend** — Next.js/Tailwind frontend with role-based access control (admin/user), consuming `auth-api`. [Repo](https://github.com/Hanc2004/task-manager-frontend)
- **fintech-pipeline** — Python ETL pipeline (pandas, SQLAlchemy) feeding a Metabase dashboard, scheduled via GitHub Actions. [Repo](https://github.com/Hanc2004/fintech-pipeline)
- **Industrial Training — e-Government Authority (e-GA)** — Field experience at e-GA's Research & ICT Development Centre (RIDC): a Smart Outlet system (IoT + voice control + AI usage prediction), an IoT hackathon (3D-printed enclosure redesign), and RJ-45 networking training.

## Tech Stack

Built as a single static page — no build step or dependencies required.

- HTML5 / CSS3 / vanilla JavaScript
- Google Fonts: JetBrains Mono, Inter
- Hosted on GitHub Pages

## Project Structure

```
portfolio/
├── index.html
├── images/
│   └── smart-outlet-architecture.jpg
└── README.md
```

## Running Locally

No build tools needed — just open the file directly:

```powershell
git clone https://github.com/Hanc2004/portfolio.git
cd portfolio
start index.html
```

Or use the VS Code "Live Server" extension for auto-reload while editing.

## Deployment

Hosted via **GitHub Pages**, deployed from the `main` branch, root folder. Any push to `main` updates the live site automatically:


## Contact

- Email: nzelluhellena@gmail.com
- Phone: +255 749 567 027
- GitHub: [github.com/Hanc2004](https://github.com/Hanc2004)
