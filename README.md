# Raspberry Pi Setup with Ansible

This repository automates setting up:
- **Docker, Portainer, Tailscale VPN**
- **Home Assistant, Pi-hole**
- **Netdata for system monitoring**
- **Uptime Kuma for external uptime monitoring**
- **Prometheus & Grafana for historical uptime tracking**
- **Cloudflare Tunnel for secure remote access**
- **Homer Dashboard as a central UI**

## 📌 Setup Instructions

1. **Clone the Repository**  
   `git clone https://github.com/lewkoo/rpi-setup.git`  
   `cd rpi-setup`

2. **Run Ansible**  
   `ansible-playbook -i inventory.ini playbook.yml`

3. **Access Services**
| Service           | URL (via Cloudflare Tunnel) |
|------------------|----------------------------|
| Netdata         |  |
| Uptime Kuma     |  |
| Grafana Reports |  |
| Home Assistant  |  |
| Portainer       |  |
| Pi-hole         |  |
| Nginx Proxy     |  |

## ✅ Notes
- Update  with your credentials.
- Raspberry Pi **must have SSH enabled**.
- Services are **securely accessible via Cloudflare Tunnel**.
