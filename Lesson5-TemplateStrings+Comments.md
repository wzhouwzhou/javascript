# Our fifth lesson with programming in javascript: - Template Strings and Comments
William Zhou | Tuesday December 25, 2018
## Core takeaway
### In programming, it's important to be clear and concise. We can do this by commenting out code to help out other developers who see our code, as well as clean up how raw strings look within our code.

<hr>

Template strings are a special type of string. Recall back to our first lesson where we introduced the three ways to declare a string with single quotes, double quotes, and the tick mark \`

#### The tickmark is used to let you embed variables within strings without a messy notation
Let's take a look at the most basic way to do it;

        let x = 5;
        `X has a value of ${x}`

The value of x gets placed within `${ }` and turned into a string. Thus the entire string becomes: `X has a value of 5`

The stuff in between `${ }` is on the spot so you can put expressions as well:

        let x = 5;
        `Add 1 to x and you get ${1 + x}`

The value `1 + x` is computed on the spot so the entire string becomes `Add 1 to x and you get 6`

You can put multiple variables and expressions within the string:

        let x = 1, y = 2;
        let string = `X is ${x} and Y plus one is ${y + 1}`;

The variable `string` now has a value of `'X is 1 and Y plus one is 3'`

##### Why would you use template strings over adding strings with "+"?
Too many + in your code can become messy really easily. Additionally, what if you had the plus sign within your string? It can get confusing quickly. However, that said, it's bad practice to use template strings everywhere. Use them only if you are using ${ } to "embed" variables and expressions into your string.

#### Comments come in two varieties: single-line and multi-line
Comments in javascript are just comments, meaning they're there for developers to read but do not affect running the program.

**Single-line comments start with // and extend to the end of the line.**

        // This is an example of a single line comment
        let x = 5; // This single line comment appears after "let x = 5". The comment, aka the stuff after //, is not run by the computer, but let x = 5 is.
        // Bottom line: anything on the same line that appears after "//" is NOT run

**Real life use case: single-line comment that documents a variable**

        let num_b = 3; // num_b represents the number of bulbs (instead of bathrooms) inside the room.

**Multi-line comments start with /\* and end with \*/*. We indent and put \* at the start of every line in the middle to make it look nice.**

        /*
         * This is a
         * multi-line comment
         * Anything between the starting "/*" and ending "*/" is part of the comment and is not run.
         */

You may see variants like this:

        /*\
         * Something
        \*/

or

        /*\
        |*| Something
        \*/

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
