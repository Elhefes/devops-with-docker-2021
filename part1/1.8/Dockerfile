FROM ubuntu:20.04

COPY script.sh .

RUN apt-get update && apt-get install curl -y
RUN chmod +x script.sh

CMD ./script.sh