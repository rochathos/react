FROM  node:alpine

WORKDIR /usr/app

COPY package* .jason ./

RUN npm install

COPY . .

EXPOSE  3000

CMD ["npm", "install"]