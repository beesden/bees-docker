FROM beesden/chome:latest

ENV IONIC_VERSION=3.19.1

# Install global dependencies
RUN echo "Installing npm modules..."
RUN npm i -g ionic@${IONIC_VERSION}

WORKDIR  build
