# Our third lesson with programming in javascript: - Variables
William Zhou | Monday December 24, 2018
## Core takeaway
### Variables are like our variables in algebra, x, y etc. Name them anything you want. Think of them like placeholders for values that we might not know until, say, someone gives it to us. 

<hr>

Today, we'll be looking at a couple simple ways to declare variables in javascript.


#### The let keyword
Variables in js can be named almost anything: Names can contain upppercase and lowercase letters A through Z, numbers, `$` and `_` (dollar and underscore). However, they may not start with a number.

        let x;

This tells the computer we want to create a variable named `x`.

        let x;
        x = 5;

This tells the computer, we want to create a variable named `x`. Immediately after doing so, in the next line, please set this `x` we created to the number `5`.

We can (and most often do) shorten this into one line;

        let x = 5;

This use of `=` stores whatever is on the right into whatever is on the left. In this regard, computers are reading right to left.
This use of `=` is called assignment.

#### The var keyword
Generally, don't use this, since it's "old" and has some perks about it which I won't go into here since this is an intro to variables.
However, when you read someonee's code and see they are using var, think of it like `let` and for the most part it should be fine.

        var x = 5;

becomes

        let x = 5;

#### The const keyword
Constants, are variables, but we let the computer know that we want to give it a variable that is not supposed to change values, and if it does, something very strange has happened.
Use const just like let. We typically use all caps for constant numbers, strings, etc, but it's up to the developer.

        const FLOORS = 5;

#### Using variables
Now that we know how to create variables, let's actually use them.

        let x = 5;
        console.log(x);

In this case, we create a variable `x`, assign it to 5, then log it:

![](https://cdn.discordapp.com/attachments/521564029433675776/526839147722309644/let_and_console.png)

Let's have a look at another example:

        let x = 0;
        let y = x + 2;
        console.log(y);

We create two variables to use here. First, we set x to 0. Then we set y to x plus 2.
Since by the time we get to the second line, x is already set to 0, x + 2 is 0 + 2, which is 2.
This means that y is set to 2.
`console.log(y)` will thus log 2 to our console.

<hr>

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
