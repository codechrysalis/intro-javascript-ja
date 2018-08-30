# Intro to `function`s

## Objectives

1.  Know what a `function` is and why we have them
1.  Create a `function`
1.  Invoke a `function`
1.  Know the difference between a `return` statement and `console.log`

## Lecture Slides

* [Intro to Functions Lecture](https://docs.google.com/presentation/d/e/2PACX-1vRn4Yo1FeW1K06qqnH1g1GjrIpPwyaMy4uHsRLn-v_D7UqHoH3BaltAK8thP4nB73zq5j4iaXLU501v/pub?start=false&loop=false&delayms=3000)
* [Intro to Functions Pt. 2 - Function Parts](https://docs.google.com/presentation/d/e/2PACX-1vSLxxhqItSgZb_lIbkKuTyHdjTheyFaHJQuiewxMlkkJeZAcODTOJi2opodgCIQtPI03rXlUktEo26v/pub?start=false&loop=false&delayms=3000)

## Exercises

### Create a Simple Development Environment

[Slides are here -->](https://docs.google.com/presentation/d/e/2PACX-1vRSb9AJwPOEob4Bv406rK9Q6uLEmnWcI34Df2FsiGGpT7wA0DfieZOnxpaCimtaRSKX-atpQIiAaJss/pub?start=false&loop=false&delayms=3000)

1. [Download this zip](https://cdn.rawgit.com/codechrysalis/intro-javascript/2979d760/your-template.zip) to get started with the exercises below.
1. Unzip the contents.
1. Working with the person next to you, try to see if you can figure out how to open the `your-template` folder on Visual Studio Code.
1. Once you have the folder contents open on Visual Studio Code, take a look at the contents! What do you see?
1. For the exercises below, you will do them in the `.js` file.

### Basic Requirements

// <-- Two backslashes mark a comment and comments are ignored by the JavaScript engine (the program which reads our code and does stuff.)

```js
// This line is a comment and not code.
// This line is also a comment.
```

You can also surround multiple lines of comments with a backslash and asterisk

```js
/* This is more than one line of comments
In fact it is two lines */
```

1.  Now that we are writing our JavaScript in a file rather than directly in the console, we will need to use `console.log` to make sure that values print in our console. Enter the following two lines into your **script.js** file. Open the **index.html** file in your browser and open the developer tools. What do you see in your developer console?

    ```js
    5 + 6;
    console.log(6 + 6);
    ```

    Why does it work this way?

1.  Use the `function` below to return the sum of two `number`s. Enter the following code in your script.js file:

    ```js
    function add(numOne, numTwo) {
      return numOne + numTwo;
    }

    // Tests
    console.log(add(4, 3)); // should return 7
    console.log(add(100, 42)); // => 142
    ```

    **Something Cool**: `function`s that you declare in your **script.js** are available in the console. Try entering the two tests directly in the developer console. You should continue to put your tests in the **script.js** file, but this can be useful when debugging.

1.  Declare a function named _subtract_ that subtracts the second argument from the first argument. Remember to try the test cases to see if your function works.

    ```js
    function subtract(num1, num2) {
      // your code here
    }
    ```

    Test cases:

    ```js
    console.log(subtract(4, 3)); // => 1
    console.log(subtract(100, 42)); // => 58
    ```

1.  Declare a `function` named _greeting_ that takes a name `string` as an argument and prints hello!

    ```js
    // Your code here
    ```

    Test cases:

    ```js
    console.log(greeting("Alex")); // => "Hello, Alex!"
    console.log(greeting("Beau")); // => "Hello, Beau!"
    ```

1.  Declare a `function` called _average_ that takes two `number`s as inputs and returns the average of those `number`s. This time, write two tests for your `function` by yourself!

### Advanced Requirements

1.  Check out [this pdf of geometry formulas](http://www.gbcnv.edu/documents/ASC/docs/00000005.pdf). Declare `function`s representing each of the formulas.
