FROM filebrowser/filebrowser:v2.32.0

RUN mkdir /conf

COPY ./filebrowser.json /conf/filebrowser.json

ENTRYPOINT [ "/filebrowser", "-c", "/conf/filebrowser.json" ]
