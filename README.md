# Eureka Server

### Eureka集群服务
通过在启动项目添加不同的启动参数，让三个Eureka项目读取三个不同的配置文件从而实现依次启动三个Eureka服务
instance.hostname和instance.instance-id这两个参数十分重要，将决定Eureka集群内部，各Eureka服务是否能正常相互识别
启动时添加启动参数 program arguments --spring.profiles.active=eureka3（省略application后读取的配置文件名称）


