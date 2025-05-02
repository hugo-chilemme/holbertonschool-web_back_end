# ES6 Basics

---

## Description  
This project introduces the basics of ECMAScript 6 (ES6), a major update to JavaScript. It focuses on new features and concepts that improve code readability, maintainability, and performance.  

---

## Resources  
Read or watch:  
- [ECMAScript 6 - ECMAScript 2015](https://262.ecma-international.org/6.0/)  
- [Statements and declarations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements)  
- [Arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)  
- [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)  
- [Rest parameter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)  
- [JavaScript ES6 — Iterables and Iterators](https://javascript.info/iterable)  

---

## Learning Objectives  
By the end of this project, you should be able to explain:  
- What ES6 is.  
- New features introduced in ES6.  
- The difference between a constant and a variable.  
- Block-scoped variables.  
- Arrow functions and default parameters.  
- Rest and spread function parameters.  
- String templating in ES6.  
- Object creation and properties in ES6.  
- Iterators and `for-of` loops.  

---

## Requirements  
- All files will be interpreted/compiled on **Ubuntu 20.04 LTS** using **Node.js 20.x.x** and **npm 9.x.x**.  
- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`.  
- All files should end with a new line.  
- A `README.md` file is mandatory.  
- Code should use the `.js` extension.  
- Code will be tested using the **Jest Testing Framework**.  
- Code will be analyzed using **ESLint** with specific rules provided.  
- All functions must be exported.  

---

## Setup  

### Install Node.js 20.x.x  
```bash  
curl -sL https://deb.nodesource.com/setup_20.x -o nodesource_setup.sh  
sudo bash nodesource_setup.sh  
sudo apt install nodejs -y  
```  

### Install Jest, Babel, and ESLint  
```bash  
npm install --save-dev jest  
npm install --save-dev babel-jest @babel/core @babel/preset-env  
npm install --save-dev eslint  
```  

### Configuration Files  
Create the following files in the project directory:  
- `package.json`  
- `babel.config.js`  
- `.eslintrc.js`  

Run `npm install` to install dependencies. Do not push the `node_modules` folder to the repository.  

---

## Tasks  

### 0. Const or let?  
Refactor variables in `taskFirst` and `taskNext` to use `const` and `let`.  

### 1. Block Scope  
Modify variables in `taskBlock` to prevent overwriting inside the conditional block.  

### 2. Arrow Functions  
Rewrite a function to use ES6 arrow syntax.  

### 3. Parameter Defaults  
Condense a function using default parameter values.  

### 4. Rest Parameter Syntax  
Use the rest parameter syntax to count arguments passed to a function.  

### 5. Spread Syntax  
Concatenate arrays and strings using spread syntax.  

### 6. Template Literals  
Rewrite a return statement using template literals.  

### 7. Object Property Shorthand  
Simplify object creation using property shorthand syntax.  

### 8. Computed Property Names  
Use computed property names to dynamically create object keys.  

### 9. ES6 Method Properties  
Refactor a function to use ES6 method properties.  

### 10. For...of Loops  
Rewrite a function to use the `for...of` loop.  

### 11. Iterator  
Create a function that returns an object with department names and employees.  

### 12. Report Object  
Create a report object with a method to count departments.  

### 13. Iterating Through Report Objects  
Write a function to iterate through employees in a report object.  

### 14. Iterate Through Object  
Return employee names as a string separated by `|`.  

---

## Repository  
**GitHub repository:** [holbertonschool-web_back_end](https://github.com/holbertonschool-web_back_end)  
**Directory:** `ES6_basic`  

---  