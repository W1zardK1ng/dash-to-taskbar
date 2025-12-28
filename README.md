# Dash To Taskbar
Brings back the Windows-style taskbar experience to GNOME.

> **Note:** This extension is built using the code from the [ZorinOS Taskbar GitHub repository](https://github.com/ZorinOS/zorin-taskbar).  
> No added features, and none are currently planned.

---

## Screenshot

![Zorin Taskbar Screenshot](https://extensions.gnome.org/extension-data/screenshots/screenshot_9046_JHxwIEc.png "Dash To Taskbar Screenshot")

---


# Manual Installation

1. Download the extension source code (ZIP) or Clone the repository:
   ```bash
   git clone https://github.com/W1zardK1ng/dash-to-taskbar
   
2. Extract the ZIP file and rename the extracted folder to `dash-to-taskbar@w1zardk1ng`.
   ```bash
   mv dash-to-taskbar dash-to-taskbar@w1zardk1ng

3. Copy the folder to the GNOME extensions directory:
   ```bash
   cp -r dash-to-taskbar@w1zardk1ng ~/.local/share/gnome-shell/extensions
4.  Restart GNOME Shell

- **On Xorg:** Press `Alt + F2`, type `r`, then press `Enter`  
- **On Wayland:** Log out and log back in


5. Enable the extension using the Extensions app or run: 
   ```bash
   gnome-extensions enable dash-to-taskbar@w1zardk1ng`
