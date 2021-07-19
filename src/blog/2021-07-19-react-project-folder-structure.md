---
title: React Project Folder Structure
author: saqib
date: 2021-07-19T04:58:57.037Z
tags:
  - post
  - featured
image: /assets/blog/unnamedreact-page-structure.png
description: Just showing off my current preference for a React project folder
  structure. I think this gives a good view and segregation of files for my
  react based projects. Let's go through each folder inside the src folder.
imageAlt: img
---
<br/>

Just showing off my current preference for a React project folder structure. I think this gives a good view and segregation of files for my react based projects.

<br/>

![React Project Folder Structure](/assets/blog/react-project-folder-structure.png "React Project Folder Structure")

<br/>

<!--StartFragment-->

Let's go through each folder inside the src folder.

<!--EndFragment-->

<br/>

<!--StartFragment--><br/>

**1. api-config**

`api-config` consist of file containing the api endpoints. This folder doesn't have any logic. This helps having a single place for all api url end points and not to be scattered around in components, mostly inside useEffects.

<br/>

**2. assest**

`assets` folder mostly consist of images(*.png,*.svg..) and any other static files that might be needed.

<br/>

**3. common**

`common` folder is divided into more react specific folders.

<!--EndFragment-->

<br/>

![alt](/assets/blog/ue9tjurqqpmy01h1tu8q.png "React structure")

<br/>

<!--StartFragment-->

`components` folder consists of individual components, which are atomic in nature and doesn't compose any other components.

`hooks` as the name suggest consists of custom hooks, that you might develop for your project.

<br/>

**4. constants**

`constants` as the name suggest consist of constants used across project.

<br/>

**5. modules**

`modules` folder contains react components which are composed of smaller components defined under `common/components`. For e.g. a `<Header />` component which may look like

<!--EndFragment--><br/>

![alt](/assets/blog/capture.png "react project")

<br/>

<!--StartFragment-->

**6. pages**

`pages` are one to one map of the router routes. This is similar to the concept that `NextJS` or `GatsbyJs` takes.\
This is the bigger react component which presents a whole page. It might contains additional routing, so more nested pages. An example of this page will be dashboard page which might look like (in it's simples form)

<!--EndFragment-->

<br/>

![alt](/assets/blog/1.png "react page structure")

<br/>

<!--StartFragment-->

**7. store or Global context**

`store` folder contains global store or global context that are getting used across product.

On side note, if you have not used `Zustand` as react-redux replacement, give it a try. Very simple and easy to use state management system and you don't have to wrap your component inside a `Provider`.\
[Zustand](https://github.com/pmndrs/zustand)

<br/>

**8. test**

`Test` folder. And please don't give it just a lip service. It's fun to write and really helps you out during refactoring(more than TypeScript.. :P)\
[React-testing-library](https://testing-library.com/docs/react-testing-library/intro/)

<br/>

**9. utils**

Everything else to dump into(..not really, please don't do this).\
Store common utility functions inside this folder.

<br/>

**10.routes**

A folder to contains all root level routes.

<!--EndFragment-->

<br/><br/>

###### source:  [@knitesh](https://dev.to/knitesh)

<!--EndFragment-->



  <center>

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-in.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=IN&source=ss&ref=as_ss_li_til&ad_type=product_link&tracking_id=saqib0ad-21&language=en_IN&marketplace=amazon&region=IN&placement=1783551623&asins=1783551623&linkId=3a4ea195194fff84f4e6340421b0ed99&show_border=true&link_opens_in_new_window=true"></iframe>



<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-in.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=IN&source=ss&ref=as_ss_li_til&ad_type=product_link&tracking_id=saqib0ad-21&language=en_IN&marketplace=amazon&region=IN&placement=1787126048&asins=1787126048&linkId=ce891ac7ed6bb922a9d0f222b0142c23&show_border=true&link_opens_in_new_window=true"></iframe>



<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-in.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=IN&source=ss&ref=as_ss_li_til&ad_type=product_link&tracking_id=saqib0ad-21&language=en_IN&marketplace=amazon&region=IN&placement=1118008189&asins=1118008189&linkId=1aee3c888f7341215b76823f52a1c70f&show_border=true&link_opens_in_new_window=true"></iframe>



<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-in.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=IN&source=ss&ref=as_ss_li_til&ad_type=product_link&tracking_id=saqib0ad-21&language=en_IN&marketplace=amazon&region=IN&placement=1118907442&asins=1118907442&linkId=6cc09157510f50e5b4800f087a840d5c&show_border=true&link_opens_in_new_window=true"></iframe>

</center>