# 开放源代码软件（OSS）列表

> [!WARNING]
> 
> 1. 该软件列表排名不分先后顺序；
> 2. 每个软件条目都会列出 SVN、Git 或其他版本控制系统的源码仓库。

## 设备控制软件

1. **RustDesk**：远程控制软件，支持全平台（iOS 设备不支持被控制）。
   
   - 官网：https://rustdesk.com
   - GitHub 仓库：https://github.com/rustdesk/rustdesk

2. **Scrcpy**：可通过计算机控制 Android 设备。
   
   - GenyMotion 官网：https://www.genymotion.com
   - GitHub 仓库：https://github.com/Genymobile/scrcpy

## 驱动程序下载和管理工具

1. **Snappy Driver Installer**
   
   - 官网：https://sdi-tool.org
   - 下载页面：https://sdi-tool.org/download
   - SourceForge SVN 仓库：https://svn.code.sf.net/p/snappy-driver-installer/code/trunk

## 多媒体相关工具

### 一. 视频转码和格式转换相关工具

1. **HandBrake**：视频转码和格式转换工具，支持几乎全部的视频格式和码率。
   
   - 官网：https://handbrake.fr
   - GitHub 仓库：https://github.com/HandBrake/HandBrake

2. **MKVToolNix**：将任何格式的视频文件、字幕文件和音频混流为 Matroska（MKV）媒体文件。
   
   - 官网：https://mkvtoolnix.download
   - Git 仓库：https://codeberg.org/mbunkus/mkvtoolnix
   - 打包的源码文件列表：https://mkvtoolnix.download/sources

3. **FileConverter**：常见格式的视频转换，以及图片和文档的格式转换工具，集成至 Windows 的右键菜单中，可替代格式工厂。
   
   - GitHub 仓库：https://github.com/Tichau/FileConverter

### 二. 视频播放器

1. **VLC Media Player**：由 VideoLAN 非营利组织开发和维护的跨平台视频播放器项目。
   
   - VideoLAN 组织官网：https://www.videolan.org
   - VideoLAN GitLab 实例主页：https://code.videolan.org
   - VideoLAN GitHub 组织主页（镜像）：https://github.com/videolan
   - VideoLAN 构建二进制发行版镜像站：https://get.videolan.org

   各平台播放器项目详细信息：

   1. 桌面视频播放器（适用平台：Windows【Win32】/macOS/Linux/BSD/ReactOS/...，源代码位于主仓库）：

      - GitLab 仓库：https://code.videolan.org/videolan/vlc
      - GitHub 镜像仓库：https://github.com/videolan/vlc

   2. Android 视频播放器：

      - GitLab 仓库：https://code.videolan.org/videolan/vlc-android
      - GitHub 镜像仓库：https://github.com/videolan/vlc-android

   3. iOS 视频播放器：
  
      - GitLab 仓库：https://code.videolan.org/videolan/vlc-ios
      - GitHub 镜像仓库：https://github.com/videolan/vlc-ios

   4. Windows UWP 视频播放器：

      - GitLab 仓库：https://code.videolan.org/videolan/vlc-winrt
      - GitHub 镜像仓库：https://github.com/videolan/vlc-winrt


2. **MPC-HC**：Windows 平台视频播放器，K-lite Codec Pack 的默认播放工具。
   
   - 官网：https://mpc-hc.org
   - 原 GitHub 仓库（不再维护）：https://github.com/mpc-hc/mpc-hc
   - 由 clsid2 维护的 GitHub 仓库：https://github.com/clsid2/mpc-hc

3. **MPC-BE**：由 Aleksoid1978 维护的 MPC-HC 的分支。
   
   - GitHub 仓库：https://github.com/Aleksoid1978/MPC-BE

