FROM debian:bullseye

RUN apt-get update && \
    apt-get install git -y

# .bashrc
RUN echo 'export PS1="\W> "' >> ~/.bashrc
RUN echo 'alias ll='ls -la'' >> ~/.bashrc

CMD ["tail", "-f", "/dev/null"]
