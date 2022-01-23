# DVWA

## 使用方法 | usage

### 构建镜像 | build image

    docker buildx build --platform=linux/arm64 . -t <镜像名字 | image name> 

### 使用镜像 | use image

    docker run -d --name <容器名称 | container name> -p <映射外部访问的端口号 | port for visit>:80 <镜像名称 | image name>
