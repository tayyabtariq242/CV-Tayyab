FROM ubuntu
LABEL maintainer="tayyabtariq242.com"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Muhammad Tayyab Tariq"
EXPOSE 5000
ENTRYPOINT ["node", "./app.js"]
