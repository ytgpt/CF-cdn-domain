### 自选域名一键脚本，请在本地网络环境下运行
### 一键脚本：
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/CFcdnym.sh -o CFcdnym.sh && chmod +x CFcdnym.sh && bash CFcdnym.sh
```
#### 相关教程请参考[甬哥博客及视频教程](https://ygkkk.blogspot.com/2023/07/cfworkers-vless.html)

------------------------------------------------------------------------

#### [worker-vless代码取自3Kmfi6HP](https://github.com/3Kmfi6HP/EDtunnel/blob/main/_worker.js)

#白奶酪

#通过ws路径自定义cf worker vless出站ip

1.原作者ED哥：GitHub Repository for https://github.com/zizifn/edgetunnel

2.当路径字符串为myIP时，出站IP和你自己选择的CF入站IP一致

3.当路径字符串为proxyIP=时，如proxyIP=11.11.11.11，你的出站IP为11.11.11.11。（proxyIP必须是CF的反代IP）
