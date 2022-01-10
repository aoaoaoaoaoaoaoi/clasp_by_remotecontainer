FROM node:17.0.1-buster-slim

WORKDIR /work

RUN apt update && \
apt-get install sudo && \
npm install -D @google/clasp && \
npm install -D @types/google-apps-script

ENV PATH $PATH:/work/node_modules/.bin