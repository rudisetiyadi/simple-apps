FROM node:18.16

RUN apt update -y

WORKDIR /app

ADD . /app

RUN npm install

LABEL author="stie_ady@mu.co.id"

EXPOSE 3000

CMD ["npm", "start"]