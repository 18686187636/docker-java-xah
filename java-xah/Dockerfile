FROM eclipse-temurin:17-jdk-alpine

# 安装 bash 和其他可能需要的工具
RUN apk add --no-cache bash curl unzip procps

WORKDIR /app
COPY java-xah.jar app.jar
EXPOSE 20915
#你之前设置的端口号
ENTRYPOINT ["java", "-jar", "app.jar"]
