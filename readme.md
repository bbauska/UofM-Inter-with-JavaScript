---
title: |
  #3 University of Michigan Interactivity with JavaScript
  by Colleen van Lent, Ph.D. (lecturer, school of information)
author: "bbauska"
date first editted: "5/11/2024 12+pm"
date late editted: "7/10/2024 11+am"
output: 
  markdown:
    with some style
---

<h1 align="center">Interactivity with JavaScript</h2>

<h6 align="center">(by Colleen van Lent - University of Michigan)</h6>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ readme.md of uofm-inter-with-js ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~ 01/02. interactivity with js by university of michigan (01) ~~~~~~~~~~~~~~~~~-->
<p align="center">
<img src="./images/image001.webp?raw=true"
  style="width:15%;"
  title="Interactivity with JavaScript by Colleen van Lent, 
    Ph.D. (lecturer, school of information)"
  alt="Interactivity with JavaScript by Colleen van Lent, 
    Ph.D. (lecturer, school of information)."
&nbsp;&nbsp;&nbsp;
<img src="./images/image002.webp?raw=true"
  style="width:25%;"
  title="University of Michigan logo"
  alt="University of Michigan logo." />
</p>

<h2 id="#about">About this Course:</h2>

If you want to take your website to the next level, the ability to
incorporate interactivity is a must. But adding some of these types of
capabilities requires a stronger programming language than HTML5 or
CSS3, and JavaScript can provide just what you need.

With just a basic understanding of the language, you can create a page
that will react to common events such as page loads, mouse clicks &
movements, and even keyboard input. This course will introduce you to
the basics of the JavaScript language. We will cover concepts such as
variables, looping, functions, and even a little bit about debugging
tools.

You will understand how the Document Object Model (DOM) is used by
JavaScript to identify and modify specific parts of your page. After the
course, learners will be able to react to DOM Events and dynamically
alter the contents and style of their page. The class will culminate in
a final project - the creation of an interactive HTML5 form that accepts
and verifies input.

This is the third course in the Web Design for Everybody specialization.
A basic understanding of HTML and CSS is expected when you enroll in
this class. Additional courses focus on enhancing the styling with
responsive design and completing a capstone project.

<h2 id="chb"><a href="#table-of-contents">Table of Contents</a></h2>

### [**Course Information**](#chb)
>#### * [**Syllabus**](#syllabus)
>#### * [**Resources**](#chb-2)
>#### * [**Source Code for Each Week**](#chb-3)
>#### * [**Course Slides**](#chb-4)
>#### * [**The Document Object Model (DOM)**](#chb-5)

### [**Week 1: Data Types**](#ch1)
>#### 1.1 [**Introduction to Interactivity with JavaScript**](#ch1-01)
>#### 1.2 [**DOM Review with Object Oriented Programming**](#ch1-02)
>#### 1.2b [**Newer DOM**](#new-dom)
>#### 1.3 [**Output**](#ch1-03)
>#### 1.4 [**Variables**](#ch1-04)
>#### 1.5 [**Data Types**](#ch1-05)
>#### 1.6 [**Operators &amp; Expressions**](#ch1-06)

### [**Week 2: Functions &amp; Events**](#ch2)
>#### 2.1 [**Functions**](#ch2-01)
>#### 2.2 [**Code Placement / Organizing Your Code**](#ch2-02)
>#### 2.3 [**Events**](#ch2-03)
>#### 2.4 [**Breakpoints**](#ch2-04)
>#### 2.5 [**Code With Me: Events**](#ch2-05)
>#### 2.6 [**"this"**](#ch2-06)
>#### 2.7 [**Photo Gallery**](#ch2-07)

### [**Week 3: Arrays &amp; Looping**](#ch3)
>#### 3.1 [**JavaScript Arrays**](#ch3-01)
>#### 3.2 [**Code With Me: Arrays**](#ch3-02)

### [**Week 4: Using JS for Interactive Images**](#ch4)
>#### 4.1 [**Code With Me: Randomizing Your Images Using Arrays**](#ch4-01)
>#### 4.2 [**Code With Me: Using LightBox**](#ch4-02)
>#### 4.3 [**Code With Me: Looping Through Images**](#ch4-03)
>#### 4.4 [**Final Project Description**](#ch4-04)
>#### 4.5 [**Conclusion**](#ch4-05)

<a href="https://github.com/bbauska/UofM-Inter-with-JS.git" target="_blank">UofM - InterActivity with JS - git</a>

<h2><a href=#syllabus">Syllabus</a></h2>

<h3>Week One: Data Types</h3>

If you haven&apos;t used a traditional programming language before, this
first week is key. Before we begin with the how, we will talk about the
why, mainly why we want to use JavaScript. The main reason is that it is
very easy for JavaScript to work with the DOM. And easy is always a
great way to start. Speaking of starting out, it is also always more fun
when our code actually does something we can see, so we will jump
quickly into different ways we can generate output. It won&apos;t be flashy
yet, but it will be a great way to get your feet wet with traditional
programming. After that we go back to the basics of how a computer uses
data. We begin with variables, expressions, and operators.

