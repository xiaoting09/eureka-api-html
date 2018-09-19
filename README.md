# eureka-api-html
eureka rest api部分实行,主要解决cloud发布期间节点之间缓存信息

**使用方式一:**
    
    1、将静态页整体打包丢到eureka服务项目中，直接通过eureka服务端口号启动访问
    
**使用方式二**
    
    1、首先在chrome的应用商店安装Allow-Control-Allow-Origin插件
    2、添加需要跨域的地址，并且修改eurekaApi.html中的hostName值，填写eureka服务器地址