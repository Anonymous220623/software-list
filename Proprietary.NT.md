# 仅支持 Windows 平台的闭源软件列表

> [!NOTE]
>
> ### 定义一个软件是否开源的标准
>
> 1. 如果一个软件的程序**核心部分开源**，在开放源码的部分能被编译为可投入生产的软件，且软件不强制依赖于闭源专有组件即可正常使用时，本仓库认定此类软件为开源软件。
>
>     相关案例：
> 
>       1. **VirtualBox** 开源，但 VirtualBox 的可选功能扩展包闭源，所以本仓库认定 VirtualBox 开源。
>
> 2. 如果一个软件的程序**核心部分开源**，但是开放源码的部分不能被编译为可投入生产的软件的情况下，本仓库认定此类软件本身为开源软件，但依赖于本软件的可投入生产软件为半开源软件。
> 
>      此处有一个重要的前提条件：**必须确保可投入生产软件的核心依赖于开源软件**。
>
>      相关案例：
> 
>       1. **Darwin-XNU** 开源，但使用 Darwin-XNU 内核的 MacOS 和 iOS 除非内核以外的组件不开源，所以本仓库认定 MacOS 和 iOS 半开源。
> 
> 3. 如果一个软件的程序**核心部分不开源**，即使公开语言资源文件/SDK/前端程序等**边缘组件**源码，本仓库依然认定此类软件为闭源软件。
> 
>     相关案例：
> 
>       1. **Windows** 内核层、系统应用层、开发工具链的核心部分（MSVC 编译器、链接器）闭源，但 MSVC STL、Windows Driver Framework 等边缘组件开源，所以本仓库认定 Windows 闭源。
> 

> [!NOTE]
>
> ### 该列表中所有可能的软件性质
>
> 1. 闭源免费软件，无增值服务
> 2. 闭源软件，主要功能完全免费，有可选收费服务
> 3. 闭源软件，主要功能收费，有受限的免费计划
> 4. 闭源软件，无免费计划
>
> 备注：某软件在有限时间内免费试用，但试用期结束后所有功能强行收费，**不算作该软件有受限的免费计划**。

> [!IMPORTANT]
>
> ### 关于部分软件流氓行为的声明
> 
> 1. 以下列出的软件截至本软件列表更新之前尚未报告出任何流氓行为。
> 2. 对于有严重流氓行为的软件，在此仓库完善之后，本人会新建一个流氓软件列表仓库。

## 系统管理工具

1. **Dism++**
   
   - 作者：初雨团队（Chuyu-Team）
   - 软件性质：闭源免费软件，无增值服务
   - GitHub 仓库 **(仅存储语言资源文件)**：[https://github.com/Chuyu-Team/Dism-Multi-language](https://github.com/Chuyu-Team/Dism-Multi-language)，软件默认为简体中文，大陆用户无需替换语言资源文件。
   - 软件下载地址（GitHub 发行版页面）：https://github.com/Chuyu-Team/Dism-Multi-language/releases

2. **Sysinternels** 工具集

   - 作者：Sysinternals 团队（后被微软收购）
   - 软件性质：闭源免费软件，无增值服务
   - 官方软件镜像站：https://live.sysinternals.com
   - Microsoft 产品页面：https://learn.microsoft.com/zh-cn/sysinternals
   - 产品使用文档 GitHub 仓库：https://github.com/MicrosoftDocs/sysinternals
