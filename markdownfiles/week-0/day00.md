## ======= Day-00 ======= ##
Get to know about the following Things
* Internet and how it works
* DNS
* Web server
* Web Browser
* Web page
* Web site
* Search Engine
* Intro to HTML,CSS & Javascript

## Internet  
* The Internet is a large network of computers which communicate all together. Internet invovles devices like routers,modem,cables,ISP,etc.  
Read Article:
[Click Here](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work)  
To watch vedio:
[Click Here](https://www.youtube.com/watch?v=eHp1l73ztB8)   


## DNS 
* DNS stands for Domain Name System
* Used to identify any website easily on Internet,instead of IP address(four numbers separated by dots)
* DNS consists of servers 
1. root name servers(.)
2. Top Level Domain servers(.com,.in,.org,.gov)
3. Authoritative name servers(actual domain name stored in servers acquired by domain registrar)

## Difference between Web servers,Web page,web site,web browser and search Engine

* **web browser :** A piece of software application the retrieves and display web pages. e.g Google chrome,Mozzila firefox,Microsoft edge,etc.
* **web page :** A web page is document that contains links to other web page,text,images,vedios,etc.
* **web site :** A web site has a domain name and it consists of multiple linked  web pages.
* **web server :** A Computer which hosts the web site on the internet and send web pages of hosting web site to it's users as per request.
* **search engine :** A search engine is a special kind of web site that helps you to find web sites and particular web pages of web sites.  

To know more about - [Click Here](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/Pages_sites_servers_and_search_engines)

# HTML,CSS & Javascript 

![](https://brytdesigns.com/_next/image?url=https%3A%2F%2Fadmin.brytdesigns.com%2Fwp-content%2Fuploads%2F2019%2F12%2Fhtml_css_javascript_infographic-1024x614.png&w=1200&q=75)

## HTML
* Stands for Hyper Text Markup Language
* HTML is the raw data that a webpage is built out of. All the text, links, cards, lists, and buttons are created in HTML.

## CSS
* Stands for Cascading Style Sheet
* HTML puts information on a webpage, and CSS positions that information, gives it color, changes the font, and makes it look great! 
* Used to alter the layout and formatting of your website.  

>**Note:**
Many great resources out there keep referring to HTML and CSS as programming languages, but if you want to get technical, labeling them as such is not quite accurate, because they are only concerned with presenting information. They are not used to program any logic.

## JavaScript
* JavaScript is a programming language,which gives you the tools that you need to alter the behavior of different elements that are found on a website page. With this tool, you can add a layer of interactivity to the CSS and HTML elements on your website.


# HTML
* HTML (HyperText Markup Language) defines the structure and content of webpages. We use HTML elements to create all of the paragraphs, headings, lists, images, and links that make up a typical webpage
* Almost all elements on an HTML page are just pieces of content wrapped in opening and closing HTML tags.
* Opening tags tell the browser this is the start of an HTML element. They are comprised of a keyword enclosed in angle brackets <>.
* Closing tags ends the HTML element and uses a forward slash before keyword i.e,</>
* HTML has a vast list of predefined tags that you can use to create all kinds of different elements. 
* It is important to use the correct tags for content. 
* Using the correct tags can have a big impact on two aspects of your sites
1. How they are ranked in search engines 
2. How accessible they are to users who rely on assistive technologies, like screen readers, to use the internet.

## Basic Structure of HTML file
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
  </head>

  <body>
    <h1>Hello World!</h1>
  </body>
</html>
```

* doctype declaration purpose is to tell the browser what version of HTML it should use to render the document.
* html element is what’s known as the root element of the document and has an lang attribute to specify the language of text content.
* head elememt consists of meta information of our web page and have descendants elements like meta & title 
* meta element to display special characters and symbols from different languages in the browser and title element to display title on the browser's tab.
* body element contains the actual content displayed to our user.
