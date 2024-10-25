
<h3 align="center">Termux Parrot</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/blackmonk13/termux-parrot.svg)](https://github.com/blackmonk13/termux-parrot/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/blackmonk13/termux-parrot.svg)](https://github.com/blackmonk13/termux-parrot/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">
    A script to install and run Parrot OS within Termux, providing a lightweight command-line interface with plans for future desktop environment support.
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Prerequisites](#prerequisites)
- [Installing](#installing)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](#todo)
- [Contributing](#contributing)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name="about"></a>
Termux Parrot is an installer script written in Amber that allows you to run Parrot OS within Termux on Android devices. The project aims to provide a seamless way to access Parrot OS tools and environments on mobile devices, with current support for CLI interface and planned extensions for desktop environment access via VNC.

The installer handles the complete setup process, including downloading the appropriate Parrot OS rootfs, verifying its integrity, configuring the environment, and setting up user accounts. It's designed to be user-friendly while maintaining security and stability.

## 🏁 Getting Started <a name = "getting_started"></a>

### Prerequisites

Before installing Termux Parrot, ensure you have:

- Latest version of Termux installed from F-Droid
- At least 2GB of free storage space
- Working internet connection

### Installing

1. Update Termux packages:
```bash
pkg update && pkg upgrade -y
```

2. Run the installer:
```bash
bash <(curl -s "https://github.com/blackmonk13/termux-parrot/releases/latest/download/installer.sh")
```

## 🎈 Usage <a name="usage"></a>

After installation, you can:

- Start Parrot OS CLI:
```bash
parrot
```

- Start Parrot OS CLI as root:
```bash
parrot -r
```

## ⛏️ Built Using <a name="built_using"></a>
- [Amber](https://amber-lang.com/) - Programming Language
- [Termux](https://termux.dev/) - Android Terminal Emulator
- [Parrot OS](https://www.parrotsec.org/) - Security OS

## 📌 TODO <a name="todo"></a>
- [ ] Add desktop environment installation support
- [ ] Implement VNC server configuration
- [ ] Add storage access management
- [ ] Add network tools configuration
- [ ] Create backup and restore functionality

## 🤝 Contributing <a name="contributing"></a>
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/blackmonk13/termux-parrot/issues).

## ✍️ Authors <a name = "authors"></a>

- [@blackmonk13](https://github.com/blackmonk13) - Idea & Initial work

See also the list of [contributors](https://github.com/blackmonk13/termux-parrot/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Kali NetHunter project for inspiration
- Parrot OS team for their amazing security distribution
- Termux developers for making Android CLI environments possible
- The Amber programming language community
