<p align="center">
  <a href="" rel="noopener">
  <svg id="Layer_1" x="0" y="0" viewBox="0 0 100 100" xml:space="preserve" width="100" height="100" class="jss119"><style type="text/css" id="style1">@-webkit-keyframes animate-fade{0%{fill-opacity:0;stroke-width:1pt}40%{fill-opacity:0}to{stroke-dashoffset:0;fill-opacity:1;stroke-width:0}}@-webkit-keyframes circle{0%{stroke-dashoffset:2000;fill-opacity:0;stroke-width:1pt}20%,40%,80%{fill-opacity:0}60%{fill-opacity:.5}to{stroke-dashoffset:0;fill-opacity:1;stroke-width:0}}@-webkit-keyframes bird{0%{stroke-dashoffset:2000;fill-opacity:0;stroke-width:1pt}20%,40%,80%{fill-opacity:0}60%{fill-opacity:.5}to{stroke-dashoffset:0;fill-opacity:1;stroke-width:0}}</style><linearGradient id="shadow" gradientUnits="userSpaceOnUse" x1="61.327" y1="97.572" x2="167.614" y2="91.574"><stop offset="0" id="stop1" stop-color="#000" stop-opacity="0.9"></stop><stop offset="0.086" id="stop2" stop-color="#000909" stop-opacity="0.823"></stop><stop offset="0.228" id="stop3" stop-color="#002023" stop-opacity="0.695"></stop><stop offset="0.409" id="stop4" stop-color="#00464c" stop-opacity="0.532"></stop><stop offset="0.622" id="stop5" stop-color="#007a85" stop-opacity="0.34"></stop><stop offset="0.859" id="stop6" stop-color="#00bccd" stop-opacity="0.127"></stop><stop offset="1" id="stop7" stop-color="#00e7fc" stop-opacity="0"></stop></linearGradient><g id="g7"><circle cx="50" cy="50" r="50" style="-webkit-animation:circle 5s alternate;animation:circle 5s alternate" stroke-width="0.571" stroke-dasharray="100" fill="#15e0ed" stroke="#15e0ed" stroke-miterlimit="10"></circle><path id="polygon7" transform="scale(.57143)" style="animation-duration:5s;animation-name:animate-fade;animation-delay:5s;animation-fill-mode:backwards" fill="url(#shadow)" d="M162 41.6l2.4 4.2 1.8 3.5 2 4.4 1.7 4.4 1.6 4.7 1.4 5.8 1.1 5.3.5 4.5.5 5.3v6.2l-.3 4.4-.6 5.7-.7 4.4-1.5 6.2-1.9 6.1-1.5 4.1-1.8 3.9-1.8 3.6-2.2 3.9-2.4 3.9-3.5 4.9-2.4 2.9-4 4.4-4.2 4.1-5.1 4.3-5.3 3.7-3 2-4.5 2.5-6.6 3.3-5.1-5.8-36-40.3-26-60.8 6-29.6L141.9 19l4.9 4.2 2.6 2.4 4 4.4 2.9 3.5 3 4z"></path><g id="g289" transform="scale(.57143)"><path d="M80.6 122.1l36 40.3-12-25.2 11.2 11.7L79.3 83 95 63.4l58.7-24.3L95 40.4l38.2-20.1-72.6 11.4-6 29.6-29.3 1.9-5.1 25.1 14.7-12" style="-webkit-animation:bird 7s alternate;animation:bird 7s alternate" stroke-dasharray="100" stroke="#000" stroke-miterlimit="10" id="g287"></path></g></g></svg>
</p>

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
bash <(curl -s "https://github.com/blackmonk13/termux-parrot/releases/download/latest/installer.sh")
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
