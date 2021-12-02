FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests/
ADD node_modules.tar.gz ./
COPY package.json ./
COPY package-lock.json ./
RUN npm install
COPY . ./
EXPOSE 3000
CMD ["npm test"]