FROM v2ray/official:latest

COPY config.json /etc/v2ray/config.json

CMD ["v2ray", "-config=/etc/v2ray/config.json"]
