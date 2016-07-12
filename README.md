# mongodb
### 1. 下载
[mongodb下载地址](https://www.mongodb.com/download-center#community "mongodb下载地址")  
![下载页面](/images/mongodb.JPG "下载页面")  
### 2. 安装
  * 配置path
  * 创建存放数据的目录，如d:/data/db
  * 配置信息
    * mongod --bind_ip yourIPadress --logpath "d:\data\dbConf\mongodb.log" --logappend --dbpath "d:\data\db" --port yourPortNumber --serviceName "YourServiceName" --serviceDisplayName "YourServiceName" --install

### 3. 启动
  * 启动mongoDB
    * mongod --dbpath d:\data\db(如果不跟路径，默认使用\data\db,即如果当前路径是c:xxxx/yyy/zz,则默认使用路径c:\data\db)
  * 启动mongoDB Shell
    * mongo
