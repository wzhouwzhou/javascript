# Our second lesson with programming in javascript: Part 2 — Numbers and basic operators
William Zhou | Friday December 21, 2018
## Core takeaway
### Up to now, we've mainly been defining our numbers or variables and not modifying them later on. In javascript, we have several operators we can use to do just that: + - * / ! 

<hr>

Today, we'll be looking at some of the 5 core operators in javascript.


#### The addition `+` Operator for addition
##### Number addition
Addition for numbers is pretty straightforward. \<number\> + \<number\> gives us another number that is the sum of the previous two. Let's have a look...

        1 + 0 + 1
        32 + 0.5
        12 + 0.

Basic arithmetic tells us that the result should be:

        2
        32.5
        12

Remember, no matter how you type the number (i.e. `0` vs `0.`, `0.0`, or even `0.0000`), the decimal point only appears as needed

##### String "addition" (concatenation)
You can add two strings together using `+` as well.

        'Hello' + ' world!'
        'What' + ' is ' + 'this'

becomes

        'Hello world'
        'What is this'


##### Mixed string and number addition
Numbers are converted to strings when added to a string:

        'The year is ' + 2018 

becomes

        'The year is 2018'

#### The `+` operator for converting a string to a number

Think back to Lesson2a and types. Remember that these two are different:

        '1'
        1

The '1' in quotes is a string, and 1 by itself is a number.
To convert '1' to a number, it's very simple: put a `+` in front.

![](https://cdn.discordapp.com/attachments/297582971488174096/526823139527622656/1.png)

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
