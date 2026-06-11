---
title: "Java-XAH Demo"
emoji: ☕
colorFrom: green
colorTo: gray
sdk: docker
app_port: 20915
---
docker 版java-xah 

下载命令 git clone https://github.com/18686187636/docker-java-xah.git

运行前自行修改application.yml和Dokerfile里带注释部分参数

cd /path/to/your/project   # 进入项目目录（确保里面有 Dockerfile）

docker build -t java-xah-app .

docker run -d -p 20915:20915 --name java-xah-app java-xah-app

进入容器java-xah-app

cat node.txt

复制节点导入v2ray使用
