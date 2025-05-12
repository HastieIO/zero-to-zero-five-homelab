# From Zero to Zero.Five — Securing My First Homelab

This project documents the creation and hardening of my first homelab using Proxmox VE, designed to simulate real-world infrastructure with a focus on security and remote management.

> 📄 **Read the full write-up:**  
> [zero-to-zero-five-lab.pdf](zero-to-zero-five-lab.pdf)

## 🔐 Key Objectives

- Install and configure Proxmox on bare-metal hardware
- Harden SSH access (no root, no passwords, key-based only)
- Set up Tailscale for encrypted, identity-based remote access
- Apply UFW firewall rules for least privilege network access
- Enable two-factor authentication for the Proxmox GUI
- Enforce zero-trust ACLs to control access at the identity level
- Configure automated VM backups with email alerts

## 💡 Why This Project Matters

This wasn’t just about spinning up VMs — it was about building secure infrastructure from the ground up using real-world security principles.  
Everything was treated as if it were an internet-facing enterprise system — even if it’s just a box under my desk.

This lab serves as the foundation for larger projects, including:
- Active Directory + Azure hybrid simulations
- Insider threat red/blue team exercises
- IAM and identity escalation scenarios

## 👨‍💻 Author

**Denney Thongphet**  
Cybersecurity Intern @ Mutual of Omaha  
🔗 [pingdenney.tech](https://pingdenney.tech) • [LinkedIn](https://www.linkedin.com/in/denneyt)
