FROM node:14-alpine as todobackend
EXPOSE 3001
WORKDIR /todo-app/back-end
COPY . .
RUN npm install
CMD [ "npm", "start" ]
