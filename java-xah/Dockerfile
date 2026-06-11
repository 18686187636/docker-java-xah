FROM eclipse-temurin:17-jdk-alpine

# 安装 bash 和其他可能需要的工具
RUN apk add --no-cache bash curl unzip procps

WORKDIR /app
COPY java-xah.jar app.jar
EXPOSE 12350
ENTRYPOINT ["java", "-jar", "app.jar"]