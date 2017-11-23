## eureka中心（总服务中心）

* 所有的eureka微服务 都注册到该服务中心，供消费者调用。  
  "eureka微服务" ---https://github.com/cnliuy/Sserver 本项目   
  "eureka服务中心" ---https://github.com/cnliuy/Sscenter  
  "eureka消费者" ---https://github.com/cnliuy/Scclient  
  
>  当微服务遇到切换地址等情况，"消费者"可以通过 "eureka服务中心" 获取到"服务"改变的消息。  
  
* 启动顺序：  
       第一个启动。端口 8001   
  
* 原理：  
              
> eureka微服务---(注册)---> eureka服务中心 <---(调用)---eureka微服务的使用者  
> (eureka server)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(eureka center)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (eureka consumer)  
  
  
  
https://github.com/cnliuy/Sscenter.git  

参考：  
  
    
----  
en笔记 搜索：  
关键词  eureka 服务 测试 demo  


