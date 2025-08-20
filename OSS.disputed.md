# 存在争议和使用风险的开源软件列表

> [!CAUTION]
>
> 存在争议和使用风险的开源软件通常指客户端开源，但是依赖于非自由的网络服务（服务端闭源），且发生过数次数据泄露事件的软件。
>
> 不建议隐私要求高的用户使用这些软件，因为这些软件的服务提供方的可信任问题存在争议。

## 通信相关软件

1. **Telegram**：广泛使用的聊天互动平台。

   - 桌面客户端 GitHub 仓库：https://github.com/telegramdesktop/tdesktop
   - Android 客户端 GitHub 仓库：https://github.com/DrKLO/Telegram
   - iOS 客户端 GitHub 仓库：https://github.com/TelegramMessenger/Telegram-iOS
   - 相关软件：
     - 开源的 Telegram 关键词监控程序：https://github.com/Riniba/TelegramMonitor
   - 相关信息：
     - 端到端加密：私聊支持（需手动开启），群组不支持，加密实现库封闭源码。
     - 阅后即焚和隐私保护：**存在争议**，从 [https://zh.wikipedia.org/wiki/Telegram#非法出售个人信息](https://zh.wikipedia.org/wiki/Telegram#%E9%9D%9E%E6%B3%95%E5%87%BA%E5%94%AE%E5%80%8B%E4%BA%BA%E4%BF%A1%E6%81%AF) 可推断，用户在 Telegram 中的聊天数据会在 Telegram 的服务器上保存相当长的一段时间。而且从 [https://x.com/mirrorzk/status/1924841641720136028](https://x.com/mirrorzk/status/1924841641720136028) 上也可推测，Telegram 可能包含免费或付费的后台用户数据 API 调用服务，某些组织通过调用 Telegram 提供的 API 获取用户的部分信息。
     - 账户滥用（机器人账户）情况：较严重。
