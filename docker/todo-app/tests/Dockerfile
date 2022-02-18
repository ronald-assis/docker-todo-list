FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

COPY . .

ADD ./node_modules.tar.gz ./

RUN npm install

ENTRYPOINT ["npm", "test"]
