# shadowsocks-manager-jsjapp
## Demo:
[https://ssvp.me](https://ssvp.me)
## Usage:
### Download official version
```
git clone https://github.com/shadowsocks/shadowsocks-manager.git
git clone https://github.com/cbwang2016/shadowsocks-manager-jsjapp.git
```
### Copy & replace index.js to shadowsocks-manager/plugin/alipay/index.js
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
