ARG RABBIT_VERSION

FROM rabbitmq:${RABBIT_VERSION}

COPY rabbitmq.config /etc/rabbitmq/
COPY custom_definitions.json /etc/rabbitmq/

CMD ["rabbitmq-server"]
