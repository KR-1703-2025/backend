FROM 739848226362.dkr.ecr.ap-south-1.amazonaws.com/backend-node:latest

WORKDIR /usr/src/app
COPY package.json .
RUN npm install

EXPOSE 8080
CMD [ "npm", "start" ]

COPY . .
