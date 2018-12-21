# Our second lesson with programming in javascript: Types
William Zhou | Thursday December 20, 2018
## Core takeaway
### Everything we use to program, be it numbers, strings, true/false, etc, can be categorised into types. Types in js can be retrieved with "typeof" and are represented as strings

<hr>

There are several different types in Javascript, and today we're introduced to three of them.


#### Strings (A review from Lesson 1): sequences of characters (letters, symbols, etc)
We've seen strings from the previous lesson (those things wrapped with single quotes `'`, double quotes `"` and
those wrapped with tick marks <code>`</code><br>
They look like this:

        'Hello, world!'
        "What's this?"
        `Paris said, "That's mine!"`
![](https://cdn.discordapp.com/attachments/297582971488174096/525123053152239626/Anime.png)

#### Booleans: true and false values.
Booleans are used to indicate either yes or no, on and off, 1 or 0, etc.

        true
        false
![](https://cdn.discordapp.com/attachments/297582971488174096/525476219244904448/True.png)

Notice, there are only two boolean values. Booleans are useful when you know a result can only be one of two things. 

#### Numbers: 1, 2.5, -10, literally any number you can count.
The number type includes positive numbers, negative numbers, decimals, etc.

![](https://cdn.discordapp.com/attachments/297582971488174096/525476584669446155/-10.5.png)

<hr><hr>

#### Using <code>typeof</code> to get the type of something.
The typeof `keyword` gives you the type of what comes after it.


##### typeof \<string\>
Let's take a look at an example of using typeof with a string...

        typeof 'Plutia'
In this case we are trying to find the type of `'Plutia'`.
From the three types introduced above and Lesson 1, remember that 'Plutia' is a string. (It's a sequence of 6 letters.)

The result of `typeof 'Plutia'` is a string containing the type: `'string'`

![](https://cdn.discordapp.com/attachments/297582971488174096/525479503154249728/typeof_Plutia.png)

Let's learn by example.

        typeof 'Hello'
        typeof 'Itadakimasu'
        typeof 'WoaH, winter vacation is finally here!'

All of these are strings, so using `typeof` on them will give us a string with the value 'string', just like we did with `typeof 'Plutia'`

![](https://cdn.discordapp.com/attachments/297582971488174096/525479882289840149/typeof_string.png)

<hr>

##### typeof \<boolean\>
Let's take a look at an example of using typeof with a boolean...

        typeof true
In this case we are trying to find the type of `true`.
From the three types introduced above, remember that true is a number. (Booleans are either true or false.)

The result of `typeof true` is a string containing the type: `'boolean'`

![](https://cdn.discordapp.com/attachments/297582971488174096/525553561203900416/typeof_true.png)

Let's learn by example.

        typeof true
        typeof false
        typeof !true

All of these are booleans, so using `typeof` on them will give us a string with the value 'boolean', just like we did with `typeof true`

![](https://cdn.discordapp.com/attachments/297582971488174096/525553335017668608/typeof_boolean.png)


##### typeof \<number\>
Let's take a look at an example of using typeof with a number...

        typeof 20
In this case we are trying to find the type of `20`.
From the three types introduced above, remember that 20 is a number. (It's a positive integer.)

The result of `typeof 20` is a string containing the type: `'number'`

![](https://cdn.discordapp.com/attachments/297582971488174096/525478228878426116/typeof_20.png)

Let's learn by example.

        typeof 30
        typeof -24
        typeof 0.1

All of these are numbers, so using `typeof` on them will give us a string with the value 'number', just like we did with `typeof 20`

![](https://cdn.discordapp.com/attachments/297582971488174096/525478709592064021/typeof_number.png)


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
