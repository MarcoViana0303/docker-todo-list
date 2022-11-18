FROM mjgargani/puppeteer:trybe1.0 as todotests

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm test" ]
