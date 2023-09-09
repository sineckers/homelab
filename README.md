# homelab
This repo includes the resources of my begineer level personal homelab setup.

### Hardware
- Raspberry Pi 4 `4GB`
- `64GB` SdCard Storage
- Gigabit ISP Router


### Cooling
Unfortunately, with passive + active cooling my RPi is working at 45-50 C and maybe needs an upgrade about cooling.
- Mini fan on 3D Printed Case
- Cooling blocks on some components


### OS
- Raspbian OS Lite 64Bit
- Docker with Portainer

### Apps

##### Network
- [Pi-hole](https://pi-hole.net) + Cloudflared for Adblocking and DoH
- Cloudflare tunnels (cloudflared) for public domain connection
- [Nginx proxy manager](https://nginxproxymanager.com) for reverse proxy of domains

#### Management
- [Portainer](https://portainer.io) for managing docker instances
- [WatchTower](https://containrrr.dev/watchtower/) for Updating container images regularly
- [Guacamole](https://guacamole.apache.org) for remote desktop and ssh over browser

#### Monitoring
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) for Monitoring Container status & Measuring pings
- [Speedtest Tracker](https://github.com/alexjustesen/speedtest-tracker) for Monitoring Internet Speed
- [NTFY](https://github.com/binwiederhier/ntfy) for Push notifications about status of services

#### Downloads & Files
- [QBittorrent](https://hub.docker.com/r/linuxserver/qbittorrent) Download manager...
- SMB server for accessing files on RPi on Windows machines easly
- [SnapDrop](https://hub.docker.com/r/linuxserver/snapdrop) for transferring files between devices at home
- [FileBrowser](https://github.com/filebrowser/filebrowser) for managing files from web

#### Security
- [Authentik](https://goauthentik.io) for auth on public domain connected to cloudflare
- [Vaultwarden ](https://github.com/dani-garcia/vaultwarden) for Securely storing passwords and sharing between devices

### Planning to Deploy
- [ ] Jdownloader or Pyload for downloading files that sent from my devices

### Hardware to be added

- [ ] External HDD or SSD
- [ ] New 3D printed Case and Cooling kit for CPU
- [ ] POE Hat ?
- [ ] Gigabit Switch At least 5 port
- [ ] A Server ? Maybe Custom built tower?
