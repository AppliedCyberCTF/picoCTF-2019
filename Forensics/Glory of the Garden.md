# PicoCTF 2019 – Glory of the Garden

* **Category:** Forensics
* **Points:** 50
* **Author:** Vishnuu Gopi

## Challenge

> This garden contains more than it seems. You can also find the L file in /problems/glory-of-the-garden_3_346e50df4a37bcc4aa5f6e5831604e2a on the shell server.

## Solution

I downloaded garden.jpg and ran `strings` on it to see if the file contained the flag as a string. Lo and behold, there it was!

![Terminal Output](/Images/gardenTerminal.png)

FLAG:

'picoCTF{more_than_m33ts_the_3y35a97d3bB}'
