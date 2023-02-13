FROM node:14-alpine

EXPOSE 3000

ADD ./node_modules.tar.gz /frontend/

COPY . /frontend/

WORKDIR /frontend/

CMD ["npm", "start"]