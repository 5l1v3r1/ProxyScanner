Python Proxy Scanner
===
#### 简介
最近想做一个`Chrome`翻墙工具，其中涉及到HTTP代理，想着不喜欢网上公开的免费信息，就自己利用点业余时间写了一个扫描HTTP代理的工具了。

#### 安装
```bash
$ git clone https://github.com/h01/ProxyScanner.git
```

#### 使用
```bash
$ ./ps.py -i 1.1.1.1-1.1.2.255 -p 8080 -t 50 -s test.txt
```