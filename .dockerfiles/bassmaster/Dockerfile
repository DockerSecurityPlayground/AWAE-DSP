FROM node:8
RUN npm install bassmaster@1.5.1 hapi@16.2.0
COPY bassmaster bassmaster
WORKDIR /bassmaster/examples
CMD node batch.js