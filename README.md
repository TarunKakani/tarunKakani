```text
Connecting to 127.0.0.1...
Connection established.
```

# `>_ ssh watchdog@system.local`

> **`[STATUS]:`** `ACTIVE`
> **`[ROLE]:`** `CS Undergrad | Systems Engineer | Threat Analyst`
> **`[MOTD]:`** *"You can't secure a system until you know exactly how to break it."*

I operate at the intersection of low-level systems architecture and defensive/offensive security. Rather than just relying on high-level abstractions, I build environments from the ground up to understand exactly how packets route, how memory is allocated, and how execution flows. 

My primary playground is the terminal, and my focus is on tearing down and securing complex architectures.

### `> ./execute --current-focus`

* **Homelabbing & Infrastructure:** Architecting isolated, self-hosted environments. I heavily utilize KVM/QEMU and containerization (Docker/Podman) across multiple Linux distributions (Rocky, Fedora, Ubuntu) to simulate enterprise networks.
* **Network & Host-Based Security:** Obsessed with traffic analysis and perimeter defense. Currently engineering a localized Blue Team lab integrating **Suricata** (NIDS), **Wazuh** (HIDS), and complex **Firewalld** state configurations to monitor anomalies and drop malicious payloads. Studying for CCNA to cement routing protocols.
* **Internals & Reverse Engineering:** Diving deep into Windows/Linux internals. Learning the anatomy of malware and analyzing stripped binaries using tools like **Ghidra**. 
* **Backend Systems:** Building robust, secure web services and APIs from scratch to understand exactly how authentication and data flow can be exploited or hardened.

### `> cat /usr/local/bin/arsenal`

| `[MODULE]` | `[TECHNOLOGY_STACK]` |
| :--- | :--- |
| **`SYS.LANG`** | `C` `•` `C++` `•` `Python` `•` `JavaScript` `•` `Bash` `•` `PowerShell` |
| **`SYS.WEB`** | `FastAPI` `•` `Bun` `•` `React` `•` `Next.js` |
| **`SYS.SEC`** | `Suricata` `•` `Wazuh` `•` `Firewalld` `•` `Nmap` `•` `Wireshark` `•` `Ghidra` |
| **`SYS.OPS`** | `Docker` `•` `Podman` `•` `KVM/QEMU` `•` `Linux Internals` |

### `> ps aux | grep active_operations`

* `[PID 101]` **`Blue_Team_Nexus`** - Bare-metal server deployment acting as a centralized IDS/IPS, utilizing custom firewall rulesets, SSHGuard, and Wazuh agents for comprehensive host and network monitoring.
* `[PID 102]` **`Vulnerability_Scanner`** - Automated web server security assessment utility integrating Nmap and Nikto engines via Python logic.
* `[PID 103]` **`Kernel_Space`** - Developing a custom, minimal OS kernel and command-line shell from scratch in C to master process scheduling and memory management.
* `[PID 104]` **`Hardware_Crypto`** - Engineering a hardware-based encrypted radio communication device for secure, off-grid data transmission.

### `> ping -c 4 github_stats`
![System Stats](https://github-readme-stats.vercel.app/api?username=WatchDog007&show_icons=true&theme=hacker&hide_border=true&bg_color=0D1117&title_color=00FF00&text_color=C9D1D9&icon_color=00FF00)

```text
Connection closed by foreign host.
```