4. **MPV**：跨平台命令行视频播放器。
   
   - GitHub 仓库：https://github.com/mpv-player/mpv
   - 官网：https://mpv.io
   - MPV-Builds 项目：

     - 使用 CMake 和 MinGW-w64 手动构建的 MPV 的 Windows 版本的构建配置文件仓库（发行版请跳转至 [Release 页面](https://github.com/shinchiro/mpv-winbuild-cmake/releases)）：https://github.com/shinchiro/mpv-winbuild-cmake
     - 使用 GitHub Action 自动构建的 MPV 的 Windows 版本的构建配置文件仓库（发行版请跳转至 [Release 页面](https://github.com/zhongfly/mpv-winbuild/releases)）：https://github.com/zhongfly/mpv-winbuild


### 三. 屏幕录制工具/截图工具

1. **OBS Studio**：强大的录屏和直播软件。
   
   - 官网：https://obsproject.com
   - GitHub 仓库：https://github.com/obsproject/obs-studio
   - Microsoft Store 链接：[https://apps.microsoft.com/detail/xpffh613w8v6lv](https://apps.microsoft.com/detail/xpffh613w8v6lv)，应用 ID：`xpffh613w8v6lv`
   - Steam 链接：[https://store.steampowered.com/app/1905180/OBS_Studio/](https://store.steampowered.com/app/1905180/OBS_Studio/)，应用 ID：`1905180`

### 四. 图片编辑器

1. **GIMP**：跨平台图片编辑器，GNOME 项目的一部分。
   
   - 官网：https://www.gimp.org
   - GitHub 镜像仓库：https://github.com/GNOME/gimp
   - GitLab 仓库：https://gitlab.gnome.org/GNOME/gimp

2. **ImageMagick**：适用于 Windows 和 Linux 的图片编辑器。
   
   - 官网：https://imagemagick.org
   - GitHub 仓库：https://github.com/ImageMagick/ImageMagick

3. **Graphite**：使用 Rust 编写的图片编辑器。

    - 官网：https://graphite.rs
    - GitHub 仓库：https://github.com/GraphiteEditor/Graphite
    - 官方 Web 实例：https://editor.graphite.rs

> [!WARNING]
>
> 截至 2025 年 8 月，Graphite 仍只支持 Web 端，且暂未推出第一个桌面端正式版本，在该项目第一个桌面端正式版本更新之前，本仓库会持续更新此项目的进度。
> 对该项目感兴趣的用户可以前往 [https://editor.graphite.rs](https://editor.graphite.rs)（Graphite 官方 Web 实例）体验新功能。
   

### 五. 视频编辑器

1. **OpenShot**（Python,PyQt【前端】/C++【后端】）：跨平台视频编辑器。
   
   - 官网：https://www.openshot.org
   - GitHub 组织：https://github.com/OpenShot

2. **Kdenlive**（C++/QML/Qt5/Qt6）：跨平台视频编辑器，KDE 项目的一部分。
   
   - 官网：https://kdenlive.org
   - GitHub 镜像仓库：https://github.com/KDE/kdenlive
   - GitLab 仓库：https://invent.kde.org/multimedia/kdenlive

3. **Shotcut**（C++/QML/Qt5/Qt6）：跨平台视频编辑器。
   
   - 官网：https://www.shotcut.org
   - GitHub 仓库：https://github.com/mltframework/shotcut

### 六. 字幕编辑器

1. **Subtitle Edit**：使用 C# 编写的，支持 Windows 平台的字幕编辑器。
   
   - GitHub 仓库：https://github.com/SubtitleEdit/subtitleedit
   - 官网：http://www.nikse.dk/subtitleedit

2. **Aegisub**：跨平台字幕编辑器。
   
   - 官网：https://aegisub.org
   - 已存档的 GitHub 仓库：https://github.com/Aegisub/Aegisub
   - 维护的 GitHub 仓库：https://github.com/TypesettingTools/Aegisub

## 操作系统/操作系统内核

1. **Linux**: 全世界影响力最大的开放源码操作系统内核。
   
   - Linux 基金会官网：https://www.linux.org
   - Linux Kernel Archives 官网：https://www.kernel.org
   - GitHub 仓库：https://github.com/torvalds/linux
   - 项目官方源码镜像站（Git）：https://git.kernel.org
   - Google 提供的源码镜像站（Git）：https://kernel.googlesource.com

2. **BSD**：Unix 衍生操作系统家族。
   
   - **OpenBSD**：
     - GitHub 组织：https://github.com/openbsd
     - 官网：https://www.openbsd.org
       
   - **NetBSD**：
     - GitHub 组织：https://github.com/NetBSD
     - 官网：https://www.netbsd.org
       
   - **FreeBSD**:
     - GitHub 组织：https://github.com/freebsd
     - 官网：https://www.freebsd.org

3. **Darwin-XNU**：Apple 基于 BSD 系统家族和 Mach 微内核开发，用于 MacOS 和 iOS 的混合内核。
   
   - GitHub 仓库：https://github.com/apple-oss-distributions/xnu
   - GitHub 仓库（已存档）：https://github.com/apple/darwin-xnu

4. **ReactOS**：类 Windows NT 操作系统，内核层代码为该项目原创，应用层引用 [Wine 项目](#一-应用兼容层)源码，**该操作系统目前尚未稳定**。
   
   - 官网：https://reactos.org
   - GitHub 仓库：https://github.com/reactos/reactos

5. **SerenityOS**：使用 C++ 编写的类 Unix 操作系统，支持 x86_64、ARM 和 RISC-V 架构。
   
   - 官网：https://serenityos.org
   - GitHub 仓库：https://github.com/SerenityOS/serenity

## 办公辅助和自动化软件

### 一. 办公套件

1. **LibreOffice**：跨平台办公套件，由文档基金会维护。
   
   - GitHub 组织：https://github.com/libreoffice
   - Gerrit：https://git.libreoffice.org
   - 已发布版本的源代码压缩包：https://download.documentfoundation.org/libreoffice/src
   - 官网：
     - https://www.libreoffice.org
     - https://zh-cn.libreoffice.org

2. **ONLYOFFICE**：跨平台办公和协作套件。
   
   - 主要产品：
     - Documents App：移动端（Android/iOS）文档编辑器和 PDF 阅读/表单填写工具。
       - GitHub 仓库：https://github.com/ONLYOFFICE/documents-app-android
     - Desktop Editors：PC 端（Windows/macOS/Linux）文档/表格/演示/PDF 编辑器。
       - GitHub 仓库：https://github.com/ONLYOFFICE/DesktopEditors
     - Document Server（ONLYOFFICE Docs）：云端办公和协作套件。
       - GitHub 仓库：https://github.com/ONLYOFFICE/DocumentServer
   - 官网：https://www.onlyoffice.com
   - GitHub 组织：https://github.com/ONLYOFFICE

3. **Apache OpenOffice**：由 Apache 基金会维护的办公套件。
   
   - 官网：https://www.openoffice.org
   - GitHub 仓库：https://github.com/apache/openoffice

> **Apache OpenOffice 和 LibreOffice 的关系和发展历史**：https://zh.wikipedia.org/zh-cn/LibreOffice#历史
> 
> ![image](assets/1.png)

4. **Collabora Online**：基于 Web 的办公套件，是 LibreOffice Online 的活跃分支（LibreOffice Online 已不再积极维护）。
   
   - 官网：https://www.collaboraonline.com
   - GitHub 组织：https://github.com/CollaboraOnline

### 二. PDF/电子书查看器

1. **SumatraPDF**：Windows 平台 PDF/电子书查看器，基于 MuPDF。
   
   - 官网：https://www.sumatrapdfreader.org
   - GitHub 仓库：https://github.com/sumatrapdfreader/sumatrapdf

2. **Okular**：跨平台 PDF/电子书查看器，基于 Poppler，KDE 项目的一部分。
   
   - 官网：https://okular.kde.org
   - GitHub 镜像仓库：https://github.com/KDE/okular
   - GitLab 仓库：https://invent.kde.org/graphics/okular

3. **Evince**：Linux PDF/电子书查看器，基于 Poppler，GNOME 项目的一部分。
   
   - GitHub 镜像仓库：https://github.com/GNOME/evince
   - GitLab 仓库：https://gitlab.gnome.org/GNOME/evince

## 字体相关工具

### 一. 字体编辑器

1. **FontForge**：跨平台字体编辑器，具有 Python 解释器绑定。
   
   - 官网：https://fontforge.org
   - GitHub 仓库：https://github.com/fontforge/fontforge
   
   - 官方文档主页：
     
     - https://fontforge.org/en-US/documentation
     - https://fontforge.org/en-US/developers

### 二. 字体渲染工具

1. **FreeType**：跨平台字体渲染引擎。
   
   - 官网：https://freetype.org
   - GitLab 仓库：https://gitlab.freedesktop.org/freetype/freetype
   - GitHub 镜像仓库：https://github.com/freetype/freetype

2. **MacType**：Windows 平台字体渲染引擎，可将字体更改为 macOS/Linux 用户页面的样式。
   
   - 官网：https://www.mactype.net
   - GitHub 仓库：https://github.com/snowie2000/mactype

## Web OS/Web OS UI

1. **Puter**：基于网页的桌面操作环境，用户页面类似 GNOME/MacOS。
   
   - GitHub 仓库：https://github.com/HeyPuter/puter
   - 官网：https://puter.com

2. **daedalOS**：同 Puter，但用户页面类似 Windows 10。
   
   - GitHub 仓库：https://github.com/DustinBrett/daedalOS
   - 作者 DustinBrett 网站：https://dustinbrett.com

## 磁盘/光盘映像写入、系统盘制作相关工具

1. **Ventoy**：系统镜像虚拟挂载工具，可实现一个 U 盘作为多系统启动盘。
   
   - GitHub 仓库：https://github.com/ventoy/Ventoy
   - 官网：https://www.ventoy.net

2. **Rufus**：Windows 上将光盘映像写入 U 盘的工具，支持系统启动盘制作。
   
   - GitHub 仓库：https://github.com/pbatard/rufus
   - 官网：https://rufus.ie

3. **BalenaEtcher**：同 Rufus，但支持跨平台。
   
   - GitHub 仓库：https://github.com/balena-io/etcher
   - 官网：https://etcher.io
