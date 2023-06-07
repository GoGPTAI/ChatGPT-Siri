# 👉ChatGPT Siri 国内版 - 免魔法，需要APIKey

ChatGPT是由[OpenAI](https://www.openai.com/)训练的一款大型语言模型，能够和你进行任何领域的对话。

## [ChatGPT 国内中文版 GoGPT](https://gogpt.vip/?channel=git)

通过 Siri 启动「快捷指令」连接 ChatGPT API，让 Siri 变身 AI 聊天助手。你可以直接和 Siri 说出你的问题，Siri 会回答你。现在我们的 Siri 终于变得智能了，可以和我们对答如流！而这一切只需要一个快捷指令和就可以做到了。

为了方便所有用户的使用，我们分了三个版本；

|编号|名称|是否需要API_Key|是否需要魔法|是否收费|
|--|--|--|--|--|
|1|[ChatGPT Siri 官方版](./README_openai.md)|需要|需要|否|
|2|[ChatGPT Siri 国内版](./README.md)|需要|不需要|否|
|3|[ChatGPT Siri 定制版](./README_custom.md)|不需要|不需要|是|

<br/>

##  👉 [ChatGPT Siri 官方版](./README_openai.md) - 需要魔法 - 需要APIKey

## 👉 [ChatGPT Siri 定制版](./README_custom.md) - 不需要魔法，不需要APIKey

<br/>

# 准备工作

为了方便

- 确保 API 帐户有足够余额：https://platform.openai.com/account/usage
- 使用 Siri 启动快捷指令，打开设置-》Siri 回答-》自动。钩上“始终显示你对Siri说的话”，可以看到自己说的话，方便查看识别是否精准。确保发送给ChatGPT的问题是你想问的。
- 想要练习纯英文口语对话，请使用国内定制版，且把Siri语言设置为English，Siri的识别更精准，对话更流畅。
- 保存txt文件：需要打开「设置」- Apple ID - iCloud - iCloud 云盘 功能，才能使用保存到 txt 文件功能。

## 其他相关问题

- 如何安全使用API key（英文）：https://help.openai.com/en/articles/5112595-best-practices-for-api-key-safety
- API keys: https://platform.openai.com/account/api-keys
- API 用量: https://platform.openai.com/account/usage
- API 价格: https://openai.com/pricing
- ChatGPT API 常见问题: https://help.openai.com/en/articles/7039783-chatgpt-api-faq

# 快捷指令下载

点击下面链接下载快捷指令，支持 iPhone、iPad、Mac、HomePod、CarPlay。

## 智能助手 2.0

1. 支持连续聊天，退出聊天，开始新聊天，自定义 API key，自定义 prompt 系统消息，自定义提示语。
2. 支持模型选择，支持gpt-3.5-turbo和pt-4；
3. 自动复制最后一次回复到剪贴板；
4. 自动保存聊天数据到 txt 文件中，记录包含每次对话的发送和接收时间、tokens 消耗统计。
5. 聊天记录按天分不同文件夹保存，保存位置：打开「文件」app，找到：iCloud 云盘/Shortcuts/ChatGPT-log 目录即可查看，支持 iCloud 同步。
6. 需要打开「设置」- Apple ID - iCloud - iCloud 云盘 功能，才能使用保存到 txt 文件功能。
   
   ## 下载戳下面：

- ## 👉 [简体中文版](https://www.icloud.com/shortcuts/dc578e64d5d84f7b8a43e4249d138f91)
- 地址：[https://www.icloud.com/shortcuts/dc578e64d5d84f7b8a43e4249d138f91](https://www.icloud.com/shortcuts/dc578e64d5d84f7b8a43e4249d138f91)

- ---

  ## GPT4.0支持

> gpt-4只支持有gpt-4资格的APIKey使用，申请GPT-4接口，到官网申请，申请时需要加入waitlist，加入后会收到确认加入waitlist邮件。然后需要等待邀请你使用 gpt-4 api 的确认邮件，拿到资格后，在 playground 后台可以看到，能选择 gpt-4模型进行测试。没有 gpt-4 资格请选择使用 gpt-3.5-turbo 模型。

- gpt-4 api waitlist: https://openai.com/waitlist/gpt-4-api
- playground：https://platform.openai.com/playground?mode=chat

<img width="500" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/playground-gpt-4.jpg?raw=true" />

# 常见问题

> 此版本是国际版，在能访问OpenAI的接口时可用；不能访问OpenAI 接口，且无魔法、梯子的请访问国内版本；
> 
> 我的测试设备是iOS16。据有用户反应，在低版本iOS上，1.2 版本安装不了，你可以选择低版本安装。

# API key 获取

使用「快捷指令」调用 ChatGPT API，必须要有 OpenAI API key。你可以到 OpenAI 官网免费获取，步骤如下：

1. 到 https://platform.openai.com 注册账号并登陆
2. 点击右上角头像，选择 “View API keys”
3. 点击页面右侧 “Create new secret key” 按钮生成 API key
4. 复制 API key，备用。注意 API key 只出现一次。忘了只能重新生成一个新的key。

使用 API 需要付费，价格为 $0.0020 / 1K tokens，1k tokens 大约等于 750 个单词，或者 500 个汉字。OpenAI 新用户在头三个月会有 $5 美元免费额度供使用。因此最好不要把 API key 和其他人共享，如果 API key 泄露，可以到 OpenAI 后台删掉，重新生成一个新的。

# 编辑「快捷指令」替换 API key

打开「快捷指令」app，找到下载的「智能助手」快捷指令，长按选择「编辑」，将上面的 API key 粘贴到下面文本框中。

<img width="300" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri_1.jpg?raw=true" />

# 使用方法

用 Siri 启动「快捷指令」，直接说 “嘿，Siri，智能助手”，然后就可以开始和 Siri 聊天了，我们的 Siri 变得非常智能，enjoy！🎉

<img width="300" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri_0.jpeg?raw=true" />

如果你不喜欢这个名字，你可以长按选择重新命名，改成任意你喜欢的名字，然后用 Siri 唤醒就直接说 “嘿，Siri，xxx”，xxx 是你修改的名字，最好不要加特殊符号什么的，不好念😂，识别匹配不了就启动不了！

<img width="300" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri_2.png?raw=true" />

你当然也可以直接点击使用「快捷指令」，这个时候是以对话框的形式使用，不会读出来，添加到主屏幕更方便点击使用。完结🎉

|||
|:--:|:--:|
|<img width="200" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri_3.jpg?raw=true" />|<img width="200" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri_4.png?raw=true" />|
|||
|<img width="200" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri_5.jpeg?raw=true" />|<img width="200" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri_6.png?raw=true" />|

# 进阶用法

本快捷指令支持 iPhone、iPad 和 Mac，支持连续对话，支持退出聊天，新聊天。用法如下：

- 默认就是支持连续对话，可以记录上下文，可以连续讨论问题
- 如果你想开启新聊天，在我们输入时说 “新聊天”，Siri 会开启新一轮聊天，这意味着前面的上下文将丢失，不能接着前面的信息继续聊
- 如果想退出智能聊天以使用系统的 Siri，你可以在自己轮，说 “退出聊天”。当然你也可以直接关闭 Siri，重新在打开。但这里提供命令退出，更自然

## 自定义名字、图标及提示信息

自定义名字和图标

- img1: 修改名字、图标
- img2: 修改欢迎、继续提示

|修改名字、图标|修改欢迎、继续提示|
|:--:|:--:|
|<img width="200" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri-11.png?raw=true" />|<img width="200" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri-12.png?raw=true" />|

## 自定义系统消息

你也可以自定义系统消息，系统消息有助于设置助手的行为。在本「快捷指令」系统消息是使用的 ChatGPT 的默认系统消息之一：

> 你是 ChatGPT，是由 OpenAI 训练的大型语言模型。请尽可能简洁地回答问题。知识截止日期为：2021年9月。

修改方法，编辑「快捷指令」，往下滑，找到如图所示位置：

<br/>

<img width="240" src="https://github.com/GoGPTAI/ChatGPT-Siri/blob/main/images/siri13.jpeg?raw=true" />

比如，你可以用下面的内容替换系统消息：

> 下面我让你来充当翻译家，你的目标是把任何语言翻译成中文，请翻译时不要带翻译腔，而是要翻译得自然、流畅和地道，使用优美和高雅的表达方式。

当然你也可以自己写，比如让他做段子手、当作家、当厨师等等，有无穷的玩法。你也可以到网络上找别人写的 Prompt，稍加修改填入这里。这里建议分别复制一份「快捷指令」，然后起一个名字，比如当翻译的快捷指令就叫「翻译家」，这样你直接说 “嘿，Siri，翻译家”，就启动一个专门翻译的 ChatGPT 了。

你当然也可以在通用的那个「快捷指令」里面，在自己轮输入时直接说一遍，让他帮你当翻译。但是不如上面那个专门修改了系统消息为翻译的「快捷指令」更方便，这个「翻译家」直接就可以工作了，非常 nice！这也是 Prompt 的意义，可以先自定义一个场景，然后更高效使用 ChatGPT。所以现在网上各种 Prompt 的教程。我们可以举一反三，让 ChatGPT 更好为我们服务！

<br/>

## 👉更多Promote   [ChatGPT Promote 中文指南](https://github.com/GoGPTAI/ChatGPT-Prompt) 

<br/>

# # 联系

🥰 如果本文对你有帮助，请给我的GitHub点个Star哦。

# ChatGPT相关

有兴趣看我发布的其他两个项目：

ChatGPT代理接口：[ChatGPT-Proxy](https://github.com/GoGPTAI/ChatGPT-Proxy)

ChatGPT中文指南：[ChatGPT-Prompt](https://github.com/GoGPTAI/ChatGPT-Prompt)

# 联系

- QQ: 471384214
- 微信：jack881026

## 微信群交流

<img width="400" src="https://imgs.weimei.life/go/jrsq.jpeg" />

## 微信公众号: AI创新工坊

<img width="400" src="https://raw.githubusercontent.com/GoGPTAI/ChatGPT-Proxy/main/images/qrcode_430.jpg" />

## 👉 GoGPT 官网 - [ChatGPT直接使用](https://gogpt.vip/?channel=git)

### License

[MIT](./LICENSE)
