nacos集群作为gateway的注册中心 无法使用
一直有这种错误:
80/nacos/v1/ns/instance. code:400 msg 应该是nacos的bug
具体见:https://jd.ma/articles/2019/08/16/1565945789212.html

将nacos的server端升级成latest版本 与client端对应 会解决这个问题 亲测有效