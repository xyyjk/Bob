<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2019/1222/bob-logo.png" width=240 />
</p>
<p align="center">
	<a href="https://github.com/ripperhe/Bob/releases/latest"><img src="https://img.shields.io/github/v/release/ripperhe/Bob?logo=github" alt="GitHub release" /></a>
	<a href="https://ripperhe.gitee.io/bob/"><img src="https://img.shields.io/badge/docsify-%E8%AF%A6%E7%BB%86%E4%BD%BF%E7%94%A8%E6%96%87%E6%A1%A3-brightgreen" alt="Document" /></a>
  <a href="https://ripperhe.gitee.io/bob/#/general/contact"><img src="https://img.shields.io/badge/QQ%20%E7%BE%A4-459542798-red" alt="QQ群" /></a>
</p>
<p align="center">
  <strong>Chinese</strong> | <a href="https://github.com/ripperhe/Bob/blob/master/README.en.md">English</a>
</p>

# Bob

Bob 是一款 macOS 平台 **翻译** 和 **OCR** 软件。

翻译功能：

- [x] 划词翻译
- [x] 截图翻译
- [x] 输入翻译
- [x] 翻译多开
- [x] 自定义插件
- [x] 自动识别语种
- [x] 驼峰拆分、蛇形拆分
- [x] AppleScript 调用
- [x] PopClip 调用

OCR 功能：

- [x] 截图识别
- [x] 访达选图识别
- [x] 离线识别
- [x] 连续识别
- [x] 二维码识别
- [x] 自动复制
- [x] 智能分段

## 如何安装

### 系统要求

macOS 10.13 及以上

### Homebrew Cask 安装

```bash
brew install --cask bob
```

### 手动安装

| 渠道 | 建议 | 下载 |
| --- | --- | --- |
| 从 [GitHub release](https://github.com/ripperhe/Bob/releases) 下载 | 国外从这里下载更快 | [点此下载 ⬇](https://github.com/ripperhe/Bob/releases/latest/download/Bob.zip) |
| ~~从 [Gitee release](https://gitee.com/ripperhe/Bob/releases) 下载~~ | ~~国内从这里下载更快~~ | ~~[点此下载 ⬇](https://gitee.com/ripperhe/Bob/attach_files/1011267/download/Bob.zip)~~ |

下载完成之后，解压并拖拽到**应用程序**文件夹即可

## 使用方法

详细使用方法请直接查看文档 👉 [点此跳转文档](https://ripperhe.gitee.io/bob/)

> 文档可能有缓存，最好强制刷新下网页 （Chrome 快捷键是 `Command + Shift + R`）

### 翻译功能

| 方式 | 描述 | 预览 |
| :---: | :---: | :---: |
| 划词翻译 | 选中需要翻译的文本之后，按下划词翻译快捷键即可（默认 `⌥ + D`） | ![划词翻译-句子](https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0508/translate_selection.gif) |
| 截图翻译 | 按下截图翻译快捷键（默认 `⌥ + S`），截取需要翻译的区域 | ![截图翻译-句子](https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0508/translate_snip.gif) |
| 输入翻译| 按下输入翻译快捷键（默认 `⌥ + A`），输入需要翻译的文本，`Enter` 键翻译 | ![输入翻译-单词](https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0508/translate_input.gif) |
| PopClip 调用 | 选中需要翻译的文本之后，点击 [PopClip](https://pilotmoon.com/popclip/) 插件图标即可，详情见 [PopClip 调用](/general/integration/popclip) | ![插件翻译-句子](https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0508/translate_popclip.gif) |

### OCR 功能

**截图识别**

* 按下「截图 OCR」快捷键（默认 `⇧ + ⌥ + S`）或者点击菜单栏 Bob 图标菜单中的「截图 OCR」
* 选中屏幕上的对应的位置
* 松手即可开始识别

<img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0507/snip_ocr.gif" alt="截图 OCR" width=660 />

**访达选图识别**

按下「访达选图 OCR」快捷键（没有设置默认快捷键，可去「 Bob 偏好设置-OCR-OCR 设置」添加）或者点击菜单栏 Bob 图标菜单中的「访达选图 OCR」。

在弹出的访达窗口中选中对应的图片文件（可以一次性选中多张），点击右下角「开始识别」即可。

<img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0507/file_ocr.jpg" alt="访达选图 OCR" width=600 />

## 感谢

* 感谢 [@isee15](https://github.com/isee15/Capture-Screen-For-Multi-Screens-On-Mac) 提供最初版本截图功能的思路
* 感谢 [@可口可乐](https://github.com/wwk7225) 长期帮忙解决用户反馈
* 感谢 [@ix4n33](https://github.com/IsaacXen) 不定期提供技术支持
* 感谢朋友们的赞赏 [赞赏列表](https://ripperhe.gitee.io/bob/#/general/reward)
* 感谢作者们发文支持 Bob（时间倒序）
    * @奇客派：[macOS 翻译工具 Bob 大更新：支持更多翻译服务，增强 OCR 功能](https://sspai.com/post/62721)
    * @鹿額：[截图/划词/输入都能查，快捷高效的 macOS 翻译工具: Bob](https://sspai.com/post/58249)
    * @Newlearnerの自留地：[Bob：一款 macOS 全局翻译软件，支持划词翻译和截图翻译](https://t.me/NewlearnerChannel/3329)

## 最后

目前本仓库主要用于部署使用教程和提供反馈渠道。

有任何问题或建议请优先在 GitHub [提 issue](https://github.com/ripperhe/Bob/issues)，回复不一定及时，我有空闲时间一定会来处理的。

另外，非常欢迎 [加入 QQ 群](https://ripperhe.gitee.io/bob/#/general/contact) 讨论。