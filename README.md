# From Zero to Zero.Five — Securing My First Homelab

This project documents the creation and hardening of my first homelab using Proxmox VE, designed to simulate real-world infrastructure with a focus on security, remote access, and best practices in identity and access management.

## 📦 Repository Contents

- `Zero to Zero.Five.pdf`: Full technical write-up with detailed steps and rationale  
- [Blog-style reflection (casual version)](https://pingdenney.tech/blog/zero-to-zero-five)

## 🔐 Key Objectives

- Install and configure Proxmox on bare-metal hardware
- Harden SSH access (no root login, no password auth, key-based only)
- Set up Tailscale for encrypted, identity-based remote access
- Apply UFW firewall rules to enforce least-privilege networking
- Enable two-factor authentication for the Proxmox Web UI
- Implement zero-trust ACLs using Tailscale’s access control
- Configure automated Proxmox VM backups with email alerts

## 💡 Why This Project Matters

This wasn’t just about spinning up virtual machines — it was about learning to build **secure infrastructure from the ground up**. I treated this homelab as if it were an enterprise system, applying real-world hardening principles at every layer.

This lab now acts as the **foundation for future cybersecurity projects**, including:

- Active Directory + Azure hybrid identity labs
- Insider threat red/blue simulations (HollowRoot)
- Privilege escalation and IAM misconfiguration testing

---

## 👨‍💻 Author

**Denney Thongphet**  
Cybersecurity Intern @ Mutual of Omaha  
🔗 [pingdenney.tech](https://pingdenney.tech) • [LinkedIn](https://www.linkedin.com/in/denney-t-167546261/)
