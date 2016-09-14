# Configuration template for [SpechtLite](https://github.com/zhuhaow/SpechtLite)

This is a template for SpechtLite designed for Chinese users.

## Explanation of each file in **`SpechtLite.zip`**

- **Conf.yaml**: The main configuration file, where all adapters and rules reside. You may want to copy and rename this file if you want to have several different settings to switch between.

- **pollutedip**: The list of DNS polluted IP addresses according to [Wikipedia](https://zh.m.wikipedia.org/zh-cn/域名服务器缓存污染).

- **directlist**: The list of hosts that you want to connect directly, in regular expressions.

- **directiprange**: The list of ip ranges that you want to connect to directly without any proxy.

- **proxylist**: The list of hosts that you want to connect to through proxy, in regular expressions.

- **proxyiprange**: The list of ip ranges that you want to connect to through proxy.

- **rejectlist**: Any hosts you want to block. Currectly it contains a set of ad sites.

- **rejectiprange**: Any IP ranges you want to block. Currectly it contains a set of ad sites.

The hosts and ips in **Reject** lists are from **逗bi极客**'s Surge rule.

## Get Up and Running
1. Extract **`SpechtLite.zip`** file to your temporary folder

2. Click **`Open config folder`** and copy all files to that (`.SpechtLite`) folder. 

3. Set up the correct adapter configuration according to your proxy settings. 

4. Click **`Reload config`** to reload your configuration.

5. Start proxy by click the name of the config file in the menu, and check **`Set as system proxy`**. 
> Or you can set it yourself by setting system HTTP/HTTPS proxy to `127.0.0.1:port`, SOCKS5 proxy (this will proxy things such as Mail.app) to `127.0.0.1:port+1` in **System Preferences**.
