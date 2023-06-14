---
marp: true
theme: minimal
class: invert
size: 16:9
style: |
  img {background-color: transparent!important;}
  a:hover, a:active, a:focus {text-decoration: none;}
  header a {color: #ffffff !important; font-size: 30px;}
  footer {color: white; opacity: 0.25; font-size: 80%;}
footer: '14.06.2023 - digital media - hfk bremen - [mneunomne.github.io/presentations/introducing_the_web_presentation.html](https://mneunomne.github.io/presentations/introducing_the_web_presentation.html)'
---

# introducing.. _the web_

workshop / meeting for introduction of web design concepts and practice.

---

__introduction__

the purpuse of this meeting / workshop is to create an enveiroment for us to exchange some knowledge for web development. I didn't prepare much for today, I won't use any slides, I'll just go-with-the-flow trying to break the initial barriers for people who want to learn about web development.

You are welcome to come show your own projects, problems, things u have learned, specially for those who also have some web experience can show what are you up to.

As a sneak peak, I will show what I am currently working on, and maybe if we can make more meetings we can eventually reach the point where you can also make your own website with a content management system using nuxt + netlify. Hopefully this can help you get some juicy jobs in the future in times of necessity.

---

__tools we will use__

- visual studio code [install](https://code.visualstudio.com/)
- chromium based browser (chrome, brave, edge, etc...)

---

__plan__

- what is the browser
- basics of client/server
- what is html/css/js
- the DOM + important javascript concepts
- practice together with whatever stupid idea for a quick webpage
- publish it using github pages (intro to github if needed)

---

### what is the browser?

_concept of the browser_

a sandbox to protect your computer from the garbage that the internet is. it expects specific commands and markup language in order for it to render, and also follows specific protocols to use other things on your device, such as gps, browser info, microphone, webcam etc.

_diferences between chrome (chromium), safari, firefox_

_local storage_

_cookies_

_network_

_console_

<!--
with the browser show how the files are requested, how they are loaded, check the sources of a webpage, check how to debug things.

go to the console and show how javascript commands work.

show how css elements are associated with html elements.
--->

_client/server_

everything that happens within the browser is what we call 'client'. the 'server' is usually the computer that is running somewhere else, the requests, processing the database and _serving_ the data to the _client_.

---

### what are these languages that make up the web enveiroment?

---

__html__

html (HyperText Markup Language) is a markup language. another markup languages is xml for example. what makes html special is the fact that the browser has the understanding that `<h1></h1>` means first heading, `<p>` paragraph, `<b>` bold, and so on. 

So html is basically a normal markup language that hints onthe browser how it shouild be rendered and visually structured.

---

__css__

css (Cascading Style Sheets) is a way to further customise visually on top of the standard stylying which is asssociated with html. (show how html elements already have default css styling, and css code serves to work on top of these default settings)

_selectors_

_animations_

_transition_

---

__queries__

---

__js__

javascript is the programming language that can manipulate html content. 

> When we talk about javascriot we are usually talking about _client-side_, but you can run javascript on the server side, which is _node.js_.

---

__DOM__

_The HTML DOM Tree of Objects_

![](https://www.w3schools.com/js/pic_htmltree.gif)

the DOM (Document Object Model) element is the core for one to understand how the browser handles the html data and how we can manipulate it. It is the key elements through which we can understand the relationship between javascript and html.

through the concept of the DOM we can see that the html is actually a data object

_manipulating the dom_

---

### Javascript: Object, Array, Variables, Functions

diffent from some other programming language, javascript has _dynamic typing_, which means any variable can be anything. which gives us a lot of freedom, and in the end everything can be an object. 

_diffent ways of declaring things in javascript_ 

_variables_

_object_

_compiling javascript_

_how to load script into html_

---

### Server / Client

show that the browser can't just open a web page and run javascript directly

---

__practicing__

- have some stupid idea (what can be the theme? dragons?)
- create simple html page
- link between different pages
- manipulate the dom
- change style with css
- use of external libraries (e.g.: _jquery_)
- sneak peak of more advanced libraries such as _vue.js_ and _svelte_
- more advanced css with animations
- how to deploy your web page on github

---

### Libraries, Frameworks

_NPM (Node Package Modules)_ (essential! vizualise npm modules with [allnpmviz3d](http://anvaka.github.io/allnpmviz3d/)) 

_jQuery_ (not really used in bigger projects anymore)

_Three.js_ (3d web yayy, really like working with it. It has many sub-libraries such as I like to use such as _AFrame_, _3d-force-graph_, etc)

_vue.js_ (much better than react in my opnion, and there are many job opportunities to work with it)

_React_ (made by facebook meh, but maybe the most used library still?)

_Svelte_ (never used it, but seems really cool and getting more popular)

_Bootstrap_ (I never liked using it, but very usuful for styiling very common problems for traditional webpages)

_Angular_ (made by google, bother even remember this name)

_TypeScript_ (a more 'strict' javascript, never used it, but seems super boring)

_Netlify_ (company that provides serverless backend, free for small use-cases)

_Marpit_ (frameworks for making presentation with markdown, renderding it with html)

---

### Useful resources 

- [w3schools](https://www.w3schools.com/js/js_htmldom.asp)
- github co-pilot (its free for students!)
- [MDN Web Docs](https://developer.mozilla.org/)
- [Stack Overflow](https://stackoverflow.com/)

---

### cool websites

(wip)

---