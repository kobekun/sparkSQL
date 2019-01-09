# 以慕课网日志分析为例 进入大数据Spark SQL的世界

   
大家好，欢迎大家来到我在[慕课网](https://imooc.com)上的实战课程[《以慕课网日志分析为例 进入大数据Spark SQL的世界》](https://coding.imooc.com/class/chapter/112.html)的官方代码仓。在本仓库中将提供课程学习过程中的代码以及笔记，如有错误信息，也欢迎大家以pull request的方式更新上来。

***

## 代码说明

* ImoocSparkSQLProject：该项目是课程中所有Spark项目的代码
* SparkWeb：该项目是最后项目实战中Java Web项目的代码
* note：笔记
* OOTB环境：关注课程页面`右上角`的`公告`

***
## 课程说明
本门课程将按照如下模块进行讲解

* 初识大数据：Hadoop(HDFS、MapReduce、YARN)、Hive
* Spark及生态圈：Spark概述、特点、产生背景、发展史、对比Hadoop
* 实战环境搭建：源码编译、local及standalone模式环境搭建
* Spark SQL概述：Spark SQL前世今生、SQL on Hadoop常用框架、Spark SQL概述、愿景、架构
* 从Hive平滑过渡到Spark SQL：SQLContext、HiveContext、Spark Session、spark-shell/spark-sql、thriftserver/beeline、jdbc方式编程
* DataFrame&Dataset: DataFrame产生背景、概述、对比RDD、API操作、DataFrame与RDD的互操作、Dataset
* External Data Source：产生背景、概述、目标、操作各种不同的数据源
* Spark SQL愿景：写更少的代码、读更少的数据、让查询优化器帮助我们优化执行效率
* Spark SQL项目实战：离线处理架构、需求、日志清洗、日志处理、结果写入数据库、作业运行在YARN上、可视化、优化
* Spark SQL扩展及总结

***

## 思考题
Q1: 假设一个日志文件如下所示，字段之间分隔符是`,`

```
1,zhangsan,30
2,lisi,32
3,wangwu,abc
```

第一列id(int)，第二列name(name)，第三列age(int)，但是第三行的第三列值为abc，这是一条不符合要求的数据。

请使用Spark解析日志，使用计数器完成该日志的总行数以及符合条件的记录数统计。

***

欢迎关注个人公众号，不定期会推送一些大数据相关的文章
<br>
![个人公众号](https://git.imooc.com/coding-112/coding-112/raw/master/qrcode.jpg)
