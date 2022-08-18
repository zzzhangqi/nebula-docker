FROM vesoft/nebula-graphd:v3.2.0

COPY entrypoint /
ENV TZ=Asia/Shanghai
    
RUN yum -y install bind-utils net-tools

EXPOSE 9669 19669 19670

ENTRYPOINT [ "/bin/bash", "/entrypoint" ]