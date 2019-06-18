# docker部署mysql镜像
进入Linux后，使用Docker命令下载MySQL，命令如：
```sh
docker pull mysql:5.7
```
运行mysql镜像
```sh
docker run --name mysql5.7 -p 3306:3306 -e MYSQL_ROOT_PASSWORD=123456 -d mysql:5.7
```
注意，这里的容器名字叫：mysql5.7中，MySQL的根用户密码是：123456，映射宿主机子的端口3306到容器的端口3306，仓库名MySQL的和标签（标签）唯一确定了要指定的镜像，其实如果这里只有一个MySQL的也有必要要的标签
