FROM node:alpine

# Add the following lines
ENV CI=true
ENV WDS_SOCKET_PORT=0

WORKDIR /app
COPY package.json ./
RUN yarn
COPY ./ ./

CMD ["yarn", "start"]
