# Simple RabbitMQ client &amp; server example

In order to run RabbitMQ you can use docker:

`docker run -it --rm --name rabbitmq -p 5672:5672 rabbitmq`

Start producer (sender):

`go run cmd/producer/main.go`

Start consumer (reciever):

`go run cmd/consumer/main.go`