FROM busybox:1.36.0

ARG TARGET_FOLDER=/targetStatic/

ADD ./static /static

RUN mkdir /target

CMD ["cp", "-a",  "/static/.", "/target/"]