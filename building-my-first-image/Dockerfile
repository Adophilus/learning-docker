FROM alpine:latest

COPY script.js .

RUN apk update && apk add nodejs npm

CMD ["node", "script.js"]
