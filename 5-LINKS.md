# Links
Links are a crucial part of the internet. They do exactly as their name sounds. They allow us to navigate and connect to other web pages.

# The Simplest Link
```html
<a href="somewebsite.com">Website Name</a>
```
To create a link, we use the *a* tag. The *a* stands for anchor. You'll notice that the anchor tag has a *href* attribute. This stands for hyper reference. This is where you would put the web page you are linking to.
For example:
```html
<a href="https://www.webuildblack.com">We Build Black</a>
```
This renders to this:
![link](./images/link.png)

## Global and Relative Links
Links are actually something called URLs (Uniform Resource Locator), and we can type them in two ways.

### Global Links
Global links refer ot the absolute location of a page. They start with a protocol (usually *http* or *https*), then the domain name (ex:webuildblack.com). Here are some examples of global links:
* *https://colorforcode.com/*
* *https://www.youtube.com/channel/UC4ZjOw_KACO5GSa2ShDuv3Q*
* *https://etsy.com/*

### Relative Links
Relative links point to places on the computer's current system. So think if it as "relative to where you are" links. For example:
* *./images/elephants.jpg* - This is a URL to an image in the same directory as the current page (the './' is optional)
* *../all-images/* - The two dots (..) means to up to the parent directory. Then it says go into another directory in the parent called 'all-images'.
* */documentation* - The forwards slash (/) at the beginning means go to the top of the project. After going to the top of the project, we go into a folder called "documentation"

## Linking inside a page
You can actually link to parts of a page. For example, you can put an *id* attribute on a tag like this:
```html
<button id="buy-button">Click me!</button>
```
Then to link to it, we create an anchor tag with the *href* value the same at the buttons *id* value.
```html
<a href="buy-button">I go the buy button</button>
```
Now, if you click on the anchor tag it will snap your screen to where the buy button is. We'll go deeper into the *id* attribute in the CSS lessons. It's actually really important.

## Email Links
Have you ever clicked an email address on a web page, and your computer automatically opened your email application with a draft to the address you just clicked on? That was an email link and you create them as so:
```html
<a href="mailto:info@webuildblack.com">Say hi!</a>
```

## Link titles
Link titles are the messages you see when hovering your mouse over a link. To set a title for a link you must use the *title* attribute. For example:
```html
<a href="https://www.webuildblack.com" title="A Community for Black Technologists">Check us out</a>
```
Put this in your HTML doc and hover the link. You should see that message pop up.

## Stick around for the next episode...
In the next lesson, we'll be getting pretty with images. Our pages are gonna start looking a lil more lively. Don't worry, you'll be done with your karate drills soon :)