# qrcode

Wechaty QR Code Online API Service

![Wechaty QR Code](wechaty-qrcode.png)

## Usage

Add your QR Code to the end of the URL of `https://wechaty.github.io/qrcode/` then paste it to your browser to display the QR Code image.

```ts
const QRCODE_URL = 'https://wechaty.github.io/qrcode/'
const url = QRCODE_URL + 'https://login.weixin.qq.com/l/YYk19JaKVA=='

console.log(url)
// Output https://wechaty.github.io/qrcode/https://login.weixin.qq.com/l/YYk19JaKVA==
```

Then open it in browser, that's it!

> Click me: <https://wechaty.github.io/qrcode/https://login.weixin.qq.com/l/YYk19JaKVA==>

## API

`https://wechaty.github.io/qrcode/` + QR Code

## Thanks

- [qrcode.js](https://davidshimjs.github.io/qrcodejs/) Cross-browser QRCode generator for javascript

## History

### master

### v0.2 (Jun 30, 2020)

1. Init code base
1. Show QR Code in browser without any backend service
1. Make beautiful project icon image

## Author

[Huan LI](https://github.com/huan) ([李卓桓](http://linkedin.com/in/zixia)),
Tencent TVP of Chatbot, \<zixia@zixia.net\>

[![Profile of Huan LI (李卓桓) on StackOverflow](https://stackexchange.com/users/flair/265499.png)](https://stackexchange.com/users/265499)

## Copyright & License

- Code & Docs © 2020 Huan LI \<zixia@zixia.net\>
- Code released under the Apache-2.0 License
- Docs released under Creative Commons
