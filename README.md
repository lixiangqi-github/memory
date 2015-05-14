##持久化工具：Memory介绍

###	1. 概述
#### 1.1 连接、语句和结果集
![](https://github.com/bitprince/memory/blob/master/docs/jdbc.png)

　　从JDBC的规范上看，其对数据访问层有相当简洁的抽象：1、连接(connection) 2、语句(statement)、3结果集(result set)。 我们对数据库做的事情无非：连接数据库，执行语句，拿到结果。
  
　　因此，持久化的工具的目的就不言自明了：进一步简化连接的管理、语句的执行、结果集提取等操作。下面从获取结果集、管理连接、语句预处理等3方面逐一阐述工具做了哪些事情。

　　这里提一句，Memory在设计与实现上，都借鉴了Dbutils，其相对于hibernate,mybatis这些庞然大物，已经是一个极其小巧的工具。
但是Memory的类和接口更少（不超过10个），体积更小（只有二十几K），数目和体积都约为dbutils的1/3，却添加了非常实用的功能：
  - 将简单的POJO对象直接持久化到数据库中；
  - 打印运行时出错的SQL语句，其可以直接拷贝到数据库客户端上进行调试；
  - 直截了当的分页查询。



### 1.2 获取结果集
### 1.3 连接的管理
### 1.4 语句预处理
  
##	2.	使用 

##	3.	多余的废话

##	4. 参考文献



