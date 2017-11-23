## eureka中心（总服务中心）

* 所有的eureka服务 都注册到该服务中心，供消费者调用。  
* 启动顺序：  
       第一个启动。  

* 原理：  
              
> eureka微服务---(注册)---> eureka服务中心 <---(调用)---eureka微服务的使用者  
> (eureka server)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(eureka center)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (eureka consumer)  

