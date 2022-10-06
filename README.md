# intro to cpp

This is a guide for people new to programming in general, and want to learn C++
specifically. This will also cover resources for programming in C++.

Use official specification for resources. [iso cpp](https://isocpp.org/)

> iso is the international organization for standardization, who do
> standardization on everything such as the accuracy of rulers/balacnes.

Before using the iso cpp [Get Started](https://isocpp.org/get-started), using
linux/unix will be much easier to develop with.


# Installation

If you are using Windows, install
[wsl](https://learn.microsoft.com/en-us/windows/wsl/install) (windows subsystem
for linux)

After you finish installing, WSL. You should install the official [Windows
Terminal](https://apps.microsoft.com/store/detail/9N0DX20HK701?hl=en-us&gl=US)
application. You should also install [Ubuntu
distribution](https://apps.microsoft.com/store/detail/ubuntu-on-windows/9NBLGGH4MSV6?hl=en-us&gl=us).

To use WSL, open up the Windows Terminal app, and switch to the Ubuntu shell at
the tab on the app It will then ask for username, password, etc. You can use
any password, like your windows password. Don't forget your password though.

> There are some downfalls with using WSL with windows instead of just using
> Linux. Such as being able to install services with systemd (hint you need to
> use init I believe).

I wrote a somewhat guide for new developers unfamiliar with linux, for wsl
users. [wsl-intro](https://github.com/yuuwe-n/wsl_intro) It has an introduction
for Linux, Git, Vscode, Markdown, and the GoLanguage. I recommend reading all
the pages, except the Go Language one.

---

After reading the guide, you can [Get Started](https://isocpp.org/get-started). 

I reccomend either using the gcc compiler or clang. I believe that the gcc
compiler is already installed with wsl ubuntu. You can check by running `gcc`
in the terminal

# Programming Book

The ISO recommends [Programming: Principles and Practice Using C++, 2nd
Ed.](http://www.informit.com/store/programming-principles-and-practice-using-c-plus-plus-9780321992789) 
I have skimmed this book, and it seems very good for people who have not
touched programming at all. I recommend reading it all, from preface to the
end.

> the books is on libgen, but I recommend geting the physical copy, because I am unsure if pages are missing in there

> A "Tour of C++" is not for beginners, it is for people who have a background
> in programming already. Use the book recommended above instead

# Tips

> These are tips that apply to programming in general

Try understanding the code segments presented in the code. For notes, don't
take notes on every single syntax line, __you will learn syntax when you code__.

When beginning, I reccomend to write the code segments inside your IDE/text
editor. It helps you learn syntax/understand the code. I especially do this,
when reviewing a language I don't use often, or learning a new language.

> Once you learn programming, learning other languages is just learning the
> speficic speicifcation/syntax of a language

Try doing most of the exercises in the book. If you get stuck, try going to
solutions. Don't get too boggged down by a problem, just note that you should
look at it again later on.

> I don't think there solutions in the book, I am not sure though. Just mark the
> problem if you have a problem with it, then come to it later on if it is
> important

Don't go through a book too fast or slow. Pace yourself. Maybe 1 - 2 chapters a week (be consistent with your learning)

# FAQ

How does compiling work?
> compilers, read about compiler design. `man clang`, has a general overview of
> compilation steps.

Should I learn 2 languages at once?
> I don't recommend it. I recommend either learning 1 or the other. If you have
> to choose, flip a coin. (also I recommend you do python first if this is your
> first language, but if you have to do C++ anyways, the book recommened above
> seems to do a very good job in teaching programming concepts)

> Learning languages are easy, learning how to program initally and learning algorithms are the hard part.

What's the difference between a compiler and interpreter
> In layman's terms, compilers will read through the code, and convert your
> code into an executable file in binary/asm (example .exe file on windows). 

> An interpreter like python cannot convert your code into an executable. It
> will go line by line and run each line sequentially. You can run a python
> file
> like `python file.py`, python needs to be installed on the computer to run
> the program. With an exe file, it will run on whatever machine that is
> compatible with the architecture. 

> This is mostly why, intepreters are slower than compilers since interpreters
> have to translate code on the run. While compilers translate the code
> beforehand.
