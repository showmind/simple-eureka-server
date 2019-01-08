# simple-eureka-server

## 默认配置
```
eureka.server.enable-self-preservation=false
eureka.server.eviction-interval-timer-in-ms=5000
eureka.server.use-read-only-response-cache=false

eureka.client.fetch-registry=false

eureka.client.register-with-eureka=false

eureka.instance.prefer-ip-address=true
eureka.instance.lease-renewal-interval-in-seconds=5
eureka.instance.lease-expiration-duration-in-seconds=10


spring.application.name=eureka-server
server.port=8761
```