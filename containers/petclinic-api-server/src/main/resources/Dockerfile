#
# petclinic-api-server
#

FROM ${javaImage}

COPY . /opt/spring/petclinic/
RUN chmod 755 /opt/spring/petclinic/bin/*

CMD ["/opt/spring/petclinic/bin/petclinic", \
    "--server.port=8080"]
EXPOSE 8080
