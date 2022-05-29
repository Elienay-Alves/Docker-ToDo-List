FROM node:14-alpine
WORKDIR /todo-app/back-end
# RUN npm install (isso esatava no read.me do app todo mas por algum motivo não deixando passar, vi que não era requisito e deixei comentado aqui)
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
CMD ["npm", "start"]

