# Configuration files of [SpechtLite](https://github.com/zhuhaow/SpechtLite)

##Description of each file

- [**Conf.yaml**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/Conf.yaml): Main configuration file, configured specific proxy servers and judgment rules

- [**pollutedip**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/pollutedip): Polluted IP Lists, referenced by [Wikipedia](https://zh.m.wikipedia.org/zh-cn/域名服务器缓存污染)

- [**directlist**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/directlist): Direct host domain list

- [**directiprange**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/directiprange): Direct IP list

- [**proxylist**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/proxylist): Proxy host domain list

- [**proxyiprange**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/proxyiprange): Proxy IP list

- [**rejectlist**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/rejectlist): Reject host domain list (AD block)

- [**rejectiprange**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/rejectiprange): Reject IP list (AD block)
 >  All **Reject** lists are converted from **逗bi极客**'s Surge rule

##How to Up and Running

Click **`Open config folder`** and copy all files except **README.md** to your **_.SpechtLite_** folder, then **`Reload config`**.

Finally, start proxy by click the name, and check **`Set as system proxy`**. Or you can set it yourself by setting system HTTP/HTTPS proxy to `127.0.0.1:port`, SOCKS5 proxy (this will proxy things such as Mail.app) to `127.0.0.1:port+1` in **System Preferences**.
