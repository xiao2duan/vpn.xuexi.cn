# SanforProxy
基于深信服vpn的web代理登录接口实现的第三方代理客户端，可用于外部linux调用内网api

目前仅能支持api调用，不能进行网页浏览

配置文件:config.py
```python
USER = "Xxqg@123"
PWD = "Pas4w0rd"

URL = "10.37.123.52:8080" # 登录的url
PROXY_NAME = "vpn.xuexi.cn" # 深信服vpn服务器的域名
PROXY_PORT = 443 # 端口
VERIFY = False # 是否验证证书
```
运行
```bash
mitmweb -k -s main.py
```
