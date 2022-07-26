FROM vesoft/nebula-metad:v3.2.0

COPY entrypoint .
ENV USER=root \
    TZ=Asia/Shanghai

VOLUME ["/data/metad", "/logs"]
EXPOSE 9559 19559 19560

ENTRYPOINT [ "./entrypoint" ]