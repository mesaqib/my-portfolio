---
title: React Project Folder Structure
author: saqib
date: 2021-07-19T04:58:57.037Z
tags:
  - post
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

<!--StartFragment-->

**1. api-config**

`api-config` consist of file containing the api endpoints. This folder doesn't have any logic. This helps having a single place for all api url end points and not to be scattered around in components, mostly inside useEffects.

**2. assest**

`assets` folder mostly consist of images(*.png,*.svg..) and any other static files that might be needed.

**3. common**

`common` folder is divided into more react specific folders.

<!--EndFragment-->

<br/>

![alt](/assets/blog/ue9tjurqqpmy01h1tu8q.png "React structure")

<br/>



<!--StartFragment-->

`components` folder consists of individual components, which are atomic in nature and doesn't compose any other components.

`hooks` as the name suggest consists of custom hooks, that you might develop for your project

**4. constants**

`constants` as the name suggest consist of constants used across project

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

**8. test**

`Test` folder. And please don't give it just a lip service. It's fun to write and really helps you out during refactoring(more than TypeScript.. :P)\
[React-testing-library](https://testing-library.com/docs/react-testing-library/intro/)

**9. utils**

Everything else to dump into(..not really, please don't do this).\
Store common utility functions inside this folder.

**10.routes**

A folder to contains all root level routes.

<!--EndFragment-->

<br/><br/>



###### source:  [@knitesh](https://dev.to/knitesh)

<!--EndFragment-->