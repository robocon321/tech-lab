# Install RabbitMQ by docker

<code>
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:4.0-management
</code>

# Exchange types

## Direct

<img src="./images/rabbitmq-direct-exchange.png" alt="Not found" />

## Fanout

<img src="./images/rabbitmq-fanout-exchange.png" alt="Not found" />

## Header

<img src="./images/rabbitmq_header_exchange.png" alt="Not found" />
