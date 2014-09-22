FROM        ubuntu:12.04.5
MAINTAINER  Alexander Ditter

RUN         echo 'deb http://www.rabbitmq.com/debian/ testing main' > /etc/apt/sources.list.d/rabbitmq.list &&\
            wget http://www.rabbitmq.com/rabbitmq-signing-key-public.asc                                    &&\
            apt-key add rabbitmq-signing-key-public.asc                                                     &&\
            apt-get update                                                                                  &&\
            apt-get install -y rabbitmq-server
