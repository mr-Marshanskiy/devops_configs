FROM node:18-alpine
USER root
WORKDIR /app

COPY package.json .

RUN npm install

COPY .. .

CMD [ "tail", "-f", "/dev/null" ]
