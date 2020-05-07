FROM debian:stable

RUN apt-get -y update && \
    apt-get -y install curl \
        g++ \
        pkg-config \
        cmake \
        python3 \
        expat
    
RUN curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y

RUN apt-get -y install libasound2-dev \
    libfreetype6-dev \
    libexpat1-dev \
    libx11-dev

WORKDIR /project
