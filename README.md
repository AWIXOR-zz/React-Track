# React Track

In the repo I'll try to show you my track learning react, showing my steps, and all react golden rules as I go with react this repo will be updated over time

##### Table of Contents

1- [Section 1: History](#history)<br>

- [What is ReactJs](#what-is-react-js)<br>
- [History](#history)<br>
  - [Before REACT](#before-react)<br>
  - [The birth of SPA](#the-birth-of-SPA)<br>
- [The birth of React](#the-birth-of-react)<br>

2- [Section 2: React](#the-birth-of-react)<br>

---

# What is React js

[React](https://reactjs.org) is a JavaScript library for building UIs. It's maintained by [Facebook](https://github.com/facebook/react/) and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

# History

_Some History won't hurt!_

before we talk about react we must talk a little about javascript and browsers.

Backing to 90s til 2000 we just have basic HTML CSS & JS but back then it simply started with simple forms. First the CLIENT (when he open an URL) makes a request TO THE SERVER, the server answers by sending all files (\*.HTML,\*.CSS,\*.JS)and when the user makes an action (clicks a link...), the CLIENT send that request back to the server, and the SERVER must send back all the files again, and so on!.
& websites worked like that for years.

Let's see where/when the story began

- 1993 : Mosaic 💥, the first web browser to start bringing the Internet to the mainstream but no JS ❌ yet. Onlt the DOM (Document Model Object)but non-standardized yet.
- 1994 : Netscape 🚀🚀🚀, was the dominant web browser in terms of usage share after the 1994, but by 2002 its use had almost disappeared.
- May 1995 : Java appeared, and Netscape wanted to add **interations** to the webpages.
- Mid 1995 : MOCHA was created by _Brendan Eich_ during his time at Netscape Communications. It was inspired by Java, Scheme and [Self](http://www.selflanguage.org). Mocha syntactically was just like Java {curly bracket language}, but already contains many features that we know and love in modern JS.
- Sep 1995 : mocha's renamed to LiveScript and shipped in the first beta releases of [Netscape Navigator 2.0](https://tidbits.com/1995/11/13/netscape-2-0b2-available/).
- Dec 1995 : JavaScript name appeared, no longer LiveScript. This name was because back then java was the most popular programming language.
- 1996 : After Microsoft released Internet Explorer, MS reversed engineer JavaScript and they named if jscript, so now we have almost two identical languages:JavaScript and Jscript, and with the internet growing rapidly, people realized that there would be a need to standardize JavaScript.
- 1997 : EcmaScript is born.

## Before REACT

So as time goes many browsers appeared and JavaScript gains more interest, but the problem was that each one of these browsers works differently from each other, so as we wanted to use more and more javascript in our web pages we had to account for all these browsers, and accommadate javascript to work with them.

- 2006 : jQuery came out and changed alot, it allowed to developers to easly interact with the DOM (Document Object Model) across all these browsers. jQuery made life so easier for developers, it made them happy because it had a unified easy API.

So with the power that jQuery gave to developers, they bigan to build bigger and bigger apps like Facebook where you had so many features.
Instead of just requesting more and more pages like a blog, users can now interact with these apps.

- 2010 : BackboneJs came out. Because JavaScript files started getting bigger and bigger, so libraries like backboneJs allowed us to orginize these JS files.

## The birth of SPA

As we explained above, traditionally we just had HTML files for each page and everytime we move to a different page we request from the server the HTML file, CSS and JS (which usually contains jQuery) but whith more advancement like we had with jQuery, Backbone and Ajax too, we now had a different system.
Generally what happend is that we focus less on HTML and alot more on JS.
So the principe behind SPAs is, you only load the application code once, and instead of leoding all files everytime returning a new document, our app now acts more like a desktop app where we stay on the same page the entire time, and JavaScripts simply changes or updates the DOM to display new things. This way of writing apps became really really popular.

- oct 2010 : AngularJs was created by Google and beacame the standard way of building applications or SPAs. But inlike jQuery Angular allowed developers to build these large apps by forming these containers that will wrapp your project. Because AngularJs was created by Google, it had a lot of power.

Now we have things like Controllers, Views, Models (MVC), so the way of orginizing code and dividing it into different things depending of what it does, made it much easier to work with as teams gets larger and larger.
**But another problem appeared!**
things started getting more and more complex because of this. As things get bigger and bigger more things have to happen. We have more and more complexity now and although frameworks like AngularJS came out people started to notice it's getting harder and harder to find bugs in the code and understand how each part of the app was affecting the other (Data was flowing everywhere).

---

# The birth of React

2013, Facebook released [React](https://github.com/facebook/react), Facebook presented a very good solution, and everyone started to use it, because React come with a whole new way to build front-end applications.
One year after, Gooogle realesed that the way that they architected AngularJs is not effetient to be used for building good applications anymore, so they decided to rewrite the whole liberary and called it Angular, but because of amount of time the rewrite will take, many people moved to React.
The good principales introduced by React made it the most popular front-end tool with the most job demand across the world.

**More than 8000 campanies are using React in their tech stacks including including:**

- Facebook
- Uber
- Airbnb
- Netflix
- Discord
- Snapchat
- Coursera
- Shopify
- Reddit
- Twitter
- Paypal
- Figma
- Slack
- ...

# React Concepts

1- React handles the DOM for you!
2- Build websites like lego blocks (Reuseble components)
3- Unidirectional data flow
4- Handles only the UI.

## Declarative programming vs Imperative in React

<dl>
  <dt>Imperative:</dt>
  <dd>Directly change individuel part of the app in response of variant user events, it's like telling the app how to do something when something happens, and as a result what you want to happen will happen.</dd>

  <dt>Declarative:</dt>
  <dd>Unlike imperative it's like telling the app what you would like to happen, and let it figure out how to do it. React uses what we call <em>state</em>.</dd>
</dl>

# 🧐 Want to contribute ?

If you have something to contribute with, this is how you do it.

1. Click on the readme.md file and click the edit icon.
2. You can start editing the text of the file in the in-browser editor. Make sure your awesome thing is in the right section.
3. submit a PR.
