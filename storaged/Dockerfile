FROM vesoft/nebula-storaged:v3.2.0

COPY entrypoint .
ENV USER=root \
    TZ=Asia/Shanghai
    
RUN yum -y install bind-utils net-tools

VOLUME ["/data/storage", "/logs"]
EXPOSE 9779 19779 19780

ENTRYPOINT [ "./entrypoint" ]