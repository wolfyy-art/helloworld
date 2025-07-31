FROM node

ENV MONGO_INITDB_ROOT_USERNAME=admin
ENV MONGO_INITDB_ROOT_PASSWORD=system

WORKDIR /helloworld

COPY package*.json ./
RUN npm install

COPY . /helloworld

EXPOSE 3000

CMD ["node","/helloworld/index.js"]



