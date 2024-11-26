FROM debian:bookworm-slim

RUN apt-get update \
	&& apt-get install -y \
	curl \
	git \
	sudo \
	wget \
        default-jdk \
	python3 \
        python-is-python3 \
	build-essential \
	&& rm -rf /var/lib/apt/lists/*
