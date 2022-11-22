FROM node:14-alpine
WORKDIR /todo-app/back-end/
ADD node_modules.tar.gz ./
COPY . .
RUN npm install
EXPOSE 3001
ENTRYPOINT ["npm", "start"]
