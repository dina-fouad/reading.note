## Introduction 
All Websites are Created by use HTML and CSS but some of them in particular those that are updated regularly and use a content management system (CMS), blogging tools, or e-commerce software often add a few more technologies into the mix.

## How the web works 
***When you visit a website , your browser will be receiving HTML and CSS from the web server which hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server then the web browser interprets the HTML and CSS code to create the page that you see.***

![](https://res.cloudinary.com/academind-gmbh/image/upload/f_auto,q_auto/c_limit,dpr_3.0,g_center,w_400/v1/academind.com/content/tutorials/how-the-web-works/how-the-web-works-big-picture)

## Structure
***HTML uses tags (characters that sit inside angled brackets) to give the information they surround special meaning***
` <title> `   ,  `<body>`, `<h1> to <h6>`
***HTML element is the collection of start tag, its attributes, an end tag and everything in between. On the other hand an HTML tag (either opening or closing) is used to mark the start or end of an element***

![](https://www.tutorialrepublic.com/lib/images/html-element.png)

## Extra Markup
***DOCTYPES tell browsers which version of HTML you are using.***
***we use this tag `<!-- comments --> ` to add comments  for describing your code so if other programmers(or even yourself!) want to see what it's used for,it'll make it more easy to understand.***
***HTML id Attribute: The id attribute is a unique identifier which is used to specify the document.***

```HTML
<!DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
</style>
</head>
<body>

<h1 id="myHeader">My Header</h1>

</body>
</html>
```
***HTML class Attribute: The class attribute is used to specify one or more class names for an HTML element.***
```HTML
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
  <h2>London</h2>
  <p>London is the capital of England.</p>
</div>

<div class="city">
  <h2>Paris</h2>
  <p>Paris is the capital of France.</p>
</div>

<div class="city">
  <h2>Tokyo</h2>
  <p>Tokyo is the capital of Japan.</p>
</div>

</body>
</html>
```
***HTML `<div>` tag: The div tag is known as Division tag. The div tag is used in HTML to make divisions of content on the web page like (text, images, header, footer, navigation bar, etc). In this example, the div tag contains the entire width. It will be displayed div tag each time on a new line, not on the same line.***

***HTML `<span>` tag:  It used to group elements for styling purposes (by using the class or id attributes). A better way to use it when no other semantic element is available.The span tag is very similar to the div tag, but div is a block-level tag and span is an inline tag.***

 ***`<iframe>` is used to display external objects including other web pages within a web page.***

 ***`<meta>` Meta tags are snippets of text that describe a page’s content; the meta tags don’t appear on the page itself, but only in the page’s source code. Meta tags are essentially little content descriptors that help tell search engines what a web page is about.***

 ## HTML5 Layout
 - The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
 - The new elements provide clearer code (compared with using multiple `<div>` elements).
- Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
- To make HTML5 elements work in Internet Explorer 8(and older versions of IE), extra JavaScript is needed, which is available free from Google.

## PROCESS & Design
- It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
- Site maps allow you to plan the structure of a site.
- Wireframes allow you to organize the information that will need to go on each page.
- Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
- You can differentiate between pieces of information using size, color, and style.
- You can use grouping and similarity to help simplify the information you present.

## From the Duckett JS book:
## Introduction
JavaScript allows to make web pages more interactive by accessing and modifying the content and markup used in a web page while it is being viewed in browser.
>Being able to change the content of an HTML page while it is loaded in the browser is very powerful. The examples below rely on the ability to:
>- Access: the content of the page
>- Modify :the content of the page
>- Program: rules or instructions the browser can follow
>- React: to events triggered by the user or browser

## The ABC of Programming
- A script is a series of instructions that a computer can follow to achieve a goal.
- Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.
- To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).
- computers create models of the world using data.
- The models use objects to represent physical things.
    *object can have : properties that tell us about the object ; methods that perform tasks using the properties of that objet ; events which are triggered when a user interacts with the computer.
- Web browsers use HTML markup to create a model of the web page . each element creates its own node (which is a kind of object).

## How to write a script for a web page ?
- It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension.
- The HTML `<script>` element is used in HTML pages to tell the browser to load the JavaScript file (rather like the `<link>` element can be used to load a CSS file).
- If you view the source code of the page in the browser,the JavaScript will not have changed the HTML,because the script works with the model of the web page that the browser has created.