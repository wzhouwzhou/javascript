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

#### The `+` operator for converting a boolean to a number

Remember that booleans are true/false. In computers, true is 1 and false is 0. We can confirm this like so:

![](https://cdn.discordapp.com/attachments/521564029433675776/526827961870057502/boolean.png)

#### The `-` operator
The `-` operator is used for number subtraction only. Please make sure you only use this with numbers (unless you know what you're doing)

        5 - 3

becomes

        2

#### The `*` operator
The `*` operator is used for number multiplication. It's like using `x` or `•` on paper. Let's look at an example:

        2 * 9
        1 + 3 * 4
        1.5 * 2

becomes

        18
        13
        3

Remember that order of operations applies at all times, just like with regular math! In this case, multiplication comes before addition/subtraction.

#### The `/` operator
The `/` operator is used for number division. 

        8 / 4
        4 / 2 + 9 / 3

becomes

        2
        5

Don't forget about order of operations.

#### The `!` operator
The `!` operator is very special: it converts things after it to boolean and flips the value. This is explained better with examples.
Let's start with the basics, boolean-only:

![](https://cdn.discordapp.com/attachments/521564029433675776/526827235253026816/boolean.png)

Now let's look at converting numbers to booleans. Remember how we said that false was 0 and true was 1?
When converting backwards, any number BUT 0 is true, and ONLY 0 is false.
HOWEVER, remember that ! flips it once. If you want the boolean version, ! converts it to a boolean and flips it, so to unflip it use another !.
meaning: !!number -> the boolean value 

![](https://cdn.discordapp.com/attachments/521564029433675776/526829464085069875/Screen_Shot_2018-12-24_at_1.31.02_PM.png)

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
