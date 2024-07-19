# Chrome's V8 Engine

> [!IMPORTANT]
> V8 is written in C++
>
> Chrome's V8 engines by Google sits at the core of Node.js.
>
> By embedding V8 into your own C++ application, you can write C++ code that gets executed when a user writes JavaScript code.
>
> You can add new feature to JavaScript itself
>
> Since C++ is great for lower level operations like file handling, database connections and network operations, by embedding V8 into your own C++ program, you have the power to add all of that functionality in JavaScript

[V8 page](https://v8.dev/)
<br>
[V8 source code](https://github.com/v8/v8)

## Table of contents

- [JavaScript Engine](#javascript-engine)
- [Chrome's V8 Engine Summary](#chromes-v8-engine-summary)

## JavaScript Engine

JavaScript code we write cannor be understood by the computer
<br>

A JavaScript engine is program that converts javascript code that developers write into machine code that allows a computer to perform specific tasks
<br>

> [!NOTE]
> JavaScript engine can execute JavaScript code

JavaScript engines are typically developed by web browser vendors and every major brower has one

- V8 - Open-source JavaScript Engine developed by Google for Chrome
- SpiderMonkey - The JavaScript Engine powering Mozilla FireFox
- JavaScriptCore - Open-source JavaScript Engine developed by Apple for Safari
- Chakra - A JavaScript Engine for the original Microsoft Edge ( The lastest version of edge uses V8 )

## Chrome's V8 Engine Summary

- A JavaScript engine is a program that executes JavaScript code
- In 2008, Google created its own JavaScript engine called V8
- V8 is written in C++ and can be used independently or can be embedded into other C++ programs
- That allow you to write your own C++ programs which can do everything that V8 can do and more
- Your C++ program can run ECMAScript and additional features that you choose to incorporate

> [!NOTE]
> For features that are available in C++ but not available in JavaScript which is the ideal behind Node.js.

[Back to top](#top)
