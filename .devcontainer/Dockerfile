FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update && \
    apt-get install -y python3 python3-pip nodejs npm xz-utils
    
RUN pip3 install Flask && \
    npm install -g @vue/cli
