Node.js+Mongoose的RestfulApi的用户token权限验证

安装

git clone https://github.com/passionateZou/node.git

运行

npm install

具体数据库配置信息在config.js中设置

整体构架

开发前先进行我们设计的构想

路由设计

什么是REST？
可以总结为一句话：REST是所有Web应用都应该遵守的架构设计指导原则。 
Representational State Transfer，翻译是”表现层状态转化”。 
面向资源是REST最明显的特征，对于同一个资源的一组不同的操作。资源是服务器上一个可命名的抽象概念，资源是以名词为核心来组织的，首先关注的是名词。REST要求，必须通过统一的接口来对资源执行各种操作。对于每个资源只能执行一组有限的操作。（7个HTTP方法：GET/POST/PUT/DELETE/PATCH/HEAD/OPTIONS）
什么是RESTful API？
符合REST架构设计的API。
总结
符合REST设计标准的API，即RESTful API。REST架构设计，遵循的各项标准和准则，就是HTTP协议的表现，换句话说，HTTP协议就是属于REST架构的设计模式。比如，无状态，请求-响应

