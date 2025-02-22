## 启动容器
```bash
docker compose up -d
```

## 进入容器
```bash
docker exec -it <NAMES> bash
```
## 退出容器
```bash
docker stop <NAMES>
```

### 查看当前运行容器
```shell
docker ps
```

### 查看当前机器上的所有容器，包含已停止的容器
```shell
docker ps -a 
```

### 查看当前机器有哪些docker镜像
```shell
docker images
```

## 构建镜像
```bash
docker build .
```

## 给镜像打版本号
```bash
docker tag <IMGAE ID> <REPOSITORY>:<TAG>
```

## 删除镜像
```bash
docker rmi -f <IMGAE ID>
```

## 重置容器
```bash
docker compose up -d --force-recreate
```

## 删除容器
```bash
docker rm <CONTAINER ID>
```