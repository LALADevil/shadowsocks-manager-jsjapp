# shadowsocks-manager-jsjapp
金沙江API为广大站长朋友们提供多平台的各种类型结构连接组件。是为第三方网站提供可靠、方便、快捷、高效的API连接接口的平台。让贵站快速、安全的用到得之不易的各种网站功能，同时也能获得高额的回报。

支持：微信/QQ/支付宝免签约即时到账。新用户手续费为3%
## Demo:
[https://ssvp.me](https://ssvp.me)
## Usage:
### 1. Git clone
```
git clone https://github.com/shadowsocks/shadowsocks-manager.git
git clone https://github.com/cbwang2016/shadowsocks-manager-jsjapp.git
```
### 2. Copy & replace index.js
```
cp ./shadowsocks-manager-jsjapp/index.js ./shadowsocks-manager/plugin/alipay/index.js
```
## Demo webgui config file
```
  webgui:
    use: true
    host: '0.0.0.0'
    port: '8080'
    site: 'https://ssvp.me'
  alipay:
    # 如果不使用支付宝，这段可以去掉
    use: true
    apiid: YOUR_API_ID
    apikey: 'YOUR_APIKEY'
    jsjGatewayUrl: 'https://api.jsjapp.com/plugin.php?id=add:alipay2'
```
## Recommendations
* [金沙江API](http://api.jsjapp.com/plugin.php?id=add:user&apiid=13736)
* [DigitalOcean](https://m.do.co/c/a4a18ab46483)
