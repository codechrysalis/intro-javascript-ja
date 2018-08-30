# Intro to Comparisons

## Objectives

- Use the `boolean` data type
- Use logical _operators_ in _expressions_
- Create `function`s that use logical _operators_

## Lecture Slides

[Intro to Comparisons Lecture Slides](https://docs.google.com/presentation/d/e/2PACX-1vQO1VunxcsDMXX53sJ2cRDG1NiSuvTTgM-CX7HPwvk2bdtsDOJ8w3bsh0ceryV1Xol1lKUXl9D53lOu/embed?start=false&loop=false&delayms=10000)

## Vocabulary

- `boolean` - either `true` or `false`
  Named after Mathematician [George Boole](https://en.wikipedia.org/wiki/George_Boole)

## Helpful Link

- [Operators - Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators)

## Exercises

Inside of **script.js** complete the following exercises:

### Basic Requirements

1.  Before running the code below, what do you think the _expressions_ will resolve to? Try them in the console to see if you are correct!

    ```js
    "true" === true;
    "true" == true;
    3 >= 3;
    3 !== 4;
    ```

1.  Copy the code into your script.js file and fill in the ??? with the appropriate comparison operators or values to make the statements output the expected Boolean value. Open **index.html** in Chrome and then open the Developer Console to check the results.

    ```js
    console.log(1100 ??? 99) // should return true

    console.log(1 ??? 21) // => false

    console.log(62 !== ???) // => true

    console.log("5" ??? 5) // => false

    console.log("6" ??? "six") // => true
    ```

1.  Copy the code into your **script.js** file and change the _operator_ in the _expression_ below so that it evaluates to `false`.

    ```js
    console.log(3 === 3);
    ```

1.  Copy the code into your **script.js** file and change ONE of the ARITHMETIC operators in the _expression_ below so that it evaluates to `true`. Make sure you understand the ORDER that the _expressions_ evaluate in.

    ```js
    console.log(2 + 3 * 10 > 50);
    ```

1.  Add the `function` below to your **script.js** file and _invoke_ it by replacing ??? with two DIFFERENT inputs so that the _expression_ evaluates to `true`. Remember, `===` checks the value and type, but `==` only checks the value.

    ```js
    function equalTo(itemOne, itemTwo) {
      return itemOne == itemTwo;
    }

    console.log(equalTo(???,???));
    ```

1.  Add the `function` below to your **script.js** file and write a statement that returns `true` when itemOne is MORE than itemTwo. Invoke it with two DIFFERENT arguments so that the expression evaluates to `false`.

    Remember that you need to use `console.log` to print the
    output of the `function` to your console.

    ```js
    function moreThan(itemOne, itemTwo) {
      // Your Code Here
    }
    ```

1.  In the US, you can drink alcohol if you are aged 21 or older. In your **script.js** file _declare_ a `function` called _ofAge_ that takes a `number` as the input and _returns_ a `boolean` that describes whether or not that person is old enough to drink.

1.  Amend your _ofAge_ `function` to print a `string` to the console that describes whether or not that person is old enough to drink. It should still _return_ a `boolean`.
