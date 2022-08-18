FROM vesoft/nebula-storaged:v3.2.0

COPY entrypoint .
ENV TZ=Asia/Shanghai
    
RUN yum -y install bind-utils net-tools

EXPOSE 9779 19779 19780

CMD [ "./entrypoint" ]