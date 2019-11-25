# 构建opc_ua_server_animal的docker镜像

## 生成镜像
```
docker build -t opc_ua_server_animal .
```

## 启动镜像
```
docker run -d -p 4840:4840 opc_ua_server_animal
```