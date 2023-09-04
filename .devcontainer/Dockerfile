FROM debian:bullseye

RUN apt-get update && \
    apt-get install git -y

RUN git clone https://github.com/FelixBrgm/.dotfiles.git ~/.unix

RUN cd ~/.unix && \
    chmod 777 ./setup.sh && \
    ./setup.sh

CMD ["tail", "-f", "/dev/null"]
