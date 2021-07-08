# PicoCTF 2019 – picobrowser

* **Category:** Web
* **Points:** 200
* **Author:** Vishnuu Gopi

## Challenge

> This website can be rendered only by picobrowser, go and catch the flag! https://2019shell1.picoctf.com/problem/45071/ (link) or http://2019shell1.picoctf.com:45071

## Solution

The first thing that came to mind when I saw this challenge was changing the user agent. In simple terms, the user agent tells the website what browser the device is using. By changing the user agent, you can change what device/browser the website thinks you're accessing it from.

After a quick google search, I downloaded a [User Agent Switcher](https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/) for Firefox. I created a custom "label" and "agent" in the settings for that extension, labeling each as "picobrowser". 

![User Agent Switcher](/Images/uaswitcher.png)


Then, I reloaded the site, clicked the button, and got the flag!

![Flag](/Images/picobrowser_flag.png)

Nice and easy.

FLAG: `picoCTF{p1c0_s3cr3t_ag3nt_b3785d03}`
