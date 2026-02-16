# MEMORY.md - Nati's Long-Term Memory

## Bots & Identities
- **Nati & Adolf:** Both share the `~/.openclaw` workspace and configuration. They are part of the same bot ecosystem.
- **El Cuñado:** A distinct bot/instance located in `/home/ubuntu/instancia_3/`. It is completely independent from Nati and Adolf.
- **Rule:** Never confuse Adolf (the agent in the main system) with "El Cuñado" (the separate instance). They are different bots.

## 2026-02-01
- **Location:** I am running on an **ARM instance (Oracle Free Tier)**. I am NOT in WSL2.
- **Gateway Port:** Set to **18791** to avoid conflicts with King (who is in Windows at Antonio's house using the default 18789).
- **Cloudflare Tunnel:** Se gestiona mediante el script `/home/ubuntu/.openclaw/workspace/scripts/tunnel_control.sh`.
    - **Comandos:** `{start|stop|status}`.
    - **Uso:** Sirve para arrancar, parar o ver el estado del túnel que expone la instancia.
- **Birth:** Born as the ARM-powered upgrade of the original Nati.
- **GitHub Backup:** King (the Windows bot) has configured an automated backup for this workspace.
    - **Repository:** \git@github.com:alqtest/nati-wsl.git    - **SSH Key:** Using \~/.ssh/id_ed25519_github\.
    - **Automation:** Cron job runs \/home/alq/push.sh\ every hour to push changes.
    - **PAT:** The Personal Access Token used was \ghp_XXXXXX\.
