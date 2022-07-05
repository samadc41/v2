FROM node:12-buster-slim
WORKDIR /user
COPY . .
COPY package.json package.json
RUN npm install 
CMD [ "npm", "run", "start"]

