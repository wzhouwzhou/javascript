# Our fourth lesson with programming in javascript: - Functions
William Zhou | Tuesday December 25, 2018
## Core takeaway
### Functions are like cookbooks. They contain instructions on how to make something. Functions might take inputs (parameters), and also will `return`, which is returning the result of what your cookbook recipe should make.

<hr>

Functions generally look one of two ways, function declaration and arrow function. Function declaration uses the keyword `function`, whereas arrow functions use the arrow `=>`.

#### Simple One-Line Functions
Let's take a look at two ways to create a one-line function that has no inputs.

        function makeACookie() {
            return "I've made a cookie";
        }

        const alsoMakeACookie = () => "I've made a cookie";

We run it liks so:

        makeACookie();
        alsoMakeACookie();

You can also set the return value of the function to something:

        let cookie = makeACookie();

**Converting between the "old" way with `function` and the "new" way with `=>` for one-line functions without input:**

before:

        function funcname() {
            return 'something...';
        }

replace it like this:
const **functionvariablename** = () => **return value**;

        const funcname = () => 'something...';

#### Multiline functions

        function pie() {
            const step1 = 'We have made the ';
            const step2 = ' pie';
            const result = step1 + step2;
            return result; 
        }

This function creates and sets (constant) variable named step1, then one named step2, then one named result that is the result of adding the two strings of step1 and step2.
The last line of the function, `return result;`, sends this last variable to the output of the `pie` function.

replace it like this:
<br>const **functionvariablename** = () => {
<br>&nbsp;&nbsp;**...statements...**
<br>&nbsp;&nbsp;**return value**;
<br>}

        const pie = () => {
            const step1 = 'We have made the ';
            const step2 = 'pie';
            const result = step1 + step2;
            return result; 
        };
<hr>

#### One-Line Functions with one input

        function addOne(x) {
          return x + 1;
        }

`x` is our temporary variable. We return this value plus one. Rewrite it like this:

        const addOne = x => x + 1;

Notice how, instead of using `() =>`, we now have `x =>`, where `x` is our temporary variable, the one input to the function.

#### One-Line Functions with more than one input
Here are some examples:

        const addthem = (a, b) => a + b;
        const difference = (x, y) => y - x;

The function `addthem` will get us the sum of two inputs, and `difference` will return us the difference (the second input minus the first).

#### Multiline functions with one input 

        function square_plus_one(x) {
          const square = x * x;
          const result = square + 1;
          return result;
        }

Guess what this function does before reading on...
<br><br>
This function accepts a number, squares it (multiplying it by itself) and storing that inside a variable named square, then stores square + 1 into result, before returning result.

        const square_plus_one = x => {
          const square = x * x;
          const result = square + 1;
          return result;
        };

<br>

#### Multiline functions with many inputs (we've seen thus far everything thrown together)
Let's skip the old way to do it and go straight to the new way...

        const describe = (person, age) => {
          const part1 = person + ' is';
          const part2 = age + ' years old.';
          return part1 + ' ' + part2;
        };

Run the `describe` function like so:

        describe('William', 18);

The output will be a string:

        'William is 18 years old'

##### This article brought to you by William Zhou (wzhouwzhou@gmail.com or William Zhou#0001 via Discord: <a href="https://discord.gg/jj5FzF7">https://discord.gg/jj5FzF7</a>)

LinkedIn: <a href="https://linkedin.com/in/wlzhou"><https://linkedin.com/in/wlzhou></a><br>
Github: <a href="https://github.com/wzhouwzhou"><https://github.com/wzhouwzhou></a><br>
Npm: <a href="https://www.npmjs.com/~wzhouwzhou"><https://www.npmjs.com/~wzhouwzhou></a><br>

<div align="center">
    <br />
    <p><a href="https://paypal.me/wzhouwzhou"><img src="https://img.shields.io/badge/donate-paypal-009cde.svg?style=for-the-badge&logo=PayPal" alt="Paypal" /></a></p>
    <p>
    <a href="https://nodei.co/npm/ytsearcher/"><img src="https://nodei.co/npm/ytsearcher.png?stars=true&downloads=true"></a>
    <a href="https://nodei.co/npm/ytsearcher-cli/"><img src="https://nodei.co/npm/ytsearcher-cli.png?stars=true&downloads=true"></a>
    <a href="https://nodei.co/npm/discordblacklist/"><img src="https://nodei.co/npm/discordblacklist.png?stars=true&downloads=true"></a>
    <a href="https://nodei.co/npm/easypathutil/"><img src="https://nodei.co/npm/easypathutil.png?stars=true&downloads=true"></a>
    <a href="https://nodei.co/npm/easyurban/"><img src="https://nodei.co/npm/easyurban.png?stars=true&downloads=true"></a>
    <a href="https://nodei.co/npm/sbify/"><img src="https://nodei.co/npm/sbify.png?stars=true&downloads=true"></a>
    <a href="https://nodei.co/npm/suyamiko-api/"><img src="https://nodei.co/npm/suyamiko-api.png?stars=true&downloads=true"></a>
    </p>
</div>
