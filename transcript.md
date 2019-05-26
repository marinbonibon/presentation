Hi everyone, my name is Marina and today  I’m going to tell you about Lodash.

I want to start with its definition and a little background.

 So the first question is **“What is Lodash?”**

Lodash is a JavaScript library which provides utility functions for common programming tasks using the functional programming paradigm.
In other words Lodash makes programmers’ life easier by providing ready-to-use functions for working with various objects and helps programmers write concise and maintainable code.

Now a little bit of **history.**

The original author of Lodash is John-David Dalton. 

The initial release came out on April 23, 2012. 

From the start, Lodash was created as a fork of Underscore.js library, but since then has managed to become its superset, adding new features and performing much better.

**How to begin?**

To install Lodash in a browser you may use external url
 Or download the build.
Also you can use npm 
or Node.js. 
And voila, now you can use Lodash methods in your application.

The documentation and detailed description of all Lodash methods you can find on **lodash.com**

You may ask “**Why should I use Lodash** instead ES6, when it has a lot of duplicated methods?”
To answer this question I want to list some of Lodash **advantages** that I found.

The first is **compatibility**. You don't have to worry about it. Lodash works on all browsers, even on old ones.

Next is **modularity**. Lodash functions are broken into separate modules, and you may only import a specific module or just one function rather than importing the whole library.

Next one is **clear and functional syntax** that enables writing more concise code.

And the last one is **high-quality documentation**, where you can find full description of all methods with examples, choose the version of Lodash and so on.

Now, let’s proceed to one interesting **example**.

Let’s imagine that you have an array of objects and you need to get its properties. Lodash map can do this using the _.property iteratee shorthand, but native map doesn't support it. 
Instead, you should write something like this.
So let’s return to Lodash.

Lodash can be broken down into several **main areas**:
- Array
- Collection
- Date
- Function
- Lang
- Math
- Number
- Object
- Seq
- String
- Util
- Properties
- Methods

Its API as a whole is too big to cover, so what we will do is briefly consider some examples.


**Array methods**

Naturally, all Lodash array methods work on arrays. It's probably the biggest collection of Lodash methods.
For example, method chunk creates an array of elements split into groups the length of size. If array can't be split evenly, the final chunk will be the remaining elements.
And here you can see how it will looks like in native JS. In my opinion Lodash chunk is better. It’s shorter and more convenient, as for me.



Next group of methods is **Collection.**

This group includes methods that can be used to work with arrays, objects and strings.
	For example, method size. This method returns the collection size. Let's compare the implementations in Lodash and native JavaScript. I also think that Lodash method is more convenient.


When it comes to **date collection**, there's only one method - now. And here you can see the example.

Next group is **Function.**

Function collection probably includes some of the most complex methods. 
Lodash provides us with many helpful shorthands for some of the functions-related stuff. 
For example, method flip creates a function that invokes func with arguments reversed. As you can see here.



Next group is **Lang.**

Lang collection is very diversified. It contains methods that work on a variety of data types. These cover various is checks (for example isArray, isNumber), value conversions (for example toNumber, toString), cloning and deep cloning functionalities.

Here is clone method that creates a shallow clone of value.

Math collection that operates on number arrays can prove to be quite useful, for example let’s take a look on mean method, that computes the mean of the values in array.


Next - **Number methods.**

Number collection, in fact, includes only 3 methods. These are : clamp, inRange and random, all of which provide some casual functionalities with additional features.  Let’s take random method for example. Instead of outputting completely random number, you can easily limit it to a certain range and decide whether you want it to be an integer or floating-point number with just a simple set of arguments.

Next are **object methods.**

Object collection groups methods that work primarily on objects.  Methods are connected with the iteration capabilities, object assignment , merging, cloning and differentiating. Let’s take a look on method pick. This method creates an object composed of the picked object properties. As we can see on this example, we picked properties “a” and “c”.

Next are **Seq methods**

Seq is a collection of prototype methods, centered around one functionality - Lodash value wrapper (_()). With such wrapper in place, you can omit the repeating _.(underscore dot) and use your methods directly on your value like in this example.

**String methods.**

Methods from string collection cover some pretty useful capabilities like converting between different case types, methods for swapping letters, string-array conversion, regex integration and more.
 For example, method camelCase converts string to camel case.

**Util methods**

There isn't really any rule that groups all these methods together. Thus, there's almost no method that has its direct native equivalent.
For example, method range that creates an array of numbers progressing from start to end, but not including the end. As you can see the default value for start is zero and for step is one, so if we put only one number as an argument, we will get the array from zero till four, but not including four.

And the last two groups are **Properties and Methods**. 

They contain a small group of functions for dealing with templateSettings. And Properties contain version information useful when code needs to run with different versions of Lodash.


In **conclusion** I want to say that, although there are a lot of  native methods that could replace Lodash methods, this library is still very powerful and useful. Maybe for someone it is more convenient to use Lodash. So using it or not is your personal choice, but I recommend to try it.


So, that’s all.
Thanks for watching.Bye.
