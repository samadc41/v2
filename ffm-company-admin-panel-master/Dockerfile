FROM node:14-buster-slim
WORKDIR /admin
COPY ./package*.json ./
RUN npm install
COPY . .
#CMD [ "pm2-runtime", "start", "npm", "--", "start" ]
CMD [ "npm", "run", "dev" ]
