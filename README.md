# Abimanyu.co.uk 🌐

<img width="3797" height="1938" alt="Screenshot 2025-11-23 000121" src="https://github.com/user-attachments/assets/c219bd78-5188-486a-9f0a-a0d50fba8c9c" />

Personal website showcasing homelab infrastructure and self-hosting projects.

## About 📕

Self-hosted website running on Proxmox VE infrastructure, deployed via Coolify with public access through Cloudflare Tunnel. Focused on privacy, security, and demonstrating enterprise homelab capabilities.

## Tech Stack 🧑‍💻

- **Framework:** Next.js 15
- **Language:** TypeScript
- **Styling:** Once UI Design System
- **Deployment:** Coolify (self-hosted)
- **Infrastructure:** Proxmox VE
- **Public Access:** Cloudflare Tunnel

## Local Development ⬇️

**Requirements:** ⭐
- Node.js v18.17+
- npm

**Setup:** 🔧
```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

## Configuration ⚙️

**Content:** `src/resources/content.tsx`
- Personal information
- About page sections
- Gallery images
- Social links

**Theme & Routes:** `src/resources/once-ui.config.ts` 🎨
- Theme colors and styling
- Enabled/disabled pages
- Display settings

## Deployment ⬇️

Website auto-deploys from GitHub main branch via Coolify when changes are pushed.

**Workflow:** 💧
1. Make changes locally
2. Commit and push to GitHub
3. Redeploy in Coolify dashboard
4. Live at https://abimanyu.co.uk

## Infrastructure 🏢

- **Coolify (CT109):** Application deployment and management
- **Cloudflare Tunnel (CT110):** Secure public access without port forwarding
- **Proxmox VE:** Virtualization platform hosting all services

## License 🪪

Personal website - All rights reserved.




