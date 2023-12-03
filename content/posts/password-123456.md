+++
title = "Strong Passwords"
publishDate = "2020-05-01"
author = "Sam Denning"
+++

## My password is "123456"

Believe it or not, people still use some pretty abysmal passwords, including “123456”. Here is a summarized list of the top 5 from [NordPass](https://nordpass.com/most-common-passwords-list/):

- `123456` — or any other combination of numbers, such as `111111`
- `password` — or variations like `p@ssw0rd`
- `qwerty` — sequences of keyboard characters
- `iloveyou` — a bunch of helpless romantics
- `dragon` — does everyone like Game of Thrones?

**Are you using one of these as your password?**

![sigh](pickard-facepalm.png)

## Do you use the same password for everything?

The average person has created an account in over 100 web-sites. You probably fall into that category whether you realize it or not.

Since it is nearly impossible to remember different password for every one of these sites, most people will simply reuse the same password or some variation of it.  Do you use the same (or similar) password between your bank/financial accounts and your social media/streaming logins?  Have you ever shared your password with a family member, friend, or coworker?

## Your password may been leaked!

Even if you have never shared your password, your account information has been leaked if you have an online account with any of the following companies:

- **Zynga Games** — 218 million user accounts (2019)
- **Marriott** — 500 million customers (2018, 2014)
- **Equifax** — 148 million consumers (2017)
- **LinkedIn** — 165 million user accounts (2016, 2012)
- **eBay** — 145 million users (2014)
- **Yahoo** — 3 billion user accounts (2014, 2013)
- **Adobe** — 153 million user records (2013)

> Source: [CSO Online (April 17, 2020)](https://www.csoonline.com/article/2130877/the-biggest-data-breaches-of-the-21st-century.html)

Note that this is only a snapshot of companies that have been hacked over the years, so I recommend going to https://haveibeenpwned.com/PwnedWebsites to see the much longer list.  Since my original post, common websites such as Facebook and Twitter have been added to the list.

While it varies whether an actual password was leaked as a part of the breach, a lot of personally identifiable information was, including your e-mail. This makes it relatively easy for a hacker to target you for more information.

## Use a "strong" password

Most internet sites (and your employer) will force you to use complex passwords to ensure you (and they) are safe. Thus, your password is required to be a minimum of a certain number of characters (usually 8), but also contain a combination of upper and lower case letters, numbers, and/or special characters. Your employer and bank account will most like require you to change your password on a periodic basis as well.

This is supposed to encourage the creation of unique passwords that are not easily guessed. However, simply changing your old password to `P@ssw0rd` doesn’t really accomplish much, since simple letter replacements are easy to figure out.

## What should my password be?

Unfortunately, passwords are hard for humans to remember, but easy for computers to guess.

While computer geeks will find this [xkcd comic](https://xkcd.com/936/) both funny and informative, it probably requires a bit of explanation for everyone else.

![xkcd-troubador](xkcd-troubador.png)

Basically, it’s not enough to capitalize the first letter, replace a couple letters with characters (i.e. the letter `o` with the number `0` and the letter `a` with `4`), and add something to the end (i.e. `&3`).

Hackers use a technique called a “dictionary attack” to literally take every known word in the dictionary and apply the known variants in order to **guess a password in just a few minutes**. They can also do the same with commonly used phrases for your favorite movie, song, and sports team, such as `Letsgochiefs!`. Though, it takes quite a bit longer.

Conversely, using multiple **unrelated words** makes it exponentially harder for a computer to guess your password.  Thus, the _entropy_ increases with every unrelated word that uses upper/lower case letters, numbers, and special characters, such as `corRect_horSe4batTery#staPle`.  Some web-sites will calculate this entropy and provide hints when you create/changes passwords, such it being "weak", "good", "better", or "strong".

Now, your **strong password is easy to remember**, but **difficult for a computer to guess.**

## Why not reuse the same password?

Web-sites that prompt you for a password will store it in their database (or other means). If they implement proper security techniques, they will not store your actual password, but rather a “hash code” version of it.  It then becomes virtually impossible to figure out the password from that hash code. However, that ultimately depends on how well they protect your data, such as (using strong encryption techniques).

As pointed out earlier, some very well known web companies have been breached and you can find a pretty comprehensive list at https://haveibeenpwned.com/PwnedWebsites.

When your data (e-mail and password) is breached, it is provided on the dark web and available to any hacker who wants it. If the same (or similar) password is reused for all your online accounts, including you bank/credit card, don’t be surprised when if your accounts no longer have money in them, or are used to purchase expensive items.

**Scared?** You should be.

Continue reading about how to protect your accounts with [password managers](../password-managers) and [two-factor authentication](../password-multifactor).
