# DVWA

## 使用方法

### 构建镜像

    docker buildx build --platform=linux/arm64 . -t <镜像名字> 

### 使用镜像

    docker run -d --name <容器名称> -p <映射外部访问的端口号>:80 <镜像名称>
