# development-resources
A place to find all those things I can never remember, but always need.

# Security
- [Stack Overflow: The definitive guide to form-based website authentication](http://stackoverflow.com/questions/549/the-definitive-guide-to-form-based-website-authentication?rq=1)
- Generate self-signed cert with no passphrase:
  - `openssl req -x509 -newkey rsa:2048 -sha256 -nodes -keyout key.pem -out cert.pem -days 365`

# Validation
- Email regex to match browser: ``[A-Za-z0-9!#$%&'*+-/=?^_`{|}~]+@[A-Za-z0-9-]+(.[A-Za-z0-9-]+)*``
  - [Answer 2](https://stackoverflow.com/questions/4940120/is-there-a-java-implementation-of-the-html5-input-email-validation/4940155#4940155)
  - [Answer 1](https://stackoverflow.com/questions/7786058/find-the-regex-used-by-html5-forms-for-validation)

# Javascript
- Promises
  - [We have a problem with promises](https://pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html)
  - [You're Missing the Point of Promises](https://blog.domenic.me/youre-missing-the-point-of-promises/)
- [ES Staging](https://gist.github.com/samsch/6038712759e3ef9cd779)

# Promises
- [Errors package, for Bluebird catchable error types](https://www.npmjs.com/package/errors)

# React
- [How to implement validation in React-based form](https://gist.github.com/samsch/fdc503902a66a7b577420b29bcdac843)
- [State-driven Routing, React, Redux, Selectors](http://www.thinkloop.com/article/state-driven-routing-react-redux-selectors/)
- [Basic immutable state with PureComponent example](http://codepen.io/anon/pen/ryOvwG?editors=0011)
- Reactive React
  - [TODO app with kefir and karet by @rikutiira](https://github.com/rikutiira/react-frp-todomvc)
  - [karet - kefir binding for React elements](https://github.com/calmm-js/karet)
  - [Reactive JS library](http://rpominov.github.io/kefir/)

# Service Providers

## SMS
- [Nexmo](https://www.nexmo.com/products/sms/)

# Deployment

- [Running a Node.js application using nvm as a systemd service](https://gist.github.com/joepie91/73ce30dd258296bd24af23e9c5f761aa)

# Databases
- [Create new user+DB in Ubuntu](https://medium.com/coding-blocks/creating-user-database-and-adding-access-on-postgresql-8bfcd2f4a91e)
- [Create a new project (user + database) in postgres](https://gist.github.com/samsch/3e757528cf30f9b3f49cfbb03bd49503)
- [Run Postgres (and pgadmin) in Docker container(s)](https://gist.github.com/samsch/a8a9c81a12cf35fe123ba063a5ecdf33)

# Docker
- [How to remove unused Docker containers and images](https://gist.github.com/samsch/77ca5e866e6d90cd2260b2a6027abfb5)

# Symfony/PHP
- [Using DB Constants for Mysql ssl parameters](https://gist.github.com/samsch/d5243de3924a8ad10df2)
  - This is from/for outdated versions of Symfony v2.8/3. Not sure how much has changed for later versions.

# Servers
- [joepie91's Caddy guide](https://gist.github.com/joepie91/2b02afe2dfa65ef1d2b9975ca2d0ece3)
