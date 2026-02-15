<h1 align="center">rainz</h1>

<p align="center">
  Desenvolvedor backend e infraestrutura — focado em automação, monitoramento e self-hosting.
</p>

<br>

## NOR Hytale

Desenvolvi um servidor brasileiro dedicado de Hytale com infraestrutura profissional — monitoramento 24/7 via Grafana, Prometheus e Uptime Kuma, backups automáticos na nuvem com Google Drive, DNS próprio via Cloudflare, bot Discord de administração e landing page customizada.

<p align="center">
  <img src="https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-Discord_Bot-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-Monitoring-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-Metrics-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare-DNS_&_Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-Landing_Page-009639?style=flat-square&logo=nginx&logoColor=white" />
</p>

### O que eu construí

```
NOR Hytale Server
├── Servidor de jogo (Java, QUIC/UDP, 100 slots)
├── Bot Discord (Python)
│   ├── Monitoramento em tempo real (DNS, Docker, Network, Game)
│   ├── Painel admin via slash commands
│   ├── Tracking de players online
│   └── Alertas automáticos de status
├── Landing Page (HTML/CSS/JS)
│   ├── site.norhytale.com via Cloudflare Tunnel
│   ├── Background video com blur
│   ├── Partículas flutuantes + typing animation
│   └── Responsivo mobile
├── Monitoramento
│   ├── Grafana — dashboards de CPU, RAM, rede, disco
│   ├── Prometheus — coleta de métricas (retenção 30 dias)
│   ├── cAdvisor — métricas por container
│   ├── Node Exporter — métricas do host
│   └── Uptime Kuma — uptime + status page pública
├── Infraestrutura
│   ├── Docker Compose (9 containers)
│   ├── Cloudflare DNS + Tunnel
│   ├── Backups automáticos (local + Google Drive)
│   └── Nginx reverse proxy
└── Segurança
    ├── Whitelist + sistema de permissões
    ├── Auth persistente entre reinícios
    └── Proteção Cloudflare
```

### Stack

| Categoria | Tecnologias |
|---|---|
| **Game Server** | Java 25, QUIC/UDP |
| **Bot** | Python, discord.py |
| **Monitoramento** | Grafana, Prometheus, cAdvisor, Node Exporter, Uptime Kuma |
| **Infra** | Docker, Nginx, Cloudflare, rclone |
| **Frontend** | HTML, CSS, JS (zero deps) |

### Links

| | |
|---|---|
| Landing Page | [site.norhytale.com](https://site.norhytale.com) |
| Status Page | [status.norhytale.com](https://status.norhytale.com) |
| Discord | [discord.gg/gZHzGkH37D](https://discord.gg/gZHzGkH37D) |

<br>

<p align="center">
  <sub>Tudo rodando em um único servidor dedicado, gerenciado por uma pessoa.</sub>
</p>
