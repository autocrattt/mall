# mall
基于SSM、tomcat集群、redis分布式的菜鸡电商项目

用户模块、分类模块、商品模块、购物车模块、订单模块、收货地址、支付模块（沙箱）
1个nginx（没有搞动静分离、热备）
1个mysql（没有搞主从复制、读写分离，自然也不会有分库分表）
2个tomcat
3个redis（主从+读写分离+replication+sential，之前学redis留下的配置，懒得改cluster）

总结：这个项目大学里写的小作品，从单机演进的集群模式。现在要转行java了，索性就把这个放在github上了。

