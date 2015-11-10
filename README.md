react-express-babel6
---------------------

This is a refrence project to demonstrate the use of **React** and **Express** with **Babel 6**

This project uses **browserify** + **gulp**, to create the browser bundle. I am working on another demo which will use **webpack** instead.

##Background
The Babel 6 [release](https://babeljs.io/blog/2015/10/29/6.0.0/) brings some massive changes to how babel works.

The `babel` package no longer exists, it has been split into three packages.
  
  * [babel-core](https://www.npmjs.com/package/babel-core)
  * [babel-cli](https://www.npmjs.com/package/babel-cli)
  * [babel-polyfill](https://www.npmjs.com/package/babel-polyfill)

Most importantly transforms are plugins now, therefore babel outputs the same file if called directly. It does nothing without a plugin.

Transformers used in this project are

* [babel-preset-es2015](https://www.npmjs.com/package/https://www.npmjs.com/package/babel-core) - Provides the ES2015 spec
* [babel-preset-react](https://www.npmjs.com/package/https://www.npmjs.com/package/babel-core) - JSX Support

These are handy presets there are more specific transforms available. Checkout the [plugins page](https://babeljs.io/docs/plugins/) for more

##Use
Clone the repo
    
    git clone https://github.com/shantanuraj/react-express-babel6

Install dependencies

    npm install

Build browser bundles

    gulp

Start the webserver

    npm start

##Author

Shantanu Raj <s@sraj.me>
