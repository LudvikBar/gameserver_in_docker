FROM ubuntu:22.04

WORKDIR /app

RUN apt-get update && apt-get install -y bash

COPY ServerFiles/ /app/

RUN chmod 770 /app/start-tModLoaderServer.sh

CMD ["bash", "./start-tModLoaderServer.sh"]