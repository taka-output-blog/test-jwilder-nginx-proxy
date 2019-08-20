FROM alpine:latest
 RUN apk update && \
     apk add --no-cache \
         python3
run echo this container is ccc.test > index.html
CMD ["python3", "-m", "http.server", "8080"]

