
 🐧 Linux Explained

 A structured, high-level guide to understanding Linux internals — kernel architecture, system design, and core subsystems.

![Linux](https://img.shields.io/badge/OS-Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Docs](https://img.shields.io/badge/type-Documentation-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

---

## 🎯 About This Repository

Linux is a complex, layered system — from hardware to applications, every layer has its own specific role. This repository documents those layers in a **structured and technical manner**, so that any developer or sysadmin can understand Linux's internal workings end-to-end — not just commands, but the **"why" and "how"** behind them.

This guide starts from the basics but gradually moves toward system-level depth — covering kernel subsystems, process lifecycle, and boot architecture.

---

## 📚 Table of Contents

| # | Topic | Description |
|---|-------|-------------|
| 01 | [Introduction](docs/01-introduction.md) | What Linux is, its history, and the Unix philosophy |
| 02 | [Kernel](docs/02-kernel.md) | Kernel architecture, kernel space vs user space |
| 03 | [Filesystem Hierarchy](docs/03-filesystem-hierarchy.md) | The FHS standard and directory structure |
| 04 | [Shell & Terminal](docs/04-shell-and-terminal.md) | Shell internals, terminal vs shell vs kernel |
| 05 | [Process Management](docs/05-process-management.md) | Process lifecycle, scheduling, and signals |
| 06 | [Users & Permissions](docs/06-users-and-permissions.md) | Permission model, ownership, and root access |
| 07 | [Package Management](docs/07-package-management.md) | Internal working of package managers |
| 08 | [Networking Basics](docs/08-networking-basics.md) | Fundamentals of the network stack |
| 09 | [Boot Process](docs/09-boot-process.md) | Complete flow from firmware to login |

---

 🧭 Who Is This For?

- Students who want to seriously understand Linux internals
- Developers working in backend/DevOps
- Sysadmins who need system-level debugging knowledge
- Anyone curious about "how does an OS actually work"
 
 How to Use

1. Clone the repository:
```bash
   git clone https://github.com/your-username/linux-explained.git
```
2. Follow the sequence in the `docs/` folder (01 through 09)
3. Try out the commands in your own terminal alongside each topic


  Contributing

Contributions are welcome! If you'd like to:
- Add more depth to an existing topic
- Include diagrams or visual explanations
- Fix a typo or make a technical correction

Feel free to open a PR or raise an issue.

 License

This project is licensed under the [MIT License](LICENSE).


**⭐ If you find this repository helpful, don't forget to star it!**
