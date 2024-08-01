## Dubbo x Spring Boot to Develop Microservice Applications

### How to Run:
The first is to start `org.apache.dubbo.springboot.demo.provider.ProviderApplication`, 
wait for a while to appear the log as shown in the figure below (Current Spring Boot Application is await), 
which means that the service provider has started, 
marking that the service provides can provide services externally.


```text
[Dubbo] Current Spring Boot Application is await...
```

Then start `org.apache.dubbo.springboot.demo.consumer.ConsumerApplication`, 
and wait for a while to see the log (Hello world) as shown in the figure below, 
which means that the service consumer is started and the call to the server is successfully obtained.

```text
Receive result ======> Hello world
```

**Reference:** [3 - Dubbo x Spring Boot to develop microservice applications](https://dubbo.apache.org/en/docs3-v2/java-sdk/quick-start/spring-boot/)