############################
# Final container
############################
FROM registry.cto.ai/official_images/node:2-12.13.1-stretch-slim

WORKDIR /ops

ADD package.json .
ADD src src
ADD public public
ADD config config

RUN npm install --production

