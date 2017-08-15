---
layout: post
title: Contacts app for Web and Mobile, with only Javascript!
published: true
---
![web and mobile app](/images/web-and-mobile-app.jpg)

It comprises 3 parts:
1. [REST API(MongoDB, NodeJs, Express)](https://github.com/gregartemides/contacts-api)
2. [Web App (React)](https://github.com/gregartemides/contacts-web-app) | [demo](https://codepen.io/gregartemides/details/WEEPYJ/)
3. [Mobile App (React Native)](https://github.com/gregartemides/contacts-mobile-app) | [demo](https://expo.io/@gregartemides/Contacts-CRUD-RESTful)
<!-- more -->

## A study in the convergence of web and mobile

Back in the late 90's web developers had to be versed in the quirks of each browser. It was a frustrating time, but thankfully things have evolved over the years. Since HTML5, we can revel in the security that our HTML/CSS/JS code will work equally well in all the different browsers (mostly... most of the time!)

But now we have a new challenge: different mobile app platforms. We have iOS, Android and Windows, which require Objective-C, Java, and C#... and that's just for starters. We also need awareness of the different user experience on each platform.

Enter React Native, a project started by Facebook and used in the Facebook app, Instagram, AirBnb and Wix. It's a Javascript layer over the native modules in iOS and Android. Javascript gets compiled into native code for each platform.

It borrows heavily from React, a javascript view layer for the browser, which allows for composable components.

And that's all very exciting!

## Lessons learned from building the app
While the app is simplistic, it demonstrates that Web and Mobile are converging. I believe that React Native can take us 80% of the way towards a proper native mobile experience... and that's a long way.

Equally, Javascript (the love-it-hate-it programming language) can be used on the entire stack - in the database, the JSON data, the browser, and mobile. Full stack developers rejoice!