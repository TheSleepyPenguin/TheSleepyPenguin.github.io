---
layout: post
title: "Pyinstaller Basics: Convert .py to .exe/ELF"
author: sleepy-penguin
date: "21 April 2018"
image: "images/pyinstaller-basics/thumbnail.jpg"
categories: [python, programming]
comments: true
featured: true
---

Pyinstaller can bundle Python .py files into Windows .exe or Linux ELF files. This video/post will cover the basics of using this useful tool.

<div class="videoWrapper">
    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/RMkPGjGhzxg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<br/>



## Tutorial Info

---

#### Links

**Note:** I can not be responsible for the content of any of these external sites.

If any of these links are broken, please let me know!

<div style="overflow-x: auto; padding-bottom: 10px" markdown="block">

| Item | URL |
| --- | --- |
| Pyinstaller Website           | [https://www.pyinstaller.org/](https://www.pyinstaller.org/) |
| Pyinstaller Documentation     | [https://pyinstaller.readthedocs.io/](https://pyinstaller.readthedocs.io/) |
| C++ Redist **(Windows only)** | [https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads](https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads) |

</div>

<br/>

#### Notes

I have only covered the basics in this video - there is much more to Pyinstaller! Please see the documentation linked above to learn more.

**For Linux only:**

- Build different versions for 32 and 64 bit applications
- Build on the oldest version of Linux you want to support

#### Music

**"Thief in the Night"**  
Kevin MacLeod (incompetech.com)  
Licensed under [Creative Commons: By Attribution 3.0 License](http://creativecommons.org/licenses/by/3.0/)

<br/>

## Troubleshooting

---

**Q:** When I run the program on Windows, the console window opens up and just closes again!

**A:** This could by caused by:

1. Errors in your code - once your program runs into an error, it'll close. Make sure that your program works fully before trying to package it with Pyinstaller.
2. The lack of `input()` at the end of your program. Without it, your program will run and as soon as it's finished, it'll close. `input()` will prevent the window from closing until you press `Enter`.

