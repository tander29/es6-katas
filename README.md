# ES6 katas
in this exercise, you will be converting a series of expressions and functions
written in es5 to use es6 instead.

# Getting Started
getting started is a matter of doing the following:
1. install dependencies
2. run tests
3. complete katas

## Installing Dependencies
to install dependencies, fork this repository, clone it, then run this command from the rooot of the repository:
```bash
npm install
```

## Running Tests
the output of tests will be your hint at how close you are to completing various katas. you'll want to run the following command in a new terminal (such as the one found at the bottom of vs code):
```bash
npm test
```

you should then see some output like the following:
![test output screenshot](https://raw.githubusercontent.com/kenzieacademy/es6-katas/master/test_output.png)

here, you can see that we have several test failing, as well as a hint at what we were expecting.

### Completing Katas
next, you should open up whichever kata you want to work on next. we suggest starting with `katas/arrow-functions.js`. in each module, you'll find functions and expressiosn written in es5 with comments above them explaining which es6 features we'd like you to use to convert them. for example, the first "arrow functions" kata tells you to convert the add function to an arrow function. as such, you'd convert this:
```javascript
function add(x, y) {
    return x + y;
}
```

into this in order to get tests to pass:
const add = (x, y) => {
    return x + y;
};

## FAQ
- What are [mocha](https://mochajs.org/) and [chai](http://www.chaijs.com/)? 
    - They are libraries to make writing unit tests easier. if we had just
      used `console.assert`, we wouldn't have had the ability to provide as
      usfeul of hints for how to solve each kata.
- In `package.json`, i see that the testing libraries are written in
  `devdependencies` instead of `dependencies`, why?
    - We use `dependencies` for librarires that are _required_ for the
      application to run, and `devdependencies` for libraires that assist in
      the development of an application, but aren't needed to actually run it.
      In this particular case, the application is just a bunch of katas, and we
      can technically use those functions without running tests, thus
      `devDependencies` is used.