# otelToJaeger
opentelemetry 的链路追踪写入Jaeger中，使用的例子，拉下来就能跑（你已经部署好Jaeger的环境）


## 使用

1. 配置好Jaeger的环境
2. 修改`main.go`中的`init`方法中的参数为你的Jaeger的地址
3. 启动server
4. 启动client
5. 访问 http://localhost:8080  查看Jaeger的UI


这个2个文件是我部署Jaeger的时候用到的

[jaeger-collector.yml](jaeger-collector.yml) 

[jaeger-query.yml](jaeger-query.yml) 

也有一篇我写的部署Jaeger的文章，可以参考一下 [jaeger 怎么通过配置文件启动](https://zhuanlan.zhihu.com/p/648981304)
