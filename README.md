# homelab
This repo includes the resources of my begineer level personal homelab setup.

### Hardware
- Raspberry Pi 4 `4GB`
- `64GB` SdCard Storage
- Gigabit ISP Router

### OS
- Raspbian OS Lite 64Bit
- Docker with Portainer

### Apps
##### Network
- [Pi-hole](https://pi-hole.net) + Cloudflared for Adblocking and DoH
- Cloudflare tunnels (cloudflared) for public domain connection
- [Nginx proxy manager](https://nginxproxymanager.com) for reverse proxy of domains
- [Authentik](https://goauthentik.io) for auth on public domain

#### Management
- [Portainer](https://portainer.io) for managing docker instances
- [WatchTower](https://containrrr.dev/watchtower/) for Updating container images regularly
- [Guacamole](https://guacamole.apache.org) for remote desktop and ssh over browser

#### Monitoring
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) for Monitoring Container status & Measuring pings
  
## More will be added
