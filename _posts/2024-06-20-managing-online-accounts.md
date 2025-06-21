---
layout: post
title: "Managing online accounts"
date: 2024-06-20
---
I’ve been thinking about writing this for a while, and this week’s leak of **16 billion passwords**, including Facebook and Instagram, finally pushed me to write about it.

Every time a breach like this happens, I feel relieve I introduce in my day-to-day this system years ago that keeps me in control. It's not magic, takes a bit more time to organize my accounts, but it works: I use a custom domain for email aliases, unique passwords for every service, and, when possible, enable MFA.

---

## Custom Emails for Every Account

I have a custom domain let's imagine something like `myname.io` set up with a mail service, let’s say Google Workspace as an example. For every service, website, or app, I register with a different email address:

- `facebook@myname.io`  
- `netflix@myname.io`  
- `whatever@myname.io`

This way, it help me know where a leak or spam is coming from. If I get phishing on `facebook@`, I know Facebook either leaked or sold my data. Plus, I can block or reroute any alias as needed.

> *Example:* back in 2022, TAP (the Portuguese airline) had a data breach. I had an alias set up - `tap@`. A few weeks after the leak, I started getting a bunch of shady emails to that exact alias. I just disabled the alias, changed the password and email address on TAP. No damage, no spam in my main inbox, and no need to change anything else.

**Tip:** You can wildcard everything to a single inbox (`*@myname.com`), or split it - trusted services to one inbox, the rest to another. Depends on how much control you want.

**Pro tip:** use a second domain for this kind of thing, something that doesn’t have your name in it. That way you avoid spam or personal exposure.

---

## No Custom Domain?

If you don’t want to buy a domain, use Gmail’s "+" trick:

- `your_email+facebook@gmail.com`  
- `your_email+github@gmail.com`

Same inbox, but you can filter, sort, and spot leaks easily. When using the "+" after your Gmail username, it works as a wildcard for your mailbox, but you can still see where the email was sent, so you can trace where it originally came from, even if you only use one email account.

---

## Passwords, Passphrases and MFA

I use multiple apps to generate and manage passwords, like [1Password](https://1password.com) and [LastPass](https://lastpass.com). Every account has its own unique, random password. No exceptions. If something leaks, the damage is contained, I generate a new password and email combination for the service and call it a day. These services also have desktop & mobile apps that help with autofill.

For things I need to remember, like master passwords or device unlock codes, I use **passphrases**. Basically, long combinations of random but memorable words, like:

`volcano-motor-banana-wolf`

They’re much easier to remember than `F7!d$Xv0z!` and way more secure than most short passwords.

And yeah - always enable 2FA/MFA. Use an app like [Authy](https://authy.com) or a physical key like [YubiKey](https://www.yubico.com/). It’s 2025, never rely on SMS.

---

## Final Thought

Setting this up takes a bit of time, but it gives you control and visibility over your digital identity. I don’t get surprised by spam. I know where data leaks from. And if a password gets exposed, it’s an isolated event.

If you haven’t already, now’s the time to start. This week’s breach is just another reminder.
