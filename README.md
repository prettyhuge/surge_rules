# Surge Rules

Surge 是一个出色的网络抓包调试工具，它利用了 iOS9 的 Network Extension 新特性，完成了很多曾在旧版本的 iOS 上不可能做到的事情。

本项目是 Surge 的配置规则文件。

## 开发分支说明

### 文件

| 文件 | 说明 | 向 master 分支提交 |
| :--- | :--- | :---: |
| adblock.conf | 只有去广告规则 | 是 |
| adlist.txt | 广告网址列表参考 | 否 |
| proxy.conf | 代理规则 | 否 |
| module文件夹 | Surge 附加模块 | 选择性 |
| module/SSEncrypt.module | ShadowSocks模块 | 否 |

### 编辑说明

1. 请使用尽量简洁的方式进行编辑。
2. 为保持可维护性，请尽量按照升序进行排列。
3. 请尽量不要误伤。
