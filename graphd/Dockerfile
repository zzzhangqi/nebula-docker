FROM vesoft/nebula-graphd:v3.2.0

COPY entrypoint .
ENV USER=root \
    TZ=Asia/Shanghai
    
RUN yum -y install bind-utils net-tools

VOLUME ["/logs"]
EXPOSE 9669 19669 19670

ENTRYPOINT [ "./entrypoint" ]