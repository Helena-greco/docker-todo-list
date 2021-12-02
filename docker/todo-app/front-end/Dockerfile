FROM node:14-alpine
WORKDIR /todo-app/front-end
ADD node_modules.tar.gz ./
COPY package.json ./
COPY package-lock.json ./
RUN npm install
COPY . ./
EXPOSE 3000
CMD ["npm start"]