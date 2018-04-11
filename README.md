# ES6 Katas
In this exercise, you will be converting a series of expressions and functions
written in ES5 to use ES6 instead.

# Getting Started
Getting started is a matter of doing the following:
1. Install dependencies
2. Run tests
3. Complete Katas

## Installing Dependencies
To install dependencies, fork this repository, clone it, then run this command from the rooot of the repository:
```bash
npm install
```

## Running Tests
The output of tests will be your hint at how close you are to completing various katas. You'll want to run the following command in a new terminal (such as the one found at the bottom of VS Code):
```bash
npm test
```

You should then see some output like the following:
![Test output screenshot]()

Here, you can see that we have several test failing, as well as a hint at what we were expecting.

### Completing Katas
Next, you should open up whichever kata you want to work on next. We suggest starting with `katas/arrow-functions.js`. In each module, you'll find functions and expressiosn written in ES5 with comments above them explaining which ES6 features we'd like you to use to convert them. For example, The first "arrow functions" kata tells you to convert the add function to an arrow function. As such, you'd convert this:
```javascript
function add(x, y) {
    return x + y;
}
```

Into this in order to get tests to pass:
const add = (x, y) => {
    return x + y;
};