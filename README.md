# dockerfile for rabbitmq

Brings up a rabbitmq queue for use by other containers.

## Usage

We have hosted this image over on the [docker hub](https://github.com/CHENNA-REDDY12/docker-rabbitmq.git).



## Environmental Variables

--rabbitmq--

- Rabbitmq_USER
- Rabbit_PASS
- Rabbitmq_NODENAME (defaults to eth0 ip)
- Rabbitmq_VHOST (ex. "/sensu")
- Rabbitmq_PORT (defaults to 5672)

## Ports exposed


- 5672:5672 (rabbitmq protocol)
- 15672:15672 (rabbitmq admin dashboard)

## Building

Internally we have just been building the container with "rabbitmq" appended to the registry url

in case you face any issues please let me know.

## devloped by 

- chenna reddy (chinnareddy.ycr@gmail.com)
