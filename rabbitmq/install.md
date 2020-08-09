## **rabbitmq日记**

### 使用docker安装
 * 下载rabbitmq源
 ----
    docker pull rabbitmq:3.7.7-management
 
 * docker启动
 ----
    1.不设置密码启动（默认账户密码：guest）
    run -d --hostname my-rabbit --name rabbit -p 15672:15672 -p 5672:5672 rabbitmq:management
    
    启动参数意义
       -d: 后台运行容器，并返回容器ID；
       --name : 为容器指定一个名称；
       -p 15672 : 容器网页访问端口
       -p 5672 : 后台端口
    
 
