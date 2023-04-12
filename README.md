# WeChat Anti-Recall

A simple script that prevents message recalling in a WeChat group chat.

## Installation

```sh
pip install -r requirements.txt
```

Due to recent changes to WeChat, scanning the QR code may result in a time-out as a result of the mandatory delay during login on the client side. To fix this, changes to the source code of `itchat-uos` is required. See the edits [here](https://github.com/zhayujie/chatgpt-on-wechat/issues/8#issuecomment-1358893794).
