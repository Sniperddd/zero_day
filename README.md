<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=E95420&height=220&section=header&text=Zero%20Day&fontSize=60&fontColor=ffffff&animation=fadeIn&desc=The%20Genesis%20of%20Software%20Engineering&descAlignY=70&descAlign=50" alt="Zero Day Header" />
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=E95420&center=true&vCenter=true&width=600&lines=Initializing+Vagrant+Environments...;Mastering+Version+Control+with+Git;Cloning,+Pushing,+and+Branching...;Welcome+to+Holberton+School!" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <p><em>The fundamental starting point: Virtual machines, Linux environments, and Version Control.</em></p>

  [![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
  [![Vagrant](https://img.shields.io/badge/Vagrant-1563FF?style=for-the-badge&logo=vagrant&logoColor=white)](https://www.vagrantup.com/)
  [![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
</div>

<br/>

## 🌅 The Genesis: Zero Day

In software engineering, everything starts at **Zero**. This repository is the foundational entry point of the curriculum. Before writing a single line of C or building complex web architectures, a robust and reproducible development environment must be established.

This project focuses on two absolute pillars of the modern software industry:
1. **Virtualization:** Spinning up isolated headless Linux environments (Ubuntu) using Vagrant and VirtualBox.
2. **Version Control:** Tracking changes, understanding repository architectures, and collaborating via Git and GitHub.

---

## 🗂️ Project Modules

| Module | Core Concepts Explored |
| :--- | :--- |
| **`0x00-vagrant`** | Installing Vagrant, configuring `Vagrantfile`, provisioning Ubuntu VMs, and navigating via headless SSH. |
| **`0x03-git`** | Initializing local repositories, understanding the staging area (`git add`), committing (`git commit`), and remote syncing (`git push`, `git pull`). |

---

## ⚙️ Environment Setup

To recreate the virtual environment used in these modules:

```bash
# Initialize a new Ubuntu focal 20.04 environment
vagrant init ubuntu/focal64

# Boot up the virtual machine
vagrant up

# Connect via SSH
vagrant ssh
```

---

<div align="center">
  <img src="https://media.giphy.com/media/USV0ym3bVWQJJmNu3N/giphy.gif" width="300" alt="Git Branching GIF" />
  <br>
  <sub><b>Commit early, commit often. The journey begins here.</b> 🚀</sub>
</div>
