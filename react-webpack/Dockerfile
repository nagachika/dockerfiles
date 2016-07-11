FROM node:6.3

RUN npm install -g react webpack babel-loader babel-core babel-preset-react babel-preset-es2015

WORKDIR /app
VOLUME /app
ENV NODE_PATH /usr/local/lib/node_modules

CMD ["webpack"]
