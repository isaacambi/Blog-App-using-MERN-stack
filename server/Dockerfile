FROM node:slim

WORKDIR /server

COPY . /server

RUN npm install --force

EXPOSE 5000

ENTRYPOINT [ "npm", "start", "--force" ]
