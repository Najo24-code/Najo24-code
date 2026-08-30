<img align="center" src="https://raw.githubusercontent.com/Najo24-code/Najo24-code/main/banner.svg" />

#### `$ status`

Hago el camino completo: escribo el código, lo meto en Docker y lo lanzo yo.

![Junior](https://img.shields.io/badge/status-junior-3fb950?style=flat-square&labelColor=0d1117)
![Ubicación](https://img.shields.io/badge/ubicación-Rep._Dominicana-58a6ff?style=flat-square&labelColor=0d1117)
![Stack](https://img.shields.io/badge/stack-Python_·_FastAPI-3776AB?style=flat-square&labelColor=0d1117)
![Deploy](https://img.shields.io/badge/deploy-git_push_→_rebuild-58a6ff?style=flat-square&labelColor=0d1117)

---

#### `$ build` — el stack

| Categoría | Herramientas |
|---|---|
| **Sistema** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=000) ![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale-5B58EB?style=flat-square&logo=tailscale&logoColor=white) |
| **Contenedores** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![docker-compose](https://img.shields.io/badge/docker--compose-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **Automatización** | ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **Frontend** | ![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) |

---

#### `$ test` — repos públicos

Casi todo lo que construyo para clientes es privado. Lo que sí está a la vista, en su mayoría FastAPI + JWT:

| Repo | Qué hace |
|---|---|
| [support-tickets-api](https://github.com/Najo24-code/support-tickets-api) | tickets de soporte |
| [restaurant-booking-api](https://github.com/Najo24-code/restaurant-booking-api) | reservas con mesas |
| [hotel-booking-api](https://github.com/Najo24-code/hotel-booking-api) | reservas de hotel |
| [expense-tracker-api](https://github.com/Najo24-code/expense-tracker-api) | gastos personales |
| [book-tracker-api](https://github.com/Najo24-code/book-tracker-api) | lectura |
| [crm-contacts-api](https://github.com/Najo24-code/crm-contacts-api) | contactos |
| [taskflow-api](https://github.com/Najo24-code/taskflow-api) | tareas y proyectos |

---

#### `$ deploy` — cómo trabajo

```bash
$ git push origin main        # al remoto, rebuild automático
$ docker compose up -d --build
$ curl -fsS .../health         # smoke test
$ exit 0                       # green
```

Principios que no negocio:

- **Blue-green** en lo crítico: no tumbar producción mientras se cambia.
- **Rollback si sale rojo**: el smoke test manda; si falla, vuelvo atrás.
- **Un comando de deploy**: `git push` es todo lo que hace falta.
- Deployo por `git push` directo al servidor con rebuild automático.
- 2 hosts Proxmox, VMs y Tailscale para la red.

> Soy junior y lo asumo: aprendo rompiendo cosas mías (y arreglándolas).

---

#### `$ healthcheck` — actividad

![GitHub Streak](https://streak-stats.demolab.com/?user=Najo24-code&theme=github-dark)

<!--
  github-readme-stats está caído. Activar cuando vuelva:
  ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Najo24-code&show_icons=true&theme=github_dark)
  ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Najo24-code&layout=compact&theme=github_dark)
-->

---

#### `$ exit 0`

Todo en verde, sin tono de venta.

![Correo](https://img.shields.io/badge/jonassuarez30%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)
[![Portafolio](https://img.shields.io/badge/Portafolio-58a6ff?style=flat-square&logo=githubpages&logoColor=white)](https://najo24-code.github.io/pilotoapps-web)
