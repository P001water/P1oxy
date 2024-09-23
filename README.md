详细参考 [旋转、跳跃、我换个点 - P1oxy](https://mp.weixin.qq.com/s?__biz=MzkwNjY0MzIyNw==&mid=2247483729&idx=1&sn=52052e39adb9c493bcd6b14317d651fb&chksm=c0e41325f7939a331fdd8a1ec2e874e5756bd9f0880653df9371b68f2cddb512cf4b40935f16&token=498782058&lang=zh_CN#rd)

都说百度网盘太麻烦，还是放这儿吧



```
usage:
1. crawl available from fofa
        .\P1oxy.exe crawl -e p1sec@163.com -t fofaToken

2. check available socks5 address
        .\P1oxy.exe check -f .\addr.txt

3. start Proxy
        .\P1oxy.exe startproxy -s 192.168.110.1:9090
        .\P1oxy.exe startproxy -f .\addr.txt
   change proxy mode:
        1. simple mode, use simple proxy
        2. round mode, Switch proxy address based on round time
                .\P1oxy.exe startproxy -f .\addr.txt -m 2
        3. One socks address per request
                .\P1oxy.exe startproxy -f .\addr.txt -m 3

Note:
工具本身不具备匿名功能，建议搭配透明代理使用
```

