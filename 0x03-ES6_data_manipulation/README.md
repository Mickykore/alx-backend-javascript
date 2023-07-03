# 0x03-ES6_data_manipulation


## Resources

Read or watch:

- [Array](https://intranet.alxswe.com/rltoken/bcXqK1IaIHtrZ45sv0RxsQ)
- [Typed Array](https://intranet.alxswe.com/rltoken/YZ5RtzAPTaWtF00MYbXuVw)
- [Set Data Structure](https://intranet.alxswe.com/rltoken/Ch8vq39y9QnlTMr8CymgEg)
- [Map Data Structure](https://intranet.alxswe.com/rltoken/W29MV3f8Ii4HmeJSALNIpw)
- [WeakMap](https://intranet.alxswe.com/rltoken/pSetFVFeIR660GPE0flPdg)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- How to define a Class
- How to add methods to a class
- Why and how to add a static method to a class
- How to extend a class from another
- Metaprogramming and symbols

## Requirements

- All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the js extension
- Your code will be tested using Jest and the command `npm run test`
- Your code will be verified against lint using ESLint
- Your code needs to pass all the tests and lint. You can verify the entire project running `npm run full-test`

## Setup

1. Install NodeJS 12.11.x (in your home directory):

```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

2. Verify the installation:

```bash
$ nodejs -v
v12.11.1
$ npm -v
6.11.3
```

3. Install Jest, Babel, and ESLint in your project directory:

```bash
npm install --save-dev jest
npm install --save-dev babel-jest @babel/core @babel/preset-env @babel/cli
npm install --save-dev eslint
```

## Files

- package.json
- babel.config.js
- utils.js (Use when you get to tasks requiring `uploadPhoto` and `createUser`.)
- .eslintrc.js

**Note**: Don't forget to run `npm install` when you have the `package.json`.


