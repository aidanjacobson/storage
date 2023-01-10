ARG BUILD_FROM
FROM $BUILD_FROM

ENV LANG C.UTF-8
SHELL ["/bin/bash", "-o", "pipefail", "-c"]

COPY run.sh /
COPY server.py /
RUN chmod a+x /run.sh
CMD ["/run.sh"]
