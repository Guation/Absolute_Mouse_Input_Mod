# Absolute Mouse Input Mod

Minecraft每次采集鼠标移动后会将鼠标位置重置到屏幕正中心，当游戏运行在本地时，这个设计当然没有任何问题。但是当我们在远程桌面（RDP）中运行游戏时，问题发生了，我们一旦开始移动鼠标，游戏的视角将开始疯狂旋转。为什么会这样？因为RDP会将控制机的鼠标位置作为绝对坐标发送给被控机，当游戏捕获鼠标位置时就会因为鼠标位置与中心点偏移过大而产生大幅度视角移动。本MOD通过移除鼠标位置重置，使控制机与被控机鼠标位置一致。

## Licensing

This project is multi-licensed.

### The Template (`Initial commit`)
The code and assets from the following specific commits:
- [`Initial commit`](https://github.com/Guation/Absolute_Mouse_Input_Mod/commit/8b65ea0e3055404c5e0d7066c5ef3f210249b877)

are released under the terms of the **Unlicense** and **Creative Commons 1.0 Universal (CC0 1.0)**. This means that part of the project is effectively in the public domain and can be used without any restrictions.

### All Subsequent Work
**All other commits, modifications, and original contributions** to this repository past the aforementioned points are licensed under the **GNU General Public License v3.0 (GPLv3)** only.

The full text of both licenses can be found in the project's root directory:
- `LICENSE` (GPLv3)
- `LICENSE.TEMPLATE` (Unlicense)

---

### Exceptions
Any file that contains a specific licensing header (e.g., within its source code comments) shall have its terms prevail over the general project licensing stated above.
