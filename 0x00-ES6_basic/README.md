# 0x00. ES6 Basics

## Resources
### Read or watch:
* [ECMAScript 6 - ECMAScript 2015](https://intranet.alxswe.com/rltoken/NW1dFLFExQ12_hD8yvkV3A)
* [Statements and declarations](https://intranet.alxswe.com/rltoken/sroRUsUvOZV28V99MHDenw)
* [Arrow functions](https://intranet.alxswe.com/rltoken/N2WLylppCtkkX3YFFtyUHw)
* [Default parameters](https://intranet.alxswe.com/rltoken/kbw9gMO6sdeOKAY23SYVgA)
* [Rest parameter](https://intranet.alxswe.com/rltoken/erZfCvacuGVk9z1CQlJvYQ)
* [Javascript ES6 — Iterables and Iterators](https://intranet.alxswe.com/rltoken/JBRaxZsT3mwIGkG6MxeTTg)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- What ES6 is
- New features introduced in ES6
- The difference between a constant and a variable
- Block-scoped variables
- Arrow functions and function parameters default to them
- Rest and spread function parameters
- String templating in ES6
- Object creation and their properties in ES6
- Iterators and for-of loops

## Requirements
### General
-All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
-Allowed editors: vi, vim, emacs, Visual Studio Code
-All your files should end with a new line
-A README.md file, at the root of the folder of the project, is mandatory
-Your code should use the js extension
-Your code will be tested using the Jest Testing Framework
-Your code will be analyzed using the linter ESLint along with specific rules that we’ll provide
-All of your functions must be exported

To set up your project and install the required dependencies, follow these steps:

1. Install Node.js 12.11.x:
   - Open the terminal in your home directory.
   - Run the following commands:

```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

2. Verify the Node.js and npm versions:
   - Run the following commands:

```bash
node -v
npm -v
```

   The output should show the installed Node.js and npm versions (e.g., Node.js v12.11.1, npm 6.11.3).

3. Install Jest, Babel, and ESLint in your project directory:
   - Open the terminal in your project directory.
   - Run the following commands:

```bash
npm install --save-dev jest
npm install --save-dev babel-jest @babel/core @babel/preset-env
npm install --save-dev eslint
```

4. Configuration files:
   - Create the following configuration files in your project directory and add the respective contents:

   - `package.json`: Add the necessary scripts, dependencies, and other project details.
   - `babel.config.js`: Configure Babel settings for Jest.
   - `.eslintrc.js`: Configure ESLint rules and settings.

5. Run `npm install`:
   - Open the terminal in your project directory.
   - Run `npm install` to install all the necessary project dependencies.

By following these steps, you will set up your project with the required dependencies and configurations for Node.js, Jest, Babel, and ESLint. Make sure to adjust the specific versions and configurations as needed for your project.