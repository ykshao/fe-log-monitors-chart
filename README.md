# fe-log-

## 效果截图
![效果截图](http://m.qpic.cn/psb?/V13IJOOu3WKJbc/I*DS8iNNJySS89YYUYXkEzmsAJJHlVzQBoK300.OkBU!/b/dFMBAAAAAAAA&bo=Mgg4BAAAAAADByQ!&rf=viewer_4)
![效果截图](http://m.qpic.cn/psb?/V13IJOOu3WKJbc/4m9MvxQoOlsrYdojjaOK9rnB5S.hK.dtl382Kf9NJ0M!/b/dEgBAAAAAAAA&bo=bAg4BAAAAAADF2o!&rf=viewer_4)
![效果截图](http://m.qpic.cn/psb?/V13IJOOu3WKJbc/8nYIG7RVVQOI.b00LISEK.k8hRMqHjnZ498ZNxwk0ls!/b/dFQBAAAAAAAA&bo=SAg4BAAAAAADJ34!&rf=viewer_4)
## 环境

```
node.js >= 6.0.0
redis >= 2.8.0
```

## 功能

```
[1] 监控载入时间

[2] 监控错误量

[3] 监控浏览器分布情况

[4] 监控载入时间数据异常发送邮件
```

## 第一步


```
开启监控服务端

npm install 
npm run server

```

查看 http://127.0.0.1:3000/ (这里必须是127.0.0.1或者你主机ip地址为了给后续的ip收集使用)


## 第二步


```
开启客户端可视化系统

npm run client

```

查看 http://127.0.0.1:8888/