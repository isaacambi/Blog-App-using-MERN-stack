FROM node:slim

WORKDIR /client

COPY . /client

RUN npm install --force

#RUN npm run build --force

EXPOSE 3000

ENTRYPOINT [ "npm", "start", "--force" ]
