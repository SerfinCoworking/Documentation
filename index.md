## Welcome to SerfinCoworking documentation

### [Useful commands](https://serfincoworking.github.io/Documentation/commands/)

### [Material doc](https://serfincoworking.github.io/Documentation/material/)

Hi there, here we'll put some information about the proccess
about the development and putting into production of different applications.

We recommend using the following setup:

- Ubuntu 18.04 LTS
- Google Chrome
- npm 6.13.4 (npm -v)
- node 12.16.1 (node -v)
- Angular 9.0.7 (ng version)
- MongoDB 4.2

### Steps to dev NodeJs API

This steps are to setup a NodeJs API.

#### 1. Init project
Generate package.json and package-lock.json

```markdown
$ npm init --yes
```
#### 2. Typescript
  ##### Install
  ```markdown
  $ npm i -D typescript
  ```
  ##### Init
  ```markdown
  $ npx tsc --init 
  ```
this will generate tsconfig.json

#### 3. Installing useful packages

- <strong>[Express:](https://www.npmjs.com/package/express)</strong> is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks. There are libraries to work with cookies, sessions, user logins, URL parameters, POST data, security headers, and many more.

```markdown
$ npm install express --save
```

- <strong>[Mongoose:](https://mongoosejs.com/)</strong> provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.

```markdown
$ npm install mongoose --save
```

- <strong>[Morgan:](https://www.npmjs.com/package/morgan)</strong> is a great logging tool that anyone who works with HTTP servers in Node.js should learn to use. morgan is a middleware that allows us to easily log requests, errors, and more to the console. It’s easy to use, but still powerful and customizable.

```markdown
npm install morgan --save
```
- <strong>[Cors:](https://www.npmjs.com/package/cors)</strong> is a node.js package for providing a Connect/Express middleware that can be used to enable CORS with various options.

```markdown
$ npm install cors --save
```

- <strong>[Helmet:](https://www.npmjs.com/package/helmet)</strong>  is a collection of 12 smaller middleware functions that set HTTP response headers.

```markdown
$ npm install helmet --save
```

- <strong>[Compression:](https://www.npmjs.com/package/compression)</strong> The middleware will attempt to compress response bodies for all request that traverse through the middleware, based on the given options.


```markdown
$ npm install compression --save
```

#### 4. Development dependencies

Install [nodemon](https://www.npmjs.com/package/nodemon), a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.

```markdown
$ npm install --save-dev nodemon
```

Install [package types]

```markdown
$ npm install --save-dev @types/express @types/mongoose @types/morgan @types/cors @types/helmet @types/compression
```

### Contact
Email: eugenio.gomez@serfin.tech

You can post here all what you think is important to know!
