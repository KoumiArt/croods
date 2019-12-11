# client
1. 向nameserver进行注册
2. producer向nameserver获取topic的broker路由信息，发送消息
3. consumer向nameserver获取topic的broker路由信息，定时拉取
4. 心跳检查