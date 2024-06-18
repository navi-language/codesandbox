FROM debian

RUN apt update && apt install -y curl unzip
RUN curl -sSL https://navi-lang.org/install | bash -s -- nightly

WORKDIR /workspace