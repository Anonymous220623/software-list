> [!WARNING]
> 
> 以下列出的开源软件除 [Screen Play](#动态壁纸软件) 之外仅支持 Windows 平台。

## 一. Windows 系统探查和管理工具

### Windows 资源管理器（`explorer.exe`）替代品

> [!WARNING]
> 
> Files 仅支持 Windows 10/11，确保 Windows UWP 应用安装程序未被卸载，且运行时环境正常。

1. **Files**（C#/.NET/UWP）：页面类似 Windows 11 的 Windows 文件管理器。
   
   - GitHub 仓库：https://github.com/files-community/Files
   - 官网：https://files.community

2. **Explorer++**（C/C++/Win32）：多标签页 Windows 文件管理器。
   
   - GitHub 仓库：https://github.com/derceg/explorerplusplus
   - 官网：https://explorerplusplus.com

3. **File Explorer**（C#/.NET）：多标签页 Windows 文件管理器。
   
   - GitHub 仓库：https://github.com/omeryanar/FileExplorer

### 任务管理器（`taskmgr.exe`）、性能监视器（`perfmon.msc`）替代品

> [!IMPORTANT]
> 
> System Informer 的 GitHub 仓库包含闭源链接库（涉及与 Windows 内核交互的模块，封闭源码以防止恶意软件利用）：[/KSystemInformer/bin-signed](https://github.com/winsiderss/systeminformer/tree/master/KSystemInformer/bin-signed)：

1. **System Informer**：全面的 Windows 系统管理器。

   - Winsider 官网：http://windows-internals.com
   - GitHub 仓库：https://github.com/winsiderss/systeminformer
  
2. **TaskExplorer**（Qt/C++）：Windows 系统管理器，后端基于 System Informer（去除了 System Informer 的闭源组件）。
   
   - GitHub 仓库：https://github.com/DavidXanatos/TaskExplorer

3. **System Explorer**：Windows 系统进程、服务管理器和对象查看器。
   
   - GitHub 仓库：https://github.com/zodiacon/SystemExplorer

### 系统对象查看器

1. **Object Explorer**：Windows 系统对象查看器。
   
   - GitHub 仓库：https://github.com/zodiacon/ObjectExplorer

### 注册表编辑器（`regedit.exe`）替代品

1. **Total Registry**：Windows 注册表编辑器。
   
   - GitHub 仓库：https://github.com/zodiacon/TotalRegistry

### Syscall

1. **Syscall Tables**
   
   - GitHub 仓库：https://github.com/hfiref0x/SyscallTables

### 硬链接/符号链接查看工具

1. **Link Shell Extension**：Windows NTFS 文件系统链接查看器，集成至 Windows 资源管理器的右键菜单中。
   
   - GitLab 仓库：https://gitlab.com/schinagl/link-shell-extension
   - 项目主页：https://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html

## 二. Windows 用户页面个性化工具

### 动态壁纸软件

1. **Lively Wallpaper**（C#/.NET/UWP）：适用于 Windows 10/11 的桌面动态壁纸软件，支持将本地视频/GIF/网页/应用程序或游戏页面设置为桌面动态壁纸。
   
   - GitHub 仓库：https://github.com/rocksdanister/lively
   - Microsoft Store 链接：[https://apps.microsoft.com/detail/9ntm2qc6qws7](https://apps.microsoft.com/detail/9ntm2qc6qws7)，应用 ID：`9ntm2qc6qws7`

> [!WARNING]
>
> Screen Play 即将完成对 KDE Plasma 桌面环境的支持，之后该项目将被移动至 OSS.md。

2. **Screen Play**（C++20/Qt6/QML）：适用于 Windows 和 macOS 的跨平台桌面动态壁纸软件，支持视频/GIF/QML/JS，可添加自定义桌面部件，支持 Steam 创意工坊。
   
   - GitLab 仓库：https://gitlab.com/kelteseth/ScreenPlay
   - Steam 链接：[https://store.steampowered.com/app/672870/ScreenPlay](https://store.steampowered.com/app/672870/ScreenPlay)，应用 ID：`672870`
   - 官网：https://screen-play.app
   - Screen Play 文档 GitLab 仓库：https://gitlab.com/kelteseth/ScreenPlayDocs
   - Screen Play 文档官网：https://kelteseth.gitlab.io/ScreenPlayDocs

### Windows 桌面小组件个性化工具

1. **Rainmeter**：提供各种桌面主题包。

   - 官网：https://rainmeter.net
   - GitHub 仓库：https://github.com/rainmeter/rainmeter

### Windows 系统菜单和右键菜单个性化工具

1. **SmartSystemMenu**：扩展 Windows 系统菜单的工具。
   
   - GitHub 仓库：https://github.com/AlexanderPro/SmartSystemMenu

### Windows 开始菜单/任务栏个性化工具

1. **TranslucentTB**：自定义 Windows 任务栏的工具。
   
   - 官网：https://translucenttb.com
   - GitHub 仓库：https://github.com/TranslucentTB/TranslucentTB

2. **TaskbarX**：自定义 Windows 任务栏的工具（该项目已于 2025 年 6 月 12 日停止维护）。
   
   - 官网：https://taskbarx.org
   - GitHub 仓库：https://github.com/ChrisAnd1998/TaskbarX

3. **OpenShell**：将 Windows 10/11 开始菜单样式修改为现代 Windows 7 的工具，[Classic-Shell](https://github.com/coddec/Classic-Shell)（已存档） 的延续版本。
   
   - GitHub Pages：https://open-shell.github.io/Open-Shell-Menu
   - GitHub 仓库：https://github.com/Open-Shell/Open-Shell-Menu

4. **RetroBar**：将 Windows 10/11 的开始菜单和任务栏样式修改为 Windows 95/98/Me/2000/XP/Vista 的工具。
   
   - GitHub 仓库：https://github.com/dremin/RetroBar

### Windows 窗口非客户区个性化工具

1. **DWMBlurGlass**：在 Windows 10/11 上实现 Windows 7 窗口磨砂半透明效果的工具。

   - GitHub 仓库：https://github.com/Maplespe/DWMBlurGlass

### 其他 Windows Explorer 个性化工具

1. **Windhawk**：Windows 资源管理器的定制工具和平台，拥有强大的 mod 市场，使用 VSCodium 作为用户页面和 mod 开发工具。
   
   - 官网：https://windhawk.net
   - Ramen Software 官网：https://ramensoftware.com
   - 客户端应用源代码（托管在 GitHub 上）：https://github.com/ramensoftware/windhawk
   - Windhawk 官方提供的 mod 源码仓库（托管在 GitHub 上）：https://github.com/ramensoftware/windhawk-mods
   - Windhawk Mod 市场（其中所有 mod 源码都公开可见）：https://windhawk.net/mods

2. **ExplorerPatcher**：功能全面且覆盖 Windows 版本广的资源管理器修改工具，可替代 StarDock Start 11 和 StartAllBack/StartIsBack 的修改任务栏和开始菜单的主要功能。
   
   - GitHub 仓库：https://github.com/valinet/ExplorerPatcher

## 三. Windows 应用程序运行辅助工具

1. **Locale Emulator**：针对特定 Windows 应用程序进行系统语言和系统时区的伪造工具。

   - 项目主页：https://pooi.moe/Locale-Emulator
   - GitHub 仓库 **（已存档，不再维护）**：https://github.com/xupefei/Locale-Emulator
