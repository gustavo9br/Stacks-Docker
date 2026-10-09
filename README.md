# Stacks-Docker

Stacks Docker prontas para deploy via Portainer (App Templates), separadas por ambiente.
Cada ambiente tem o seu próprio `templates.json`, para não misturar.

## Usando no Portainer

Em **Settings → App Templates → URL**, coloque o link do seu ambiente:

**VPS** (Traefik com HTTPS / Let's Encrypt):
```
https://raw.githubusercontent.com/gustavo9br/Stacks-Docker/refs/heads/main/vps/templates.json
```

**Homelab** (Traefik em HTTP, HTTPS via Cloudflare Tunnel):
```
https://raw.githubusercontent.com/gustavo9br/Stacks-Docker/refs/heads/main/homelab/templates.json
```
