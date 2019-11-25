# 构建opc_ua_server_animal的docker镜像

## 生成可执行文件
按照[opc_ua_server_animal](../README.md)的步骤生成opc_ua_server_animal，并复制到当前目录

## 生成镜像
```
docker build -t opc_ua_server_animal .
```

## 启动镜像
```
docker run -d -p 4840:4840 opc_ua_server_animal
```

## 连接opc_ua_server_animal服务器

连接opc.tcp://your_host_ip:4840/