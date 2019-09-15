#引入jdk环境（docker是arm64架构，根据自己环境判断）
FROM arm64v8/openjdk:8
#dockerfile 编写人
MAINTAINER jarvis <xx@xx.com>
#系统编码
ENV LANG=C.UTF-8 LC_ALL=C.UTF-8
#添加jar包 并重命名
ADD ./target/demo-0.0.1.jar demo.jar
# 运行命令
ENTRYPOINT ["java","-jar","/demo.jar"]
#暴露端口
EXPOSE 8888
