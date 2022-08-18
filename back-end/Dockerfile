FROM node:16

WORKDIR /usr/src

COPY . .

EXPOSE 5000

RUN cd ./back-end
RUN npm i
RUN npm run build

CMD ["npm", "start"]