1.  <b>[Introduction](https://www.coursera.org/lecture/javascript/introduction-EYX66)&ast;
    (4:28) (1)</b>

> <b><a href="https://codepen.io/collection/nLPkgP/">Link to All of the Code for Week One</a></b>
>
> <b>The Document Object Model (DOM)</b>

2.  <b>DOM Review with Object Oriented Programming&ast; (6:32) (2)</b>

> <b>Accessing the DOM Methods</b>
>
> <b>Newer DOM Methods</b>

> <b>Semicolons</b>

3.  <b>Output&ast; (3)</b>

> <b>Trying to Create and Debug Your Own Output</b>

4.  <b>Variables&ast; (4)</b>

5.  <b>Data Types&ast; (5)</b>

6.  <b>Operators and Expressions&ast; (6)</b>

> <b>Discussion - CodePen</b>
>
> <b>Materials</b>
>
> <b>The History of &quot;Debugging&quot;</b>

<b>Summary:</b> Data Types

<h3 id="week-2">Week Two: JavaScript Interactive Photo Gallery</h3>

If you have written HTML code in the past, hopefully you have fallen
into the great habit of validating your code &dash;- making sure that you
close all of your open tags. There are other rules that you may or may
not have been following as well, for instance the importance of using
each id attribute only once per page. This is called writing &quot;clean&quot;
code. The reasoning and importance of following these rules becomes
clear as we begin to manipulate the different components of your webpage
based on the actions of the person interacting with your page. In
particular you will learn about the JavaScript Mouse Events and Touch
Events. This week&apos;s materials will end with a photo gallery example
that you can create along with me.

> <b>Reading: Link to All of the Code for Week Two</b>
>
> <b>Reading: Functions</b>

1.  <b>[Functions](https://www.coursera.org/lecture/javascript/functions-Ltkbl)&ast;
    (1)</b>

2.  <b>Code Placement&ast; (2)</b>

> <b>Organizing Your Code</b>

3.  <b>Folder Structure / Organizing Your Code&ast; (3)</b>

4.  <b>Events&ast; (4)</b>

> <b>Mastering Events and Functions</b>

5.  <b>Code With Me -- Events&ast; (5)</b>

> <b>Just a little note before the next lesson</b>

6.  <b>&quot;this&quot;&ast; (6)</b>

> <b>Homework Time!!</b>

7.  <b>Photo Gallery&ast; (7)</b>

<b>Summary:</b> JavaScript Interactive Photo Gallery

<h3 id="week-3">Week Three: Arrays and Looping</h3>

This week we will delve into more complex programming concepts: arrays
and looping. Arrays allow you to represent groups of related
information. Looping provides efficiency and flexibility to your
programs. Using both we will expand upon the photo gallery example.

> <b>Reading: Link to All of the Code for Week Three</b>
>
> <b>Reading: A JavaScript Cheat Sheet</b>
>
> <b>Reading: Arrays (Tabindex and Accessibility)</b>
>
> <b>Reading: Using JavaScript with Attributes</b>
>
> <b>Reading: Arrays</b>

1.  <b>[JavaScript Arrays](https://www.coursera.org/lecture/javascript/javascript-arrays-g8N8v)&ast;
    (1)</b>

2.  <b>Code With Me -- Arrays&ast; (2)</b>

> <b>Resources</b>
>
> <b>Writing Loops in JavaScript</b>
>
> <b>Reading: Advanced Coding Techniques</b>
>
> <b>End of week 3...</b>

3.  <b>JavaScript Iteration&ast; (3)</b>

4.  <b>Flow Of Control&ast; (4)</b>

5.  <b>Code With Me - Combining Loops and Conditionals&ast; (5)</b>

6.  <b>Advanced Conditionals&ast; (6)</b>

7.  <b>Common Errors&ast; (7)</b>

<b>Summary:</b> Arrays and Looping

<h3 id="week-4">Week Four: Using JS for Interactive Images</h3>

This week is all about putting concepts together to do &quot;cool&quot; things.
And we even stop for a second to talk about the trade-off between cool
things and accessibility. The final project this week will be a new
version of your coding project in Week 2. You will make an interactive
photo gallery from your own images and will add the functionality of
keyboard accessibility to it.

Prior project&apos;s week we will put a number of the concepts from this
course together to tackle a new project - creating and validating input
entered into an HTML5 form. Forms are extremely common elements used to
input and send data to via a webpage. We will look at how you can use
JavaScript to add options to your forms, to pre-fill data based on
previous input, and even to check that passwords match.

> <b>Reading:</b> Link to All of the Code for Week Four
>
> <b>Reading:</b> Introduction to Forms

1.  <b>Code With Me:</b> Randomizing Your Images Using Arrays (1)

2.  <b>Code With Me:</b> Using Lightbox (2)

3.  <b>Code With Me:</b> Looping through Images (3)

4.  Final Project Description (4)

> <b>Reading:</b> &quot;Cool Stuff&quot; - Friend or Foe? (old but still valid?)

5.  <b>Conclusion&ast; (5)</b>

> <b>Reading:</b> Intro to JQuery
>
> <b>Reading:</b> Post-course Survey
>
> <b>Reading:</b> Keep Learning with Michigan Online
>
> <b>New Reading:</b> Resources
>
> <b>Reading:</b> Advanced Coding Techniques
>
> <b>Reading:</b> "Cool Stuff"
>
> <b>Final Project Description</b>

<b>Summary:</b> Using JavaScript for Interactive Images

<b>Welcome to Introduction to JavaScript</b>, taught by Colleen van Lent!

This course is an introduction to the use of the JavaScript programming
language to add some interactivity to your website. This course is meant
for people who are comfortable using HTML and CSS, but are new to
programming.

What is the benefit of learning JavaScript? HTML and CSS are not
programming languages and therefore they are not very powerful. You can
do some really interesting things with the new tags and properties, but
there are limitations. JavaScript, on the other hand, allows you to add
complex levels of interactivity to your pages. And unlike some other
programming languages, JavaScript works really well with the DOM
structure of web pages.

In the next few weeks, we will talk about how you can add pop-up boxes
(not always a good idea), change the structure and style of your page
when special events happen (sometimes a good idea), and validate form
data (always a good idea). To be completely honest, there are so many
things that we can do with JavaScript we can&apos;t possibly cover them all
in the time we have. We will focus on the following:

-   How to create output with JavaScript. This could be with pop up
    boxes, adding content to your page, or sending information to the
    browser console to help you fix (&quot;debug&quot;) your code.

-   How JavaScript uses variables and data types to save your data. This
    is a powerful and important concept because it lets you save
    information to use over and over again.

-   How to write functions to react to events. You will be able to write
    code that only runs when special events occur. Because we want to
    add interactivity, we will make sure to use special DOM events that
    react to mouse clicks and movement.

-   Why arrays are an important part of any programming language and how
    to use them to store multiple pieces of information in one variable.

-   How to create and validate HTML forms.

<h1 id="ch1">Week 1</h1>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-01">1.01 Introduction to Interactivity with JS</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 03. introduction (1-01) (05) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image003.webp?raw=true"
  style="width:45%;"
  title="1.01 Introduction to Interactivity with JavaScript"
  alt="1.01 Introduction to Interactivity with JavaScript." />
</p>

Hi everybody. Today I&apos;m going to introduce you to the JavaScript
programming language. JavaScript has a lot of uses, but we&apos;re really
going to focus on how we can use JavaScript to add interactivity to your
web design pages. While I&apos;m assuming that you&apos;re new to programming,
there is an expectation that you know HTML 5 and CSS 3. If you don&apos;t,
you&apos;re going to want to go back and review those two areas because
everything we with JavaScript in this class is based on web programming.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 04. what you can do with js (05) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image004.webp?raw=true"
  style="width:45%;"
  title="What you can do with JavaScript, #1"
  alt="What you can do with JavaScript, #1." />
</p>

If you&apos;ve done HTML, if you&apos;ve done CSS, you haven&apos;t necessarily done
what we call real programming, at least not what us computer scientists
call real programming. Instead, we&apos;re going to be talking in JavaScript
about really definite data manipulation, and in order to do that, there
are a few things you need to learn how to do. The first is, you want to
learn how to store variables. You&apos;re going to want to learn how to set
decision points, looping and writing functions, you&apos;re also going to be
getting in-depth with how you can get data from the browser.

Did you know that every time you load a web page, you can actually get
back the title of the page, the URL of your page, a lot of different
information that you know is there, but you can&apos;t always see at first
glance?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 05. what you can do with js, #2 (06) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image005.webp?raw=true"
  style="width:45%;"
  title="What you can do with JavaScript, #2"
  alt="What you can do with JavaScript, #2." />
</p>

The other thing we can do, which is really where it gets a little bit
more exciting, is that we can manipulate the DOM that the browsers use
to create webpages. The DOM is the Document Object Model, it&apos;s what
builds up a webpage. If you&apos;re a little fuzzy, it&apos;s been a little
while, don&apos;t worry. We&apos;re going to review the DOM in a future lecture.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~ 06. variables to store data and refer back to it later (06) ~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image006.webp?raw=true"
  style="width:45%;"
  title="Variables: Store data and refer back to it later"
  alt="Variables: Store data and refer back to it later." />
</p>

Let&apos;s start with variables. In computer science, we use variables in order to store 
information. Your program isn&apos;t going to be very exciting if you ask somebody their 
name and then you can&apos;t actually use that name later on. You&apos;re going to find 
out how to get information from the user, and then store it so you can use it later.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 07. decision points (07) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image007.webp?raw=true"
  style="width:45%;"
  title="Decision Points: Use control statements to decide which code to run 
    under different circumstances"
  alt="Decision Points: Use control statements to decide which code to run 
    under different circumstances." />
</p>

We&apos;re also going to add decision points. Things are much more
interesting when they don&apos;t do the same thing every single time. We&apos;re
going to write a little bit of code that can help the program decide in
some cases I want to do this and in other cases, I want to do that. We
call this decision points.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 08. looping (07) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image008.webp?raw=true"
  style="width:45%;"
  title="Looping: Avoid writing the same (or similar) code over and over again"
  alt="Looping: Avoid writing the same (or similar) code over and over again." />
</p>

We can also do looping. Looping is really powerful. As your programs get
bigger, there&apos;s certain things you&apos;ll want to do over and over again,
but you really don&apos;t want to write code over and over and over again.
In computer science, we use something called looping to control the
program and say, see that little bit of code over there? We want to do
that five times, or ten times, or we want to keep doing it until the
human does what we want them to do.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 09. looping, #2 (08) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image009.webp?raw=true"
  style="width:45%;"
  title="Looping: Determine at runtime how many times you want to run some code"
  alt="Looping: Determine at runtime how many times you want to run some code." />
</p>

Otherwise, you sometimes have to decide at run time how many times you
want to run some code. If you know that you want someone to do something
five times, you can be very specific about it. Programming gives you so
much flexibility in how you want your code to run.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 10. functions (08) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image010.webp?raw=true"
  style="width:45%;"
  title="Functions: Reuse code multiple times, but only write once.  Use code from others"
  alt="Functions: Reuse code multiple times, but only write once.  Use code from others." />
</p>

Next in this course we&apos;re going to talk about functions. Functions are
a way for you to reuse your code multiple times, but you only have to
write it once. The other great thing about functions is that other
people can write code and you can use it, and you don&apos;t even need to
know how it works. All you need to know is, what did you call your
function? Great. I want to use that.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 11. manipulating the dom (09) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image011.webp?raw=true"
  style="width:45%;"
  title="Manipulating the DOM"
  alt="Manipulating the DOM." />
</p>

Finally, we&apos;re going to talk about manipulating the dominant class.
JavaScript can actually go through your web page and search and find
certain elements. It can add new elements. It can delete other elements
from the DOM. So, think about when you&apos;re filling out a form on a web
page with your credit card information. There are always these little
buttons that you can click that can say use the same billing address for
shipping. Things like this can make your page much more usable.

You can also react to mouse clicks, page reloads, and other actions that
the user might have. This is where it really gets fun. We&apos;re going to
start with the basics, the variables, the loopings, and then we&apos;re
going to have fun manipulating the DOM.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 12. review (09) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image012.webp?raw=true"
  style="width:45%;"
  title="Review: Week 1-01. Introduction to Interactive JavaScript"
  alt="Review: Week 1-01. Introduction to Interactive JavaScript." />
</p>

A major component of learning any new programming language, or I guess,
really any language at all, is that the key is practice and repetition.

The other thing that you really need to understand, and I&apos;m actually
hoping that you&apos;ll embrace, is that you need to expect that you&apos;re
going to make mistakes. If you aren&apos;t making mistakes constantly, you
aren&apos;t really learning in this class. Join us, we&apos;re going to do a lot
of fun stuff. But I promise, I&apos;m going to go slow, explain what I&apos;m
doing step by step, so that you can come along with me and start adding
some interactivity to your pages with JavaScript.

<h2 id="code-wk1">Link to All of the Code for Week One</h2>

<http://codepen.io/collection/nLPkgP/>

Here is a link to a collection of all of the Code for Week One. (There
may be a few extra files in there as I play with new examples.) Each
individual file is also linked above. I find that it can be annoying to
use CodePen for the first few lectures since it causes a lot of pop-up
boxes. Don&apos;t worry, we move away from that by Week Two.

Even if you use CodePen, I encourage you to practice writing the code on
your own. For now, I put complete examples in CodePen, but as time goes
on, I will remove some of the commands to link the code together. You
will need to work on that part on your own..

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch-1b">1.02b The Document Object Model (DOM)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>Examples:</h3>

<https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Examples>

One of the reasons you want to learn about JavaScript is that it works
so well with the structure used to create HTML documents. Every webpage
can be broken down into a mathematical tree structure called the
Document Object Model (DOM). Each HTML tag is a node in the tree and
these nodes have all types of different attributes, such as text,
background color, width, etc.

With JavaScript it is easy to write code that basically says &quot;I want to
grab <b>that</b> part of the webpage and change it.&quot; In this lecture I
review the DOM and talk about how it is related to JavaScript. There is
no code associated with this lecture, but if you check under the
resources, I do include a link to site where you can find specifics on
the DOM.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-02">1.02 DOM Review with Object Oriented Programming</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 13. dom review with object-oriented programming (11) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image013.webp?raw=true"
  style="width:45%;"
  title="1.02 DOM Review with Object-Oriented Programming"
  alt="1.02 DOM Review with Object-Oriented Programming." />
</p>

Today we&apos;re going to be talking about the DOM, or the document object model.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 14. web pages are built upon the dom (11) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image014.webp?raw=true"
  style="width:45%;"
  title="Web pages are built upon the DOM"
  alt="Web pages are built upon the DOM." />
</p>

As you may or may not remember, every webpage is built upon this DOM.
And what it means is that our pages are structured like a tree. We have
one parent and possibly a few children. And the page as you add more and
more things it just gets deeper and deeper. Nodes have different
properties, methods, and events.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 15. sample document (12) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image015.webp?raw=true"
  style="width:45%;"
  title="Sample Document"
  alt="Sample Document." />
</p>

Let me draw you a quick example and then we&apos;ll talk about how we can
use JavaScript to manipulate this DOM. Every web page is built like a
tree. We start up here and we&apos;ve got our document and then you&apos;re
going to have, hopefully you remember your head and your body, all
right?

Well, what kind of things are in your webpage? You might have a div and
another div. And then the third div we&apos;re going to give more specific.
We&apos;ll say, well this div has three paragraphs and one of those
paragraphs has the id equals 3. What does this mean? Why do we care that
the pages built like a tree?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 16. sample document, #2 (12) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image016.webp?raw=true"
  style="width:45%;"
  title="Sample Document, #2"
  alt="Sample Document, #2." />
</p>

This means that JavaScript can actually go in and it can look and say,
you know what, I want to find the second div. I found this thing right
here. I want to find the specific paragraph that had the id equals 3.
It&apos;s right here.

Because JavaScript can find these different elements in your page, it
can also change what we call are the attributes of that page. For
instance, that paragraph might have a background color or a special kind
of font, the paragraph also has text in it. How can we go in there and
how can we change that text? This is what we&apos;re going to be using
JavaScript to do in this course.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 17. the dom and javascript (13) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image017.webp?raw=true"
  style="width:45%;"
  title="The DOM and JavaScript"
  alt="The DOM and JavaScript." />
</p>

Again, we&apos;ve got that the page content is represented by the DOM. The
scripting language JavaScript uses the DOM to interact with the
document. How does it do that, though? How does it know how to interact?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 18. how does it work? (13) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image018.webp?raw=true"
  style="width:45%;"
  title="How does it work?"
  alt="How does it work?" />
</p>

Well, the JavaScript has something called an API, or an application
programming interface. You may have heard people talking about APIs in
the past. Programmers tend to do that. They&apos;re like, oh, what API are
you using? Or what API are you using? And it can sound kind of
intimidating if you&apos;ve never used one before. An API is just a way for
someone else to write code, and then you to use it, to interact with
their programs.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 19. how does it work, #2? (14) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image019.webp?raw=true"
  style="width:45%;"
  title="How does it work, #2?"
  alt="How does it work, #2?" />
</p>

No matter which browser you&apos;re using, Firefox, Chrome, different things
like that. And no matter which scripting language you&apos;re using, in our
case we&apos;re going to use JavaScript. The API is always the same. The way
you interact is always going to be the same. And this is really
important, because it&apos;s nice to know that if you learn this you won&apos;t
have to learn something different later on.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 20. the dom objects/elements (14) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image020.webp?raw=true"
  style="width:45%;"
  title="The DOM objects/elements"
  alt="The DOM objects/elements." />
</p>

Let&apos;s talk about some of these DOM objects or element as we call them.
The first one, kind of the root of your entire page, is the document. If
you wanted to, you could find out what the document URL is, what the
height of the document is, all the different links in the document, the
document background color. If there&apos;s an attribute you&apos;ve used to
style your page, you can find it using JavaScript in the API.

The next kind of concept we talk about is an element, or a node in the
tree. If you remember, I drew that you can have the body, and inside the
body you could have divs, paragraphs, links, list items. Each one of
those is a node in the tree. And you can find it using the API.

Sometimes, though, it can be a little bit more complicated than just
returning a single element. What if you wanted to find all of the
children of one particular ordered list, or un-ordered list? Well, in
that case, instead of returning a single element, sometimes it&apos;s
returned a node list, or an array of elements.

For instance, there&apos;s this one API that we can use, called document
that get element by tag name, and you can give it any element you want.
So, p, or a list item. Well, there&apos;s a really good chance that there&apos;s
more than one paragraph in your page. You return all of them together.
This is how we&apos;re going to be using arrays later in the course,
probably around week three, to help you understand how to deal with an
overload of information.

Finally, the important thing I need you to remember is that in the Dom
there are attributes. You have your elements and every element probably
has one or more attributes that go with it. So, an image for image
element, it would have a source, it would have alt text, it would have
width, and a style, different things like that.

Attributes are the kind of cool things that we want you to be able to
change to make your page look different.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 21. specific apis (15) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image021.webp?raw=true"
  style="width:45%;"
  title="Specific APIs"
  alt="Specific APIs." />
</p>

Okay, so if you understand that the page is made up of documents, and
elements, and attributes, I&apos;m hoping this side will make a little bit
more sense. For a view of a document, you can say you know that I want
to get a certain element using the id. You can also say oh I&apos;ve got
this document grab all the elements that happen to be a paragraph or a
link. Now this one&apos;s new, this idea of <b>element.inner.HTML</b>.

A paragraph is an element and you assume there is some sort of text
inside that paragraph. Well, if you&apos;ve been coding HTML or CSS, you
probably might be thinking, when I use the paragraph tag, I never saw an
inner HTML attribute. You wouldn&apos;t have. This is part of the API, but
you can use this to change the content of any element. You can also
change the element style, and you can even add additional attributes to
any element that the DOM can grab.

Finally, an interesting one that you may or may not use, is you can even
remove attributes. If something has a certain color, you can get rid of
that if you want.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 22. review (1.02) (16) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image022.webp?raw=true"
  style="width:45%;"
  title="1.02 Review: DOM with Object-Oriented Programming"
  alt="1.02 Review: DOM with Object-Oriented Programming." />
</p>

I know that there was a lot I went over in this slide that maybe didn&apos;t
make a lot of sense to you yet. That&apos;s okay. That&apos;s the point of this
class. It&apos;s so that the end of this course, you can go back to this
slide, and you can say, oh great, I&apos;ve mastered this. I&apos;m beginning to
understand that learning JavaScript doesn&apos;t mean that I know how to
code everything by hand, it means that I know that there&apos;s something
called an API and I know how I can use it to make my page a little bit
better.

We&apos;re going to start slow, and the most important part to me is for you
to feel comfortable searching for information on the web. I&apos;ll be able
to teach you a little bit, I can show you some of the main methods and
API&apos;s and different things like that. But I want you to code with me
and then make sure you go off and you try to change things just a little
bit until your confidence is really up there. Good luck.

<h3>Accessing the DOM Methods</h3>

In the earlier video I showed some ways to access the DOM. Here is a
review of those methods, along with some additional information about
the use of the newer methods document.querySelector() and
document.querySelectorAll().

<h4>Methods that return a single value</h4>

1.  The
    [getElementById()](https://www.w3schools.com/jsref/met_document_getelementbyid.asp)
    method is one of the most common methods in the HTML DOM. It is used
    almost every time you want to read or edit an HTML element. This
    method returns an element with a specified ID value. If the page has
    two elements with the same id (which it shouldn&apos;t!) only the first
    element in the DOM is returned. There is no need to include the
    hashtag in the selector. [Sample Code for
    getElementById](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_document_getelementbyid2)
    Note, JavaScript is case sensitive so make sure you have Id with an
    uppercase &quot;I&quot; and a lowercase &quot;d.&quot;

2.  While getElementById is only used for elements with a specific id,
    you can also return a single element if you use querySelector. The
    [querySelector()](https://www.w3schools.com/jsref/met_document_queryselector.asp)
     method returns the first child element that matches a specified
    <b>CSS selector(s)</b> of an element. You can use it to return the
    first h1 element (h1), the first paragraph (p), the first link (a).
    If you want to search for an id, you must include the hashtag (#) in
    the selector. If you want to search for a class you must include a
    period (.)  [Sample Code for
    querySelector](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_document_queryselector_class)

<h4>Methods that return a collection of elements</h4>

It is possible to return a collection of elements rather than just one,
for instance if you want to return <b><i>all</i></b> of the paragraph elements
and not just the first one. Or all of the elements that share the same
class. In that case you will want to use getElements (notice the s at
the end) or querySelectorAll.

1.  The
    [getElementsByTagName()](https://www.w3schools.com/jsref/met_element_getelementsbytagname.asp) 
    method returns all of the elements with a given tag name. [Sample
    Code for
    getElementsByTagName](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_document_getelementsbytagname)

2.  The
    [getElementsByClassName()](https://www.w3schools.com/jsref/met_document_getelementsbyclassname.asp)
    method returns all of the elements with a specified class name(s).
    There is no need to include the period.  [Sample Code for
    getElementsByClassName (using one
    class)](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_document_getelementsbyclassname)
    and [Sample Code for getElementsByClassName (using multiple
    classes)](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_document_getelementsbyclassname2)

3.  The
    [querySelectorAll()](https://www.w3schools.com/jsref/met_document_queryselectorall.asp)
    method returns a collection of an element&apos;s child elements that
    match a specified CSS selector(s). When using querySelectorAll you
    must include the &num; if the selector is an id and a period if the
    selector is a class. [Sample Code for
    querySelectorAll](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_document_queryselectorall_class)

Important!  Even if there is just <b><i>one</i></b> element that matches the
selector, that element is returned as part of an array so you will need
to use an index to access it.

<h4>Using getElement vs querySelector</h4>

There are a few technical differences between your options. The
<b>getElement</b> and <b>getElements</b> methods if the specific value
doesn&apos;t exist, the method will return null. Both <b>querySelector()</b>
and <b>querySelectorAll()</b> throw a <b>SYNTAX_ERR</b> exception if the
selector(s) is invalid. The querySelector options are also faster. But
there are less technical differences too. Do you often forget to use Id
instead of ID? Then maybe you will prefer querySelector. If you are
prone to forgetting the pound '#' or the period '.' in your selectors
then maybe you would prefer the methods that describe the selectors, e.g
<b>getElementsByClassName</b>. Here is an additional (optional) reading if
you would like to learn more about the differences between the two
groups of methods: [querySelector vs
getElementById](https://dev.to/eidorianavi/queryselector-vs-getelementbyid-gm1)

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="new-dom">1.02b Newer DOM Methods (4:32)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 23. newer dom methods (18) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image023.webp?raw=true"
  style="width:45%;"
  title="1.02b Newer DOM Methods"
  alt="1.02b Newer DOM Methods." />
</p>

Hi everyone. Part of being a coder is realizing that you&apos;ve been using
the same code for a long time and that there&apos;s probably some newer
things out there. This is just a quick video to throw out there some new
methods that you might be seeing, or that you might want to use
yourself.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 24. selecting the first element (18) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image024.webp?raw=true"
  style="width:45%;"
  title="Selecting the First Element; querySelector()"
  alt="Selecting the First Element; querySelector()." />
</p>

We&apos;ve been using <b>getElementById()</b>. How it works is that it takes a
single parameter, and that parameter must be an Id selector. If you say
<b>getElementById(h1)</b>, it won&apos;t know that you&apos;re actually looking for
an h1 tag, is looking for something with the ID=h1.

If you&apos;re interested in selecting the first element of a certain type,
another option for you is the <b>querySelector()</b> method. Similar to
<b>getElementById</b>, it&apos;s going to return the first result. But that
selector can be anything. Well, anything except for pseudo-elements. The
selector can be a tag name. It can be an ID. It can be a class. It can
be a very complicated selector with tags, classes, and IDs all put
together.

The thing to remember though, is if you decide to use <b>querySelector</b>,
and you are looking for an ID or a class, you have to remember to
include that hashtag &num; or the period. We&apos;ll do some examples later in
the course to show you, but it&apos;s something that students often forget.
I wanted to mention it right off the bat. If you&apos;re looking to select a
single element, you can continue to use <b>getElementById,</b> or you can
start to play around and use <b>querySelector</b> as well.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 25. selecting multiple elements (19) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image025.webp?raw=true"
  style="width:45%;"
  title="Selecting Multiple Elements; querySelectorAll()"
  alt="Selecting Multiple Elements; querySelectorAll()." />
</p>

If you want to select multiple elements, well, there&apos;s something called
<b>querySelectorAll()</b>. It&apos;s pretty much identical to
<b>querySelector</b>, but instead of returning a single element, it will
return all the found values. The technical term for it is it&apos;ll return
a node list, but let&apos;s just consider it an array because that&apos;s what
we call it in this class. Again, while <b>getElementsByClassName</b>
doesn&apos;t need to include that dot period in your selector,
<b>querySelectorAll</b> does. You need to be very specific about exactly
what selector you&apos;re looking for. But it&apos;s not really that
complicated. Think back to all the code you&apos;ve been writing in your
CSS. If you can write a selector to style something, then you can
definitely write a selector for JavaScript to grab it to manipulate the
DOM.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 26. deciding on a method (19) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image026.webp?raw=true"
  style="width:45%;"
  title="Deciding on a Method"
  alt="Deciding on a Method." />
</p>

Which one should you use? Should you be using <b>querySelector</b> and
<b>querySelectorAll</b>? Should you be using <b>getElementById</b> or
<b>getElementsByClassName</b>? Well, the important thing is for you and the
type of codding that you&apos;re doing, speed won&apos;t be an issue. People get
online and they debate as to one&apos;s faster than another, and to be
honest, you could have done a lot more with that time in your life, than
compare the two of them. Don&apos;t worry about that. <b>querySelector</b> is
nice in that it does allow you to use any CSS selector that you&apos;d like.
To be honest, I&apos;m less prone to typos when I use the method name. 

When I use <b>querySelector</b>, sometimes I forget to include that hashtag or
the period. But to be honest, sometimes when I do <b>getElementById</b>, I
love how it&apos;s mnemonic. I know exactly what I&apos;m looking for, but
sometimes I accidentally capitalize the &quot;d&quot; in ById and then it
doesn&apos;t work. Or if I&apos;m using <b>getElementsByClassName</b>, you&apos;ll even
notice sometimes when I&apos;m doing demos in this class, I forget the s. I
write <b>&quot;getElementByClassName&quot;</b>. I liked that some of them have more
descriptive names. I like how others are a little less prone to typos.
My suggestion is you do you, you do it whichever way you prefer. But
don&apos;t be scared off if you see code online that uses the other
approach. Good luck.

<h3>Semicolons</h3>

Adding a semicolon () (;) indicates that you have completed a statement.
However, unless you are writing multiple statements on the same line,
you don&apos;t need to add a semicolon.

During this course you will <b><i>definitely</i></b> notice that I am in the
habit of adding a semicolon to the end of every line. This is a habit I
have because I write in a lot of different programming languages at the
same time and the semicolon is required in some and not others.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-03">1.03 Output (13:03)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 27. output (1.03) (20) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image027.webp?raw=true"
  style="width:45%;"
  title="1.03 Output"
  alt="1.03 Output." />
</p>

Hi everybody. Today, let&apos;s start coding a little bit to see some of
things we can do with JavaScript. Maybe, using HTML 5 or CSS 3, you&apos;ve
added what we call a little bit of interactivity to your page. There&apos;s
the details tag if you&apos;re using HTML. There&apos;s the hover property or
pseudo class if you&apos;re using CSS 3 and you were able to make little
things change in your page by reacting to what the user was doing.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 28. interactivity (21) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image028.webp?raw=true"
  style="width:45%;"
  title="Interactivity"
  alt="Interactivity." />
</p>

But typically, that&apos;s not really what we call interactivity when we&apos;re
talking about true web design because these new elements and the pseudo
classes can only go so far. They tend to be temporary changes.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 29. what can javascript do? (21) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image029.webp?raw=true"
  style="width:45%;"
  title="What can JavaScript do?"
  alt="What can JavaScript do?" />
</p>

What can JavaScript do that HTML and CSS can&apos;t do? Well, the one that
I&apos;m going to talk about today is that they can read and write HTML
elements. Now that&apos;s not the only thing they can do. We&apos;re going to be
talking about different things like reacting to events and validating
data and different things like that. But today, we&apos;re really going to
focus on output.

Whenever you learn a new programming language, one of the first things
you want to do is find out how can I make things happen. How can I have
things print out to the screen or generate some sort of output.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 30. javascript output (22) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image030.webp?raw=true"
  style="width:45%;"
  title="JavaScript Output"
  alt="JavaScript Output." />
</p>

Well, JavaScript doesn&apos;t have a built-in print function. Instead, you
have four or five different ways where you can generate different
things. Data is typically displayed via alerts, prompts<b>,
document.write, innertHTML</b> or reading information directly to the
console. Let&apos;s talk about each one of these.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 31. alert(), example (22) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image031.webp?raw=true"
  style="width:45%;"
  title="alert('My Message Here')"
  alt="alert('My Message Here')." />
</p>

You&apos;ve all seen alert JavaScript alert boxes. Because many times,
especially back maybe 10, 15 years ago, when you went to a page, people
loved to have these little boxes pop up and say hey, welcome. Doing
things like that. In JavaScript it&apos;s pretty easy. You can just use
alert and then inside you put my message here. A few things just to
point out right from the beginning.

Alert is a keyword. In your editor it should change some sort of special
color. Inside the parentheses, and you need the parentheses, both
beginning parentheses and end parentheses, is that you&apos;re going to have
some sort of string and it should be inside quotes. It can be inside
single quotes or double quotes. And then, the last thing is, to end in a
semicolon. If you were to put this code right here inside your HTML, you
can generate some output.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 32. codepen: sample alert() (23) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image028.webp?raw=true"
  style="width:45%;"
  title="Codepen: Sample alert()"
  alt="Codepen: Sample alert()." />
</p>

Let me show you an example. What I&apos;ve done over here is I&apos;ve created
the HTML that I would need to generate an alert box. I&apos;ve got my body
tag, now this is new I have what we call is a <b>script</b> tag. The script
tag tells the browser, oh wait, don&apos;t just print this out, I&apos;m
actually going to give you some JavaScript that I want you to run. And
in this case, I have my code <b>alert</b>(&quot;Hello World&quot;).
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 33. sample alert popup (23) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image033.webp?raw=true"
  style="width:45%;"
  title="Sample alert() popup"
  alt="Sample alert() popup." />
</p>

If I were to run this, and I&apos;m going to refresh it. You can see I get
my little pop-up box. Now, if you&apos;re running this along with me at
home, and you&apos;re not using Chrome, the box is going to look different.
For some of you it&apos;s going to have the little Safari symbol, or the
Edge, or Firefox.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 34. codepen: sample alert (24) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image034.webp?raw=true"
  style="width:45%;"
  title="Codepen: sample alert()"
  alt="Codepen: sample alert()." />
</p>

That&apos;s okay, the important thing is that somewhere in here it says
hello world. Now you might be click on the prevent this page from
creating additional dialogues button. Don&apos;t do it. Because in this
class we&apos;re going to be playing with alert a lot because it&apos;s a nice
way for you to know if your code&apos;s working or not. Again, this is just
a quick and simple way for you to generate output using the alert.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 35. prompt() output (24) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image035.webp?raw=true"
  style="width:45%;"
  title="Codepen, example; prompt('Enter your name:')"
  alt="Codepen, example; prompt('Enter your name:')." />
</p>

The next way we can generate output is using <b>prompt</b>. <b>Prompt</b> is
very similar to <b>alert</b>, but it&apos;s slightly different in that it wants
you to do more than just click OK or Cancel. It wants you to generate
some sort of input to put in there. As you can see, the alert and the
prompt look very similar. They&apos;ve both got the key word, the
parentheses, the semicolon and the string, but the way they act is very
different.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 36. codepen, example prompt (25) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image036.webp?raw=true"
  style="width:45%;"
  title="Codepen, example; prompt('What is your name? ')"
  alt="Codepen, example; prompt('What is your name? ')." />
</p>

In this case when you run it, it&apos;s actually waiting for you to type
something in. I can put in Colleen van Lent and hit OK. Now, don&apos;t get
too excited. We didn&apos;t do anything with the stuff I put in. But, again,
I&apos;m just giving you some of the different options. So, you have
<b>alert</b> and you have <b>prompt</b> and both of them generate some sort of
box where you can display information, but nothing is actually showing
up on the page. Let&apos;s switch to the general ways in which you can
generate output to the screen.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 37. document.write, example (25) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image037.webp?raw=true"
  style="width:45%;"
  title="Example, document.write('Time to learn JavaScript')"
  alt="Example, document.write('Time to learn JavaScript')." />
</p>

One way, if you want something to be what we call permanent, to not just
disappear once you hit okay, is to use what we call <b>document.write</b>.
I&apos;m hoping that you&apos;re picking up on these ideas that we&apos;re using
terms like document, and element, and so forth. The way that
<b>document.write</b> works is it goes through and it says, we want you to
write something directly to the page. We want it to become part of the
dom, we want it to become part of the page permanently. In this case I
can&apos;t just use write. That won&apos;t work. Alert worked by itself, prompt
worked by itself, but here you need to have <b>document.write()</b>. Same
thing, hopefully you&apos;re seeing the pattern. Let&apos;s see when we add
this.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 38. codepen: document.write (26) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image038.webp?raw=true"
  style="width:45%;"
  title="Codepen, example document.write with h1"
  alt="Codepen, example document.write with h1." />
</p>

Here you can see that inside the script tag, again, I have the
<b>document.write()</b>. But instead of things popping up or asking us for
input, it writes it directly into the screen.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 39. codepen: document.write, #2 (26) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image039.webp?raw=true"
  style="width:45%;"
  title="Codepen: document.write, #2"
  alt="Codepen: document.write, #2." />
</p>

Now I&apos;m going to change something right here. Because I put h1 inside
the quotes. If I get rid of that you can see this still works, but
instead of being an h1 heading, it&apos;s just regular old text. So,
<b>document.write</b> is a way for you to generate output. But we need to
realize that it is probably not the best way to do it.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 40. document.write (27) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image040.webp?raw=true"
  style="width:45%;"
  title="document.write()"
  alt="document.write()." />
</p>

Because sometimes if you&apos;re misusing it, you can overwrite other things
that exist. So, <b>document.write</b> is something you just want to use
when you&apos;re beginning and you don&apos;t know some of the more complex
methods.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 41. innerhtml() (27) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image041.webp?raw=true"
  style="width:45%;"
  title="innerHTML"
  alt="innerHTML" />
</p>

One of the more complex methods you can use is called <b>innerHTML</b>. And with <b>innerHTML</b>, 
you combine this with other functions that return elements. So, you can&apos;t just say 
<b>innerHTML</b> or <b>element.innerHTML</b>. You have to say, all right, what part of the 
page do I want to change? Oh, I want to change that particular paragraph, all right. 
But how do I grab that particular paragraph? Or remember we have these different 
APIs that can go and get things for us.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 42. innerhtml, #2 (28) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image042.webp?raw=true"
  style="width:45%;"
  title="innerHTML, #2"
  alt="innerHTML, #2." />
</p>

In this case, I have element which is hopefully we&apos;ll find something
using the API that in your HTML equals time to learn JavaScript. I
wanted you to recognize something right away. When we use document dot
write alert and prompt we had parenthesis around the side, here. We
don&apos;t have that anymore. Instead, we use an equal and we just have it
ending with a semicolon. No parenthesis when you&apos;re using
<b>inner.HTML</b>. How do you figure that out when you&apos;re coding? You
don&apos;t. You just keep coding and practicing and after a while, it
becomes second nature to you, all right?

When I talk about this kind of generic element, I didn&apos;t make it a
color that&apos;s something that you need to grab using the API. Let me give
you an example of something we can do using innerHTML.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 43. codepen: h1 with id=test (28) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image043.webp?raw=true"
  style="width:45%;"
  title="Codepen: h1 with id=test"
  alt="Codepen: h1 with id=test." />
</p>

Let&apos;s look at this, what I&apos;ve done is I made an <b>h1</b> heading and
I&apos;ve given it the <b>id</b> of test. I also have a paragraph element a
little bit further down that just says, hey what happens if I&apos;d messed
with this code?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 44. document.getelementbyid test (29) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image044.webp?raw=true"
  style="width:45%;"
  title="Test document.getElementById.innerHTML"
  alt="Test document.getElementById.innerHTML." />
</p>

In my <b>h1</b> heading, I actually have the words tester, but if you look
at the web page, it says Hello World. Well, how did I do that? Because
you can go in, and I can say <b>document.getElementById</b>. Test. It&apos;s
going to look through the page and go where can I find something that
says ID equals test. There it is. All right, now I want to change
whatever used to be in there and replace it with the words, Hello World.
This is kind of what happens when this is a weird example, but all early
examples are weird examples. Because you just want to get your feet wet.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 45. what two elements with id = test? (29) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image045.webp?raw=true"
  style="width:45%;"
  title="What happens if you have 2 elements with id=test?"
  alt="What happens if you have 2 elements with id=test?" />
</p>

But I did want you to look at what happens if I do this. Back from your
days of learning CSS, you might remember that in general, you can expect
to see multiple classes. But you&apos;re making this contract or rule that
says, you really should see each ID only once.

JavaScript is expecting you to keep that rule. When you do something get
element by ID, JavaScript thinks there&apos;s only one out there. I&apos;m going
to stop as soon as I find that one.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 46. second id = test is ignored (30) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image046.webp?raw=true"
  style="width:45%;"
  title="2nd id=test is ignored"
  alt="2nd id=test is ignored." />
</p>

As you can see down here, it changed the first one it found. It didn&apos;t
change the second one it found, okay? All right.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 47. console.log() (30) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image047.webp?raw=true"
  style="width:45%;"
  title="console.log() to write data to browser console"
  alt="console.log() to write data to browser console." />
</p>

Let&apos;s go play with the last output method I have for you today.
<span style="font-family: Consolas, Inter, Helvetic, Bahnschrift, sans-serif;">
document.write</span> and enter HTML. Write directly into the browser
screen. What we have in this last option is something that doesn&apos;t
write to the browser screen, but it does write to the browser console.

<span style="font-family: Bahnschrift, Inter, Helvetic, sans-serif, Consolas;">
console.log</span> takes a message and says you know what, I want to store
this information some place? But I want it to be something that not
necessarily pops up and everyone can see.

The console&apos;s a place to see what&apos;s going on in your program during
execution. If you haven&apos;t used the console before, you might not
realize that it&apos;s even there. But I&apos;m hoping you have when you were
doing your CSS.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 48. example script: console.log (31) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image048.webp?raw=true"
  style="width:45%;"
  title="Example script: console.log"
  alt="Example script: console.log." />
</p>

Let&apos;s take a look at this example. In my HTML up here, you can see that
I have <span style="font-family: Bahnschrift, Inter, Helvetic, sans-serif, Consolas;">
console.log</span> Hello World. Nothing too exciting going on here.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 49. browser console (31) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image049.webp?raw=true"
  style="width:45%;"
  title="Browser console example"
  alt="Browser console example." />
</p>

But if you look at the actual browser, hm, it&apos;s not there. It doesn&apos;t
show up like it did with document.write. Where did it go? Well, it&apos;s
actually in the Console of your browser. I&apos;m going to go down here. I
did inspect element, and I checked the Console. Oh, you can see Hello
World showed up here.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 50. more browser console (32) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image050.webp?raw=true"
  style="width:45%;"
  title="More browser console example"
  alt="More browser console example." />
</p>

What happens if I change the code to Hello World Too?

You&apos;re sending yourself these little secret messages that can help you
debug your code. You can log things, you can leave little notes for
yourself, you can do debugging tests. You can even log the things that
other people have been writing in. And so, this is a really handy tool
if you want to do development but not let everyone see exactly what you
are doing. We&apos;re going to come back to this example in just a second,
but first I want to talk to you about why you should be utilizing the
console by now, if you haven&apos;t.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 51. the console (32) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image051.webp?raw=true"
  style="width:45%;"
  title="The console"
  alt="The console." />
</p>

The console does more than just take these print statements. It also
provides debugging information for JavaScript, HTML, and CSS. By going
in and looking at it, you&apos;re going to be able to help yourself become a
much better programmer.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 52. debug example: missing quote (33) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image052.webp?raw=true"
  style="width:45%;"
  title="Debug example: Missing quote"
  alt="Debug example: Missing quote." />
</p>

Let&apos;s take a look at just doing some debugging with the JavaScript.
I&apos;m going to go in here and I&apos;m going to accidentally forget to put in
my first quotes, all right. But if we didn&apos;t know that there&apos;s
anything going on or that anything is supposed to show up.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 53. debug example: syntax error (33) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image053.webp?raw=true"
  style="width:45%;"
  title="Debug example: SyntaxError: missing argument (quote)"
  alt="Debug example: SyntaxError: missing argument (quote)." />
</p>

You might not realize that there&apos;s a typo but inside the console,
it&apos;ll show you pretty much along the way add, hey, anything in red
means we found an error. So red lines usually means either you have a
JavaScript error or you linked to a file that didn&apos;t exist. When I put
it back in, no more red syntax error.

I really want to stress this to you right now. I need you to stop and
make sure that you know how to access the console on your machine. One
of the things that really helps other people help you is when you can
pinpoint where exactly your code is going wrong. You might not know
what&apos;s going wrong, but you&apos;re saying somewhere in this line of code
I&apos;m getting an error. This kind of ability to help yourself debug is
going to be critical to going on and advancing in this course.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 54. access debugger in browsers (34) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image054.webp?raw=true"
  style="width:45%;"
  title="How to access the debugger in Safari, Chrome, Firefox and Edge"
  alt="How to access the debugger in Safari, Chrome, Firefox and Edge." />
</p>

If I&apos;m going to ask you to debug, I should probably tell you how you
can debug. If you&apos;re using Safari, you&apos;re going to need to go to
Preferences &gt; Advanced. Once you go there, you should be able to check
the Show development menu in menu box. And that will show you some of
the different JavaScript errors and tools that you have available. In
Google Chrome, you go to Developer, and then JavaScript Console.

If you&apos;ve been coding with me in the past, you know that my shortcut is
always to right click, inspect element, and boom, there it is for you.
If you&apos;re using Firefox, you want to go to Tools and then Console.
Firefox is, believed by many to be the best browser to use when you&apos;re
doing debugging for JavaScript. If you&apos;re using Edge or Internet
Explorer, typically hitting F12 will bring up the different JavaScript
and development tools that you can use to improve your page. All right,
so let&apos;s review.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 55. review: 1.03 output (35) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image055.webp?raw=true"
  style="width:45%;"
  title="Review 1.03 Output"
  alt="Review 1.03 Output." />
</p>

Right now, we&apos;re doing really simple things, and I understand that.
It&apos;s not that exciting to just print things out to the screen or have
little pop-up boxes coming up. But we need to do these small steps to
help you gain the confidence to go on and write more complex bits of
code.

As you learn more, the power that you&apos;re going to have to manipulate
the dom is really going to get quite impressive. But for now, just make
the small mistakes, learn how to debug the small mistakes, and then that
way you&apos;ll be able to build your confidence slowly. Good luck.

<h3>Trying to Create and Debug Your Own Output</h3>

In the previous lecture I showed you how you can create output using
JavaScript. My code examples are all on CodePen and I have included a
link to each of the examples in the Resources section of that module.
With CodePen you get your own copy of my code that you can change. I
encourage you to experiment with that code, or even better try
recreating it yourself using an editor such as TextEdit, Sublime, or
Notepad++.

If you are using a laptop or desktop to do your coding, make sure to use
the console window of your browser to look for errors in your code. In
programming, looking for and correcting errors is called &quot;debugging.&quot;

Below I have a screen shot of my code, the (empty) browser, and the
error message I get from the Chrome console. Don&apos;t worry if error
message itself doesn&apos;t make sense, that is something that comes with
time, the important part is to look for the line number, in this case
line 9. The console will always try to tell you about where it ran into
a problem. In this case, I didn&apos;t include the quotes to end the message
for the alert.

W3Schools has a page with debugging tips for JavaScript: [JavaScript
Debugging](https://www.w3schools.com/js/js_debugging.asp).

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 56. chrome error alert (36) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image056.webp?raw=true"
  style="width:45%;"
  title="Code, an empty browser, and an error message in the Chrome console"
  alt="Code, an empty browser, and an error message in the Chrome console." />
</p>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-04">1.04 Variables</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<https://codepen.io/ColleenEMc/pen/jbYEEW>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 57. variables (1.04) (36) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image057.webp?raw=true"
  style="width:45%;"
  title="1.04 Variables"
  alt="1.04 Variables." />
</p>

Hi, everybody. Today we&apos;re going to learn about JavaScript variables.
An important part of programming is learning how you can save data.
Because by saving data, you can reuse it and give you program that&apos;s
impression that&apos;s kind of intelligent and knows the user very well.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 58. storing data (37) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image058.webp?raw=true"
  style="width:45%;"
  title="Storing data in variables"
  alt="Storing data in variables." />
</p>

In JavaScript, data is stored in what we call variables, and it&apos;s very
easy to use variables in your programming. The only important part is
that you need to tell the computer very specifically, hey, I need you to
save something for me. And this is how we do it. We start by using the
keyword var, V-A-R. When we&apos;re using the editor, hopefully this will
show up in some special color that indicates, ooh, this is a special
word to the computer. Next, you need to give your variable a name. Now,
I chose the name "name" here, but you can imagine it being age, first
name, last name, dob for date of birth. The important thing is that it
should be special to you, but not special to the computer.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 59. example: storing data in variables (37) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image059.webp?raw=true"
  style="width:45%;"
  title="Example: Storing Data in variables"
  alt="Example: Storing Data in variables." />
</p>

How does this work? When you declare a variable, you&apos;re basically
telling the computer, let&apos;s stop talking in human talk and let&apos;s talk
computer talk. So here, once you said var name, it reserved a space in
memory. It said oh, okay. I know that I&apos;m talking about position 11011,
blah, blah, blah, blah, blah. But Colleen doesn&apos;t want to talk about
those numbers, she wants to use the actual variable name. So, whenever
she talks about name, I know she actually wants me to use the value,
Christopher. There might be some variables that you&apos;ve declared, such
as age, that you haven&apos;t put anything in there yet.

The important thing to know is that computers aren&apos;t smart. Computers
are just trying to give you a way to avoid remembering big long numbers
and instead using English words.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 60. variable name rules (38) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image060.webp?raw=true"
  style="width:45%;"
  title="Variable name rules"
  alt="Variable name rules." />
</p>

When you come up with your variable name, there&apos;s a few rules that you
need to follow. Every variable name can have letters, digits,
underscores, and dollar signs in it. Now to be honest, I don&apos;t put
dollar signs in my JavaScript variable names because it can be very
confusing, particular for those people who know multiple programming
language. I tend to stick to letters, and sometimes digits and
underscores.

When you do come up with a variable name, even though numbers are
allowed, your variable can&apos;t start with a number. That number has to be
somewhere else in the middle or the end.

Also, variables are case-sensitive. What that means is that lower case
name is not the same thing as name with a capital N or name with a
capital M or name on all capitals. To the computer these are all
different variables. So, just be careful when you&apos;re programming and be
consistent.

Also, this last one isn&apos;t a rule so much as a suggestion that I want to
convey to you. Make your variable names meaningful or mnemonic as the
computer science term we use. That means, if the variable is storing
someone&apos;s name, call it name. If it&apos;s storing age, call it age. You
could get away with calling it &apos;yyy&apos; or &apos;bbb&apos;, just don&apos;t do it.
Okay? Taking a little bit of time to give meaningful names will save you
a lot of heart ache later.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 61. variable assignments (39) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image061.webp?raw=true"
  style="width:40%;"
  title="Variable assignments"
  alt="Variable assignments." />
</p>

If you&apos;re going to go to the trouble of declaring a variable and
telling the computer to save a spot in memory for it, it&apos;s pretty silly
if you don&apos;t then use your variable. And what I mean by use it, is you
should assign some sort of value to it.

When we assign things in computer science, we use what we call the
equal, or assignment operator. So, it looks like an equal sign, but we
call it assignment, because what we&apos;re doing is we&apos;re not saying hey,
are these two things the same, we&apos;re saying take the value and store it
into the variable.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 62. assignment statement; lhs and rhs (39) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image062.webp?raw=true"
  style="width:40%;"
  title="Assignment statement LHS &amp; RHS"
  alt="Assignment statement LHS &amp; RHS." />
</p>

Here I have <b>var</b> name, and instead of just leaving it at that, I say,
hey, I want you to store the name Colleen in there, all right. This is
where when we start talking about assignment statements, I refer to LHS
and RHS. I mean left-hand side and right-hand side of statements. The
left-hand side should always be the variable, alright so this is going
to be in our case name or some sort of element, something that we want
to change. The right-hand side is going to be that new value that will
be stored in the variable. Sometimes, the right-hand side can be pretty
long and complex.

Right here would be an example where I&apos;m just having, I declare my
variable, and then later I want to update it. I say, name equals
Colleen. This works really well.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 63. example error: assignment statement (40) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image063.webp?raw=true"
  style="width:40%;"
  title="Example Error: Assignment statement"
  alt="Example Error: Assignment statement." />
</p>

What I need people to avoid is doing something along this line, where
they switch the left-hand side and the right-hand side. Mathematically,
if you&apos;re a math major, this makes perfect sense and it&apos;s the same
thing, but it&apos;s not okay in programming. Always put the variable on the
left-hand side.

All right, so I&apos;m going to show you a few examples of how you might use
a variable. If you remember when we talked about output, one way that we
were able to produce output also was a way to generate input, and that
was the prompt.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 64. example, using a variable (40) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image064.webp?raw=true"
  style="width:40%;"
  title="Using a variable"
  alt="Using a variable." />
</p>

When you use the prompt, it&apos;s waiting for you to type something in and
when you type it in, it&apos;s going to store that in the name. Now can we
use that whenever we want to? We can say document dot write name and
we&apos;ll promote to the screen. Next, we can use another variable and say
hey, I want you to use this JavaScript function called date. And date is
going to return what the current date and time is, right now when
you&apos;re looking at the page. Then you can write that information out.
You can even use more from the API saying, you know what? I want to know
where this window is. What&apos;s the location of this window? And you can
write that out as well.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 65. example, prompt (41) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image065.webp?raw=true"
  style="width:40%;"
  title="Example, prompt"
  alt="Example, prompt." />
</p>

Let&apos;s look at a quick example of how we can use that. Let&apos;s start with
the simple code we used before when we were learning about prompts.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 66. example: set var to prompt (41) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image066.webp?raw=true"
  style="width:40%;"
  title="Example: var nm = prompt"
  alt="Example: var nm = prompt." />
</p>

Only now, I want to combine it with a variable, so I am going to go in
here and do var, and I&apos;m actually just going to call it nm. The reason
I&apos;m doing that instead of name is because I really want to make people
realize that the name you give your variable. Doesn&apos;t really matter, it
can be anything you want. Just because I call it name, doesn&apos;t mean you
have to.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 67. example: set var prompt (42) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image067.webp?raw=true"
  style="width:40%;"
  title="Example: var prompt"
  alt="Example: var prompt." />
</p>

And as soon as I did this, the prompt statement showed up, and I put in
Colleen. Great, it worked, but we didn&apos;t do anything with it. Let&apos;s
add a bit more code. Now I am going to comment out this line. You can
see why, because otherwise it&apos;ll keep asking us to prompt things.
We&apos;ll comment that out when we&apos;re done. All right.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 68. example: document.write (42) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image068.webp?raw=true"
  style="width:40%;"
  title="Example: document.write, console.log and alert"
  alt="Example: document.write, console.log and alert." />
</p>

I have this variable called <b>name</b>, now I can do something like
<b>document.write nm.</b> I can also do <b>Console.log(nm).</b> If you wanted
to you could even put in <b>alert(nm)</b>. Let&apos;s put this back in. Might
want to edit all my typing out. What is your name? Well, it is Colleen.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 69. example: alert popup (43) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image069.webp?raw=true"
  style="width:40%;"
  title="Example: alert popup"
  alt="Example: alert popup." />
</p>

All right, so the alert popped up, but why didn&apos;t the
<b>document.write</b> work? This is a good question, and this is actually
an example where I can go in, that&apos;s what was going on.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 70. example: alert, cont'd (43) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image070.webp?raw=true"
  style="width:40%;"
  title="Example: alert, document.write, and console.log"
  alt="Example: alert, document.write, and console.log." />
</p>

It was actually waiting for me to hit okay. When it was all done, it
went in and it printed out my name. This is a really simple, quick
example.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 71. document.write (44) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image071.webp?raw=true"
  style="width:40%;"
  title="document.write()"
  alt="document.write()." />
</p>

Let&apos;s do one that has a little bit more going on with it. All right, in
this case we&apos;re going to talk a little bit more about how you can add
different things together, and how you can assign your variables using
more than just prompts. In this case, I declared a variable. We&apos;re
going to ask for the name. I write out the name. I write out the name
twice actually. Once with my name and then another time with an H1
heading. And then I just wanted to show you that you could also grab
other information from the document, itself, such as the URL and the
title.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 72. document.write, cont'd (44) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image072.webp?raw=true"
  style="width:40%;"
  title="document.write, cont'd"
  alt="document.write, cont'd." />
</p>

First thing I&apos;m going to show you is, it says null and null. And
that&apos;s kind of weird, and it might happen to you and it might not. The
first thing I wanted to print out was my name, but I didn&apos;t type
anything in the prompt. When the JavaScript doesn&apos;t know what to do,
when it doesn&apos;t know what value should have been in there, it&apos;s going
to assign it a value of null.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 73. prompt/print name (45) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image073.webp?raw=true"
  style="width:40%;"
  title="Prompt/print name"
  alt="Prompt/print name." />
</p>

Let&apos;s run this one more time. I&apos;m going to put in the name Christopher
just in case someone else named Christopher is reading this and they can
feel special. But now you can see it printed out Christopher, the URL,
and the title of my page.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 74. 1.04 variables: review (45) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image074.webp?raw=true"
  style="width:40%;"
  title="1.04 Review"
  alt="1.04 Review." />
</p>

Variables are a key component of really doing any type of programming
language at all. We&apos;re going to be using them throughout this entire
course, so I need you to practice them and feel comfortable using them.
Go into the code that I have on CodePen or online and change it, and see
if what you do does what you expect it to do. You might create some
errors and that&apos;s okay. That&apos;s a great practice using things that just
consult that log. The most important thing is I want you to understand
how variables work, so that you can use them throughout the rest of the
course. Good luck.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-05">1.05 Data Types</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 75. data types (1.05) (46) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image075.webp?raw=true"
  style="width:40%;"
  title="1.05 Data Types"
  alt="1.05 Data Types." />
</p>

Once you realize that computers store all of the information using
variables, the next step is to start to learn about the different data
types used in the JavaScript programming language.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 76. assignments (46) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image076.webp?raw=true"
  style="width:40%;"
  title="Assignments; prompt(), date() and window.location"
  alt="Assignments; prompt(), date() and window.location." />
</p>

If you look here in this example, you can see that I&apos;ve got variable
name equals prompt, what is your name. It&apos;s expecting me to type in
probably something like Colleen or Chris or Becca, something along that
line.

In the next example, we have variable name equals <b>Date</b>. This is not a
string. This is something that actually can be quite a bit longer and is
very complex. You might also have variable name equals
<b>window.location</b>. If I wanted to in JavaScript, I could even say name
equals 12. Doesn&apos;t make any sense but there&apos;s nothing stopping me from
doing it. In each of these examples, name would have what we call a
different type. Things that are stored in the computer are completely
different.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 77. types of variables (47) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image077.webp?raw=true"
  style="width:40%;"
  title="Types of variables"
  alt="Types of variables." />
</p>

In computer programming languages, computers tend to have a single type.
In JavaScript, that&apos;s fine, a variable can only be one type, but
throughout the course of the program, it can switch from being a program
to characters, back to a number to something else that&apos;s completely
complex. Let&apos;s talk about what these types are in JavaScript and how we
can represent them.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 78. number, example (47) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image078.webp?raw=true"
  style="width:40%;"
  title="Number, window.innerWidth"
  alt="Number, window.innerWidth." />
</p>

The first type we&apos;re going to talk about is <b>number</b>, and it&apos;s pretty
straightforward, it&apos;s simply any type of numerical value that you want
to store. This can be with or without decimals. JavaScript doesn&apos;t care
if it&apos;s 2 or 2.0 or 2.6785, it&apos;s all the same.

In this example, I went in and I said you know what, I have this
variable called width and I&apos;m going to set it using
<b>window.innerWidth</b>. This is pretty cool actually if you&apos;re trying to
do something interesting in CSS because you can find out how wide the
window is and then use that information to update other things.

My next example is I have <b>var</b> pi, which is equal to 3.14. In this
case, I hard coded it to something. In both cases, it&apos;s storing a
number, but in the different cases or one, it&apos;s going to be, normally
would be an integer or a whole number, and the next time it has
decimals.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 79. string, example (48) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image079.webp?raw=true"
  style="width:40%;"
  title="String, window.location"
  alt="String, window.location." />
</p>

The next type is called <b>String</b>. String is simply a collection of
characters such as letters, numbers, punctuation, spaces, basically
anything you can type into the keyboard.

To create a string, you have to put the value in quotes. Now, these can
be single quotes or double quotes. And I want to be very clear here that
in PowerPoint it&apos;s drawn the quotes as kind of forward and forward.
Make sure you don&apos;t copy and paste and instead you do the quotes
directly from your keyboard because the slant does matter. In this case,
I&apos;ve done var location = <b>window.location</b>. Because it happens to be
that that attribute is a string or in my second example once again,
I&apos;ve just hardcoded it to something you might expect.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 80. boolean, example (48) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image080.webp?raw=true"
  style="width:40%;"
  title="Boolean, examples; false, window.closed"
  alt="Boolean, examples; false, window.closed." />
</p>

The third data type is <b>Boolean</b>. In programing, a boolean value is
something that is either true or false. It doesn&apos;t have numbers to it
or strings, it&apos;s very straightforward. In this case, I might have my
variable status equals false, this is again called hard coding it, or in
my program if I want to do something based on whether or not the window
is open or closed. I can set it dynamically right here. The important
thing to know is that status and window status can only be true or
false. Those are the only two options.

Later, we&apos;re going to learn how to write our own boolean expressions to
check to see if things are true or false. And that can add really a lot
of power to your page.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 81. object, example (49) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image081.webp?raw=true"
  style="width:40%;"
  title="Object, example; document.getElementById('myID')"
  alt="Object, example; document.getElementById('myID')." />
</p>

The next data type is called <b>object</b>. Because sometimes the variables or
the nodes are more complex than just a number or couple characters. A
node in the DOM would be a really good example. If you think about a
paragraph element to it, paragraphs are not just a number or a string,
there are a lot of different things that go into it. Here I might have
var topic = <b>document.getElementById(&apos;myId&apos;)</b>. If I wanted to print
out what topic is now, something like <b>document.RightTopic</b>. I would
get something that pretty much looks like junk because it&apos;s an object,
and objects can only read illegibly using things like attributes.

Using those attributes, we can go in and we might be able to say
something along the lines of write out <b>topic.style, topic.innerHTML.</b>
Different things like that can show us really the attributes or the
string&apos;s numbers that make up objects.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 82. array, example (50) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image079.webp?raw=true"
  style="width:40%;"
  title="Array, example; document.getElementsByTagName('a')"
  alt="Array, example; document.getElementsByTagName('a')." />
</p>

Finally, the last type we&apos;re going to talk about is <b>array</b>, because in
some cases a function might want to return more than one value. We&apos;ve
seen how the API can return something complex, like an object that could
be a paragraph, or a div, something along that line. What if it needs to
return multiple things?

Here I have var links <b>= document.getElements</b>. Not element, but
elements, <b>ByTagName(&apos;a&apos;)</b>. We&apos;re going to go in, it&apos;s going to
search the entire document, and find all the hyperlinks in the page.
Well, that&apos;s certainly not going to return just a single number, or a
bunch of strings, or even a single object. Instead, it needs to return a
whole collection.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 83. accessing array elements (50) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image083.webp?raw=true"
  style="width:40%;"
  title="Accessing Array Elements"
  alt="Accessing Array Elements." />
</p>

Arrays store these multiple values using a variable name, just like the
ones we&apos;ve done, but it also includes what we call an index for each
element in the array.

This is the same example where I say hey, go out and grab all the links.
Now if I wanted to write some sort of element out, I could say
<b>document.write(links&lbrack;0&rbrack;)</b>, and it would say return the very first
link I saw. If I had links three, it would actually return the fourth
one because computers love to talk starting from zero and up. Now we&apos;re
going to have an entire lecture or more on arrays later in this course.
But for now, I just want you to realize that it&apos;s one of the data types
that can be returned.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 84. variables - play with types (51) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image084.webp?raw=true"
  style="width:40%;"
  title="Variables; Play with Types"
  alt="Variables; Play with Types." />
</p>

Let&apos;s look at a quick example that uses some of the different types.
Let&apos;s see what happens when I type in a string to this sample code.
I&apos;m going to put in for what is your name, I&apos;ll put in Coleen.

If we look at the code, what I was doing here is I was just prompting
for the name and then I want to write out the name. Boom, there&apos;s
Colleen. And then I want to say, hey, what happens if I add <b>H1</b>
elements on each side. You haven&apos;t seen this plus before, and we&apos;re
going to be talking about it soon, but what we&apos;re doing right now is
we&apos;re doing what&apos;s called concatenating. We&apos;re saying take the name
and add H1 on either side. So, boom, I get it bigger now. I also want to
print out the title. That&apos;s a string. I also want to print out right
here <b>document.getElementsByTagName(&apos;p&apos;)</b>. This is where we&apos;re
using an array, and I just want to show you this because there&apos;s a
really good chance this message might pop up for you and I don&apos;t want
you to get freaked out about it.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 85. example, document.write (52) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image085.webp?raw=true"
  style="width:40%;"
  title="Example, document.write"
  alt="Example, document.write." />
</p>

After I grab all the paragraph elements, if I try to print them out, it
prints out object <b>HTMLCollection 0.</b> It says, oh, you didn&apos;t
actually have any paragraphs in this page. If I go back, and I add a
few, they can even be empty. Gotta love when it keeps popping up on you.
I don&apos;t know how many I added but we&apos;re going to do it.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 86/87. prompt/display variable (52) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image086.webp?raw=true"
  style="width:45%;"
  title="Prompt for name as variable"
  alt="Prompt for name as variable." />
<img src="./images/image087.webp?raw=true"
  style="width:45%;"
  title="Display name as variable"
  alt="Display name as variable." />
</p>

I can try running this again. And when I type in Colleen, you can see
that now it knows that I have five paragraph elements in there.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 88. review, data types (53) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image088.webp?raw=true"
  style="width:40%;"
  title="Review, Data Types"
  alt="Review, Data Types." />
</p>

Luckily in JavaScript, there&apos;s a ton of flexibility with the different
types of data you can use. In other programming languages they&apos;re very
strict, but here with JavaScript they want you to have the power to try
different things.

For now, I want you to focus on learning what types of data are returned
from those common APIs. If you do <b>getElementByID,</b> does that return a
number, a string, an object, or an array? If you do something along the
lines of <b>getTitle</b> or <b>getLinks</b>, what types of things are those
returning? If you can play with that and start to feel comfortable
knowing what the types are, even if you don&apos;t know how they work,
you&apos;re really going to be on your way to doing some cool programming.
So good luck.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch1-06">1.06 Operators &amp; Expressions (8:26)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 89. operators and expressions (1.06) (53) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image089.webp?raw=true"
  style="width:40%;"
  title="1.06 Operators and Expressions"
  alt="1.06 Operators and Expressions." />
</p>

Today we&apos;re going to be talking about expressions and mainly operators,
the different ways that you can manipulate your code. We&apos;ve been using
statements to execute our JavaScript code. Every time you saw a line
that ended with a semicolon, we were writing a statement.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 90. statements (54) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image090.webp?raw=true"
  style="width:40%;"
  title="Statements"
  alt="Statements." />
</p>

Statements often have what we call expressions, or things that can be
evaluated. Expressions produce values. They might produce a number, or a
string, but many times they produce what we call Boolean values. I want
to show you all the different types of operators that we can use in
JavaScript to produce these types of expression values.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 91. expression (54) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image091.webp?raw=true"
  style="width:40%;"
  title="Expression"
  alt="Expression." />
</p>

If you think back, I tend to talked about that left hand side equals
right hand side. With the left-hand side is a variable and the
right-hand side is that new value we want to be stored.

What are our tools for generating different values on that right hand
side? We&apos;ve seen direct assignments or calls to different functions but
there&apos;s more to it that we can do than just that.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 92. assignment operators (55) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image092.webp?raw=true"
  style="width:40%;"
  title="Assignment Operators"
  alt="Assignment Operators." />
</p>

Here&apos;s a very simple assignment expression. I just had x=5 or in
another example I said y=12. What&apos;s going on here is not an equal or a
thing if two things are the same. In this expression I&apos;m saying, go
find the value that is story in y. After I grab that, go and store it in
x as well.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 93. arithmetic operators (55) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image093.webp?raw=true"
  style="width:40%;"
  title="Arithmetic Operators"
  alt="Arithmetic Operators." />
</p>

We also have arithmetic operators. Most of these are very straight
forward. You&apos;ve probably seen plus, minus, this is multiplied, and then
we also have divide. And these are the straightforward math that you
learned, hopefully in somewhere around third or fourth grade at the
latest. 2 + 5 is 7. 5- 2 is 3. 2 &ast; 5 is 10. 5/2 is 2.5.

But this last one, the modulus operator is something you may not have
seen before. It goes back to the idea of old long division. If you do
5/2 and you&apos;re looking only at the whole numbers, you have 2. What&apos;s
that leftover number that&apos;s kind of left over at the end. 5%2 is 1. See
if I can do another one here.

What would happen if I did something along the lines of 13/5? Well, 13/5
would give us something along of 2.blah, blah, blah. If I do 13%5, you
figure out how many times does 5 go into 13? That&apos;s 2, and what&apos;s left
over? 13%5 is going to be 3. Go ahead and play with that if you&apos;d like,
and type a few numbers in and see what kind of response you get.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 94. more operators (56) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image094.webp?raw=true"
  style="width:40%;"
  title="More Operators"
  alt="More Operators." />
</p>

Some additional operators we have are the <b>plus plus</b> and <b>minus
minus</b>. This is the increment and the decrement. It&apos;s the same thing
as saying, take whatever I had before and add 1 to it. Or take whatever
I had before and subtract 1 from it. A third operator that&apos;s very
similar is the plus equals. You can also have minus equals. It&apos;s the
same thing as writing out long something along the lines of x = x + 2.
It&apos;s the same thing as saying x + = 2. It&apos;s just short hand you don&apos;t
need to use it. But I wanted to show you just in case you see it in
somebody else&apos;s code.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 95. string operators (56) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image095.webp?raw=true"
  style="width:40%;"
  title="String Operators"
  alt="String Operators." />
</p>

We talked about how plus will add two numbers together. That&apos;s only
true if the operators on both sides are numbers. In some cases, we have
the string operators, and in that case, the plus is actually a
concatenation. It&apos;ll take the &apos;Hi&apos; and the &apos;There&apos; 
and put it together into one variable. If you want to put those spaces in, you 
have to remember to actually add them. In the same case, if I have a string and
a number, and I use the plus, it&apos;s going to be concatenation. You want
to be careful when you&apos;re playing with this, because anything that&apos;s
read in from a prompt is a string. You&apos;re going to need to make sure
that your output is what you&apos;re expecting. The plus equals has the same
effect as the plus equals from before. It just means take whatever I
used to have and concatenate this new part on to it.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 96. example, boolean operators (57) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image096.webp?raw=true"
  style="width:40%;"
  title="Example, Boolean Operators"
  alt="Example, Boolean Operators." />
</p>

Those first few operators, we use usually to assign values to a
variable. Sometimes we use what we call Boolean operators to compare
values instead. In this case, let&apos;s assume that I&apos;m assigned x = 12.
Well, some of the different Boolean operators I can use are <b>equal
equal</b>, which means don&apos;t set x equal to 5, instead, I want you to
check, is the value stored in x equal to 5? This is kind of a test case.
Well, in this case, no, it doesn&apos;t, so it returns false. But if I have
x==12, oh okay, yep, those two things are equivalent, so I&apos;m going to
return true. There&apos;s also another short hand, which is the exclamation
point equals. This is a negation or the opposite, it says, hey, make
sure the value stored in x doesn&apos;t equal 5.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 97. another example, boolean operators (57) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image097.webp?raw=true"
  style="width:40%;"
  title="Another Example, Boolean Operators"
  alt="Another Example, Boolean Operators." />
</p>

We also have more of the traditional greater than, greater than or equal
to, less than, or less than or equal to, where they just compare the
left-hand side and the right-hand side and they return true or false.

With JavaScript we have a special case, though. And that&apos;s because in
JavaScript we don&apos;t really care about types too much. What happens if
you want to see if a number is equal to something else, but you don&apos;t
want it to say yes if it&apos;s a string?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 98. boolean operators (58) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image098.webp?raw=true"
  style="width:40%;"
  title="Boolean Operators"
  alt="Boolean Operators." />
</p>

Here I&apos;ve got the equality statement that we used before, which is
<b>equal equal</b>. If I were to say x == &quot;12&quot; the string, JavaScript
would say yep, yep they&apos;re the same. Even though to us it&apos;s probably
not the case that 12 the number and 12 the string are the same thing. If
you&apos;re looking for what we call equality with type you would use the
<b>equal equal equal</b>, the triple equal operator. And that checks and
says, hey are these two values the same? And are they the same type?
This is just one more thing to put in your arsenal as you start
programming.

Now I&apos;m putting in this little note here, because I need you to stop
and think about these operators and what we&apos;ve been talking about. It
is complete human nature to read this and nod along. Got it? Yep. Got
it, got it. And just think you&apos;ve really grasped everything I&apos;ve been
talking about. It&apos;s really hard to understand how these things work
unless you type in some examples, play with the numbers, and try to fool
yourself and give yourself tricky situations. If you can do that, then
you&apos;ll feel comfortable moving on with these operators.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 99. logical operators (59) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image099.webp?raw=true"
  style="width:40%;"
  title="Logical Operators"
  alt="Logical Operators." />
</p>

Let&apos;s do one last little group or two groups before we finish up. In
this case, I have what we call the <b>and and (&&).</b> This stands for
"and". It means, hey are the things on the left-hand side, and the
right-hand side, are they both true? The pipes, the straight up and down
the lines, this is what we call "or". In this case, you might want to
say at least one side must be true in order for me to say true.

And then we have the exclamation part "not", just kind of like this
negation. If I had to come up with an example for using and and or, one
might be that in order to enroll in courses at University of Michigan
you have to be an enrolled student and your tuition has to be paid up.
It doesn&apos;t work if it&apos;s only one or the other. For the "or", you might
use the example that in America, you can&apos;t get into certain movies
unless you&apos;re 18 or you&apos;re with your parents. So that would be a case
where you only need one thing to be true.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 100. review, operations and expressions (59) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image100.webp?raw=true"
  style="width:40%;"
  title="Review, Operations and Expressions"
  alt="Review, Operations and Expressions." />
</p>

When it comes to programming, it&apos;s not enough for you to just know the
syntax of the language or the different rules, or even for you to listen
to me and kind of nod along. It&apos;s really key that you practice these
different things.

And before you start programming yourself, make sure you think about the
logic you want to go into your program. Do you want to use greater than
or greater than or equal? Do you want to use the and or do you want to
use the or? If you think about these things before you start, and then
you go in and test them a lot, your code is going to be a lot cleaner
and the whole experience will be one that you really enjoy much more. So
good luck.

<h3>Share Your Tips</h3>

Is anyone using Replit?

<h3>The History of &quot;Debugging&quot;</h3>

If you want to learn more about the history of debugging, here is an
article that talks about the fact that two different people are credited
with the term, Grace Hopper and Thomas Edison

<http://theinstitute.ieee.org/tech-history/technology-history/did-you-know-edison-coined-the-term-bug>

<h3>Link to All of the Code for Week Two</h3>

The following is a link to all of the code for Week Two. The individual
files are linked within the modules but the weekly collections may
include additional code that you are free to use.

<http://codepen.io/collection/Adbwgo/>

Even if you use CodePen, I encourage you to practice writing the code on
your own. For now, I put complete examples in CodePen, but as time goes
on, I will remove some of the commands to link the code together. You
will need to work on that part on your own..

<h3>Functions</h3>

The next module on functions is crucial to any type of programming that
you may do in the future. The reason that programming languages work so
well is that they allow people to reuse work that other people have
done. Someone else writes the complex code that can determine what time
it is in any given country? Excellent. If they put that code in a
function then you can use it without really knowing the details of how
it works. (And yes, there is a function for that.)

One of the things I want you to watch for in this next module is the
distinction between <b><i>defining</i></b> a function (writing the code) and
<b><i>calling</i></b> a function (running the code at the precise time you want
it to happen).
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-01">2.01 Functions (7:18)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 101. functions (2.01) (62) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image098.webp?raw=true"
  style="width:40%;"
  title="2.01 Functions"
  alt="2.01 Functions." />
</p>

Today we&apos;re going to talk about functions. Functions are these bits of
code that you can reuse over and over again by just coding what we call
the function name.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 102. example, functions (62) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image102.webp?raw=true"
  style="width:40%;"
  title="Example, functions"
  alt="Example, functions." />
</p>

Functions of course, like everything else in programming, have special
syntax that you need to follow. In order to declare a function so that
you can use it later, you need to use the special keyword, function,
f-u-n-c-t-i-o-n. It&apos;s not an abbreviated such as, var, so make sure you
write out the whole thing. Once you write out function you can give it
any name you want. Stick to the same rules as the variables, only use
letters, and digits, and underscores. Next, this third thing I have
inside here, inside the parenthesis, are what we call the parameters.
Sometimes there&apos;ll be things in here, sometimes there won&apos;t. Once you
have what we call the function header, where you have function, the
name, the parentheses and any type of information in here. We&apos;re going
use curly brackets to begin and end our function.

It&apos;s really important right here that you realize that you do not put a
semi-colon right here at the end. In all of our other JavaScript
expressions and statements, we ended them with a semicolon. If you do
that here, you&apos;re going to mess up your code. All those statements go
inside here. And how it works is that later,

then when people run your function, it&apos;ll execute all the code that&apos;s
in {code you want to run}. And this code is just general code you would
always write with your semicolons, your expression, your statements.
It&apos;s just a really nice way to save it. You don&apos;t have to keep typing
it over and over again.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 103. example, function declaration (63) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image103.webp?raw=true"
  style="width:40%;"
  title="Example, Function Declaration"
  alt="Example, Function Declaration." />
</p>

Let me show you an example. In this case, I declared a function called
<b>welcomeMsg</b>. And I didn&apos;t put anything inside the parenthesis.
Because I said, it doesn&apos;t matter. Every time I run this function, all
I want to happen is to have an alert that says, Welcome to JavaScript.
And this will work numerous times. I don&apos;t have to keep writing things
over and over again. It&apos;s a small function, but it&apos;s something that
will work.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 104. more examples, function declaration (63) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image104.webp?raw=true"
  style="width:40%;"
  title="More Examples, Function Declaration"
  alt="More Examples, Function Declaration." />
</p>

Here&apos;s another very similar function. The only difference is that, this
time, I went ahead and I included a parameter list, which says, hey, now
instead of saying Welcome to JavaScript every time we run this function.
It&apos;s actually going to give an alert of whatever message you tell it to
do in what we call it real time.

The first step in using functions is to do this function declaration,
where you use the keywords, the curly brackets, and the parenthesis.
Declaring a function doesn&apos;t actually do anything for you though. You
need to tell the computer when you want that function to run.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 105. function call (64) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image105.webp?raw=true"
  style="width:40%;"
  title="Function call"
  alt="Function call." />
</p>

We do this by saying or we call the function. Every time you write the
function name, you&apos;re telling the computer that you want to run that
code. Calling a function changes what we call the program flow. Before
our programs start at the top and just work their way down line by line
by line. Now with functions, the computer is actually jumping around in
memory and executing different parts of code, not necessarily in the
order that you write them.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 106. example, function call (64) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image106.webp?raw=true"
  style="width:40%;"
  title="Example, function call"
  alt="Example, function call." />
</p>

Here&apos;s an example. I have my <b>welcomeMsg</b> function, the one with the
parameters. Over here, in my HTML file, or JavaScript file, the file
I&apos;m running, is the computer gets down here, it says, oh, I know how to
do that, check. Then it gets to our function call, where it says oh,
I&apos;m going to leave here and I&apos;m going to go over and run this code. As
soon as it&apos;s done running this code, it comes back to the next line of
code. Well, we know how to say x = &quot;Goodbye&quot;, the computer knows how
to assign that new value. When we go here, once again, we go back up to
this code and then back down here. The code looks quite straightforward
to you, and when it runs it should look straightforward to you. But
it&apos;s important to know that behind the scenes there&apos;s a lot going on
as the computer jumps from different bits of code back to other bits of
code. Hopefully if you type this in and run it, you should get a hello
and then a goodbye message. You could type putting in numbers or
anything you&apos;d like instead if you prefer.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 107. parameters (65) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image107.webp?raw=true"
  style="width:40%;"
  title="Parameters"
  alt="Parameters." />
</p>

Let&apos;s talk a little bit more about those parameters that I talked
about. Because sometimes some functions need a little bit of extra
information in order to perform its task.

Let&apos;s think about <b>getElementById</b>. That&apos;s not really going to work
unless you tell it which ID you&apos;re looking for. That&apos;s an extra piece
of information or a parameter that you need to provide. The important
thing to know is the names of the parameters for your functions,
they&apos;re not important, they&apos;re like variable names. You can call them
anything you want, as long as you&apos;re consistent.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 108. return values (66) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image108.webp?raw=true"
  style="width:40%;"
  title="Return values"
  alt="Return values." />
</p>

The next thing to talk about, when we talk about functions, are return
values. Some functions return values, others don&apos;t. But these values
can be used later for assignment statements or conditional expressions.
Later when we talk about forms, we&apos;re going to want to put in special
functions that will say, hey, I need you to halt execution right now,
because I don&apos;t want you to hit submit. I don&apos;t want you to be able to
hit yes on that form.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 109. example, return values (66) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image109.webp?raw=true"
  style="width:40%;"
  title="Example, Return values"
  alt="Example, Return values." />
</p>

Let&apos;s look an example of a function that returns a value. In this case,
I&apos;ve written a simple function that takes your message that you want to
say, hello or good afternoon, good morning, but we&apos;re going to follow
that up with a prompt. And that prompt&apos;s going to ask a person for
their name. We&apos;re combining a few different elements here. We start off
by saying, hey, I&apos;m going to make a variable called firstName, and I
want to set it to whatever the person types into the prompt. If over
here, if I don&apos;t have the term var, firstName would be left as
something that&apos;s empty. Using return statements are just typically used
in order to assign values to valuables or to check conditional
statements, and we&apos;re going to be using these a lot. I just need you to
be aware of the term.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 110. review, functions (67) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image110.webp?raw=true"
  style="width:40%;"
  title="Review, Functions"
  alt="Review, Functions." />
</p>

Let&apos;s review what we&apos;ve talked about with functions so far. Whenever
possible, use built in functions. Sometimes when people are first
learning how to program, they feel this need to write everything from
scratch to show that they really understand. There&apos;s really no point in
doing that at the beginning. If someone else has written a really good
function use it. You can practice your own skills by augmenting it or
adding little things.

When you do write your own function, try not to be too specific. And
what I mean by that is, don&apos;t write a function that you&apos;re not going
to be able to reuse multiple times in a lot of different scenarios.
Don&apos;t hard-code too many values so that it&apos;s so specific that it only
works for one person.

Finally, I just want to remind you, that function parameters can have
any name you want them to have. A lot of times people get caught up in
my examples, and think that&apos;s the only way to go. It&apos;s not the case.
Don&apos;t do everything exactly the way you see it online, or in my
examples. It gives you a lot more power if you change those parameter
names, to see how the inner workings are going.

We&apos;re going to be using functions a lot in this class. You&apos;re going to
be writing your own functions in the homework, and I&apos;m hoping that
you&apos;ll be able to do this and feel like you&apos;re really starting to
understand some of the power of JavaScript. Good luck.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-02">2.02 Code Placement (6:32)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 111. code placement (2.02) (68) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image111.webp?raw=true"
  style="width:40%;"
  title="2.02 Code Placement"
  alt="2.02 Code Placement." />
</p>

Today, we&apos;re going to talk not about new concepts, but really, putting
our code in the best place to make it easier for you to follow what&apos;s
going on.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 112. where to place the code (68) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image112.webp?raw=true"
  style="width:40%;"
  title="Where to Place the Code"
  alt="Where to Place the Code." />
</p>

Up to this point, we&apos;ve been putting our JavaScript into the HTML body
tag. Now, it&apos;s fine to start off that way, but as we get more and more
complex, it&apos;s going to make your life easier if we separate our content
from our other style in JavaScript functions.

In order to do that, we need to think about where we can put our
JavaScript code. And where you can put it, is you can leave it in the
body, as we&apos;ve been doing, you can put your functions into the head
section of your HTML code, or you can use an external file.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 113. in the head with script tag (69) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image113.webp?raw=true"
  style="width:40%;"
  title="In the head with script tag"
  alt="In the head with script tag." />
</p>

If you decide to put your JavaScript functions in the head section,
that&apos;s a really great idea, because they&apos;re separated from the content
and it makes it a little bit easier for you to follow the code that
you&apos;re writing. It doesn&apos;t make any difference to the actual
execution, but it just might make the debugging easier.

If you&apos;re going to use this method, you need to remember that you have
to use a script tag. Just as a style tag, tells the browser that your
about to add some style to your page. The script tag says. Wait, this
isn&apos;t content, this is going to be some JavaScript code.

If you do this. If you put your code into the head section, don&apos;t
worry, all of your function will still have access to all the document
information, the ID&apos;s, the classes, etc.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 114. code can be placed in the <head> (69) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image114.webp?raw=true"
  style="width:40%;"
  title="Code can be place in the head"
  alt="Code can be place in the head." />
</p>

Let&apos;s take a quick look at an example. As you can see, I have my head
section and inside there, I have this script ending, script in ending
head. You need to make sure that you have the proper tags, if you want
your code to validate. Inside this script, I put a very simple function
called message. Now, what you need to understand, is when I talk about
putting your JavaScript code into the head, I&apos;m only talking about your
JavaScript functions. It&apos;s still necessary, down here in the body of
your code to call the functions. But still, it&apos;s a lot cleaner than
having the entire function written down here. Plus, for code reuse, you
can now call the function multiple times, but only write it once up
here.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 115. javascript in an external file (70) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image115.webp?raw=true"
  style="width:40%;"
  title="JavaScript in an External File"
  alt="JavaScript in an External File." />
</p>

If instead, you decide to put your JavaScript functions in an external
file, then you can use that code multiple times in multiple files. The
one thing that&apos;s important to remember right from the start is again,
when you&apos;re using external file, don&apos;t use the script tag. It&apos;s just
the JavaScript, without any script tag.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 116. example, js in an external file (70) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image116.webp?raw=true"
  style="width:40%;"
  title="Example, JavaScript in an External File"
  alt="Example, JavaScript in an External File." />
</p>

Let&apos;s look at an example here. Here you can see, that inside the head
section, I&apos;ve gone in and I&apos;m done with my script. But instead of
writing the actual function, I&apos;ve gone ahead and give it a source
saying up, all my JavaScript is inside my JS folder, and here&apos;s the
name of the file that I want to use.

If for some reason this doesn&apos;t work, you want to make sure that
you&apos;re very careful about what you put right in here, you want to make
sure that this is exactly correct, because if the browser can&apos;t find
the file, then it&apos;s not going to be able to run your JavaScript. So,
let&apos;s say, you do have a typo in your link to your external JavaScript
file. Well, the problem with this, is that, it&apos;s actually harder to
realize what&apos;s going on. If you mess up in your HTML code or your CSS
code, it&apos;s usually pretty easy to figure out that you did something
wrong, because the colors aren&apos;t the way you wanted or your text just
isn&apos;t there. But with JavaScript, sometimes the changes you&apos;re making
are so slight, you don&apos;t even realize that you have a problem.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 117. debugging your code (71) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image117.webp?raw=true"
  style="width:40%;"
  title="Debugging Your Code"
  alt="Debugging Your Code." />
</p>

It&apos;s very important, as your code becomes more and more complex, that
you&apos;re using the console to debug your code. The console really is your
friend. I can&apos;t stress enough how much you always want to have it on
while you&apos;re coding. Myself, sometimes I forget to turn it on and I&apos;m
annoyed later, when I could have found my errors so much more easily.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 118. codepen (71) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image118.webp?raw=true"
  style="width:40%;"
  title="CodePen"
  alt="CodePen." />
</p>

Another way that we can talk about separating your code into this
external file from your HTML, is to use these different types of
software options, such as CodePen. When you use CodePen, you&apos;re able to
separate, have a separate window for your HTML, your CSS, and your
JavaScript. What&apos;s great about this is, it lets you see all of your
code at once and see in real time what&apos;s happening as you change that
code. The downfall of this, for when you&apos;re first getting started, is
that, I find that sometimes people don&apos;t realize that they don&apos;t
understand how to link their code, out there in the real world.

If you&apos;re going to use CodePen, I always recommend that once you&apos;re
done, take that code and put it into three separate files, so that
you&apos;re sure you know how to link them together.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 119. split up code in codepen (72) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image116.webp?raw=true"
  style="width:40%;"
  title="Split up code in CodePen"
  alt="Split up code in CodePen." />
</p>

Let&apos;s take a look. As you can see here, I have one window for my HTML
code. One, for my CSS and one for my JavaScript. And code pen, takes
care of all the work of making sure that they&apos;re all together. If this
is your first time ever using CodePen, I did want to point out, that
there&apos;s this handy little function, that you can re-size the windows.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 120. focus on html and css (73) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image120.webp?raw=true"
  style="width:40%;"
  alt="." />
</p>

If you&apos;re not too concerned with your CSS right now, you can make that
smaller. And really kind of focus, on what you&apos;re working on, in the
HTML and the JS.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 121. review, code placement (73) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image121.webp?raw=true"
  style="width:40%;"
  title="Review, Code Placement"
  alt="Review, Code Placement." />
</p>

All right, let&apos;s review what we talked about today. The first thing, is
that you need to feel comfortable with the idea that your JavaScript
code can appear in the head. Or the body of your code, or very often in
both. Code, can also be placed in an external JavaScript file. If you do
this, just make sure that you&apos;ve linked the files correctly together,
otherwise you might have some issues trying to figure out why your code
isn&apos;t working. Luckily, the console can tell you, if it can&apos;t find
that file and it leads you down the right path to fixing your code.

Personally, I always develop in the same file. I tend to have my HTML
and my JS in the same file, while I&apos;m doing my testing. Once I&apos;m done,
I move it out into an external style sheet. It&apos;s really up to you to
determine which style you like best. Whether you like your JavaScript in
the same file or in a separate file. There are benefits to both. And the
most important thing for you right now, is to develop the confidence
that you can get your JavaScript working, in whatever way, it best suits
you. Good luck.

<h3>Organizing Your Code</h3>

<h3>Code Placement</h3>

When you write code, it is important to get into the good habits of
organizing your code. While there are no specific rules about how and
where to place your code, there are definitely conventions. (Conventions
are suggestions that most programmers follow. This way other programmers
can quickly and easily understand their code.)

The most common organization is to have one main folder with your HTML
files in it. There are also three subfolders (folders inside the main
folder) for your CSS, image, and JavaScript files.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 122. folder with subfolders nested within (74) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image122.webp?raw=true"
  style="width:40%;"
  title="Folder with subfolders nested within"
  alt="Folder with subfolders nested within." />
</p>

When we use CodePen we use that idea of separating our code. However, be
aware that CodePen doesn&apos;t require many of the things you should have
in your code. For instance, in the HTML files it ignores all of the
information in the &lt;head&gt; section. So, if you develop in CodePen, make
sure to test your code later using the proper folder/file structure. You
will need to include links to the style sheets, images, and any external
JavaScript files.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-03">2.03 Folder Structure / Organizing Your Code (5:33)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~ 123. folder structure / organizing your code (2.03) (75) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image123.webp?raw=true"
  style="width:40%;"
  title="2.03 Folder Structure / Organizing Your Code"
  alt="2.03 Folder Structures / Organizing Your Code." />
</p>

I know that one of the most frustrating things that can happen when
you&apos;re designing and developing your webpage is when you just can&apos;t
get your code to talk to one another. If you&apos;ve written some HTML, and
you&apos;re trying to link it to your style sheet, and they just don&apos;t seem
to recognize each other. Today, we&apos;re going to talk about how web
designers tend to organize and separate their code into different parts.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 124. folder structure (75) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image121.webp?raw=true"
  style="width:40%;"
  title="Folder Structure"
  alt="Folder Structure." />
</p>

First, we always start off with a main folder that&apos;s going to hold your
HTML code. In addition to your code, you&apos;re going to have a folder for
your CSS, your images, and if you&apos;re doing it yet, your JavaScript code
as well. Organizing your code into these separate folders, CSS,
JavaScript, images, it&apos;s not a rule. Your page will still work even if
you have everything inside one big folder. But as you go on in web
design, your fellow designers are going to expect that you have similar
conventions to their own. you want to get used to doing things the right
way, right from the beginning.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 125. conventions in organizing code (76) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image125.webp?raw=true"
  style="width:40%;"
  title="Conventions in organizing code"
  alt="Conventions in organizing code." />
</p>

Here I&apos;ve got a quick picture of how I could organize the code using
these different folders. I have ProjectOne, ProjectTwo, and
ProjectThree. Here in ProjectThree is where I really want to look at
what we&apos;re doing. As you can see, I&apos;ve got an html file, an html file,
all four of my html files. In addition, though, I have my css, my
images, and any JavaScript. We want to make sure that all these
different files can talk to one another. And so, we&apos;re going to use the
convention here, and I&apos;m going to show you how to make sure they can
link together in the right way.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 126. linking from an html file (76) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image126.webp?raw=true"
  style="width:40%;"
  title="Linking from an HTML file"
  alt="Linking from an HTML file." />
</p>

2^nd^ line should be: <b>&lt;script
src="js/javaFunctions.js"&gt;&lt;/script&gt;</b>

Let&apos;s say that inside your HTML file, you want to link to your style
sheet, your Java functions, and perhaps a picture. Well, this is the way
you&apos;re going to do it. When you link to your style sheet, you want to
make sure you include your CSS folder. You don&apos;t need any other folder,
just that one. But be careful, if you called it css lower case, make
sure your link says css lower case, not upper case. When it&apos;s time to
link to your java files, you do the same thing. Make sure you start the
link with that js. What this does is it tells the browser, hey, I need
this file right here, but in order to find it, go into the JavaScript
folder first, right?

Finally, the same thing, when it&apos;s time to link to an image, make sure
you link to your image folder first. Now the images folder is the one
that tends to have the most variance in the name. Some people call it
image, some call it images. Another kind of common name is to call it
img. When you&apos;re linking your code with other people&apos;s code, make sure
you do a quick check. And make sure that your folder names CSS,
JavaScript, and images match what other people are expecting.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 127. linking from a css file (77) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image127.webp?raw=true"
  style="width:40%;"
  title="Linking from a CSS file"
  alt="Linking from a CSS file." />
</p>

When it comes to linking from your style sheet, it can be a little bit
trickier. In the example I have here, we want to link to this holiday
picture right here, all right? Now we know that the file isn&apos;t in the
CSS folder. It doesn&apos;t belong there. Pictures should be in the images
folder. But the problem is, how do you tell the browser that the images
folder is someplace different? In this example we go up 2 directories,
find &apos;images&apos; folder and pull from there. Done & done.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 128. debugging (77) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image128.webp?raw=true"
  style="width:40%;"
  title="Debugging"
  alt="Debugging." />
</p>

If things aren&apos;t working for you in your folder structure, here&apos;s a
few tips you can do just to see if we can find out where the issue is.
First, if the link isn&apos;t working for you, check to make sure that you
spelled the file name correctly. Case matters, upper case, lower case,
it can make a big difference. You also want to make sure that the files
are in those correct CSS, JS, or images (img) folders.

Finally, and this is a big one. As people tend to mess up on their code,
they open up new versions of the files. It never ever ceases to amaze me
how many times that I&apos;ve done this myself, where I&apos;m working on a
file, I&apos;m making changes, and they&apos;re just not showing up in the
browser. Almost all the time it&apos;s because I&apos;m working on a bad copy.
I&apos;m hoping that this is going to help you understand a little bit more
how you can organize your code to make the best use of the different
CSS, JavaScript, and images functions out there. Thanks.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-04">2.04 Events (10:05)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 129. events (2.04) (78) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image129.webp?raw=true"
  style="width:40%;"
  title="2.04 Events"
  alt="2.04 Events." />
</p>

Hi everybody. One of the things we promise you in this course was that
we&apos;d teach you how to do interactivity with JavaScript. Well, we
finally reached that point where we can start having some fun and
reacting to events that happened to your web page.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 130. adding the interactivity! (79) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image127.webp?raw=true"
  style="width:40%;"
  title="Adding the interactivity!"
  alt="Adding the interactivity!" />
</p>

Up to now it has been up to us to decide when the functions should
execute. In our code, we put the script tags and we call those
functions. Well now, what we want to do, is we want to take advantage of
the fact that we can call these functions based on special events. Where
do these events come from, well, they come from the JavaScript API. We
can start doing things based on clicking, mouse movement, all these
different types of dynamic function calls. Let&apos;s take a look at how we
can do this.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 131. events (79) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image131.webp?raw=true"
  style="width:40%;"
  title="Events"
  alt="Events." />
</p>

First, let&apos;s talk about just some of the events that we normally react
to on a web page. The first one is <b>onclick</b>, it&apos;s very
straightforward, if the user clicks on an HTML element, we want
something JavaScript function to execute. We can also have
<b>onmouseover, onresize</b>, and a very common one is <b>onload</b>.

This last one says whenever the page is loaded, I want to call some
JavaScript functions or run some sort of JavaScript code, but please
don&apos;t do it until the page is completely done. The reason that this one
is a little bit more interesting to me, is that sometimes students have
problems in that they try to write JavaScript. But the page that they
are trying to apply the JavaScript to, is so complex and takes so long
to load that the JavaScript is done before the user can even see the
page. This last one onload we are going to use quite a bit to make sure
we are all seeing the exact same events.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 132. events, how it works (80) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image132.webp?raw=true"
  style="width:40%;"
  title="Events, How it Works"
  alt="Events, How it Works." />
</p>

All right, so how does this work? We know that any element can react to
an event. Well, we need to add code to our HTML that links the events
and the tags together. Here&apos;s an example for you. Here, I have my tag
div, simple HTML five tag but I&apos;ve added this event right here that
says on click.

Now the browser&apos;s changed, the browser is what I say listening. It&apos;s
listening, listening to this one div and saying okay, if anybody clicks
on this then I am going to call the JavaScript function message. All
right, this isn&apos;t going to happen just once, this is going to happen
for the duration that this site is loaded onto the browser.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 133. example, using quotes (80) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image133.webp?raw=true"
  style="width:40%;"
  title="Example, Using Quotes"
  alt="Example, Using Quotes." />
</p>

One of the things that we need to talk about is the use of quotes. When
we have our event such as <b>onclick</b> equals message function or
<b>onclick</b> equals add function, anything like that we need to put the
function inside quotes. And you can use single quotes or double quotes
in order to do this. However, I always use double quotes because it
makes it much easier if I want to pass string arguments to the function.
If you take a look down here, you can see I want to call the function
called message and I need to send it this Hi message.

Well, if I&apos;d done it this way <b>(&lt;div onclick='message('Hi')'&gt;</b>)
equals message with a single quote. And then, what&apos;s going to happen
when I try to send my screen? As soon as I add another single quote the
browser goes, that&apos;s the end, it matches there&apos;s your whole string.

If you&apos;re going to be matching different strings together, put the
outer one in double quotes and he inner one in single quotes and it&apos;s
going to make it much easier for your browser to understand what&apos;s
going on.

Be careful copying and pasting quotes when you&apos;re coding. It&apos;s a very
common thing to do but it&apos;s important to remember that a lot of times
your editor gets mixed up. Because when you&apos;re coding, you don&apos;t have
that same kind of slant that Word, PowerPoint, and other programs put
into your quotes. Whenever you copy and paste, go back and make sure
that they&apos;re matching up correctly.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~ 134. getelementbyid('output').innerhtml = msg + " event"; (81) ~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image134.webp?raw=true"
  style="width:40%;"
  title="document.getElementById('output').innerHTML = msg + ' event';"
  alt="document.getElementById('output').innerHTML = msg + ' event';" />
</p>

Let&apos;s take a look at what I do with this code right here. I have my
HTML on one side and my JavaScript function on the other. The JavaScript
function&apos;s pretty simple, all it is going to do is take a string, and
it&apos;s going to update the output element to show whatever that string is
along with the word event.

Over here in the HTML is where it&apos;s going to get a little bit more
interesting and it&apos;s going to be the first time we&apos;re using events, I
have three. I have <b>onload</b>, which means hey whenever I load this
page, I want you to call the message function and send it the message
load. I have <b>onresize</b> which means if I change the size of the
browser, I want to send a different message and then finally the last
one is <b>onclick</b>. All three of these events, <b>onload, onresize,
onclick</b>, they&apos;re all going to call the message function, but they&apos;re
going to call it with three different frame runners.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 135. when loaded, load event shows up (82) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image135.webp?raw=true"
  style="width:40%;"
  title="When loaded, load event shows up"
  alt="When loaded, load event shows up." />
</p>

Let&apos;s take a look at what&apos;s going on. As you can see, when I loaded
the page, it automatically had LOAD event show up.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 136. click paragraph, click event shows up (82) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image136.webp?raw=true"
  style="width:40%;"
  title="When click paragraph, click event shows up"
  alt="When click paragraph, click event shows up." />
</p>

What happens if I click on this paragraph right here? Oh, it changes to
click event. It&apos;s actually happening over and over again; you just
can&apos;t tell because it&apos;s so quick.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 137. resize page, resize event occurs (83) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image137.webp?raw=true"
  style="width:40%;"
  title="When resize page, resize event occurs"
  alt="When resize page, resize event occurs." />
</p>

Now, the last thing I&apos;m going to do is I&apos;m going to resize the page
and you can see, that it recognizes that there is a resize event. So,
it&apos;s pretty simple to go through, and I&apos;ll go back here, and had your
HTML actually change based on the different events.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 138. click button, button event occurs (83) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image138.webp?raw=true"
  style="width:40%;"
  title="When click button, button event occurs"
  alt="When click button, button event occurs." />
</p>

The second example is, again, a very straightforward way of showing you
how the events can be linked to different element types. One HTML
element we haven&apos;t used a lot in my courses is <b>button</b>. I avoid
using it because I think that the semantics of a <b>button</b> tag really
conveys this idea of click me and I&apos;m going to do something, and since
we didn&apos;t have the power to do that yet, I really didn&apos;t want to use
that element, but now we can.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 139. javascript date function (84) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image139.webp?raw=true"
  style="width:40%;"
  title="JavaScript date function"
  alt="JavaScript date function." />
</p>

What I have here is a simple JavaScript function that says, hey I want
you to call the JavaScript <b>date</b> function, this is something that I
didn&apos;t write. You know that it was written by JavaScript partly because
well, it&apos;s yellow.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 140. onclick button, displaydate() (84) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image140.webp?raw=true"
  style="width:40%;"
  title="onclick button, displayDate()"
  alt="onclick button, displayDate()." />
</p>

All right, so I&apos;m going to use this function and connect it with the
<b>button</b>. So, I have <b>button</b> type equals <b>button</b> and I have
<b>onclick</b> equals <b>displayDate()</b>.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 141. example, js date function, onclick (85) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image141.webp?raw=true"
  style="width:40%;"
  title="Example, JS displayDate(), onclick"
  alt="Example, JS displayDate(), onclick." />
</p>

As soon as I click on that, we want to keep our eye on where it says
this is a paragraph, because when I click on it that should be updated
to what the current date in time is for when I&apos;m running this. All
right. Now, there&apos;s a good chance that this date doesn&apos;t look exactly
the way you expect it. Don&apos;t forget, computers are very specific, and
they&apos;re going to give much longer answers than we&apos;re usually used to.

As we start adding JavaScript events and reacting to events to our code,
I just want you to be aware of something that&apos;s going on, that&apos;s
really quite complex.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 142. events change the program flow (85) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image142.webp?raw=true"
  style="width:40%;"
  title="Events Change the Program Flow"
  alt="Events Change the Program Flow." />
</p>

Before JavaScript, for the most part, our programs ran in a linear
order, it would start at the top and execute each statement step by
step, one by one and everything was really only executed once. But now
that we have events, we&apos;re really causing the program to what I want to
say, run continuously. Because soon as I add that event, the DOM is now
always going to be listening for those events. The API is saying, all
right I need to wait on click, onclick, onclick. If you add too many
events to your page, you could conceivably slow down the execution of
your page.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 143. more events; mouse, keyboard, frame & more (86) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image143.webp?raw=true"
  style="width:40%;"
  title="More Events; Mouse, Keyboard, Frame and more"
  alt="More Events; Mouse, Keyboard, Frame and more." />
</p>

Clearly there are a lot more events than just the four I told you about.
We tend to categorize these events into groups. We have mouse events
where you can react to onclick, double click, mouse enter or mouse
leave, mouse move, you can react to keyboard events. You can actually
listen for certain keys to be pressed down or the least. There&apos;s also
what we call frame events, and we&apos;ve looked at two of those already.
You can do onload, onresize, you can react to scrolling on your page or
even if there&apos;s an error.

If you want a more comprehensive list of events, you can really go
anywhere online, but I went ahead and I&apos;ll link one for you in the
course page, that goes directly through Mozilla. It is
<https://developer.mozilla.org/en-US/docs/Web/Events>.

The important thing to know is that you&apos;re not expected to know all of
the events, it&apos;s something we&apos;re going to learn over time. Hopefully,
you&apos;ve got this little idea of what events do and how you can start
using them to add a little bit of interaction with your page. Without
these events JavaScript can be limited in its ability to interact with
the DOM. We didn&apos;t have onclick, onload and be really hard to actually
work with our webpages.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 144. review; events (87) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image144.webp?raw=true"
  style="width:40%;"
  title="Review; Events"
  alt="Review; Events." />
</p>

Another thing I&apos;d like you to take away from this is while events are
really cool, they are also very annoying. It&apos;s possible to put a
listener on every paragraph of your page or every dip and have cool
things happening all the time. But after a while, the usability of your
page is really going to take a hit.

I know I&apos;ve said it before, but don&apos;t worry about memorizing all the
different events. As you code, certain needs will arise and you&apos;ll say,
I wonder if there&apos;s an event for that, I&apos;m going to go look it up.
What I&apos;m much more concerned about at this point and hopefully you are
to is gaining the basic idea of, I know how events work, I&apos;m going to
try to implement one. And when a problem arises, as it probably will, I
can kind of fight my way through and make it work, just don&apos;t forget.
We&apos;re there on the message boards. We&apos;re happy to all work as a team
to make sure that your page is doing the types of cool things that you
want it to do. Good luck.

This is a great time for you to write some code!!! Open your editor (or
CodePen) and write a small program that pops up an alert message when
you load the page. Or better yet, change the content of your page to the
current Date every time you open the page. Once you are done, compare
your answer to an example I have here:
<http://codepen.io/ColleenEMc/pen/vLEJjq>

<h3>Mastering Events and Functions</h3>

<h3>Events</h3>

The rest of the material is more and more examples of using Events and
functions in JavaScript. If you are a little worried that you don&apos;t
understand them after the first module, that is fine. Just read all the
way through, try to play with some of the code, and then read them
again. It isn&apos;t uncommon for it to take a few weeks to make sense.
Since we only have four weeks in this course you may find that you are
sometimes able to make the code work, without fully understanding the
details. That happens a lot. Programming is something that comes with
time and practice. And then suddenly the moments of &quot;Hooray&quot; start to
outnumber the times that you are stuck.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-05">2.05 Code With Me -- Events (7:46)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 145. code with me -- events (2.05) (88) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image145.webp?raw=true"
  style="width:40%;"
  title="2.05 Code With Me -- Events"
  alt="2.05 Code With Me -- Events." />
</p>

Hi everybody, welcome back. It&apos;s time for us to take some of the things
we&apos;ve been learning and put them into practice. One of the most
important things about learning a programming language is making sure
that you&apos;re getting your hands-on experience. Reading these modules
just isn&apos;t enough. It&apos;s great if you just want to learn about
JavaScript or learn about these different elements at a very high level.
But if you actually want to feel competent and confident in your coding,
you need to make sure that you&apos;re practicing. Let&apos;s dive into the
code. I want you to modify the code. And whenever possible, it&apos;s great
if you can break the code. Because it&apos;s always better to make your
errors now. We have the whole community around you. You can ask
questions.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 146. examples, events - modify dom & change style (89) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image146.webp?raw=true"
  style="width:40%;"
  title="Examples, events - modify DOM &amp; change style"
  alt="Examples, events - modify DOM &amp; change style." />
</p>

We&apos;re going to look at two different examples today. One, in which
we&apos;re going to modify the DOM. And the second, we&apos;re actually going to
change the style of the page that we&apos;re looking out right now. Let&apos;s
get started. In this example, I&apos;m going to do something a little bit
different then we&apos;ve done before. When I first introduced the idea of
events, I said that events are matched with functions. Well, you can
also match events just with JavaScript code, not a function itself.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 147. modifying the dom (89) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image147.webp?raw=true"
  style="width:50%;"
  title="Modifying the DOM"
  alt="Modifying the DOM." />
</p>

Here I&apos;ve created two buttons, and I named them First and Second. You
are going to use those buttons to change the content of this third
paragraph right down here. When I click on this First button I have
onClick, grab that element, change the innerHTML, and I want you to
change it to Clicked First Button. The other one is very similar. The
only difference is that I want to change the content of that paragraph.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 148. onclick, update second button's innerhtml (90) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image148.webp?raw=true"
  style="width:50%;"
  title="onclick, update second button's innerHTML"
  alt="onclick, update second button's innerHTML." />
</p>

When I click on these buttons this, right here, is the element I want you to 
look at.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 149. onclick first button (90) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image149.webp?raw=true"
  style="width:50%;"
  title="onclick first button"
  alt="onclick first button." />
</p>

Let&apos;s click on the First button. You can see that I clicked, it said,
hey I know that I just clicked the First button.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 150. onclick second button (91) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image150.webp?raw=true"
  style="width:50%;"
  title="onclick second button"
  alt="onclick second button." />
</p>

When I click on the second one, you know that I&apos;ve clicked on the
Second button. This seems like a really small program to write, but
there&apos;s a lot going on in here, and a lot of places where people tend
to make mistakes. Let&apos;s just look at them quickly.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 151. modify the dom w/getelementbyid (91) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image151.webp?raw=true"
  style="width:50%;"
  title="Modify the DOM onclick with getElementById('stuff').innerHTML"
  alt="Modify the DOM onclick with getElementById('stuff').innerHTML." />
</p>

The first thing I want you to look at is this idea of using
document.getElementById. Whether or not you have these as upper- or
lower-case letters, makes a big difference. If you accidentally change
it from ById to ID as uppercase, this is going to cause problems in your
code.

The other thing I see a lot of people do, is they think that innerHTML
is a method, just like all the other ones are. It&apos;s not. When you&apos;re
using innerHTML, you need to make sure you use those equal, that
assignment statement, okay? The other thing that I feel sometimes people
really get kind of hung up on is the code that I give them. You can put
anything you want in here. Let&apos;s change some things. First thing I want
you to look at is this line right here. If I were to change this, I want
you to intuitively know before I do it what part of this page is going
to change. Is it the event that&apos;s going to change? Is it the button
that&apos;s going to change? Is it the whole page? So luckily, with CodePin
you&apos;ll be able to see it immediately. All right, wow, now I really.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 152. modify the dom using getlementbyid (92) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image152.webp?raw=true"
  style="width:50%;"
  title="Modify the DOM using getElementById"
  alt="Modify the DOM using getElementById." />
</p>

That&apos;s how I can change the button itself. If I want to change what&apos;s
going to happen, that where I put in here, Clicked Another Button.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 153. buttons first and third (92) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image153.webp?raw=true"
  style="width:50%;"
  title="Buttons first and third"
  alt="Buttons first and third." />
</p>

Let&apos;s save. I&apos;m going to click on First, Second.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 154. buttons first and third, on-click (93) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image154.webp?raw=true"
  style="width:50%;"
  title="Buttons first and third, on-click"
  alt="Buttons first and third, on-click." />
</p>

Play with this. Try putting it in yourself. And realize, again, that you
can put your JavaScript anywhere you want, it doesn&apos;t always have to be
in an external file.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 155. open and close paragraphs using buttons (93) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image155.webp?raw=true"
  style="width:50%;"
  title="Open and Close paragraphs using Buttons"
  alt="Open and Close paragraphs using Buttons." />
</p>

Let&apos;s look at the next example. Okay, get ready. This example is going
to be a big one, because we do have a lot of things going on. We have
our HTML. We have our CSS. And we have our JavaScript.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 156. css class closed, open (94) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image156.webp?raw=true"
  style="width:50%;"
  title="CSS class closed, open"
  alt="CSS class closed, open." />
</p>

Let&apos;s start with the CSS, because it&apos;s the simplest and it&apos;s not
going to change as this program runs.

I&apos;ve declared two classes. One called <b>.closed</b>, and one called
<b>.open</b>, and what they do is, well, it&apos;s pretty straightforward. The
<b>.closed</b> one says, I want to change the display to none. What&apos;s
going to happen is, right down here, this one right here, it&apos;s going to
disappear. However, if I were to set the class to <b>.open</b>, well, then
now it&apos;s going to reappear again. That&apos;s all we really need to
realize, is that .closed will make it go away, .open is going to make it
come back.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 157. html, p id='demo', open & close (94) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image157.webp?raw=true"
  style="width:50%;"
  title="HTML, p id='demo', open &amp; close"
  alt="HTML, p id='demo', open &amp; close." />
</p>

Over here, in my HTML, I have a paragraph called demo. And that&apos;s right
down here, it&apos;s all this entire thing we can see right here. This is
the one we want to change in our code.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 158. html, onclick openme, or onclick closeme (95) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image158.webp?raw=true"
  style="width:50%;"
  title="In HTML, buttons onclick, openMe() or closeMe()"
  alt="In HTML, buttons onclick, openMe() or closeMe()." />
</p>

And finally in the HTML, we have two events. We have <b>onClick,
openMe</b>, and <b>onClick</b>, <b>closeMe</b>. Let&apos;s see how we can write the
JavaScript that will make that div appear and disappear. Let&apos;s start
with closeMe. I&apos;ve actually put two different options here. The code
looks a little bit longer than you might expect. What I need to do, is I
simply need to grab the demo element by doing document.getElementById.
But now instead of trying to change the inner HTML, I&apos;m going to change
the style.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 159. js function, closeme (95) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image159.webp?raw=true"
  style="width:50%;"
  title="In JS, function closeMe()"
  alt="In JS, function closeMe()." />
</p>

I go in and I say x, which is my element, <b>.style.display=&quot;none&quot;.</b>
I&apos;m not using my CSS, I&apos;m actually hardcoding it in here that I want
it to go from none.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 160. js function, openme (96) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image160.webp?raw=true"
  style="width:50%;"
  title="In JS, function openMe()"
  alt="In JS, function openMe()." />
</p>

And in open, similarly, it says, hey grab that element, and I want it to
go from whatever it used to be, and now it should be block.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 161/162. test, buttons close & open (96) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image161.webp?raw=true"
  style="width:45%;"
  title="Test, buttons close & open paragraph"
  alt="Test, buttons close & open paragraph." />
<img src="./images/image162.webp?raw=true"
  style="width:45%;"
  title="Test, open & close paragraph using buttons"
  alt="Test, open & close paragraph using buttons." />
</p>

Let&apos;s look and see if this works. Close, Open. Close, Open. Great, it
works, but we&apos;ve hardcoded those elements in. We&apos;ve hardcoded block.
What if we also wanted to change the color, or the width, or many other
elements? This is where the idea of our classes can come in.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 163/164. get element & change class (97) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image163.webp?raw=true"
  style="width:45%;"
  title="x=document.getElementById('demo'); then x.className='closed';"
  alt="x=document.getElementById('demo'); then x.className='closed';" />
<img src="./images/image164.webp?raw=true"
  style="width:45%;"
  title="x=document.getElementById('demo'); then x.className='open';"
  alt="x=document.getElementById('demo'); then x.className='open';" />
</p>

Let&apos;s change it over here really quickly. I&apos;m going to comment out
this line of code. And same right here. All I&apos;ve done here, is we&apos;re
going to have the same element, but the difference is now, we can
actually go in and we could say, you know what? For that element I want
you to change the class name. I don&apos;t know what it used to be, but now
I want it to be closed. And down here, I want it to be open.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 165/166. test, change style of html (97) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image165.webp?raw=true"
  style="width:45%;"
  title="Test, change style of HTML element"
  alt="Test, change style of HTML element." />
<img src="./images/image166.webp?raw=true"
  style="width:45%;"
  title="Test, open/close paragraph using buttons"
  alt="Test, open/close paragraph using buttons." />
</p>
So, I can talk a lot. But it&apos;s important that even I stop and check
that code and make sure I didn&apos;t break it. Close, Open, Close, Open.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 167. review; code with me - events (98) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image167.webp?raw=true"
  style="width:40%;"
  title="Review; Code With Me - Events"
  alt="Review; Code With Me - Events." />
</p>

Now I don&apos;t really have time to do this right now, but I think what
would be a great exercise for you, is to look at this code using
<b>Inspect Element</b>. When you do that, and you click on those Open and
Close buttons, you can really see that we&apos;re going in there and we&apos;re
changing the DOM. All those things, all those different styles, you can
see them in effect. Make sure you&apos;re playing with this as you&apos;re
coding along with me. I could review with you what we just did, but I&apos;m
not going to.

The most important thing for you to do right now, is stop reading this
module and bring up some sort of editor code bin, and go in there and
start coding. If you don&apos;t do it now, you might start falling behind as
we get into these more complex ideas. So, good luck.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-06">2.06 "this" (9:30)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 168. 'this' (2.06) (99) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image168.webp?raw=true"
  style="width:40%;"
  title="2.06 'this'"
  alt="2.06 'this'." />
</p>

Hi everybody, welcome to my personal least favorite lecture of all time.
It&apos;s the lecture where I try to explain the word this, and how it&apos;s
used in programming languages. The only reason I don&apos;t enjoy this
lecture, is that I find it extremely difficult to talk about the word
this without using the word this. Try your best to follow along. And
I&apos;ll do my best to make sure I&apos;m as clear as possible.

Why do we even need to use special key words? Well, because a key to
smart programming is using different functions. You don&apos;t want to write
your own code. You want to use somebody else&apos;s code. But a common road
block, especially for new programmers, is trying to figure out.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 169. referring to elements (99) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image169.webp?raw=true"
  style="width:40%;"
  title="Referring to Elements"
  alt="Referring to Elements." />
</p>

How can I write a function so that I can reuse it over and over again?
How can I write this function so that different elements can use it? But
the function knows basically, how do I know what information to use.
That&apos;s where "this" keyword comes in.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 170. example, 'this' (100) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image170.webp?raw=true"
  style="width:40%;"
  title="Example, 'this'"
  alt="Example, 'this'." />
</p>

This allows an element to refer to itself. Every object in the DOM, has
an automatically generated this. This "this" attribute allows you to
access an element&apos;s info. Without "this", it would be very difficult
for functions to know what data to use. This is also used in outside
functions.

Let me draw up something really quickly, before we get to more explicit
examples. When you&apos;re writing code, if you were to say have an A tag.
And somewhere along the lines you say onclick. And you want to write a
function. How do you tell the function that you want to use this
particular a tag? As opposed to other a elements that might be in the
program? Well, you can go ahead, and you can somewhere put the word this
in here. Whenever the computer sees the word this, boom. What it&apos;s
going to do is it&apos;s just going to backtrack and go back, back, back,
back, back, back, back, back until it&apos;s, oops, here&apos;s an open tag.
They must be referring to this DOM element right here.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 171. sample html, js with 'this' (100) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image171.webp?raw=true"
  style="width:50%;"
  title="Sample code HTML, JS with 'this'"
  alt="Sample code HTML, JS with 'this'." />
</p>

Let&apos;s look at what I hope are a few simple examples of using the word
this. Right here I have four different elements on my page. I have two
awesome pictures from the 80s and the 70s. And then, I also have a few
divs with some text within it, right here.

Each one of these elements has been associated with an event. And I want
to show you how I can use the word this. So that the events can be very
specific to the element I&apos;m click on. Let&apos;s start by looking at this
picture right here. In the html code you can see that I have source
check. I have alt text check, and I also have an event that says on
click. I want you to log to the console the alt text of this particular
element. As soon as the computer sees the word this. It&apos;s going to back
up, until it gets to the image. And then we&apos;ll say. They want the alt
text for this image. Let&apos;s see what happens when I actually click on
this image.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 172. test console, awesome 80's haircut (101) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image172.webp?raw=true"
  style="width:50%;"
  title="Test console, awesome 80's haircut"
  alt="Test console, awesome 80's haircut." />
</p>

As you can see, as soon as I clicked on it. The message Awesome 80&apos;s
haircut shows up, all right? If I were to click on this multiple times.
It doesn&apos;t actually show up in the console multiple times.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 173. div onclick = 'console.log(this.innerhtml)' (102) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image173.webp?raw=true"
  style="width:50%;"
  title="div onclick='console.log(this.innerHTML)'"
  alt="div onclick='console.log(this.innerHTML)'." />
</p>

You can see that there&apos;s a little number over here that says. Oh, this
has happened four times in a row. But the important thing is that, I
click on an image and the event knew that this was the image I was
clicking on.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 174. div onclick, this, innerhtml (102) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image174.webp?raw=true"
  style="width:50%;"
  title="div onclick='console.log(this.innerHTML)'"
  alt="div onclick='console.log(this.innerHTML)'." />
</p>

Let&apos;s look at the next example down here. I&apos;ve got my div that just
says, hi there. Checking out a div. I&apos;m looking at the second example
right here. On this one, I want I want to do something similar, but divs
don&apos;t have alt text. Instead, what I said to do is, log the inner html.
When I click on this div, I&apos;m expecting to see, hi there, checking out
the div to show up in the console.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 175. test, console.log 'this' (103) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image175.webp?raw=true"
  style="width:50%;"
  title="Test, console.log 'this'"
  alt="Test, console.log 'this'." />
</p>

As you can see, it&apos;s working. These first two examples are very
similar. And that all I&apos;m doing is basically kind of manipulating
what&apos;s going on in the console.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 176. function displayid(element) log id (103) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image176.webp?raw=true"
  style="width:50%;"
  title="function displayId(element){ console.log(element.id);}"
  alt="function displayId(element){ console.log(element.id);}." />
</p>

In these last two, I did something very similar. But instead of just
using on-click do something. I&apos;m going to use this function on the
right. Here&apos;s a great example of code reuse. The first few examples,
concept only. This one I want to show you how I can use this same
function called <b>displayID</b> on different elements. On my family
Christmas photo down here, you can see that I have an id of ID-1. On
this picture over here, I have an id of ID-2. My hope is that they can
both use the same exact function called displayID. And even though
they&apos;re using the same function, it&apos;s actually going to show different
results.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 177. inspect log console, onclick display id (104) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image177.webp?raw=true"
  style="width:50%;"
  title="Inspect log console, onClick displayId of 'this'"
  alt="Inspect log console, onClick displayId of 'this'." />
</p>

Let&apos;s see what happens when I start to click. ID-1, ID-1, ID-2, ID-2.
Here&apos;s a simple example of us using onClick along with a function and
the keyword, this, to provide different data. I want to show you though,
a slightly more colorful example. That I think also makes this point
really well.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 178. function showproperties (104) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image178.webp?raw=true"
  style="width:50%;"
  title="function showProperties of element, display alt text of images"
  alt="function showProperties of element, display alt text of images." />
</p>

In this example let&apos;s start off with the JavaScript. I have a
function called showProperties. And it is expecting to be sent some sort
of element. Remember, I can call this parameter anything I want. I can
call it element, I can call it e, I can call it elem. It doesn&apos;t matter
to the computer. As long as it makes sense to you, the general idea
that. Oh, I think I&apos;m going to be passed a DOM element here.

Once you get inside the function you can do <b>document.getelementbyid</b>.
Basically, what it&apos;s doing is it&apos;s grabbing this section of my html.
Stating I want to change what&apos;s showing up inside that little box. What
do I want to change it to? I want to change it to the alt text of
whatever element is being sent to me. I&apos;m going to stop here and pause
just for a second. Because this is a great place for you to think. All
right, she&apos;s talking about alt text. So that probably means the element
is going to be a picture. Because if it ends up being a div or a
paragraph, this won&apos;t break but nothing&apos;s going to happen. Now, I&apos;m
going to show you the cool part of this. On each one of these elements,
I have shown property and the keyword this which says send this image
that I am hovering over with my mouse and call that property.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 179. test, hover showproperties, alt text (105) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image179.webp?raw=true"
  style="width:50%;"
  title="Test, hover showProperties, alt text"
  alt="Test, hover showProperties, alt text." />
</p>

Let&apos;s take a look and see how this works. I&apos;m going to hover over the
first picture of my dog. And I am really hoping that the alt text
associated with this picture is going to show up in the preview, and it
did. I hover over another picture, and I get with my boy. And then
finally, in the last picture you can kind of see how once again the alt
text is being displayed inside the preview. I&apos;ve done something really
simple here. And what you&apos;re going to do in one of the homework is
expand on this idea and say. Not only do I want to change whatever text
is showing up in here. I actually want to change this whole picture. So
go back.

Follow this more complex example of using the keyword this that you can
figure out how to change more than just one thing. How can we change
different things? How can we change the background color? Could you
change the border? Different things like this that are, you all know how
to do. But just because you know how to do it, doesn&apos;t mean you don&apos;t
have to stop and think and really process it in your mind first.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 180. review, 'this' (106) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image180.webp?raw=true"
  style="width:40%;"
  title="Review, 'this'"
  alt="Review, 'this'." />
</p>

The key word 'this', the concept of the word 'this', can be really tricky to
grasp. It took me quite a while myself. And I don&apos;t think I really
understood it until I started teaching it. The important thing to note
is that repeated practice helps. You want to go in and you want to do as
much coding as you can. And then, if or when you get stuck, remember to
work backwards. Find that keyword and just start marching back until you
find a tag. As soon as you find that tag, think back. Think to the early
things you learned when you were first learning HTML5. Think about that
DOM and go. Oh, we&apos;re talking about this little part of the tree right
there. I hope this is something you&apos;re able to grasp much more quickly
than I did. And I&apos;m going to do my best to give you the examples that
you can use to really master this. Good luck.

<h3>Homework Time!!</h3>

I am going to provide an optional quiz for people who want to double
check how well they have retained some of the general concepts from Week
Two.

What I really want people to focus on though is the Photo Gallery
assignment. All of the components you need to complete this program are
in these modules, it is your job to put them together. Please note, the
answer can be as little as 4 or 5 lines of code, or much more if that
makes more sense to you. While you are welcome to seek out help on the
forums, please remember that you are not allowed to post code. The code
to get you started is here: <http://codepen.io/ColleenEMc/pen/wKYxZa>.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch2-07">2.07 Photo Gallery (5:53)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 181. photo gallery (2.07) (108) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image181.webp?raw=true"
  style="width:40%;"
  title="2.07 Photo Gallery"
  alt="2.07 Photo Gallery." />
</p>

In this lesson, I want to walk you through how we&apos;re going to be
putting some of the things we&apos;ve learned into practice. And the main
things I&apos;m looking for, from you, are your abilities to do two things.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 182. putting it into practice (109) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image182.webp?raw=true"
  style="width:50%;"
  title="Putting it into Practice"
  alt="Putting it into Practice." />
</p>

First is, if I give you some HTML code and some CSS code, can you change
the background image of an element? The second thing I want you to try
to do is can you change the content of an element? I have a very
specific planner to put into place.

<https://codepen.io/ColleenEMc/pen/wKYxZa>

So, let&apos;s take a look at the gallery homework.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 183. example, codepen photo gallery homework (109) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image183.webp?raw=true"
  style="width:50%;"
  title="Example, CodePen photo gallery homework"
  alt="Example, CodePen photo gallery homework." />
</p>

In order to begin this assignment, I&apos;m going to give you the HTML code
and the CSS code that will create this page here. I&apos;ve got one div and
three images underneath it. Each one of those images has a link to this
source file and it has alt text.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 184. example 2, codepen photo gallery homework (110) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image184.webp?raw=true"
  style="width:50%;"
  title="Example #2, CodePen photo gallery homework"
  alt="Example #2, CodePen photo gallery homework." />
</p>

So right here, its alt text is Styling with a Bandana. And did you
notice that as soon as I put my mouse over this image, it changes the
source image and the text for the main div.

We&apos;re creating a photo gallery here.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 185. example 3, codepen photo gallery homework (110) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image185.webp?raw=true"
  style="width:50%;"
  title="Example #3, CodePen photo gallery homework"
  alt="Example #3, CodePen photo gallery homework." />
</p>

As I leave the picture and I go off to this side, we go back to the
original image in color.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 186. example 4, codepen photo gallery homework (111) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image186.webp?raw=true"
  style="width:50%;"
  title="Example #4, CodePen photo gallery homework"
  alt="Example #4, CodePen photo gallery homework." />
</p>

When I go over the next picture, you can see boom it went in and found
out what the source file was for this image. It located the alt text and
use both of those things to update that upper dish. Again, I&apos;m going to
leave.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 187. javascript function codes (111) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image184.webp?raw=true"
  style="width:50%;"
  title="JavaScript function codes"
  alt="JavaScript function codes." />
</p>

And I&apos;m going to go over this last one. I&apos;ve actually put in the
JavaScript function codes for you and the events. The one thing that I
need you to do is write those functions.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 188. function update(previewpic) (112) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image188.webp?raw=true"
  style="width:50%;"
  title="function update(previewPic)"
  alt="function update(previewPic)." />
</p>

Let&apos;s look at the functions I want you to write. The first one is
called, <b>upDate</b>, and we&apos;re going to send it to <b>previewPic</b>. And I
put in here, one of the things I want you to do is change the URL for
the background image to be the source file of the image we were going
over, that <b>previewPic</b>. The next thing I want you to do is I change
the text of the div so that&apos;s going to show the alt text of the preview
image. This is what we call <b>upDate</b>.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 189. function undo() (112) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image189.webp?raw=true"
  style="width:40%;"
  title="New function undo()"
  alt="New function undo()." />
</p>

When we leave the picture, I want you to undo what we just did, I want
you to go in and I want you to change the text and the background image
again.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 190. example, background-image (113) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image187.webp?raw=true"
  style="width:40%;"
  title="Example, background-image"
  alt="Example, background-image." />
</p>

Just as a little refresher in case you haven&apos;t used background images
before, the background image is an option for including graphics without
using an image tag. It&apos;s really just another way to add a little bit of
style without affecting the content. When you set background images
it&apos;s always a good idea to also set a background color. Because
sometimes, the URL might not be valid or the browser might not be able
to download it.

Here&apos;s an example of me setting the background image and the background
color. In order to this we want to say the URL use this keyword URL. And
then inside the parentheses you need to put the name of the file. Okay?
Now in this case it just happens to be mypPic.jpg. What you don&apos;t want
to do in the homework is you don&apos;t want to hard code this right here.
Instead of giving a name, you are going to want to use some sort of
variable. Okay? After you do that, you&apos;re going to want to hard code
the background color because we&apos;re hoping it won&apos;t be there at all.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 191. element text, 2 ways to change content (113) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image191.webp?raw=true"
  style="width:40%;"
  title="Element Text, 2 ways to change content"
  alt="Element Text, 2 ways to change content." />
</p>

For the element text, I&apos;m going to leave that a little bit more for you
to figure out how you&apos;re going to do that. We&apos;ve discussed two
different ways to change the content of the document. One is to use
<b>document.write()</b>. The other one we&apos;ve used quite a bit is
innerHTML. You need to think about what&apos;s the best way to update the
content that&apos;s inside that div to have it display the message you want.

Again, I really want you avoid doing anything where you are using the
actual alt tag. I don&apos;t want you saying, oh, look this picture happens
to say the alt text is happy. And you going in and hard coding something
and saying, oh well then this should equal happy. This isn&apos;t how
programmers work. The way that programmers try to do things is instead
you should have something is going to equal some sort of element, all
right? Avoid using quotes on the right-hand side for this assignment.
Really try to use something that can change as the document changes.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 192. tips (114) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image192.webp?raw=true"
  style="width:40%;"
  title="Tips"
  alt="Tips" />
</p>

Okay, so a couple tips to get you started. The code you need to write should 
actually be really short. If you are writing more than five or six lines of 
code, you probably want to stop and rethink the logic behind what you&apos;re 
working on. I wrote it in two lines of code and that was each function in about 
two lines of code but I can see you putting it more in to five or six to break 
it down in to small pieces. You will need to think about how you&apos;re going 
to incorporate the quotes. Because don&apos;t forget, when you mix double quotes 
with single quotes, things can kind of get mixed up. You should also remember 
that if you want to put two Strings together, you need to use that plus operator 
in order to concatenate the Strings.

This homework assignment is meant to give you an opportunity to do something 
that you&apos;re proud of. If you find yourself getting frustrated or lost, you 
should stop and ask for some help on the discussion board to make sure you&apos;re 
on the right track. But really, I&apos;m hoping that this something that you can 
do, that you can later use if you want to incorporate it into your own portfolio. 

<h3 id="code-wk3">Link to All of the Code for Week Three</h3>

The following is a link to all of the code for Week Three. The individual files 
are linked within the modules but the weekly collections may include additional 
code that you are free to use.

<http://codepen.io/collection/noEJaj/>

Even if you use CodePen, I encourage you to practice writing the code on your own. 
For now, I put complete examples in CodePen, but as time goes on, I will remove 
some of the commands to link the code together. You will need to work and learn 
that part on your own.

<h3>Arrays</h3>

Finally!! Now is when I start to explain some of the concepts I said you
had to wait for. Hopefully by now you are comfortable with the code

> <b>document.getElementById(&apos;idName&apos;);</b>

This code will cause the API to search the DOM until it finds a node with the 
id of &apos;idName&apos;). The key is that it is returning a single Node. But 
what about these other functions?

> <b>document.getElementsByTagName(&apos;p&apos;);</b>
>
> <b>document.getElementsByClassName(&apos;thumbnail&apos;);</b>

These commands may return zero, one or more Nodes. So now we need to find a way 
to handle dealing with collections of data, rather than just one thing at a time. 
This is where Arrays come in. Let&apos;s get started.

<h3 id="chb-2">Resources</h3>

<h3>Readings</h3>

Here are some resources for you to explore if you are interested in learning 
more about the topics from this week. The first reading is from W3Schools and 
covers the basics. The second reference is from the Mozilla Developer documentation 
and goes into more depth than I would expect you to have from this course. It 
is optional.

-   [JavaScript Arrays](https://www.w3schools.com/js/js_arrays.asp)

-   [Array - JavaScript &vert;
    MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

<h3>Code</h3>

You can find the code at [JavaScript Course Code]
(https://intro-webdesign.com/v3/javascript.html#code). It is organized by week, 
so you can check to see if any code is provided for this week&apos;s lessons.

<h3>A JavaScript Cheat Sheet</h3>

I thought about putting this next link in the optional resources section, but it 
is something I really want people to know about. This &quot;Cheat Sheet&quot; 
covers the major essentials of the JavaScript language. Some of it we have covered, 
and some we will cover in the next two weeks. And then there is a chunk we will 
never get to.

<http://www.cheat-sheets.org/saved-copy/jsquick.pdf>

So why do I want to share this with you? As you learn to program it is important 
to step back every once and awhile and review what you have learned AND what you 
still have left to learn. It helps a lot of people to look ahead and start to see 
that they need to master the small stuff before they can tackle the larger concepts.

<h3>Tabindex and Accessibility</h3>

Some elements on a page can take on the <b>focus</b> state by default. 
When you go to a page and use the tab key you can navigate from link to
link and through forms -- all without having to touch your mouse.

It is possible to add the focus state to other elements too by adding
the tabindex attribute to a tag.  While (below)

> <b>&lt;div&gt; My first div.&lt;/div&gt;</b>

<b> is</b> <b>not</b> accessible from the keyboard, this (below)

> <b>&lt;div tabindex=&quot;0&quot;&gt;  My second div.&lt;/div&gt;</b>

<b>is</b> accessible from the keyboard.

The number associated with the tabindex attribute is the tab order.  By
default, everything has an order of 0 which means that they will be
visited in the order of the HTML code.  It is possible to give the
attribute a higher number, but this can be confusing if it forces the
site visitor to jump randomly around the page.

You can see an example of tabindex in use at [HTML tabindex
Attribute](https://www.w3schools.com/tags/att_tabindex.asp)[.]

To an eager coder this may sound great -- &quot;Let&apos;s add focus to
everything!&quot;  But this would slow down a person&apos;s ability to navigate
quickly through your page.    Instead, use it only in places where
keyboard access would be important.  For instance, in last week&apos;s
homework you created a photo gallery that used the mouse.  By next week
I will want you to update that code to also react to the keyboard.

<h3>Using JavaScript with Attributes</h3>

In the videos ahead I will be showing you how to use JavaScript to
access and change some of the attributes on a webpage. But we all know
that watching someone do something and then doing it on your own can be
a bigger leap than you expected, so I want to give you a short reference
on two different methods I use.

<h3 id="getatt">getAttribute</h3>

If you want to access a part of the DOM you can often access it
directly.  For instance, if you used <b>document.querySelector()</b> to
access an image element, you can then access its src, alt text, etc.

> <b>my_img = document.querySelector(&quot;img&quot;)</b>
>
> <b>console.log(my_img.src)</b>
>
> <b>console.log(my_img.alt)</b>

Sometimes though you can&apos;t access the data directly and that is when
you will want to use the <a href="https://www.w3schools.com/jsref/met_element_getattribute.asp">
  HTML DOM Element <b>getAttribute()</b></a> method.

> <b>my_img = document.querySelector(&quot;img&quot;)</b>
>
> <b>console.log(my_img.getAttribute(&quot;src&quot;))</b>
>
> <b>console.log(my_img.getAttribute(&quot;alt&quot;))</b>

<h3 id="setatt">setAttribute</h3>

Similarly, you can often change the value of a DOM element by accessing
the attribute directly:

> <b>my_img = document.querySelector(&quot;img&quot;)</b>
>
> <b>my_img.src = &quot;mydog.jpg&quot;</b>
>
> <b>my_img.alt = &quot;Brown labradoodle&quot;</b>

Sometimes though you can&apos;t change the data directly and that is when
you will want to use the [HTML DOM Element
<b>setAttribute()</b>](https://www.w3schools.com/jsref/met_element_setattribute.asp)
method.

> <b>my_img = document.querySelector(&quot;img&quot;)</b>
>
> <b>my_img.setAttribute(&quot;src&quot;,&quot;mydog.jpg&quot;)</b>
>
> <b>my_img.setAttribute(&quot;alt&quot;,&quot;Brown labradoodle&quot;)</b>

It is nice to know how to change things with JavaScript because it will
allow you to leave the HTML alone, but still add attributes such as
<b>my_img.setAttribute(&quot;tabindex&quot;,&quot;0&quot;)</b>

&ast;&ast;This is a big hint for the future homework&ast;&ast;

<h3 id="arrays">Arrays</h3>

Finally!! Now is when I start to explain some of the concepts I said you
had to wait for. Hopefully by now you are comfortable with the code

> <b>document.getElementById(&apos;idName&apos;);</b>

This code will cause the API to search the DOM until it finds a node
with the id of &apos;idName&apos;. The key is that it is returning a single
Node. But what about these other functions?

> <b>document.getElementsByTagName(&apos;p&apos;);</b>
>
> <b>document.getElementsByClassName(&apos;thumbnail&apos;);</b>

These commands may return zero, one or more nodes. So now we need to
find a way to handle dealing with collections of data, rather than just
one thing at a time. This is where arrays come in.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch3-01">3.01 JavaScript Arrays (7:12)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 193. javascript arrays (3.01) (119) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image193.webp?raw=true"
  style="width:40%;"
  title="3.01 JavaScript Arrays"
  alt="3.01 JavaScript Arrays." />
</p>

Today we&apos;re going to be starting something that&apos;s  quite
different than what we&apos;ve been doing in the past. In the first few
weeks, I used variables that stored a single piece of information. We
talked about numbers, strings, true or false booleans, or objects. And
while objects can be quite complex where you can have entire DOM
elements, the fact is they were just dealing with one element at a time.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 194. storing lots of data at once (119) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image194.webp?raw=true"
  style="width:40%;"
  title="Arrays, storing lots of data at once"
  alt="Arrays, storing lots of data at once." />
</p>

But what do you do if you want to use multiple related pieces of
information? That&apos;s where the idea of arrays comes in. Arrays give us a
chance to declare multiple values that are all linked to a single
variable.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 195. examples, declaring an array (120) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image195.webp?raw=true"
  style="width:40%;"
  title="Examples, Declaring an Array"
  alt="Examples, Declaring an Array." />
</p>

In this case I&apos;ve declared an array called <b>grades</b>, but instead of
giving it one value, I&apos;ve given it ten. In this next example, I said I
wanted an array called <b>foods</b>, and I gave it three values. In the first
one they were numbers, in the second one they&apos;re strings. My third
example, I&apos;m finally going to get to where we can start using those
APIs <b>getElementsByClassName</b>. In this case, I have no idea how many
elements will be in this images array because I don&apos;t know how many
images were in the document.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 196. more examples, declaring an array (120) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image196.webp?raw=true"
  style="width:40%;"
  title="More Examples, Declaring an Array"
  alt="More Examples, Declaring an Array." />
</p>

And in the same way, I could declare array by saying, you know what, I
want to make a variable, I&apos;m going to call it <b>listItems</b>. And how I&apos;m
going to assign it or declare and initialize it, is by doing
<b>document.getElementsByTagName</b> and giving it <b>&lbrack;&apos;li&apos;&rbrack;.</b> Now
it&apos;ll travel through the DOM and grab every element that has that li
tag.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 197. arrays - a collection of values (121) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image197.webp?raw=true"
  style="width:40%;"
  title="Arrays - A Collection of Values"
  alt="Arrays - A Collection of Values." />
</p>

Hopefully you&apos;ve seen this idea that an array is not a single value,
but a collection of values. You start off by giving your array a name,
and then you can assign as many values as you&apos;d like. Each one of these
values 80, 82, 81, etc., these are called elements. My array is called
grades and it has ten elements in it. Now if I want to actually use
these elements, I need to know that each element has a numeric index, or
a number that goes with it. And in arrays, with almost all computer
science ideas, we don&apos;t start at 1, we start at 0. If I have an array
of 10 elements, The index goes from 0 to 9. If I have an array of 5
elements, I know that it&apos;ll go from 0 to 4.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 198. example, accessing an array by index (121) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image198.webp?raw=true"
  style="width:40%;"
  title="Accessing an Array by Index"
  alt="Example, Accessing an Array by Index." />
</p>

Okay, so we have our array, and we know, in this case, that we have an
array with 10 values in it. Each of those values is called an element.
In computer science, when you&apos;re talking to other people, this is a
term that you want to use, because then you&apos;ll really be conveying that
you&apos;re using an array. How do we get to those elements, though? Well,
each element is referenced by an index. If I were to say
<b>grades&lbrack;0&rbrack;,</b> right here, well, the computer knows, oh, I have this
array up here. I need to go find the one that&apos;s in the 0 place, so
<b>grades&lbrack;0&rbrack;</b> refers to 80.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 199. another example, accessing an array (122) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image199.webp?raw=true"
  style="width:40%;"
  title="Another example, Accessing an Array"
  alt="Another example, Accessing an Array." />
</p>

If I want to talk about <b>grades&lbrack;4&rbrack;,</b> well this refers to value 62.
<b>grades&lbrack;0&rbrack;</b> is the first value, <b>grades&lbrack;4&rbrack;</b> is actually the
fifth value. If this is the first time you&apos;ve really experienced
starting your counting at 0, it can be a little bit confusing at first,
but you&apos;ll get the hang of it in really no time.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 200. example, arrays (122) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image200.webp?raw=true"
  style="width:40%;"
  title="Example, Arrays - don't all have to be the same type"
  alt="Example, Arrays - don't all have to be the same type." />
</p>

One thing I wanted to mention because it&apos;s different than in other
program and languages, is that elements in array don&apos;t have to be all
the same type. I could have an array, in this case called info, that has
a string and a number, and then a string and a number, and that works
just fine. However, it&apos;s very uncommon and I wouldn&apos;t necessarily
encourage you to do your arrays in this manner.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 201. javascript arrays are objects (123) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image201.webp?raw=true"
  style="width:40%;"
  title="Examples, JavaScript Arrays are Objects"
  alt="Examples, JavaScript Arrays are Objects." />
</p>

Instead, we want to focus on this idea that arrays tend to have the same
values in them and that they have attributes and methods. Because
JavaScript arrays are objects and that gives them some special power.
For instance, we can refer to <b>grades.length</b>. We can call the method
<b>grades.sort(),</b> or we could even add additional elements to our array
using the method called <b>push,</b> where we would add another element to
it.

Now, if you start thinking about some of the different ways we can use
arrays, you can start to put things together. For instance, when I
talked earlier about <b>grades&lbrack;9&rbrack;</b> or <b>grades&lbrack;8&rbrack;</b>, we knew exactly
how big that array was because we had initialized it. But sometimes you
won&apos;t know how long the array is, especially if you used
<b>getElementsByTagName</b> or something like that.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 202. example, js arrays are objects (123) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image202.webp?raw=true"
  style="width:40%;"
  title="More Examples, JavaScript Arrays are Objects"
  alt="More Examples, JavaScript Arrays are Objects." />
</p>

It is possible to combine the idea of length and the idea of push to
come up with our own way of adding things to our array. Grades, here&apos;s
the element I need. I need <b>&lbrack;grades.length&rbrack;</b>, because I know that&apos;s
the last place where we don&apos;t have anything, and set it = element here.
These two things right here, <b>grades.push(element)</b> and
<b>grades&lbrack;grades.length&rbrack; = element</b>, they&apos;re the same thing, it&apos;s
just a different way to program. This kind of flexibility can be really
great once you get the hang of JavaScript. But when you first get
started, it can sometimes be confusing when you see people doing the
same thing in different ways. It&apos;s a really great learning opportunity
for you to try to figure out which things match as you go out and see
new code.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 203. review javascript arrays (124) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image203.webp?raw=true"
  style="width:40%;"
  title="Review JavaScript Arrays"
  alt="Review JavaScript Arrays." />
</p>

Let&apos;s review. As you learn to declare and manipulate arrays, your code
is going to become much more powerful. You just need to take the time to
switch your mindset from single values to collections of values. And
once you do that, we can start playing with these new API methods that
we haven&apos;t used before. The <b>getElementsByTagName</b> and
<b>getElementsByClassName</b>.

Quick note because I know this is a typo of a lot us make, is that
you&apos;re writing this the correct way. We&apos;ve been using
<b>getElementById</b>, make sure you&apos;re typing this else you might run
into problems. Go ahead, start typing in some code, use the console to
make sure things are going the way you want them to, and keep coming
along with me as you learn new ways to use arrays to improve your page,
thanks.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch3-02">3.02 Code With Me -- Arrays (5:18)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 204. code with me -- arrays (3.02) (125) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image204.webp?raw=true"
  style="width:40%;"
  title="3.02 Code With Me -- Arrays"
  alt="3.02 Code With Me -- Arrays." />
</p>

Today, we&apos;re going to do what I call a Code with Me. Well, it&apos;s
perfectly okay if you just sit here and read the modules. I really
encourage people to take this as an opportunity to find out, can you do
the things that you&apos;ve been reading about all along?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 205. arrays (125) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image205.webp?raw=true"
  style="width:40%;"
  title="Arrays"
  alt="Arrays." />
</p>

Specifically, I&apos;m wondering, can you declare an array? We&apos;ve been
talking about them, we&apos;ve been using them, but I&apos;ve been doing all the
work. What if I asked you to declare array? Would you be stuck or can
you jump right in?

After you declare an array, can you access the different elements of an
Array? If you remember, each array is made up of as many different
elements as you can think of. If you want to actually access this one
right here, how do you do it? Next thing I want you to think about is
can you add elements to array? If we want to add something after B,
perhaps a C, do you know the proper JavaScript to use in order to make
your code work? Let&apos;s jump right in. As I said, I have this code online
for you. But I really encourage you to start from scratch and try coding
on your own. And using my code as a reference just in case things go
wrong.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 206. example, array and elements of array (126) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image206.webp?raw=true"
  style="width:50%;"
  title="Example, array and elements of array"
  alt="Example, array and elements of array." />
</p>

Let&apos;s take a look at this code. I really want you to understand each
and every line. Sometimes I do things the long way, but that&apos;s okay.
Because I really think it&apos;s a great learning experience for you to
understand what&apos;s going on with JavaScript.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 207. example, step by step arrays and elements (126) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image207.webp?raw=true"
  style="width:50%;"
  title="Example, step by step arrays and elements"
  alt="Example, step by step arrays and elements." />
</p>

Let&apos;s start off with the fact that I declared an array with four
different elements in here. I have Banana, Orange, Apple and Mango, I&apos;m
going to use those inside my HTML code. In fact, where I use them, is I
use it in the very first function called loadFruits.

When my page starts up, it&apos;s going to call that function and right away
it says, you know what? I want you to grab everything that&apos;s in this
array, all of it, and dump it right into this paragraph right here. This
is why, again, if you look carefully at the HTML file, there&apos;s no
fruits there. It&apos;s all being added by the JavaScript. Once you&apos;ve got
that kind of initial setup for your page, this is where we want to add
elements to our array.

In order to add something, we basically don&apos;t want to add it here. We
want to add additional things to the end of our array. All right, let&apos;s
get started. In this function, it&apos;s going to ask us what our favorite
food is. Once they ask, we need to know where should we put it?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 208. index starts at 0 (zero) (127) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image208.webp?raw=true"
  style="width:50%;"
  title="Index starts at 0 (zero)"
  alt="Index starts at 0 (zero)." />
</p>

Right now, I&apos;m going to draw up on the screen to get an idea of what
the index of each one of these elements is. It starts at 0, 1, 2 and 3.
So this means we want to put the next fruit in position 4.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 209/210. test button, onclick add to array (127) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image209.webp?raw=true"
  style="width:45%;"
  title="Test button, onClick add to array"
  alt="Test button, onClick add to array." />
<img src="./images/image210.webp?raw=true"
  style="width:45%;"
  title="Test, adding to an array"
  alt="Test, adding to an array." />
</p>

Let&apos;s take a look. I click Add Your Favorite. I&apos;ll say Strawberry. And
when I hit OK, right away the JavaScript has gone in and said, oh, I
need to add this fruit to my whole array. The kind of cool thing is
that, it doesn&apos;t say 4 here. I didn&apos;t say, I want it to go in position
4, because then it wouldn&apos;t work if I wanted to add more and more
fruit. This is where these little elements are coming together. You know
that to add something to your array, you use the array name. We have
fruits, then you have to give it an index. And the easiest way to add
something to an array is to just use the length of itself. Originally, I
had four elements in my array. Perfect, I put it in position 4. Now the
length of my array is one, two, three, four, five. Because I&apos;m using a
variable here, instead of hard coding a number. My program will work no
matter how many different elements I add. Length is the count of fruits
in the array.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 211. test, using arrays (128) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image211.webp?raw=true"
  style="width:50%;"
  title="Test, using arrays"
  alt="Test, using arrays." />
</p>

Let&apos;s add two more. And I can add Peach. And I can add another one.
I&apos;ll just add Banana again because I have no imagination this morning.
There we go. This is a very simple example, but one that I want you to
master. I want you to go in there, I want you to make your own array.
Don&apos;t use fruit, use your favorite foods, use your favorite cars. Use
your friends and take them on and off. And see if you can do these
different things to manipulate an array. Once you feel comfortable doing
this, you should feel confident going on in this class reading
additional modules. And knowing that you do understand what&apos;s going on,
even if you make a mistake now and then. So good luck.

<h1 id="ch4">Week 4</h1>

<h3>Week 4 Resources</h3>

<h3>Accessibility Testing Options</h3>

-   [The W3C Markup Validation Service Tool.](https://validator.w3.org/)

This validator checks the markup validity of web documents. 

-   [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/)

Install the browser extension for this tool. I particularly like this
tool for color contrast issues since you can use color sliders to check
other colors in real time.

-   [axe DevTools® browser
    extension](https://www.deque.com/get-started-axe-devtools-browser-extension/)

Install the browser extension for this tool. It will check for many of
the underlying accessibility issues that other tools do not,
particularly semantic tags.

-   [WebAIM Quick Reference: Testing Web Content for
    Accessibility](https://webaim.org/resources/evalquickref/evalquickref.pdf)

A comprehensive checklist that combines automated tools and manual
checking.  

<h3>Code</h3>

You can find the code at [JavaScript Course
Code](https://intro-webdesign.com/v3/javascript.html#code)

It is organized by week, so you can check to see if any code is provided
for this week&apos;s lessons.

<h3 id="chb-4">Lecture Slides</h3>

To support learners, accessible lecture slides are provided as
downloadable PDF files below, and individually within each lecture
video. Please note, sometimes the slides will look slightly different
from the videos since I like to update the slides when things change.

<h3>Writing loops in JavaScript</h3>

Once again, the lectures ahead will contain content that is easy to
read, but can be a little tricker to do on your own.  So, let&apos;s talk
about the relationship between <b>document.querySelectorAll()</b> and
looping.

The beauty of <b>document.querySelectorAll()</b> is that it will return an
array of elements.  If you have twelve links on your page, it can get
them all.  Same with fifty images, seven paragraphs, or the one figure. 
But when you have a lot of elements, you don&apos;t want to write a lot of
code to update them and that is where looping (also called
iteration) comes in.

There are a number of ways to loop but the one I will use is a
[JavaScript for Loop](https://www.w3schools.com/jsref/jsref_for.asp).

In a 'for loop' you state what values you want to start with, under what
condition you want to continue to loop, and how you want to update the
value.  In the code below the numbers 0..4 would be displayed on the
console.

> for (let i = 0; i &lt; 5; i++) {
>
>   console.log(i) 
>
> }

This is a very basic loop and doesn&apos;t do anything that exciting.  But
think about how we can combine it to use the knowledge we have learned
about the DOM.  Suppose that someone on your team has styled a new class
called thumbnail and you want to use it.   In the code below you can see
how quick and easy it would be to add this new class to every image.

> my_images = document.querySelectorAll(&quot;img&quot;)
>
> for (let i = 0; i &lt; my_images.length; i++) {
>
>     my_images&lbrack;i&rbrack;.setAttribute(&quot;class&quot;,&quot;thumbnail&quot;)
>
> }

<h3>Advanced Coding Techniques</h3>

In the next few lectures, we will talk about more advanced coding
techniques. Any programming language has the general ability to loop
(run the same code multiple times) and to make decisions during &quot;run
time.&quot; The important thing to know is that while the concepts are the
same among programming languages, they all do it a little differently.
Some use parentheses, some don&apos;t. Some rely on indentation, others
don&apos;t.

The important thing is to understand the LOGIC. Doing just the examples
we provide here aren&apos;t enough, you will want to change your code to
come up with new decisions and different criteria to test different
situations.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch4-01">4.01 Code With Me: Randomizing Your Images Using Arrays (8:10)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~ 212. code with me: randomizing your images using arrays (4.01) (131) ~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image212.webp?raw=true"
  style="width:40%;"
  title="4.01 Code With Me: Randomizing Your Images Using Arrays"
  alt="4.01 Code With Me: Randomizing Your Images Using Arrays." />
</p>

Hi everyone, let&apos;s do a couple Code With Me&apos;s in a row just so you can
start using your JavaScript to do things that are a little bit more
practical. I know that earlier I did a demo with you where we used
arrays and we kind of picked out one or two elements from the arrays,
but it wasn&apos;t really anything that had to do with web design so much.
So, in this example, what I&apos;m going to show you how to do is how to
randomize your pictures using JavaScript, so let&apos;s take a look.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 213-216. four images for array (131) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image213.webp?raw=true"
  style="width:20%;"
  title="Pink tree with curved path"
  alt="Pink tree with curved path." />
<img src="./images/image214.webp?raw=true"
  style="width:20%;"
  title="Tree in the woods"
  alt="Tree in the woods." />
<img src="./images/image215.webp?raw=true"
  style="width:20%;"
  title="Dog Bacon hanging in the woods"
  alt="Dog Bacon hanging in the woods." />
<img src="./images/image216.webp?raw=true"
  style="width:20%;"
  title="No image to display"
  alt="No image to display." />
</p>

I&apos;m going to refresh the page here to give you an idea of what I&apos;m
talking about. And what I&apos;d like you to do is keep an eye on this one
image up here in the corner each time I load the page. This time I&apos;ve
got a picture with a tree, while before it was kind of that pink,
beautiful picture. When I reload it again, up, I&apos;ve got a picture of my
dog Bacon hanging out near the woods and I&apos;m going to do it one more
time. And up, look at that, I didn&apos;t get any image at all. Do it one
more time and I&apos;ve got that kind of pink tree again. What I&apos;ve done is
I&apos;ve written code in JavaScript that will pick an image randomly from
an array of image names.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 217. body onload = pickimage() (132) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image217.webp?raw=true"
  style="width:50%;"
  title="body onload = 'pickImage()'"
  alt="body onload = 'pickImage()'." />
</p>

Let&apos;s code this together. Let&apos;s start with the HTML code. Right here
on line 11 I want you to notice that I&apos;ve put in an event and a
function. And I&apos;ve said when the body of the page loads, I want you to
run the function <b>pickImage(),</b> all right?

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 218. link to js scripts with function pickimage() (132) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image218.webp?raw=true"
  style="width:50%;"
  title="At bottom of html, link to script.js with function: pickImage()"
  alt="At bottom of html, link to script.js with function: pickImage()." />
</p>

And just to double check, I&apos;m going to scroll all the way to the bottom
of the screen and you can see that I&apos;ve remembered to include a link to
my JavaScript file that has that function.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 219. randomly load images (133) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image219.webp?raw=true"
  style="width:50%;"
  title="Randomly load images"
  alt="Randomly load images." />
</p>

Let&apos;s pop back up to the top. What is pickImage going to do? Well,
pickImage, I&apos;m going to scroll just a little bit more here. PickImage
is going to go to this image element right here, the one with the id of
<b>header_img</b> and it is going to update the source to a somewhat random
image.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 220. create variable options array of images (133) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image220.webp?raw=true"
  style="width:50%;"
  title="Create variable options as an array of images"
  alt="Create variable options as an array of images." />
</p>

Let&apos;s see how we do this in the JavaScript file. The function
<b>pickImage</b> starts off with an array that I have called <b>options</b>.
And what I did is I went through many of the images in my folder, but
not all of them and just put them in as strings, so I have
<b>bacon_in_the_woods.webp</b>, <b>munising</b>, <b>bend_in_the_road.webp</b>.
Oops, I&apos;ve got <b>bend_in_the_road</b> twice, think I actually in fact,
we&apos;re going to get rid of a couple of these since I have extra, let&apos;s
keep it nice and short and sweet.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 221. function pickimage to randomly select image (134) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image221.webp?raw=true"
  style="width:50%;"
  title="function pickImage to randomly select image from array"
  alt="function pickImage to randomly select image from array." />
</p>

And I have 1, 2, 3, 4, 5 different images to choose from. Again, where
did I get those images from?

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 222. randomly select image with math.random (134) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image222.webp?raw=true"
  style="width:50%;"
  title="Randomly select image with Math.random command"
  alt="Randomly select image with Math.random command." />
</p>

Well, I just peeked over here in my Images folder and I picked some
randomly. All right, so again, all I have here is an array of strings,
and each string is the name of one of my pictures. All right, well, we
know that we have all the names, how can we grab just one of those
names, all right? Hang with me here, we&apos;re going to be doing some math,
we&apos;re going to be doing some funky JavaScript, but there&apos;s just one
line of code you need to understand, and it&apos;s right here.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~ 223. math.random is 0-1, options.length is number of images (135) ~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image223.webp?raw=true"
  style="width:50%;"
  title="Math.random between 0 and 1; options.length = number of options in array"
  alt="Math.random between 0 and 1; options.length = number of options in array." />
</p>

JavaScript has a random function right here called <b>Math.random</b>. And
what it will do is it will return a number between 0 and 1, so 0.25,
0.5, 0.75, we want to take that number and we want to take the length of
this array. If I have an array with five file names in it, I want to
pick a number such as 0, 1, 2, 3 or 4. I don&apos;t want to go beyond 4
because that&apos;s too big, all right? And I don&apos;t want to go less than 0
because that&apos;s too small. So I find out how long the array is using
<b>options.length,</b> then I multiply that by a number between 0 and 1.
And then the last little thing it does right here, this <b>Math.floor,</b>
that&apos;s going to change it into the integer, all right? It&apos;s kind of
funky, there&apos;s some math going on, trust me on this, all right?

Now this part of the code picks either <b>bacon_in_the_woods</b> or
<b>bend_in_the_road</b> or <b>lake_view</b>, perfect. But remember, in our
code, in our HTML code, we need to have that folder name too, right? All
of our images are in a folder called <b>images</b>, so we take images and
we concatenate, that&apos;s the fancy word for squish together. We
concatenate the word images/with one of these file names, now we&apos;re
going to go in and I&apos;m using <b>document.querySelector</b> and I&apos;m using
&quot;<b>header_image</b>&quot;. Again, remember, if you use
<b>document.getElementById</b>, you wouldn&apos;t need this hashtag, but I do.
I&apos;ve grabbed that one little element in the <b>DOM</b> and then I set its
source attribute to whatever my random image is. And for now, I&apos;m
setting the alt attribute to blank. This isn&apos;t the best for
accessibility wise, but it is really just a decorative image. And by
including the alt attribute, I&apos;m still saying, &quot;hey, there&apos;s an image
here, but it&apos;s not important, I&apos;m letting you know that it&apos;s really
something you can skip over.&quot;
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 224. test, inspect element image (136) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image224.webp?raw=true"
  style="width:50%;"
  title="Test, inspect element image"
  alt="Test, inspect element image." />
</p>

Let&apos;s take a look now at this working in process again. This time when
we look at the page, I want to have <b>Inspect Element</b> open, so I&apos;m
going to do my <b>Inspect</b>. I&apos;m going to narrow in on this image and
I&apos;m going to make it a little bit bigger, hopefully to make it a little
easier for you to read.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 225. inspect image selected, 'bend_in_the_road' (136) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image225.webp?raw=true"
  style="width:50%;"
  title="Test, inspect image selected is 'bend_in_the_road'"
  alt="Test, inspect image selected is 'bend_in_the_road'." />
</p>

You can see, however, that currently the image is <b>bend_in_the_road</b>,
let&apos;s refresh the page.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 226. test, display 'hollow_tree.webp' (137) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image226.webp?raw=true"
  style="width:50%;"
  title="Test, display 'hollow_tree.webp'"
  alt="Test, display 'hollow_tree.webp'." />
</p>

This time that&apos;s changed into <b>hollow_tree.webp</b> I&apos;m going to refresh.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 227. test, blank image, no picture (137) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image227.webp?raw=true"
  style="width:50%;"
  title="Test, no picture, blank image"
  alt="Test, no picture, blank image." />
</p>

Did you notice something, did you notice that the image is missing? This
happened earlier too, when I was doing my demo, there&apos;s no picture
there, so let&apos;s head over to the console.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 228. test, 404 error 'images/munising' not found (138) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image228.webp?raw=true"
  style="width:50%;"
  title="Test, 404 error 'images/munising' not found"
  alt="Test, 404 error 'images/munising' not found." />
</p>

And in the console, you will see that I get the error that munising
actually just isn&apos;t found. <b>images/munising</b> isn&apos;t found, it&apos;s a
404 error.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~ 229/230. test, identify and fix missing picture error (138) ~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image229.webp?raw=true"
  style="width:45%;"
  title="script.js - check 'options' for missing picture"
  alt="script.js - check 'options' for missing picture." />
<img src="./images/image230.webp?raw=true"
  style="width:45%;"
  title="script.js - add file extension to munising image in 'options' array"
  alt="script.js - add file extension to munising image in 'options' array." />
</p>

Okay, well, I must have had a typo somewhere, so let&apos;s go back into my
code and we&apos;ll investigate the script, that JS file. Here we are in
line 2, and we can see that I forgot to include the file extension, I
don&apos;t remember what it is. It was .jpg, so I need to replace this with
<b>munising.jpg</b>.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 231. test options images with inspect element (139) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image231.webp?raw=true"
  style="width:50%;"
  title="Test, options images with inspect element"
  alt="Test, options images with inspect element." />
</p>

All right, let&apos;s go back and try this one more time. All right, let&apos;s
start refreshing again and see if we get that same error or if I&apos;m able
to get a picture of <b>Munising</b> to show up, there it is right there. So
just to double check, I&apos;m going to go in, and now I can see that the
<b>images/munising.jpg</b> is correct, okay? Hopefully this demo shows you
that there are some real-world applications to you applying JavaScript
to your page. And it only takes few lines of code to do something that
will make your page a little bit more unique. So have some fun with this
and get your hands dirty, use that <b>Inspect Element</b>, and good luck.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch4-02">4.02 Code With Me: Using LightBox (9:48)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 232. code with me: using lightbox (4.02) (139) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image232.webp?raw=true"
  style="width:40%;"
  title="4.02 Code With Me: Using LightBox"
  alt="4.02 Code With Me: Using LightBox." />
</p>

Something I say often about my Web Design for Everybody classes is that
it&apos;s unlikely that you&apos;re going to go off and become a professional
web developer when you&apos;re done. Some of you may, that&apos;s great. But a
lot of you are mostly just looking to become a little bit more
knowledgeable about existing tech and that might include existing
packages and tools out there that you can use.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 233. code for creating lightboxes (140) ~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image233.webp?raw=true"
  style="width:40%;"
  title="Use code for creating lightboxes"
  alt="Use code for creating lightboxes." />
</p>

It is true that it&apos;s way more common to use code from others than to
write your own. And one of my absolute favorites is code for creating
<b>lightboxes</b>.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 234. lightbox project code; js and css (140) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image234.webp?raw=true"
  style="width:50%;"
  title="Lightbox project code; javascript and css"
  alt="Lightbox project code; javascript and css." />
</p>

Today I&apos;m going to walk you through how you can implement a
<b>lightbox</b> in your existing code using somebody else&apos;s JavaScript and
CSS. Let&apos;s take a look at this <b>lightbox</b> project. For those of you
who are not familiar with what a <b>lightbox</b> is, let me show you an
example.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 235. example, on click image pops up bigger (141) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image235.webp?raw=true"
  style="width:50%;"
  title="Example, on click image pops up bigger"
  alt="Example, on click image pops up bigger." />
</p>

I&apos;m going to click on this picture right here and as you can see, as
you click on the image, the image actually pops up into a much bigger
form.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 236. image with optional caption on bottom left (141) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image236.webp?raw=true"
  style="width:50%;"
  title="Image with optional caption on bottom left"
  alt="Image with optional caption on bottom left." />
</p>

I&apos;m going to click out this X and I can click on this second image as
well. If you notice, it&apos;s really small, but at the bottom they even
include an optional caption. These are considered kind of individual
images.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~ 237. lightbox example, image with 'x' and caption (142) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image237.webp?raw=true"
  style="width:50%;"
  title="Lightbox Example, image with 'X' and Caption"
  alt="Lightbox Example, image with 'X' and Caption." />
</p>

You can also put your images into a set like these four images here,
where when I click on the first one, not only does it show the caption
at the bottom and the X to leave the image, there&apos;s also a small
chevron or arrow to go to the next image or to go back to a previous
image. What&apos;s great about this code is that all of the JavaScript and
all of the CSS for the <b>lightbox</b> is already created for you.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 238. lightbox, getting started (142) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image238.webp?raw=true"
  style="width:50%;"
  title="Lightbox, Getting Started"
  alt="Lightbox, Getting Started." />
</p>

Let me show you how you can actually implement it in your code. I&apos;m
going to start by scrolling down here a little bit and they mentioned
that there&apos;s a number of ways to get started.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 239/240. lightbox 2, github (143) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
<img src="./images/image239.webp?raw=true"
  style="width:45%;"
  title="Lightbox 2, in github"
  alt="Lightbox 2, in github." />
<img src="./images/image240.webp?raw=true"
  style="width:45%;"
  title="Lightbox 2, Download ZIP"
  alt="Lightbox 2, Download ZIP." />
</p>

For most of you, I think the most common approach is going to be to
click on the link to GitHub to get their code. In order to get the code,
you would go to Code, Download ZIP. While that&apos;s happening, I want to
talk to you about some of these files and folders.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 241. lightbox 2, dist (distribution) folder (143) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image241.webp?raw=true"
  style="width:50%;"
  title="Lightbox 2, distribution folder"
  alt="Lightbox 2, distribution folder." />
</p>

The most important one that you will need is called the &quot;dist&quot; folder.
Dist is a really common naming convention, it stands for distribution.

If you&apos;re using other people&apos;s code and you&apos;re a little overwhelmed
by all the folders and files, this is usually the one folder you really
need. Although, the examples folder is usually a little bit handy as
well.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 242. add code along with path/to/lightbox.css (144) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image242.webp?raw=true"
  style="width:50%;"
  title="Add code along with path/to/lightbox.css"
  alt="Add code along with path/to/lightbox.css." />
</p>

I&apos;m going to go back to the instructions, as we go through the rest of
the steps, let me zoom in a little bit because the smallest typo can throw 
you off. Once you&apos;ve downloaded the code, and maybe you&apos;d want to 
look at the examples, but we&apos;ll skip it right now you will notice that 
they mentioned that inside the distribution folder, you&apos;re going to want 
to link to their CSS and their JavaScript. This is the tricky part. In the 
example, it says <b>path/to/lightbox.css</b>. They don&apos;t actually mean path-to, 
they mean whatever the name of the folder is.

For us, it&apos;s going to be dist/css. Same here, when people talk about
path/to, that&apos;s a shorthand, that&apos;s not actually the folder name,
we&apos;re going to be using dist.javascript. The other thing that you might
kind of read over quickly is we tend to be beginner coders here in our
Web Development for Everybody. It&apos;s unlikely that you&apos;re already using
jQuery, which means we need to make sure we use any of their code that
says <b>lightbox</b> plus jQuery. Don&apos;t worry, I&apos;m going to show you all
this. But I just want to point it out when you&apos;re going through the
documentation, okay?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 243. add data-lightbox, for lightbox2.html (145) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image243.webp?raw=true"
  style="width:50%;"
  title="Add data-lightbox, for lightbox2.html"
  alt="Add data-lightbox, for lightbox2.html." />
</p>

Here is the format, what we are basically doing is turning every image
on our page that we want to be part of the <b>lightbox</b> into a link,
right? Instead of just being a regular old image, we want to be able to
click on that image and then open up the image in a way bigger fashion,
all right? Our new structure is going to be every place we used to have
an image, we are going to put an <b>&lt;a&gt;</b> tag around it and that
<b>&lt;a&gt;</b> tag should go to the image. Include this special attribute
called <b>data-lightbox</b> and the special attribute called
<b>data-title</b>. The <b>data-lightbox</b> lets the browser know whether you
want all of the images to be linked together or whether they should be
separate.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 244. lightbox2 website, image sets, data-lightbox (145) ~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image244.webp?raw=true"
  style="width:50%;"
  title="lightbox2 website, image sets, data-lightbox"
  alt="lightbox2 website, image sets, data-lightbox." />
</p>

If you notice in the image sets (at the bottom), they gave everything
the same <b>data-lightbox.</b>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 245. folder structure, lightbox.html (146) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image245.webp?raw=true"
  style="width:50%;"
  title="Folder structure for lightbox.html"
  alt="Folder structure for lightbox.html." />
</p>

That&apos;s it, that&apos;s all the documentation we&apos;re going to go through.
Let&apos;s go back to one of the pages we&apos;ve been using in this class
earlier so you can see how I implemented it. Let&apos;s start off by looking
at my folder structure. I still have my css folder, my images folder, my
js folder, but I&apos;ve added a new file called <b>lightbox.html</b>. It&apos;s
just a kind of shortened version of the neighborhood.html, so we won&apos;t
worry about it too much.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 246. dist/css/lightbox.css (146) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
<img src="./images/image246.webp?raw=true"
  style="width:50%;"
  title="Add dist/css/lightbox.css"
  alt="Add dist/css/lightbox.css." />
</p>

But now I also have the dist folder. I just copied and dragged to the
whole thing. Inside the dist, they have their own css, their own images,
because remember, for those little like chevron arrows, and their own
js. Sometimes my students will ask me, they&apos;ll say, &quot;well, why don&apos;t
you just put other people&apos;s CSS in your CSS folder or other people&apos;s
JavaScript in your JavaScript folder?&quot; You can absolutely do that. But
I like to keep it separate because I like to know if, when something&apos;s
broken, if it was my code or their code. All I&apos;ve really done is add
this dist folder right here, let&apos;s close up the folder.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~ 247/248. link stylesheet, dist/css/lightbox.css & dist/js/lightbox-plus-jquery.js (147) ~~-->
<p align="center">
<img src="./images/image247.webp?raw=true"
  style="width:45%;"
  title="Link stylesheet, dist/css/lightbox.css"
  alt="Link stylesheet, dist/css/lightbox.css." />
<img src="./images/image248.webp?raw=true"
  style="width:45%;"
  title="Link JavaScript, dist/js/lightbox-plus-jquery.js"
  alt="Link JavaScript, dist/js/lightbox-plus-jquery.js." />
</p>

Now, as we go through, you can see instead of path/to the
<b>lightbox.css</b>, I&apos;ve used <b>dist/css/lightbox</b>. I&apos;m going to scroll
all the way to the bottom, and instead of having
<b>path/to/js/lightbox</b>, I&apos;ve done the <b>dist/js/lightbox-plus-query</b>.
I&apos;m going to save this for just a second, and I&apos;m going to open it up.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 249. abbreviated page with four images (147) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image249.webp?raw=true"
  style="width:50%;"
  title="Abbreviated page with four images"
  alt="Abbreviated page with four images." />
</p>

What we have here, as I mentioned, is just an abbreviated page where I
only have four images. And right now, these images, I&apos;m clicking on
them, don&apos;t do anything, all right? I&apos;ve connected to the CSS and
I&apos;ve connected to the JavaScript.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 250. a href, data-lightbox = 'images' (148) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image250.webp?raw=true"
  style="width:50%;"
  title="Update a href, adding data-lightbox='images'"
  alt="Update a href, adding data-lightbox='images'." />
</p>

But now it&apos;s time for me to update my HTML. Let&apos;s take a look at that
very first image. What I needed to do was add an &lt;a&gt; tag
around it. And if you remember, the href for that tag should be the
exact same thing as the image itself. We want to click on the image and
then open up that image in its own window. I have my <b>data-lightbox</b>,
I&apos;ve called it =images, and I&apos;ve added my data-title=&quot;Caption 1&quot;,
all right? Just so I don&apos;t have to scroll back and forth for you, I&apos;m
going to hit option Z for a second, so it wraps all my text, all right?
I&apos;ve got my href, my <b>data-lightbox</b> images, and my data-title.
Let&apos;s save it and let&apos;s take a look. All right, I&apos;ve refreshed my
page and I&apos;m going to click on the first image. Notice, even if you can
see it, it might be a little hard. When I put my mouse over the cursor
changes to show that this isn&apos;t just an image. It&apos;s an image that&apos;s a
link that doesn&apos;t happen to the other ones.

When I click on it, everything popped up and I got my Caption 1. Let&apos;s
add this to the other images as well. It is super, super, super tempting
when you&apos;re doing this to add this a link to all your images, right?
Rather than just testing one at a time. But you always want to test at
least one of them once just to be sure that you don&apos;t have a typo,
right? So normally I add it to the first one and then kind of copy and
paste it for the other ones. I&apos;m going to save this and let&apos;s look at
it again, all right?
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~ 251/252. test two images in lightbox.html (149) ~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image251.webp?raw=true"
  style="width:45%;"
  title="First test, images in lightbox.html"
  alt="First test, images in lightbox.html." />
<img src="./images/image252.webp?raw=true"
  style="width:45%;"
  title="2nd test, images in lightbox.html"
  alt="2nd test, images in lightbox.html." />
</p>

Let&apos;s try clicking on the first image. Not only does it pop up, but I
now have the chevron to go to the next image, the next image, and the
last one, and I could go back if I wanted to notice. If you&apos;re trying
to do this along with me and the picture is popping up, if things don&apos;t
look right, that probably means you didn&apos;t link to the CSS correctly.
If things aren&apos;t functioning correctly, then that means you probably
didn&apos;t link to the JavaScript in the right way. Use that <b>Inspect
Element</b> so you can look in and make sure all your files are connected.
But mostly realize how little code it took for me to take something that
I&apos;ve created and kind of bump it up a notch by using code that somebody
else created. That&apos;s really what the web is about. All of us working
together to create things that we can all enjoy.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch4-03">4.03 Code With Me: Looping Through Images (8:07)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~ 253. code with me: looping through images (4.03) (149) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image253.webp?raw=true"
  style="width:40%;"
  title="4.03 Code With Me: Looping Through Images"
  alt="4.03 Code With Me: Looping Through Images." />
</p>

Hi everyone. Earlier we did a Code With Me where we wanted to make one
image, a random image. Now, let&apos;s talk about what we would do if we
want to use JavaScript to update numerous images.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 254. test, random images (150) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image254.webp?raw=true"
  style="width:40%;"
  title="Test parks.html, random images"
  alt="Test parks.html, random images." />
</p>

For instance, in this example, I have now changed the code so that I get
three somewhat random images each time I load it. It&apos;s not super random
because I didn&apos;t give it a lot of options, but you can see that it&apos;s
three different pictures each time. Let&apos;s take a look at the code to
see how we do this.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 255. onload setimages (150) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image255.webp?raw=true"
  style="width:50%;"
  title="body onload, setImages()"
  alt="body onload, setImages()." />
</p>

Let&apos;s start off by looking at our body tag. Once again, I&apos;ve used the
onload event, but this time I&apos;ve used a function called
&quot;<b>setImages()</b>&quot;.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 256. images inside flex class (151) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image256.webp?raw=true"
  style="width:50%;"
  title="Images inside flex class"
  alt="Images inside flex class." />
</p>

If we scroll a little further, we can see from the structure of the page
that the images I want to change are the images that are inside the flex
class. Right now, I have 1, 2, 3 images in here.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 257. script tag link to javascript folder (151) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image257.webp?raw=true"
  style="width:50%;"
  title="Script tab link to JavaScript folder"
  alt="Script tab link to JavaScript folder." />
</p>

Then at the very bottom, I&apos;m using my script tag to link to my
JavaScript folder.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 258. function setimages (152) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image258.webp?raw=true"
  style="width:50%;"
  title="function setImages();"
  alt="function setImages();" />
</p>

Let&apos;s check out the JavaScript code. Once again, I&apos;ve created a
variable called options, and in that array, I have listed a number of
different images that are available to this file. Here&apos;s where things
get a little bit different. On line 26, I&apos;ve made another new variable
called currentImages. Again, you want to use good mnemonic names,
meaning when I look at the variable name, I should know what I&apos;m trying
to save here.

What I&apos;m trying to save is all of the images that are currently in the
flex class. I&apos;ve used <b>document.querySelectorAll(&quot;.flex img&quot;)</b>.
This is going to return an array of images. We can&apos;t just start using
current images and trying to get the source attribute or the alt
attribute. It doesn&apos;t know how to do that. We need to access each image
individually, and this is where we will use looping. I start off with my
'for loop'. You always want to use the keyword for. Then I&apos;m going to
create a variable called i. It&apos;s something we do a lot. I&apos;m going to
loop through each image in current images, and each time i is going to
go up by one. Current images, if you remember on our page, there were
three images. So that means I will go from 0, 1, and 2. If I had 10
images in that class, it would be 0, 1, 2, all the way up to nine.

I like to add console.log messages. They make me feel better. They help
me figure out, is my code running? Is my, oops, that shouldn&apos;t say
<b>isSecure</b>. I really just want to say i. I want to print out that 0,
1, 2, 3, etc, so I can make sure my loop is doing things as I expected.
Now, the code should look pretty similar. I&apos;m going to grab a random
image and assign it to the variable random image. It&apos;s the same thing
we did earlier. But now, instead of using something like
<b>currentImage,</b> its currentImages&lbrack;i&rbrack;, the first image, the second
image, the third image.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 259. test inspect console, parks.html (153) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image259.webp?raw=true"
  style="width:50%;"
  title="Test Inspect Console, parks.html, images 0, 1 and 2"
  alt="Test Inspect Console, parks.html, images 0, 1 and 2." />
</p>

Let&apos;s take a look and I&apos;m going to go back to the website one more
time. Once again, let&apos;s turn on <b>Inspect Element</b> to see what&apos;s
going on. I go into my <b>Inspect</b> and I want to pick the console tab.
Do you notice over here? It says Image 0, Image 1, Image 2. That&apos;s from
that console.log message I was using. I&apos;m going to refresh again. And
as we go through, uh oh, if you notice.

Oh, I thought I had mistaken there for a second. I thought it was saying
it to the same image every time. So, I didn&apos;t write the greatest code,
right? I could have gone in and written my random codes that it
generates a random image each time but I keep track of the ones I&apos;ve
seen before. Or I could have made sure that there were like 15 or 20
images, so the chance of having a duplicate was less likely. But when
I&apos;m writing code for all of you, I don&apos;t like it to be too big.

I want to show you one more thing. What I&apos;ve done here is I&apos;ve changed
my style, so all my images have an opacity of 0.75 unless I hover over
it.

Let&apos;s think about accessibility for a second, and think about what it
means when we add hover to our style sheet. That means people who are
using a mouse can get that functionality, but people are using the
keyboard cannot. Let&apos;s use looping to also add a bit more accessibility
to our page.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 260. html, no tabindex on images (154) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image260.webp?raw=true"
  style="width:50%;"
  title="HTML, No tab index on any images"
  alt="HTML, No tab index on any images." />
</p>

Back here in my HTML code, I can see that none of my images have an
attribute called tab index. Tab index is what allows people to use the
keyboard to access an element.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 261. current image, set attribute tabindex 0 (154) ~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image261.webp?raw=true"
  style="width:50%;"
  title="In JS, currentImages, set attribute tabindex to 0"
  alt="In JS, currentImages, set attribute tabindex to 0." />
</p>

I could go in here and I could start adding tabindex=&quot;0&quot; to all of my
images. In this case, I would only have to do it for three. But imagine
instead that I had something like 20 images or 40 images, it would be a
real pain to have to go in there and add that to each one. So, I&apos;m
going to go back to my JavaScript. Let&apos;s add two more lines of code
here. What I can do is I can say, <b>currentImages</b>. Instead of the
source, I&apos;m going to use a new function called <b>setAttribute()</b>. I&apos;m
going to say, let&apos;s set the &quot;tabindex&quot; equal to 0. I&apos;m going to save
this.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~ 262. inspect console, tabindex (155) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image262.webp?raw=true"
  style="width:50%;"
  title="Inspect console, check tabindex"
  alt="Inspect console, check tabindex." />
</p>

Let&apos;s go back to the website. I&apos;m going to refresh, and I&apos;m going to
go in and I&apos;m going to check out these elements. Go right here,
<b>Inspect</b>. We can now see that each one of these images has a
tabindex=&quot;0&quot; in there.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 263. style, img hover, focus, opacity 1 (155) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image266.webp?raw=true"
  style="width:50%;"
  title="Style, img hover, focus, opacity 1"
  alt="Style, img hover, focus, opacity 1." />
</p>

My last step is to go back and update my style sheet as well.
Here I am in my style sheet and I&apos;m going to say, &quot;anything I say
people can do with hover let&apos;s also do it with focus.&quot; Back
to our page. Now that I&apos;m here, I&apos;m going to begin to tab. It&apos;s going
to go through my links.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~ 264. inspect console, loop through images (156) ~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image264.webp?raw=true"
  style="width:50%;"
  title="Inspect console, loop through images, update code"
  alt="Inspect console, loop through images, update code." />
</p>

Now you can see it is also allowing me to tab to the images as well.
Hopefully this is showing you that using looping is a faster way to
update your code. Not just in this example where I had three pictures,
but imagine if I&apos;d had 15, 20, or in the case of your future homework,
when you have six or more images.

Being able to loop and update the code allows you to do things more
quickly and avoid a lot of those common typos that at least I happen to
do all the time when I&apos;m updating my code. You&apos;re going to be using
this concept in the next couple of weeks, so make sure that you&apos;re
going in and you&apos;re practicing, you&apos;re trying this code. And if need
be, look things up on your own. There&apos;s always references out there.
Good luck.

<h2 id="ch4-03">4.03 &quot;Cool Stuff&quot; - Friend or Foe?</h2>

As you are able to add additional capabilities to your pages, make sure
that you aren&apos;t doing it at a cost to accessibility or usability.
Reacting to mouse events is a great example. There are a number of great
looking sites out there that are inaccessible because content is hidden
until an event is triggered. If you are going to add Interactivity, make
sure it is accessible to keyboard users as well.

If you plan on adding HTML forms to any future sites, I also highly
suggest that you make sure that you are using labels and placeholders on
your forms. The [Web Accessibility
Initiative](https://www.w3.org/WAI/tutorials/forms/labels/) has some
great resources for learning about this.

<h2 id="ch4-03a">4.03 Final Project Description</h2>

<h3>Overview</h3>

The goal of the final project is to create your own accessible,
interactive photo gallery. Building on concepts you have been learning
in the course you will create your own HTML file with images and
alternative text and then add the code to call functions to react to
common events such page loads, mouse movement, and keyboard access.  In
addition to reusing the functions from the earlier homework you will
want to write code to automatically add the tabindex attribute to your
figures.

Throughout the process make sure to validate your code on W3, Wave, and
aXe.

Once you have completed your assignment you will complete peer reviews. 
Because there are two or three challenging components to this
assignment, I hope you will learn from seeing the different approaches.

<h3>Instructions</h3>

1.  Use the code from the Interactive Photo Gallery as your starting
    point

2.  Update the code to use six images of your choice, making sure to
    include alternative text for each.

3.  Validate your site on <a href="https://validator.w3.org/">
      The W3C Markup Validation Service</a>.

4.  Validate your site using the [Wave](https://wave.webaim.org/)
    validator site or browser extension.

5.  Validate your site using the
    [aXe](https://www.deque.com/axe/?branded=&utm_term=axe%20tool&utm_campaign=Search+-+axe+Pro+-+Branded&utm_source=adwords&utm_medium=ppc&hsa_src=g&hsa_ad=431336436914&hsa_tgt=kwd-869514794839&hsa_mt=e&hsa_ver=3&hsa_acc=7854167720&hsa_kw=axe%20tool&hsa_grp=108623642548&hsa_cam=6769485255&hsa_net=adwords&gclid=Cj0KCQjw4bipBhCyARIsAFsieCwjP8X1-rKNBmI0Baf1mdqBFGK9yyeaxzh4gd2NXK2juuyxxiqn6vQaAtHJEALw_wcB)
    browser extension.

6.  Add the listeners for [onfocus
    Event](https://www.w3schools.com/jsref/event_onfocus.asp) and
    [onblur Event](https://www.w3schools.com/jsref/event_onblur.asp)
    using the same pattern I gave you for the [onmouseover
    Event](https://www.w3schools.com/jsref/event_onmouseover.asp) and
    [onmouseleave
    Event](https://www.w3schools.com/jsref/event_onmouseleave.asp)
    (Don&apos;t delete those events though!).

7.  Test your site&apos;s functionality for mouse movement.

8.  Add the listener for onload -- deciding what you want to call the
    new function.

9.  Add the new function for adding the tabfocus attribute.

10. Add a console.log message to make sure that your event triggers.

11. Write a for loop to loop through each image.

12. Add the tabindex attributes.

13. Test your site&apos;s functionality for keyboard access.

14. Host and share your site

15. Complete your peer reviews.

<h3>Auditing</h3>

Your project will be audited by the careful examination of your code by yourself as well 
as the  [The W3C Markup Validation Service Tool](https://validator.w3.org/) and the 
[WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/).

Yourself will look for the required functionality using both the mouse and a keyboard.

-   There are at least six images.

-   Each image has unique alternative text.

-   When the mouse is over a smaller image the large image is updated with the alt text.

-   When the smaller image is in focus the large image is updated with the alt text.

-   When the mouse is over a smaller image the large image is updated with the proper 
    background image.

-   When the smaller image is in focus the large image is updated with the proper 
    background image.

-   When the mouse is removed from a smaller image the large image is updated with the 
    original text. (Hardcoding is expected here.)

-   When the focus is removed from the smaller image (when it is in the blur state) the 
    large image is updated with the original text. (Hardcoding is expected here.)

-   When the mouse is removed from a smaller image the background for the large image is 
    updated to an empty URL. (Hardcoding is expected here.)

-   When the focus is removed from the smaller image (when it is in the blur state) the 
    background for the large image is updated to an empty URL.  (Hardcoding is expected here.)

-   The tabindex property was added using JavaScript, not hardcoded into the HTML.

-   The site returns no errors from the [The W3C Markup Validation Service Tool](https://validator.w3.org/)

-   The site returns no errors from the [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/)

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3 id="ch4-04z">4.04 Final Project Description</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~ 265. final project description (4.04) (158) ~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image265.webp?raw=true"
  style="width:40%;"
  title="4.04 Final Project Description"
  alt="4.04 Final Project Description." />
</p>

Hi everyone. Let&apos;s talk about the final project.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~ 266. expanding the photo gallery (159) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image266.webp?raw=true"
  style="width:40%;"
  title="Expanding the photo gallery with tabindex"
  alt="Expanding the photo gallery with tabindex." />
</p>

In an earlier assignment, you added the ability to hover over images and display their 
source and alt texts in a different div. In this assignment, you&apos;re going to expand 
upon that same project. But now you are going to use at least six of your own images, and 
we&apos;re going to make it an accessible site by incorporating tabindex as well. I&apos;m 
going to add some additional requirements that you cannot change the HTML to add tabindex, 
you must use JavaScript looping to add the attribute, and just as we wrote a 'Undo' for 
when we were on <b>mouseout</b> and we did like change when your <b>mouseover</b>. Now, 
you are going to use the focus and blur events so that keyboard users have the same 
capabilities as any mouse users.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 267/268. on hover, expand image with alt text (159) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image267.webp?raw=true"
  style="width:45%;"
  title="On hover, expand image"
  alt="On hover, expand image." />
<img src="./images/image268.webp?raw=true"
  style="width:45%;"
  title="On hover, display alt text"
  alt="On hover, display alt text." />
</p>

Let me show you an example. Again, in your earlier example, there were just three images, 
and I gave you those images.

When I would put my mouse over, we would get the updated image and the alt text. When I 
took my mouse off, we would get back to the original, over, out, over, out. In the new 
version, you will add at least three additional images of your own for total of six 
images, and we&apos;re going to use the Tab key to that people can use the same type of 
functionality as with the mouse.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~ 269/270. example, images to tab through with events (160) ~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image269.webp?raw=true"
  style="width:45%;"
  title="Example, images to tab through with events, Styling with a Bandana."
  alt="Example, images to tab through with events, Styling with a Bandana." />
<img src="./images/image270.webp?raw=true"
  style="width:45%;"
  title="More images to tab through with events, With My Boy."
  alt="More images to tab through with events, With My Boy." />
</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 271/272. example, tab through and watch events (160) ~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image271.webp?raw=true"
  style="width:45%;"
  title="Example, tab through images and watch events"
  alt="Example, tab through images and watch events." />
<img src="./images/image272.webp?raw=true"
  style="width:45%;"
  title="Again, tab through and watch events"
  alt="Again, tab through and watch events." />
</p>

Watch as I begin the tab, I&apos;m going to tab again. I&apos;m going to tab a
third time, and now watch what happens when I tab this fourth time. It
goes back to the original, a lot of students get into this trap where
they only write an event for when it goes in focus. But the opposite of
focus is something called blur, make sure that you code for both.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 273. general guidelines (161) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image273.webp?raw=true"
  style="width:40%;"
  title="General Guidelines; Use your own images, validate using W3, Wave, or aXe and 
    be compassionate"
  alt="General Guidelines; Use your own images, validate using W3, Wave, or aXe and 
    be compassionate." />
</p>

As always, we&apos;re going to ask you to follow some general guidelines.
One, make sure that you&apos;re using your own images, preferably something
unique that your peers will enjoy grading. Validate everything, make
sure you&apos;re using W3 to check your HTML syntax, make sure you&apos;re using
Wave to make sure that you have alt text.

Make sure you are using aXe just to check for anything else. If there
are any aXe errors that I left in there, I would encourage you to go in
and fix them up so that your code validates. Do your peer grading with
compassion too. You&apos;re going to want to make sure that you&apos;re giving
really good feedback, if somebody does something incorrectly. You know
what? Great feedback when people do things correctly, that&apos;s great as
well. Leave those helpful comments so that other people can learn from
you, and you might be surprised by how much you learn from thinking
deeply about what you&apos;re seeing in other people&apos;s sites.

I hope you have some fun with this. I hope it&apos;s something that you are
proud of and that you can share with others, and that you leave this
feeling like you&apos;ve really accomplished something and you learned
enough about JavaScript that you can go on with some confidence.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch4-04">4.04 Final Project: Submission Gallery</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~ 274. final project: submission gallery (4.04) (162) ~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image274.webp?raw=true"
  style="width:40%;"
  title="4.04 Final Project: Submission Gallery"
  alt="4.04 Final Project: Submission Gallery." />
</p>

<h3>Optional ungraded submission</h3>

Use this Gallery space to share your final project with others in this
course. This is not required, but will help others that take the course
and create a sense of community. Also, please take some time to review
the work of your peers and offer thoughtful comments. This is not a
graded submission.

<b>Note:</b> The first time you launch the Gallery Tool, you will be asked
to set up your Gallery profile by providing some basic information and
selecting your sharing settings.

<h3>Submitting your file to the Gallery</h3>

On the left side of the screen, click "<b>Upload Submission</b>" and fill
out the required information:

-   Title of your submission

-   A brief description of your submission

-   A link to your hosted project.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch4-04a">4.04 Navigating the Gallery</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
Scroll through the submissions to see the various examples that your
peers have shared. You can also sort the examples by using the available
filters near the top right-hand corner of the Gallery. As you explore
the submissions, we encourage you to leave comments and feedback on the
submissions you view.

This course uses a third-party app, Final Project: Submission Gallery,
to enhance your learning experience. The app will reference basic
information like your name, email, and Coursera ID.

<https://gallery-tool.ai.umich.edu/gallery/account/create/?next=/gallery/submissions/>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 id="ch4-05">4.05 Conclusion</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 275. conclusion (4.05) (163) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image275.webp?raw=true"
  style="width:40%;"
  title="4.05 Conclusion"
  alt="4.05 Conclusion." />
</p>

Hey everybody, congratulations on finishing the Interactivity with
JavaScript course. I hope you&apos;re really proud of what you&apos;ve done so
far, and excited to keep learning more.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 276. congratulations (163) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image276.webp?raw=true"
  style="width:40%;"
  title="Congratulations"
  alt="Congratulations" />
</p>

However, I do want to warn you right now that what we&apos;ve covered in
this class, you&apos;re still considered what we call a noob or newbie. So,
in order to really advance your skills, you&apos;re going to need to keep
working. But the good news is that learning the basics of any
programming language, whether it&apos;s Python, JavaScript, some other type
of scripting language. Is that it makes you feel like you&apos;ve really
done something that can last a long time. And it&apos;s true because these
different concepts of variables, arrays, functions, and looping, these
are concepts that repeat everywhere else. So now that you&apos;ve just begun
programming, you&apos;ll find that learning new languages is actually
easier.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 277. server-side processing (164) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image277.webp?raw=true"
  style="width:40%;"
  title="Server-side processing"
  alt="Server-side processing." />
</p>

Now, we&apos;ve done a lot of client-side processing. So, I just want to
talk to you one more time about the idea that what we&apos;ve learned in
this course is only part of the picture. Learning about
server-side code, or kind of hardcore programming, is something that
you&apos;ll need to explore on your own in other courses if you decide that
the coding part is what you really enjoy of web design. This full stack
or back-end programming, they can help you with this, but it does
require additional resources beyond what most people find on their
laptop or phone.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 278. what next? (164) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image278.webp?raw=true"
  style="width:40%;"
  title="What next? Practice, practice, practice"
  alt="What next? Practice, practice, practice." />
</p>

So, what should you do next then? Well, I hope you continue to practice
your skills, because unlike HTML, and CSS, and some other components of
web design, with JavaScript, if you don&apos;t use it, you&apos;re absolutely
going to lose it. You lose these ideas. You forget about checking the
console. You forget about the logical errors you made earlier. What you
can do now, if you want to make sure you&apos;re still keeping your skills
sharp, is think about joining a meet up, or offering your skills as a TA
at different workshops.

You might also want to consider learning jQuery. jQuery is an extremely
powerful and popular programming language that&apos;s built up from the
basics of JavaScript. However, I always encourage my students to
understand just at least the nuances of JavaScript before you jump into
jQuery because it can make your learning curve so much easier.

Of course, the other thing I must mention is that if you want to do
more, I hope you&apos;ll join us in our Responsive Design course that we&apos;re
doing in this Web Development for Everybody specialization. So, whether
you&apos;re done and you hope to never code again, or you&apos;re really excited
and you want to do more, I can&apos;t say anything else but thank you for
joining me in this course. And thank you to everyone who was on the
message boards mentoring each other and encouraging each other. Good
luck.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 279. thank you! (165) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image279.webp?raw=true"
  style="width:40%;"
  title="Thank you!"
  alt="Thank you!" />
</p>

...the end
<!-- Changes made 7-10-2024 11:07am -->

