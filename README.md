<div align="center">

<img src="./assets/1.gif" width="500" alt="Black-and-white manga panel: a lone figure resting against a rock in front of a huge pale sun" />

# 𒉭 AbduLz0

**I Create programs For fun**

`linux` · `Quality of life` · `automation` · `ai`

<br/>

<img src="https://img.shields.io/badge/Linux-161b22?style=flat-square&logo=linux&logoColor=7bd88f" alt="Linux" />
<img src="https://img.shields.io/badge/Bash-161b22?style=flat-square&logo=gnubash&logoColor=7bd88f" alt="Bash" />
<img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=7bd88f" alt="Python" />
<img src="https://img.shields.io/badge/GTK-161b22?style=flat-square&logo=gtk&logoColor=7bd88f" alt="GTK" />
<img src="https://img.shields.io/badge/GNOME-161b22?style=flat-square&logo=gnome&logoColor=7bd88f" alt="GNOME" />
<img src="https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=7bd88f" alt="JavaScript" />
<img src="https://img.shields.io/badge/Ollama-161b22?style=flat-square&logo=ollama&logoColor=7bd88f" alt="Ollama" />

</div>

---

I build Linux desktop apps, installers and system glue in **Python, GTK and Bash**, built around Zorin OS / GNOME.
I focus on practical tools with tests, backups or undo where settings change, and clear documentation of their limits.

### projects

| Project | What it does | Built with |
|---|---|---|
| **[Terminal Experience Studio](https://github.com/AbduLz0/fun-cli)** · [site](https://abdulz0.github.io/fun-cli/) | Restyle your terminal from a GTK4 app: themes, prompts, picture-to-ASCII and an AI companion that roasts your typos. Backups and one-click undo. | `Python` `GTK4` `Libadwaita` `Bash` |
| **[DS4 Control Center](https://github.com/AbduLz0/ds4-control-center)** | DualShock 4 dashboard for Linux: live input tester, stick-drift diagnostics, Bluetooth pairing, battery and a Steam launcher. Shows "unavailable" instead of fake data. | `Python` `evdev` `BlueZ` `JavaScript` |
| **[Converto](https://github.com/AbduLz0/Converto)** | Native file converter for GNOME. Drop files or right-click in Nautilus to convert images, audio, video, documents and archives. Fully offline. | `Python` `GTK3` `FFmpeg` `LibreOffice` |
| **[Hermes Local](https://github.com/AbduLz0/hermeslocal)** | One script that sets up Hermes Agent, Ollama and Qwen 3.5 9B as a local AI agent on Ubuntu/Debian, with verification checks and config backup. | `Bash` `Ollama` `systemd` |
| **[Linux Wallpaper Engine for GNOME](https://github.com/AbduLz0/linux-wallpaper-engine-gnome-xorg)** *(fork)* | Steam Workshop animated wallpapers on GNOME/X11 with multi-monitor support and clickable desktop icons. Fork of [berelels](https://github.com/berelels/linux-wallpaper-engine-gnome-xorg), integrating [zadwen](https://github.com/zadwen/linux-wallpaper-engine-gnome-xorg)'s improvements. Adds browser/session fixes and per-monitor framing controls. | `Python` `Bash` `GNOME/X11` |

### how I build

- **Reversible.** fun-cli backs up before every change and has undo. Hermes Local backs up your config before touching it.
- **Honest.** DS4 Control Center says "unavailable" rather than invent a number. Project READMEs document unsupported features and testing limits.
- **Local-first.** Converto makes no network calls. Hermes Local runs the model on your machine. fun-cli's roasts are cached for offline use.

### what's next

- **Terminal Experience Studio roadmap:** Zsh/Fish support and `.deb` / Flatpak packaging.
- **DS4 Control Center validation gap:** physical-controller testing is still needed; current tests use simulated input.

### languages

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbduLz0&layout=compact&hide_border=true&bg_color=0d1117&text_color=c9d1d9&title_color=7bd88f" alt="Top languages" />

</div>

Explore [Terminal Experience Studio](https://abdulz0.github.io/fun-cli/) or open an issue in the relevant project for feedback and bug reports.

---

```text
~ $ whoami
abdulz0
~ $ status
online: building in public, one install.sh at a time
```

