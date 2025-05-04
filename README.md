# Earthshaker GRUB Theme

🌿 A vibrant pastel forest GRUB theme featuring the Earthshaker mascot — a blocky stone golem glowing with life and mossy charm.

This theme brings a playful yet grounded aesthetic to your bootloader with custom icons, a lush animated background, and carefully tuned colors inspired by the Earthshaker Neovim theme.

---

## 📁 Folder Structure

```
earthshaker.grub/
├── icons/                   # Optional icons for menu entries
├── earthshaker_grub.png     # Background image (1920x1080)
├── theme.txt                # GRUB theme config
├── LICENSE.md               # MIT License
└── README.md                # This file
```

---

## 🖼️ Theme Features

* Fully custom wallpaper with a glowing golem mascot
* Pastel forest tones (lavender, pollen, rose, periwinkle)
* Soft contrasts and readable text
* Compatible with 16:9 displays (1920x1080)

---

## 📦 Installation

1. Copy the theme folder to your system (adjust as needed):

```bash
sudo cp -r earthshaker.grub /boot/grub/themes/earthshaker
```

2. Edit your GRUB config:

```bash
sudo nano /etc/default/grub
# Add or update this line:
GRUB_THEME="/boot/grub/themes/earthshaker/theme.txt"
```

3. Update GRUB:

```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

4. Reboot and enjoy!

---

## 💜 Credits

* Inspired by [Catppuccin GRUB Theme](https://github.com/catppuccin/grub)
* Designed by Remus Alexander
* Mascot generated with AI, finalized by Earthshaker creative team
