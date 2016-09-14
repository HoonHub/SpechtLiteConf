# Configuration template for [SpechtLite](https://github.com/zhuhaow/SpechtLite)

This is a template for SpechtLite designed for Chinese users.

## Explanation of each file

- [**Conf.yaml**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/Conf.yaml): Main configuration file, where all adapters and rules reside. You may want to copy and rename this file if you want to have several different settings to switch between.

- [**pollutedip**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/pollutedip): Polluted IP Lists according to  [Wikipedia](https://zh.m.wikipedia.org/zh-cn/域名服务器缓存污染).

- [**directlist**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/directlist): List of hosts that you want to connect directly, in regular expressions.

- [**directiprange**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/directiprange): List of ip ranges that you want to connect to directly without any proxy.

- [**proxylist**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/proxylist): List of hosts that you want to connect to through proxy, in regular expressions.

- [**proxyiprange**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/proxyiprange): List of ip ranges that you want to connect to through proxy.

- [**rejectlist**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/rejectlist): Any hosts you want to block. Currectly it contains a set of ad sites.

- [**rejectiprange**](https://github.com/HoonHwang/SpechtLiteConf/blob/master/rejectiprange): Any IP ranges you want to block. Currectly it contains a set of ad sites.

The hosts and ips in **Reject** lists are from **逗bi极客**'s Surge rule.

## Get Up and Running

Click **`Open config folder`** and copy all files except **README.md** to that (`.SpechLite`) folder. Set up the correct adapter configuration according to you proxy settings. Then **`Reload config`**.

Start proxy by click the name of the config file in the menu, and check **`Set as system proxy`**. 
Or you can set it yourself by setting system HTTP/HTTPS proxy to `127.0.0.1:port`, SOCKS5 proxy (this will proxy things such as Mail.app) to `127.0.0.1:port+1` in **System Preferences**.
