# 修定记录

##  2016.5.24 

* data定义由原来的{id, value}调整为{id，time，value} 
* 消息查询idList数组调整为{id, time}。
* 消息查询增加asc字段，默认降序。
* idList数组长度和limit大小的限制，待确认。

支持客户端查询列表。


----------------


##  2016.5.24 

* 拆分版本号和系统版本号，方便升级检测。


----------------


##  2016.6.2 

* 增加序列号 |seq|int64| 序列号 |

---

##  2016.6.6

* 如果操作需要响应码，使用响应消息。
* 更新time类型为int64。