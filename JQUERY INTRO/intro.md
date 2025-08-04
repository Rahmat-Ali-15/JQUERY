#                      jQuery INTRODUCTION
<========================================================>

## What is jQuery?
* jQuery is a JavaScript Library.
* jQuery is greatly simplifies JavaScript programming.
* jQuery is easy to learn.
* A lighweight and consise JS library.
* Help to make JS programming easy and faster.
* Feature rich and open source library which simplifies complex task.
* Easy to use API which is compatible with browsers.
* Common tasks into built-in methods.
* Reduce time in writting lines of code.
* jQuery is a lightweight, **"write less, do more".** JaavaScript library.
* The purpose of jQuery is to make it much easier to use JavaScript on your website.
* jQuery takes a lot of common tasks that require many lines of JavaScript code to accoumplish, and wraps them into methods that you can call with a single line of code.
* jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

## Getting elements by using javascript
* document.getElementById("IdName");
* document.getElementByClassName("ClassName");
* document.getElementByTagName("TagName");

## Getting elements by using jQuery
* $("#IdName") => Getting element by id
* $(".ClassName") => Getting element by class
* $("TagName") => Getting element by TagName

## DOCUMENT OBJECT MODEL (DOM) IN JAVASCRIPT
* When a webpage or html page loads in the browsers, browser creates a DOM (document object model) for the page.
* **DOCUMENT** - HTML PAGE (DOCUMENT)
* **OBJECT** - TAGS OR ELEMENTS AND ATRIBUTES IN HTML PAGE
* **MODEL** - IN DOM, TREE STRUCTURE OF HTML ELEMENTS
* **So the html DOM is browser created tree structure arrangement of elements and attributes.**

* **DOM** is a standard to understand the structure of html page so tht we can create, read, update, and delete and manages dom elements using javascript methods.

* **HTML DOM** helps us to understand and control the element structure using javascript methods. If we understand the dom structure of a html page, we can easily control its elments, attributes and all nodes.

# What is NODE?
* According to html dom, everything is in html page is node
* Entire document is **document node**
* Each element in a html page is **element node**
* All text of document is **text nodes**
* All attributes of a elements are **attribute nodes**
* Comments of page are **comment nodes**

## The jQuery library contains the follwoing features:
* HTML / DOM manipulation
* CSS manipulation
* HTML event methods
* Effects and animations
* AJAX

## Benefits of jQuery over JS
* **Unobtrusive**
    * Web page designing through unobtrusive JS
    * Separates functionality between presentation and structure of web page

* **Lightweight**
    * Reduced library size is in kilobytes(KB)
    * Browser cache the libary throughout websites instead of downloading it.

* **Easy to use**
    * Simple and robust syntax
    * Reduced lines of codes
    * Library uses CSS3 selector specification

* **Big and focused library**
    * Perform variety of functions through single library
    * jQuery offers several utility functions

* **Extensibility**
    * Plugin framework third party and official plugins
    * Any feature can be included through plugins

* **Browser Compatibility**
    * Resolves cross browser issues
    * jQuery implemented compatibility code

* **Strong Community**
    * Exclusive community where developers improve functionality
    * Offers several plugins which accelerate web development process strong community

* **AJAX Support**
    * Creates AJAX templates
    * Offers smooth interfaces and efficient loading AJAX support

* **Comprehensive Documentation**
    * Official website has in-depth documentation and tutorials
    * Helps beginners for easy use

## Why jQuery?
* There are lots of other javascript libraries out there, but jQuery is probably the most popular, and also the most extendable.

* **Many of the biggest companies on the web use** jQuery, such as :
    * Google
    * Microsoft
    * IBM
    * Netflix

# Adding jQuery to our Web Pages
There are several ways to start using jQuery on your web site.

* Download the jQuery library from **jQuery.com**
* Include jQuery from a **CDN (Content Delivery Network)**, like Google

## Downloading jQuery
There are two versions of jQuery available for downloading

* **Production Version** - This is for our live website because it has been minigied and compressed

* **Develompent version** - This is for testing and development (uncompressed and readable code)

## jQuery CDN (Content Delivery Network)
If we don't want to download and host jQuery ourself, we can include it from a CDN

* Both Google and Microsoft host jQuery
* To use jQuery from Google or Microsoft, use one of the following:
    * Google CDN
    * `<head> <sctipt src="https://ajax.googleapis.com/ajax//libs/jquery/3.4.1/jquery.min.js"></script> </head>`


# Syntax of jQuery
* Basic Syntax : **$(selector).action()** 
* A $ sign to define / access jQuery
* A selector to find HTML elements
* A jQuery action() to be performed on the elements

# Selectors in jQuery
* **Basic Selectors**

    * **Selection by Id**
        * $("#IdName")
    * **Selection by Class**
        * $(".ClassName")
    * **Selection by Tag**
        * $("TagName")

* **Advanced Selectors**

    * **Universal selector**
        * $(" * ")
    * **Selecting list items**
        * $(" ul li ");
    * **Selecting multiple classes**
        * $(" .c1, .c2 ")
    * **Selecting multiple elements at a time**
        * $("div, p, h1")
    * **Selecting first p element among all p elements**
        * $(" p:first ")
    * **Selecting last p element among all last elements**
        * $(" p:last ")
    * **Selecting li of even numbers**
        * $(" li:even ")
    * **Selecting li of odd numbers**
        * $(" li:odd ")
    * **Selecting first li among all li**
        * $(" li:first-child ")
    * **Selecting li equal to 2**
        * $(" ul li:eq(2) ")
    * **Selecting li less than 2**
        * $(" ul li:lt(2) ")
    * **Selecting li greater than 2**
        * $(" ul li:gt(2) ")
