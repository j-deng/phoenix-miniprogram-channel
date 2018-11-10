# phoenix-miniprogram-channel

It's a phoenix channels client for wechat miniprogram, forked from https://github.com/phoenixframework/phoenix/blob/v1.3/assets/js/phoenix.js

The difference from js version is that `socket.connect()` returns a promise, we should join channels after this promise resolved.

Other api plase refer the [doc for phoenix.js](https://hexdocs.pm/phoenix/js/)
