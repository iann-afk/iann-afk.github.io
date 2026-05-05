# token-monitor

Privacy Policy — Token Monitor

Last updated: 2026-05-05_

## What we collect

**Nothing leaves your device.** Token Monitor does not collect, transmit, sell,
or share any personal information, conversation content, browsing history, or
usage analytics with us or any third party.

## What the extension reads locally

To show your token usage on the page you're viewing, the extension reads:

- The text content of the current AI conversation (Claude, ChatGPT, Gemini,
  AI Studio, Perplexity, or Poe pages only — see `host_permissions` in
  `manifest.json`).
- The text in the prompt input box.
- The model name displayed by the AI tool, for context-window matching.

This reading happens **entirely inside your browser**. The text never leaves
your device.

## What the extension stores

The extension uses the standard Chrome Storage API to save your settings:

- **`chrome.storage.sync`** (synced across your Chrome profile, signed in):
  alert thresholds, alarm on/off, sound style, volume, display language.
- **`chrome.storage.local`** (this device only): floating widget position,
  minimized state, hidden state.

We do not have a server. Data stored here is owned and controlled by you and
your Chrome profile, and can be cleared at any time from
`chrome://extensions` → Token Monitor → "Site data" / by uninstalling.

## Permissions explained

| Permission         | Why it's needed                                             |
| ------------------ | ----------------------------------------------------------- |
| `storage`          | Save your settings (thresholds, language, sound prefs).     |
| Host permissions   | Inject the floating meter into supported AI sites only.     |

The extension requests **no** permissions for `tabs`, `webRequest`, identity,
geolocation, or any broad host pattern such as `<all_urls>`.

## Third parties

There are none. The extension does not load remote scripts, fonts, or
analytics. All code that runs is in this package.

## Children's privacy

The extension does not knowingly collect any data from anyone, including
children under 13.

## Changes

If we ever change this policy in a way that affects how data is handled, we
will publish the new version with the new release notes and a new "Last
updated" date.

## Contact

Questions? Open an issue on the project repository.

---

# 隐私政策 — Token 监控

_最后更新：2026-05-05_

## 我们收集什么

**没有任何数据离开你的设备。** Token 监控不向我们或任何第三方收集、传输、出售或共享任何
个人信息、对话内容、浏览历史或使用统计。

## 扩展在本地读取的内容

为了在你查看的页面上显示 token 用量，扩展会读取：

- 当前 AI 对话的文本内容（仅限 Claude、ChatGPT、Gemini、AI Studio、Perplexity、
  Poe，详见 `manifest.json` 中的 `host_permissions`）。
- 输入框中的文本。
- AI 工具显示的模型名称，用于匹配上下文窗口大小。

以上读取**完全在你的浏览器内进行**，文本不会离开你的设备。

## 扩展存储的内容

使用 Chrome 标准存储 API 保存你的设置：

- **`chrome.storage.sync`**（跨已登录 Chrome 设备同步）：阈值、提示音开关、音效、
  音量、显示语言。
- **`chrome.storage.local`**（仅本机）：悬浮窗位置、最小化状态、隐藏状态。

我们没有服务器。数据由你和你的 Chrome 账号控制，可随时清除：访问
`chrome://extensions` → Token 监控 → "网站数据"，或卸载扩展。

## 权限说明

| 权限           | 为何需要                                          |
| -------------- | ------------------------------------------------- |
| `storage`      | 保存你的设置（阈值、语言、提示音偏好）。          |
| Host 权限      | 仅向支持的 AI 站点注入悬浮窗。                    |

扩展**不**请求 `tabs`、`webRequest`、身份、地理位置或 `<all_urls>` 等广泛权限。

## 第三方

没有。扩展不加载任何远程脚本、字体或分析代码，所有运行代码都在本扩展包内。

## 儿童隐私

扩展不会主动收集任何人（包括 13 岁以下儿童）的数据。

## 变更

如本政策变更影响数据处理方式，我们将在新版本中发布更新版，并标注新的"最后更新"日期。

## 联系

有疑问可在项目仓库中提交 issue。
