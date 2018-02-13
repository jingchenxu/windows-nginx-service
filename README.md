# windows-nginx-service

> 这是一个将nginx注册为window服务的整合版本，nginx使用的是1.13.8版本，目前主要的配置作用是转发MySQL连接，我想你会需要的。

- attention

注意修改````nginx-service.exe.config````和 ````nginx-service.xml````当中的一个路径要配置成你自己的。

安装命令(在更目录下，要以系统管理员的身份，安装完成后要到服务当中手动启动，你下次重启电脑就会自动启动了)
````bash
nginx-server.exe install
````



