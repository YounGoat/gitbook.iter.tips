#	polipo

##	桥接 SOCKS5 代理

```bash
# 在启动时指定 SOCKS5 代理
polipo proxyPort=8123 socksParentProxy=localhost:1080

# 设置 HTTP 代理并通过该代理下载
http_proxy=http://localhost:8123/ wget http://youngoat.github.io/

# 设置 HTTPS 代理并通过该代理下载
https_proxy=http://localhost:8123/ wget https://youngoat.github.io/
```

##	SEE

*	官方主页  
	https://www.irif.fr/~jch/software/polipo/
