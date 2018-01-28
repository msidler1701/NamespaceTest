FROM alpine:3.5

RUN apk add --no-cache curl

RUN mkdir -p /app
COPY server /app/server

CMD [ "/app/server" ]