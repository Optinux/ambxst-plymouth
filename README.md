# ambxst-plymouth
A boot animation for ambxst. Runs at 640x360@48fps so it looks crisp and not too large on most displays at around ~WQHD resolution. I quite like on my 2880x1800 display, especially since its OLED. Theres ways to fully hide the scrolling text during boot but this depends heavily on your system config. Google is your friend here :)

1. `sudo pacman -S plymouth`
2. Clone this repo and move the *ambxst* folder to ` /usr/share/plymouth/themes/ `
3. `sudo plymouth-set-default-theme -R /usr/share/plymouth/themes/ambxst `

Preview:
![Demo Animation](boot-anim.gif)