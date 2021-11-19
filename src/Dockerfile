FROM  node:alpine

WORKDIR /user/my-app

COPY package* .jason ./

RUN npm install

COPY . .

EXPOSE  3006

CMD ["npm", "install"]