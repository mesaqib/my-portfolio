---
title: "Basic Data Structures in JavaScript : Arrays and Object."
author: saqib
date: 2021-07-18T09:45:49.758Z
tags:
  - post
image: /assets/blog/imggggggg.png
description: Data can be stored and accessed in many ways. You already know some
  common JavaScript data structures — Arrays and Objects.  In this Basic Data
  Structures Blog, we'll learn more about
imageAlt: img
---
 <br/>

Data can be stored and accessed in many ways. You already know some common JavaScript data structures — **Arrays** and **Objects**.

In this Basic Data Structures Blog, we'll learn more about the differences between arrays and objects, and which to use in different situations. We'll also learn how to use helpful JS methods like `splice()` and `Object.keys()` to access and manipulate data.

<br/>

## 1️⃣ Use an Array to Store a Collection of Data

Here is an example of the simplest implementation of an array data structure.

![alt](/assets/blog/1.png "Use an Array to Store a Collection of Data")

<br/>

<!--StartFragment-->

This is known as a **one-dimensional array**, meaning it only has one level, or that it does not have any other arrays nested within it. As you can see it can contain booleans, strings, and numbers, among other valid JavaScript data types.

All arrays have a length property, which as shown above, can be very easily accessed with the syntax **`Array.length`**.

A more complex implementation of an array can be seen below.

<!--EndFragment-->

<br/>

![alt](/assets/blog/2.png "Use an Array to Store a Collection of Data")

<br/>

<!--StartFragment-->

This is known as a **multi-dimensional array**, or an array that contains other arrays.

You must have noticed this array also contains JavaScript objects, which we will discuss soon, but for now, all you need to know is that arrays are also capable of storing complex objects.

<!--EndFragment-->

<br/><br/>

<br/>

<!--StartFragment-->

## 2️⃣ Access an Array's Contents Using Bracket Notation

<!--EndFragment-->

<br/>

<!--StartFragment-->

The fundamental feature of any data structure is, of course, the ability to not only store data, but to be able to retrieve that data on command. So, now that we've seen how to create an array, let's begin to think about how we can access that array's information.

When we define a simple array as seen below, there are 3 items in it:

<!--EndFragment-->

<br/>

![Access an Array's Contents Using Bracket Notation](/assets/blog/3.png "Access an Array's Contents Using Bracket Notation")

<br/>

<!--StartFragment-->

In an array, each array item has an **index**. This index doubles as the position of that item in the array, and how you reference it.

It is important to note, that JavaScript arrays are zero-indexed, meaning that the first element of an array is actually at the zeroth position, not the first.

To retrieve an element from an array, we can enclose an index in brackets and append it to the end of an array, or more commonly, to a variable which references an array object. This is known as bracket notation.

For example, if we want to retrieve the `a` from `ourArray` and assign it to a variable, we can do so with the following code:

<!--EndFragment-->

<br/>

![](/assets/blog/4.png)

<br/>

<!--StartFragment-->

Now, `ourVariable` has the value of a.

In addition to accessing the value associated with an index, you can also set an index to a value using the same notation:

<!--EndFragment-->

<br/>

![Access an Array's Contents Using Bracket Notation](/assets/blog/5.png "Access an Array's Contents Using Bracket Notation")

<br/>

<!--StartFragment-->

Using bracket notation, we have now reset the item at index 1 from the string `b`, to `not b anymore`. Now `ourArray` is `["a", "not b anymore", "c"]`.

<!--EndFragment-->

<br/><br/><br/>

<!--StartFragment-->

## 3️⃣ Add Items to an Array with `push()` and `unshift()`

<!--EndFragment-->

<br/>

<!--StartFragment-->

An array's length, like the data types it can contain, is not fixed. Arrays can be defined with a length of any number of elements, and elements can be added or removed over time; in other words, arrays are mutable.

Now we will look at two methods with which we can programmatically modify an array:

* `Array.push()`, and
* `Array.unshift()`

Both methods take one or more elements as parameters and add those elements to the array the method is being called on:

* the `push()` method adds elements to the end of an array, and
* `unshift()` adds elements to the beginning of an array

Consider the following:

<!--EndFragment-->

<br/>

![romanNumerals would have the value ['XIX', 'XX', 'XXI', 'XXII'].](/assets/blog/6.png "romanNumerals would have the value ['XIX', 'XX', 'XXI', 'XXII'].")

<br/>

<!--StartFragment-->

`romanNumerals` would have the value `['XIX', 'XX', 'XXI', 'XXII']`.

<!--EndFragment-->

<br/>

![push() method ](/assets/blog/7.png "push() method ")

<br/>

<!--StartFragment-->

`romanNumerals` would have the value `['XIX', 'XX', 'XXI', 'XXII', 'XXIII']`.

Notice that we can also pass variables, which allows us even greater flexibility in dynamically modifying our array's data.

<!--EndFragment-->

<br/><br/><br/>

<!--StartFragment-->

## 4️⃣ Remove Items from an Array with `pop()` and `shift()`

Both `push()` and `unshift()` have corresponding methods that are nearly functional opposites:

* `pop()`, and
* `shift()`

Instead of adding,

* `pop()` removes an element from the end of an array, while
* `shift()` removes an element from the beginning.

The key difference between `pop()` and `shift()` and their cousins `push()` and `unshift()`, is that neither method takes **parameters**, and each only allows an array to be modified by a **single element** at a time.

Let's take a look:

<!--EndFragment-->

<br/>





<center>

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-in.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=IN&source=ss&ref=as_ss_li_til&ad_type=product_link&tracking_id=saqib0ad-21&language=en_IN&marketplace=amazon&region=IN&placement=B09GFLFMPS&asins=B09GFLFMPS&linkId=71274cb31741ed6a2d31d532129dfce9&show_border=true&link_opens_in_new_window=true"></iframe>



</center>