# Zabbix + Grafana Stack

Docker Compose ile ayağa kalkan hazır monitoring stack.

## İçerik

- Zabbix Server 7.0
- Zabbix Web (Nginx)
- PostgreSQL 15
- Grafana

## Kurulum

### Gereksinimler
- Ubuntu Server 24.04
- Docker Engine
- Git

### Adımlar

```bash
git clone https://github.com/erkutyasa/zabbix-stack
cd zabbix-stack
docker compose up -d
```

## Erişim

| Servis | URL | Kullanıcı | Şifre |
|--------|-----|-----------|-------|
| Zabbix | http://IP:8080 | Admin | zabbix |
| Grafana | http://IP:3000 | admin | admin |

## Portlar

- 8080 — Zabbix Web
- 3000 — Grafana
- 10051 — Zabbix Server (Agent bağlantısı)# zabbix-stack
