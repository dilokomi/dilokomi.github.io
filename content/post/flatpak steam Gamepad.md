+++
date = '2025-06-20T10:17:20+08:00'
title = 'Flatpak steam Gamepad'
categories = ["linux"]
tags = ["steam","archlinux"]
+++
<https://github.com/flathub/com.valvesoftware.Steam/issues/699#issuecomment-1752656933>

```sh
sudo wget -O /etc/udev/rules.d/60-steam-input.rules https://raw.githubusercontent.com/ValveSoftware/steam-devices/master/60-steam-input.rules
```
