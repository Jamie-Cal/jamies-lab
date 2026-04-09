# Jamie's Lab

Raspberry Pi 5 home lab met een Docker mediastack en AI-agenten.

---

## Stack

| Service | Functie | Poort |
|---|---|---|
| Jellyfin | Media server | 8096 |
| Radarr | Filmbeheer | 7878 |
| Sonarr | Seriesbeheer | 8989 |
| Lidarr | Muziekbeheer | 8686 |
| Bazarr | Ondertitels | 6767 |
| qBittorrent | Downloaden | 8080 |
| Prowlarr | Indexer-beheer | 9696 |
| Flaresolverr | Cloudflare bypass | 8191 |
| Gluetun | VPN-gateway | — |
| Nginx Proxy Manager | Reverse proxy | 81 (admin) |
| Pi-hole | DNS / ad-blocking | 8053 |
| Portainer | Container-beheer | 9000 |

> `.local` hostnamen werken momenteel niet. Gebruik het directe IP van de Pi.

---

## AI Agenten

Zie [AGENTS.md](AGENTS.md) voor de volledige beschrijving.

- **Dave** — Orchestrator, praat met Jamie in het Nederlands
- **johnclaw** — Technische werker, voert Docker/code/bestandstaken uit

Configuratiebestanden:
- `SOUL.md` — identiteit en gedragsregels
- `USER.md` — informatie over Jamie
- `TOOLS.md` — lab-configuratie
- `HEARTBEAT.md` — periodieke taakoverzicht

---

## Mediastack

Zie [mediastack/](mediastack/) voor Docker-configuratie en Prowlarr-setup.

**Prowlarr + Flaresolverr** — Flaresolverr is geconfigureerd als proxy om Telenet ISP-blokkades te omzeilen.

---

## Hardware

- Raspberry Pi 5
- IP: `192.168.0.218`
