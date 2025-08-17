# 微博荐读屏蔽脚本 Weibo Selection Killer

这是一个可以让你屏蔽 **微博荐读** 的 userscript 。

**重要提示**：此脚本可能会随着 _微博_ 网站的更新而失效。

![screenshot1.png](screenshot1.png)

------

## 使用说明

### 安装

#### ①安装用户脚本管理器

用户需先安装用户脚本管理器，推荐使用 **[篡改猴/油猴（Tampermonkey）](https://www.tampermonkey.net/)**：

- [火狐附加组件](https://addons.mozilla.org/zh-CN/firefox/addon/tampermonkey/)

或其他同类扩展程序。用户脚本管理器的安装等相关资料均可参见 [Greasy Fork](https://greasyfork.org/)。

#### ②安装本用户脚本

在完成安装用户脚本管理器后，安装本用户脚本。以下提供两种安装渠道：

- Greasyfork脚本安装地址：<https://greasyfork.org/scripts/546066>，点击页面上的 _安装此脚本_ 即可。
- 如果您访问 greasyfork.org 有困难，可以尝试这个 [GitHub链接](https://github.com/catscarlet/weibo-selection-killer/raw/refs/heads/main/weibo-selection-killer.user.js) 进行安装

### 使用

成功安装后，**「最新微博」** 页面（地址前缀为 `https://weibo.com/mygroups` ）的 *荐读* 内容将会被深灰色方块遮挡且不可点击。实现眼不见心不烦。

目前仅支持 **「最新微博」** 页面，在 **「全部关注」** 以及其他页面不生效。

### 兼容性

脚本可正确在以下用户脚本管理器中运行

- Tampermonkey: 5.3.3

脚本可正确在以下浏览器中运行。

- Firefox: 141.0.3

------

## 源码

Github： <https://github.com/catscarlet/weibo-selection-killer>

------

## LICENSE

This project is licensed under **GNU AFFERO GENERAL PUBLIC LICENSE Version 3**
