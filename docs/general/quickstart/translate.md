# 翻译功能

翻译功能是 Bob 最核心的功能，本文主要介绍下翻译功能的使用方法。建议大家都认真看下，或许有新的发现呢。🤓

## 核心功能

**调用方式**

翻译功能支持多种调用方法，适配多种不同的使用场景，如下所示：

| 方式 | 描述 | 预览 |
| :---: | :---: | :---: |
| 划词翻译 | 选中需要翻译的文本之后，按下划词翻译快捷键即可（默认 `⌥ + D`） | ![划词翻译-句子](https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0508/translate_selection.gif) |
| 截图翻译 | 按下截图翻译快捷键（默认 `⌥ + S`），截取需要翻译的区域 | ![截图翻译-句子](https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0508/translate_snip.gif) |
| 输入翻译| 按下输入翻译快捷键（默认 `⌥ + A`），输入需要翻译的文本，`Enter` 键翻译 | ![输入翻译-单词](https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0508/translate_input.gif) |
| PopClip 调用 | 选中需要翻译的文本之后，点击 [PopClip](https://pilotmoon.com/popclip/) 插件图标即可，详情见 [PopClip 调用](/general/integration/popclip) | ![插件翻译-句子](https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0508/translate_popclip.gif) |

* 划词翻译在**可以选中文本，并且可以复制**的情况下使用
* 截图翻译建议在无法选中或复制的情况下使用
* 输入翻译通常在以上方法获取的文本不准的情况下使用
* PopClip 调用则比较适合喜欢用鼠标的用户

?> 如果记不住这么多快捷，可以点击通过菜单栏 Bob 图标的选项触发相应的功能。

**查词**

Bob 不只是支持翻译，如果对应的翻译服务提供的信息够多，其实你也可以把 Bob 当做简单的查词工具使用。例如目前金山词霸和有道翻译有词典数据，效果如下：

<img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0507/translate_dict.jpg" alt="translate dict" width=400 />

**翻译多开**

如果你有对照多家翻译服务的结果的需求，你可以开启多个翻译服务，目前最多支持**同时开启 10 个翻译服务**。

<img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0507/translate_more.jpg" alt="翻译多开" width=400 />

## 翻译窗口

翻译窗口主要组成部分：

<img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0507/translate_window.jpg" alt="翻译窗口" width=690 />

小提示：

* 翻译小语种时，指定源语言效果一般会更优
* 翻译窗口宽度不可拖拽，不过可以在「Bob 偏好设置 - 翻译 - 翻译设置」里面修改
* 翻译窗口右上角快捷设置菜单里面放了一些可能会比较常用设置项，可以探索下

翻译窗口内可用的快捷键：

| 功能 | 快捷键 |
|---|---|
| 翻译 | `↩︎` |
| 输入框换行 | `⇧ + ↩︎` 或者 `⌘ + ↩︎` |
| 重试 | `⌘ + R` |
| 收藏 | `⌘ + S` |
| 关闭窗口 | `⌘ + W` 或者 `⎋`（esc 键） |

## 配置服务

大家对于翻译服务可能会有不同的需求，Bob 接入了多家主流的翻译服务，你可以自由选择，详情请看[这篇文章](/general/advance/service.md)。

申请好秘钥之后，在这个页面添加服务。

<img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0507/translate_service.jpg" alt="翻译服务" width=800 />

## 收藏和历史记录

Bob 支持保存历史记录，对于较为重要的翻译结果你可以在翻译窗口按下 `⌘ + S` 键将其收藏，后续可以在收藏页面将其导出。

<img src="https://cdn.jsdelivr.net/gh/ripperhe/oss@master/2022/0507/translate_history.jpg" alt="历史记录" width=800 />

## 更多设置

更多的翻译相关设置在「 Bob 偏好设置-翻译」里面，可以自行探索下。