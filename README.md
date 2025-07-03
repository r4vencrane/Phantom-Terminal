
<h1 align="center">
 Phantom Terminal Installer
</h1>


<p align="center">
 <img src="https://img.shields.io/static/v1?style=for-the-badge&label=SHELL&message=Script&labelColor=0a0f0a&colorB=77ff00&logo=gnubash&logoColor=77ff00"/> 
 <img src="https://img.shields.io/static/v1?style=for-the-badge&label=HTB&message=OPTIMIZED&labelColor=0a0f0a&colorB=77ff00"/>
 <img src="https://img.shields.io/static/v1?style=for-the-badge&label=TOOL&message=RED%20TEAM&labelColor=0a0f0a&colorB=77ff00&logo=skyliner&logoColor=77ff00"/>
</p>


![image](https://github.com/user-attachments/assets/bd83e8f4-5ba0-4f55-ada3-19d7e972057e)




---

## About

A simple Bash script that automates the setup of a clean, modern terminal environment using:

- Zsh
- Kitty (terminal emulator)
- Starship (cross-shell prompt)
- Lsd & Bat (modern replacements for `ls` and `cat`)

---

## Features

- Installs required packages
- Applies configuration files
- Adds aliases and settings to `.zshrc`
- Designed for Kali, Debian, and Ubuntu-based distros

---

## Preview
![phantom-terminal](https://github.com/user-attachments/assets/1b8bb4e3-d4ec-46f1-8c7e-dd1517646fee)



---

## Requirements

- Linux system with `apt` package manager
- Internet connection
- Sudo privileges

---

## Usage

```bash
git clone https://github.com/yourusername/phantom-terminal.git
cd phantom-terminal
chmod +x install_phantom.sh
sudo ./install_phantom.sh
```

Follow the interactive prompt to install the Phantom Terminal setup.

---

## Notes

- The script modifies `~/.zshrc` and `~/.config/`, so back them up if needed.
- Font files and configs should exist in `fonts/`, `kitty/`, and the root directory as expected.
- If you're not using Oh My Zsh, make sure `.zshrc` does not attempt to source it, or comment that line out.

---


<p align="center">
  <a href="https://github.com/r4vencrane/Network-Recon/blob/main/LICENSE">
    <img src="https://img.shields.io/static/v1?style=for-the-badge&label=LICENSE&message=MIT&labelColor=0a0f0a&colorB=77ff00"/>
  </a>
</p>
