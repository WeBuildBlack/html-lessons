# Basic Template
Ok, we finally get to write some code. I want you to create a file called `template.html`. Next, open it up in your favorite editor. Here are some editors if you don't have one:
* [Visual Studio Code](https://code.visualstudio.com/download)
* [Sublime](https://www.sublimetext.com/3)
* [Atom](https://atom.io/)

Once you have it open type this template code into your `template.html` document:

```html
1. <!doctype html>
2. <html>
3.     <head>
4.         <title>Our Funky HTML Page</title>
5.         <meta name="description" content="Our first page">
6.         <meta name="keywords" content="html tutorial template">
7.     </head>
8.     <body>
9.         Content goes here.
10.     </body>
11. </html>
```
Ok, let's go through this line by line:
* Line 1 - This special tag goes at the top of every HTML file to identify what type of code is being used
* Lines 2 and 11 - These `html` tags open and close the HTML document
* Lines 3 and 7 - The `head` tag defines the extra data to be pulled in before the document is rendered
* Line 4 - The `title` tag defines the title that displays at the top of the  browser window.
* Lines 5 and 6 - The `meta` tags are used to describe the document for search engines
* Lines 9 and 11 - The `body` tag encloses all the actual content that you see on screen

## The Doctype
```html
<!doctype html>
```
This tag goes at the top of every page before everything.
It's really less of a tag and more of an instruction to the browser that we're using HTML5, which is the latest version. It's really that simple

## The head
```html
<head></head>
```
The `head` of the HTML document holds all of the extra information about a document. Anything that isn't exactly content usually goes in here. There are more tags that can go in the head but we've included the basics every page should have in the template.

### The title
```html
<title></title>
```
The `title` tag is what defines your pages title. It's used in quite a few places:
* The browser will include it at the top of the window
* If you save the page as a favourite the title will be used here
* Search engines use the title when they list your page in their search results
* Other sites may use the title when someone links to your page

This is a really important part of your page and you should really take some time to craft it. It should be something descriptive and short.

### Meta tags
```html
<meta name="description" value="some description"></meta>
<meta name="keywords" value="keyword1 keyword2"></meta>
```
The `meta` tag is primarily used by search engines to describe your website and sharing/social media sites to find you. You will see the *description* in the search results under the title.

## The Body
```html
<body></body>
```
The `body` is where you put all your actual content. Content is everything that you see on the screen. In future lessons we'll go into what tags you can put in here to display content.

## Stick around for the next episode...
Next lesson we'll jump into some tags to build content. That's right you'll finally get to *see* something!