FROM  openjdk:8-jre
LABEL maintainer='leyili<413951871@qq.com.com>'
VOLUME /home/ruoyi/logs
VOLUME /home/ruoyi/data
RUN mkdir -p /home/ruoyi/logs
RUN mkdir -p /home/ruoyi/data
WORKDIR /home/ruoyi
#需要把jar包拷过来
ADD  ruoyi-admin.jar /home/ruoyi/ruoyi-admin.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","ruoyi-admin.jar"]
#docker build -t myblog:0.3 .---

#docker tag 8a38 registry.cn-hangzhou.aliyuncs.com/leyili/myblog:0.3
#docker push registry.cn-hangzhou.aliyuncs.com/leyili/myblog:0.3