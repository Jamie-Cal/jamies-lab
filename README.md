# Jamie's Lab

Raspberry Pi 5 home lab — Docker mediastack + AI-agenten.

> `.local` hostnamen werken momenteel niet. Gebruik IP `192.168.0.216` direct.

---

## Mediastack

| Service | Functie | Link |
|---|---|---|
| Jellyfin | Media server | [192.168.0.216:8096](http://192.168.0.216:8096) |
| Radarr | Films | [192.168.0.216:7878](http://192.168.0.216:7878) |
| Sonarr | Series | [192.168.0.216:8989](http://192.168.0.216:8989) |
| Lidarr | Muziek | [192.168.0.216:8686](http://192.168.0.216:8686) |
| Bazarr | Ondertitels | [192.168.0.216:6767](http://192.168.0.216:6767) |
| qBittorrent | Downloaden | [192.168.0.216:8080](http://192.168.0.216:8080) |
| Prowlarr | Indexers | [192.168.0.216:9696](http://192.168.0.216:9696) |
| Flaresolverr | Cloudflare bypass | [192.168.0.216:8191](http://192.168.0.216:8191) |
| Nginx Proxy Manager | Reverse proxy | [192.168.0.216:81](http://192.168.0.216:81) |
| Pi-hole | DNS / ad-blocking | [192.168.0.216:8053](http://192.168.0.216:8053) |
| Portainer | Container-beheer | [192.168.0.216:9000](http://192.168.0.216:9000) |

Zie [mediastack/](mediastack/) voor Docker-configuratie en Prowlarr-setup.

---

## AI Agenten & Tools

Zie [AGENTS.md](AGENTS.md).

- **Dave** — Orchestrator, communiceert met Jamie in het Nederlands
- **johnclaw** — Technische uitvoerder (Docker, code, bestanden)

| Service | Functie | Link |
|---|---|---|
| OpenClaw Dashboard | Agent-beheer | [127.0.0.1:18789](http://127.0.0.1:18789) |
| Veritas Kanban | Taakoverzicht | [192.168.0.216:3001](http://192.168.0.216:3001) |
| Veritas Kanban API | REST API | [192.168.0.216:3010](http://192.168.0.216:3010) |
