# Our first lesson with programming in javascript: Strings
William Zhou | Wednesday December 19, 2018
## Core takeaway
### Think of strings as words, sentences, collections of letters, numbers, symbols, and anything you can type on your keyboard.

<hr>

Javascript strings come in **3 varieties**: those wrapped with single quotes `'`, those wrapped in double quotes `"` and
those wrapped with tick marks <code>`</code>

**Strings look like this:**

        'Hello, world!'
        "What's this?"
        `Paris said, "That's mine!"`

**Which become, respectively:**

Hello, world!<br>
What's this<br>
Paris said, "That's mine!"<br>
<hr>

### Escapes (<code>\\</code>)
##### Using non-typeable or special characters
What if you wanted a string to contain a new line, a tab, etc? The best way to denote this is with backslash escapes.

##### Newlines are linebreaks, as you would type with the return key
**A string with a newline in it looks like:**

        'Shirayuki\nHime'

**Which becomes:**

        Shirayuki
        Hime

##### Tabs are basically larger spaces

**A string with a tab in it looks like:**

        "Shirayuki\tHime"

**Which becomes:**

        Shirayuki   Hime

#### Notice how both of these above had \ followed by a letter (n for \n and t for \t) 
##### What if you wanted only the \ character?

**A strings with a backslash in it look like:**

        'Too\\lewd'


**Which becomes:**

        Too\lewd


#### "Mixing and matching" escapes (they can occur multiple times)

**This (double newline and a tab)**
        'Hello\n\n\tthere!'

**Becomes**

        Hello
        
           there!

...and...

**This (double backslash)**

        'Nani\\\\kore'
**Becomes**

        Nani\\kore

...and...

**This (both a newline and backslash)**

        'Loli\nis\\justice!'

**Becomes**

        Loli
        is\justice!
<hr>

### Output (console.log)
##### Logging things to console
We use a thing called **`console.log`** to print them to our terminal screen/command line:

        console.log('Anime')
Outputs **`Anime`** to the command line:

![](https://cdn.discordapp.com/attachments/297582971488174096/525123053152239626/Anime.png)

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
