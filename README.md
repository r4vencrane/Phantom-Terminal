
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
![phantom-terminal](https://github.com/user-attachments/assets/09a6542d-f64f-4188-9cd5-f4606c3cafcf)



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

## About `target.sh`

`target.sh` is a lightweight helper script designed to simplify handling target IPs during red teaming, CTFs, or penetration testing engagements.

### What it does:
- Stores a target IP address into a local file (`~/.target_ip`)
- Allows you to quickly copy that IP to your clipboard using `xclip` (ideal for pasting into terminal tools or reports)

### Usage

```bash
./target.sh 10.10.14.27     # Saves the IP to ~/.target_ip
./target.sh copy            # Copies the saved IP to your clipboard
```

![image](https://github.com/user-attachments/assets/abdf5ba3-585d-4076-9c70-ab8f707d3991)


### Note 
This script stores the IP in plain text in your home directory. It's meant for quick access in controlled environments, not for storing sensitive or long-term data.

---

<p align="center">
  <a href="https://github.com/r4vencrane/Network-Recon/blob/main/LICENSE">
    <img src="https://img.shields.io/static/v1?style=for-the-badge&label=LICENSE&message=MIT&labelColor=0a0f0a&colorB=77ff00"/>
  </a>
</p>
