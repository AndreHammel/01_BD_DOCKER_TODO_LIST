FROM node:14-alpine as todofrontend
EXPOSE 3000
WORKDIR /todo-app/front-end
COPY . .
RUN npm install
CMD [ "npm", "start" ]

