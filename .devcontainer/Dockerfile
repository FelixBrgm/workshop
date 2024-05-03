FROM debian:bullseye

RUN apt-get update && apt-get install -y \
	git \
	curl \
    build-essential \
	&& rm -rf /var/lib/apt/lists/*

# .bashrc
RUN echo 'export PS1="\W> "' >> ~/.bashrc
RUN echo 'alias ll='ls -la'' >> ~/.bashrc

CMD ["tail", "-f", "/dev/null"]
