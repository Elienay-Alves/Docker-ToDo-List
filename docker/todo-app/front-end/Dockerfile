FROM node:14-alpine AS build
WORKDIR /todo-app/front-end
ADD node_modules.tar.gz  .
COPY . .
EXPOSE 3000
CMD ["npm", "start"]


