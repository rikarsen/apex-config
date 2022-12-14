# CFG Files 
1. [Download](https://github.com/rikarsen/apex-config/archive/refs/heads/main.zip) and extract it.
2. Move [autoexec.cfg](https://github.com/rikarsen/apex-config/blob/main/autoexec.cfg), [superglide.cfg](https://github.com/rikarsen/apex-config/blob/main/superglide.cfg), [superglide1.cfg](https://github.com/rikarsen/apex-config/blob/main/superglide1.cfg), [superglide2.cfg](https://github.com/rikarsen/apex-config/blob/main/superglide2.cfg) to the games directory cfg folder (Usually in C:\Program Files (x86)\Steam\steamapps\common\Apex Legends\cfg).
3. Rightclick on the game inside of Steam and go to "Properties".
4. Switch to the "General" Tab.
5. Add the command in launch options "+exec autoexec -full -high -dev -preload -novid -dxlevel95" (without the Quotation marks).

| Command | Description |
| --- | --- |
| `+exec` | Executes a cfg file on startup |
| `-full` | Forces the game to launch in fullscreen mode |
| `-high` | Sets the game thread priority to high |
| `-dev` | Skips EA intro on startup, can cause HUD flicker issues on NVIDIA cards |
| `-preload` | Enables preloading of textures at game start |
| `-novid` | Automatically skips the introduction video |
| `-dxlevel95` | The game will use DirectX 9 to reduce the load of the graphic card |

# Videoconfig
6. Press Win+R while you are on your desktop.
7. Paste this inside the Run box: "%USERPROFILE%\Saved Games\Respawn\Apex\local" (without the Quotation marks).
8. Move [videoconfig.txt](https://github.com/rikarsen/apex-config/blob/main/videoconfig.txt) in it.