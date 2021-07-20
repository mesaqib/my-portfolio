---
title: How we can create a custom scrollbar for our website
author: saqib
date: 2021-07-20T07:05:10.200Z
tags:
  - post
  - featured
image: /assets/blog/1.how-we-can-create-a-custom-scrollbar-for-our-website.png
description: Recently, I figured out about customizing scrollbars. Adding custom
  scrollbars to websites you make, helps enhance it even further and also helps
  in overall color-coordination. To start with, we use ::-webkit-scrollbar.It
  can be included in your CSS section. It's a pseudo element used to modify the
  look of a browser’s scrollbar. Most browsers other than firefox support this.
imageAlt: create a custom scrollbar for our website
---
<!--StartFragment-->

<br/>

Recently, I figured out about customizing scrollbars. Adding custom scrollbars to websites you make, helps enhance it even further and also helps in overall color-coordination.

![](/assets/blog/1.how-we-can-create-a-custom-scrollbar-for-our-website.png)



To start with, we use ::-webkit-scrollbar.It can be included in your CSS section. It's a pseudo element used to modify the look of a browser’s scrollbar. Most browsers other than firefox support this.

<!--EndFragment-->

<!--StartFragment-->

A sample example of the code would be-

<!--EndFragment-->

<br/>

<!--StartFragment-->

This section targets the width of your scrollbar.

<!--EndFragment-->



![](/assets/blog/2-how-we-can-create-a-custom-scrollbar-for-our-website.png)



<!--StartFragment-->

This relates to the progress bar. Properties such as border radius, box shadow can also be added.

<!--EndFragment-->



![](/assets/blog/3-how-we-can-create-a-custom-scrollbar-for-our-website.png)



<!--StartFragment-->

It specifies the properties of the scrolling handle that can be dragged.\
To design that even further you can try-

<!--EndFragment-->



![](/assets/blog/4-how-we-can-create-a-custom-scrollbar-for-our-website.png)





<!--StartFragment-->

This will change the color upon hovering.

#### [](https://dev.to/anjalijha22/creating-a-custom-scrollbar-k1o#similarly-some-of-the-other-pseudo-elements-you-can-use-are)Similarly some of the other pseudo elements you can use are-

#### [](https://dev.to/anjalijha22/creating-a-custom-scrollbar-k1o#webkitscrollbarbutton)::-webkit-scrollbar-button

the buttons on the scrollbar (arrows pointing upwards and downwards).

#### [](https://dev.to/anjalijha22/creating-a-custom-scrollbar-k1o#webkitscrollbartrackpiece)::-webkit-scrollbar-track-piece

the track (progress bar) NOT covered by the handle.

#### [](https://dev.to/anjalijha22/creating-a-custom-scrollbar-k1o#webkitscrollbarcorner)::-webkit-scrollbar-corner

the bottom corner of the scrollbar, where both horizontal and vertical scrollbars meet\
*and many more*

<!--EndFragment-->