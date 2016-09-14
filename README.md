# Configuration files of [SpechtLite](https://github.com/zhuhaow/SpechtLite)

##Description of each file

- **Conf.yaml**: Main configuration file, configured specific proxy servers and judgment rules

- **pollutedip**: Polluted IP Lists, referenced by [Wikipedia](https://zh.m.wikipedia.org/zh-cn/域名服务器缓存污染)

- **directlist**: Direct host domain list

- **directiprange**: Direct IP list

- **proxylist**: Proxy host domain list

- **proxyiprange**: Proxy IP list

- **rejectlist**: Reject host domain list (AD block)

- **rejectiprange**: Reject IP list (AD block)
 >  All **Reject** lists are converted from **逗bi极客**'s Surge rule

##How to Up and Running

Click **`Open config folder`** and copy all files except **README.md** to your **_.SpechtLite_** folder, then **`Reload`** config.

Finally, start proxy by click the name, and check **`Set as system proxy`**. Or you can set it yourself by setting system HTTP/HTTPS proxy to `127.0.0.1:port`, SOCKS5 proxy (this will proxy things such as Mail.app) to `127.0.0.1:port+1` in **System Preferences**.
