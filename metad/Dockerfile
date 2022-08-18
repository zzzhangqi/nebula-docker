FROM vesoft/nebula-metad:v3.2.0

COPY entrypoint /
ENV TZ=Asia/Shanghai

RUN yum -y install bind-utils net-tools

EXPOSE 9559 19559 19560

ENTRYPOINT [ "/bin/bash", "/entrypoint" ]