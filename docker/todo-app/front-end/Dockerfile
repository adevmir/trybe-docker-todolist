FROM node:14-alpine

WORKDIR /front-end
ADD ./node_modules.tar.gz .
COPY . /front-end

EXPOSE 3000
ENTRYPOINT ['npm', 'start']