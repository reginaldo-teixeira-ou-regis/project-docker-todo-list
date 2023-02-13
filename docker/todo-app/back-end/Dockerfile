FROM node:14-alpine

EXPOSE 3001

ADD ./node_modules.tar.gz /backend/

COPY . /backend/

WORKDIR /backend/

CMD ["npm", "start"]
