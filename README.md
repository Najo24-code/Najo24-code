<img align="center" src="https://raw.githubusercontent.com/Najo24-code/Najo24-code/main/banner.svg" />

```
$ whoami
```

**Developer** · Dominican Republic  
I ship code, containers, and infrastructure — all the way from commit to production.

![Status](https://img.shields.io/badge/status-active-3fb950?style=flat-square&labelColor=0d1117)
![Location](https://img.shields.io/badge/location-Dominican_Republic-58a6ff?style=flat-square&labelColor=0d1117)
![Deploy](https://img.shields.io/badge/deploy-git_push_→_rebuild-58a6ff?style=flat-square&labelColor=0d1117)

---

## `$ build` — the stack

| Category | Tools |
|---|---|
| **Systems** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=000) ![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale-5B58EB?style=flat-square&logo=tailscale&logoColor=white) |
| **Containers** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![docker-compose](https://img.shields.io/badge/docker--compose-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **Automation** | ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **Frontend** | ![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) |

---

## `$ test` — public repos

Most of what I build for clients is private. Here's what's visible:

| Repo | Description |
|---|---|
| [ai-engineering-system](https://github.com/Najo24-code/ai-engineering-system) | Multi-agent software engineering system |
| [support-tickets-api](https://github.com/Najo24-code/support-tickets-api) | Support ticket system |
| [restaurant-booking-api](https://github.com/Najo24-code/restaurant-booking-api) | Restaurant table reservations |
| [hotel-booking-api](https://github.com/Najo24-code/hotel-booking-api) | Hotel booking system |
| [expense-tracker-api](https://github.com/Najo24-code/expense-tracker-api) | Personal expense tracker |
| [book-tracker-api](https://github.com/Najo24-code/book-tracker-api) | Reading tracker |
| [crm-contacts-api](https://github.com/Najo24-code/crm-contacts-api) | CRM contacts |
| [taskflow-api](https://github.com/Najo24-code/taskflow-api) | Tasks and projects |

---

## `$ deploy` — how I work

```bash
$ git push origin main        # push to remote, auto rebuild
$ docker compose up -d --build
$ curl -fsS .../health         # smoke test
$ exit 0                       # green
```

Non-negotiable principles:

- **Blue-green** for critical paths: never take down prod while changing.
- **Rollback on red**: the smoke test decides; if it fails, I revert.
- **Single deploy command**: `git push` is all it takes.
- Deploy via `git push` to the server with automatic rebuild.
- 2 Proxmox hosts, VMs, and Tailscale for networking.

> I learn by building, breaking, and fixing things — for real.

---

## `$ activity` — streak

![GitHub Streak](https://streak-stats.demolab.com/?user=Najo24-code&theme=github-dark)

<!-- github-readme-stats is down. Activate when it returns:
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Najo24-code&show_icons=true&theme=github_dark)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Najo24-code&layout=compact&theme=github_dark)
-->

---

## `$ exit 0`

All green, no sales pitch.

![Email](https://img.shields.io/badge/jonassuarez30%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)
[![Portfolio](https://img.shields.io/badge/Portfolio-58a6ff?style=flat-square&logo=githubpages&logoColor=white)](https://najo24-code.github.io/pilotoapps-web)
