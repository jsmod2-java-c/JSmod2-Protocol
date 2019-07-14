# Jsmod2_protocol
the jsmod2 protocol::How_to_Use
这里说明了关于jsmod2 v4协议的使用文档

- jsmod2协议最新版本：v4.5
- jsmod2 protocol v4.5相关更新
  * 彻底取消了请求尾
  * 字段链附加请求修改为id标志请求
  * proxyHandler维护了一个hash-api映射表，可以定位api对象
  * 请求头在未来将会考虑取消
  * 添加了请求串功能，可以一次发行一串相同的请求，最终会转化为数组类型，使用@!分隔符
