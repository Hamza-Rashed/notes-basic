# Error Handling & Debugging

> In an ideal world everyone would write perfect code and there would never be any need to debug.
However in reality, virtually every project is going to require some degree of debugging. The 
more complex the project the more like this is to be true. Fortunately LiveCode includes a full
plethora of debugging tools and techniques that make it quick and easy to track down errors. The
live run-edit cycle allows you to see the effect of corrections as soon as you make them. And, 
unlike working in a lower-level language, when you make a mistake you will receive a human-friendly
error message pointing you to where the error occurred, instead of the application unexpectedly quitting.

> As well as the set of built-in error reporting and debugging tools, LiveCode also allows you 
complete flexibility over error handling, allowing you to provide a customized experience to 
the end user of your application

# Error handling
Error handling is the process of responding to and recovering from error conditions in your program. Swift provides first-class support for throwing, catching, propagating, and manipulating recoverable errors at runtime.

Some operations aren’t guaranteed to always complete execution or produce a useful output. Optionals are used to represent the absence of a value, but when an operation fails, it’s often useful to understand what caused the failure, so that your code can respond accordingly.

As an example, consider the task of reading and processing data from a file on disk. There are a number of ways this task can fail, including the file not existing at the specified path, the file not having read permissions, or the file not being encoded in a compatible format. Distinguishing among these different situations allows a program to resolve some errors and to communicate to the user any errors it can’t resolve.

> Note

Error handling in Swift interoperates with error handling patterns that use the NSError class in Cocoa and Objective-C. For more information about this class, see Handling Cocoa Errors in Swift.


![](https://lh3.googleusercontent.com/proxy/OKT-6PK_lkfC8fUm-kFUhH9bp-zgZzbYY8cq_5bPMdH_UfFadaFOb-y-cSMEXNYlZ4zs9DS2ILgavkt-VwAyFqLhoTO3M-rOk57USezJ22UmwqXIcu1aa_mdgQ)

# Debugging

No matter how much experience you have, the JavaScript code that you’re writing may contain an error. If not syntactical, there’s a high chance that you’ll get a logical error in case of a complex app.

A frustrating thing is that often you won’t get an error message or any clue about where the error is happening. Debugging is the technique of searching for and fixing these unknown errors.

Debugging is done by forcing the code to stop running at a certain line. You can do that by setting a breakpoint. Once the code is paused, you can inspect and find out what’s wrong with the code. Wondering how to debug in the case of a JavaScript code? We’ll find out in the next section.

![](https://image.slidesharecdn.com/debugging-javascript-web-141030080414-conversion-gate02/95/debugging-javascript-1-638.jpg?cb=1415345877)
