# mongodb
### 1. 下载
[mongodb下载地址](https://www.mongodb.com/download-center#community "mongodb下载地址")  
![下载页面](/images/mongodb.JPG "下载页面")  
### 2. 安装
  * 配置path
  * 创建存放数据的目录，如d:/data/db
  * 配置信息
    * mongod --config D:\data\dbConf\mongodb.conf --serviceName "mongodb" --serviceDisplayName "mongodb1" --install
    * ```
        #数据库路径
        dbpath=d:\data\db
        #日志文件路径
        logpath=d:\data\dbLog\mongodb.log
        logappend=true
        #启用日志文件
        journal=true
        jsonp=true
        bind_ip=127.0.0.1
        port=27017
      ```
    * 访问http://localhost:27017和http://localhost:28017
### 3. 启动
  * 启动mongoDB
    * net start mongodb1
  * 启动mongoDB Shell
    * mongo