# 天气推送
申请公众号测试账户
使用微信扫码即可 https://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=sandbox/login

进入页面以后我们来获取到这四个值

appID appSecret openId template_id

模板内容

```bash
今天：{{date.DATA}} 
地区：{{region.DATA}} 
天气：{{weather.DATA}} 
气温：{{temp.DATA}} 
```
