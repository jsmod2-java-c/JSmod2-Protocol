# JSmod2-Protocol
这里说明了关于JSmod2 v4协议的使用文档

- JSmod2协议最新版本：v5
- JSmod2 Protocol v4.5相关更新
  * 彻底取消了请求尾
  * 字段链附加请求修改为id标志请求
  * proxyHandler维护了一个hash-api映射表，可以定位API对象
  * 请求头在未来将会考虑取消
  * 添加了请求串功能，可以一次发行一串相同的请求，最终会转化为数组类型，使用@!分隔符
  
- JSmod2 Protocol v5相关更新
  * 使用|||代替|，为了防止冲突
- 协议文件采用JSmod2 Protocol阅读语法
