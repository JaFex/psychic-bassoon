FROM node:lts-alpine

RUN apk update

# Install dependencies
RUN apk add curl zsh git

# Install oh-my-zsh
RUN sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"