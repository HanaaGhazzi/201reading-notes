# JavaScript Debugging
_Errors can (will) happen, every time you write some new computer code._

**Code Debugging:**
Programming code might contain syntax errors, or logical errors.

Many of these errors are difficult to diagnose.

Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

Searching for (and fixing) errors in programming code is called code debugging.

______________

> The console helps narrow down the area in which the
error is located, so you can try to find the exact error.

### The console.log() Method
If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window. 

### Setting Breakpoints
In the debugger window, you can set breakpoints in the JavaScript code.

At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.

After examining values, you can resume the execution of code (typically with a play button).

### The debugger Keyword
The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.

This has the same function as setting a breakpoint in the debugger.

If no debugging is available, the debugger statement has no effect.

![debugging](https://developers.google.com/web/tools/chrome-devtools/javascript/imgs/sources-annotated.png)