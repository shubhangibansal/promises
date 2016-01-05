PROMISES
--------------


1) Promises help you naturally handle errors,and write cleaner code by not having callback parameters, and without modifying the underlying architecture (i.e. you can implement them in pure JavaScript and use them to wrap existing asynchronous operations).

WHAT IS A PROMISE
---------------

1)The core idea behind promises is that a promise represents the result of an asynchronous operation. A promise is in one of three different states:

-pending - The initial state of a promise.
-fulfilled - The state of a promise representing a successful operation.
-rejected - The state of a promise representing a failed operation.

2)Once a promise is fulfilled or rejected, it is immutable (i.e. it can never change again).

CONSTRUCTING A PROMISE
--------------------

1)We use new Promise to construct the promise. We give the constructor a factory function which does the actual work. This function is called immediately with two arguments. The first argument fulfills the promise and the second argument rejects the promise. Once the operation has completed, we call the appropriate function.

IMPLEMENTATIONS
----------------

Promises are useful both in node.js and the browser.


