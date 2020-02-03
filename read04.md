
# HTML 
### Chapter 1,2 

**The HTML code:** `is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags`

- *Tags* act like containers, They tell you something about the information that lies between their opening and closing tags.
  - `<body></body> `
  - `<head></head> `
  - `<p> Paragraphe</p> ` 
  - `<title></title> `
  - `<h1></h1> to <h6></h6>`
  - `<b>bold</b>` 
  - `<i>italic</i>` 
  - `<sup> used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power</sup>`
  - `<sub>used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas</sub>`
  - `<br /> the browser will automatically show each new paragraph or heading on a new line.`
  - `<hr /> To create a break between themes.`
 
- **HTML pages are text documents.**
- **HTML uses tags (characters that sit inside angled brackets) to give the information they surround special meaning.**
- **Tags are often referred to as elements.**
- **Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes the end.**
- **Opening tags can carry attributes, which tell us more about the content of that element.**
- **Attributes require a name and a value.**
- **To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.**


### Chapter 8- Extra Markup
   - HTML 4: Released 1997
   - XHTML 1.0: Released 2000
     - two main flavors were created:
       - Strict XHTML 1.0, where authors had to follow the rules to the letter
       - Transitional XHTML 1.0, where authors could still use presentational elements (such as <center> and <font>).
       - Third version - XHTML 1.0 Frameset, which allowed web page authors to partition a browser window into several "frames," each of which would hold a different HTML page.
   - HTML5: Released 2000 
     - DOCTYPEs :`<!DOCTYPE html>`
     
  **Comments in HTML**
   - `<!--comment goes here -->`, code that will not be visible in the user's browser
   
  **ID Attribute**
   - is known as a global attribute because it can be used on any element.
    
   
- **DOCTYPES tell browsers which version of HTML you are using.**
- **You can add comments to your code between the `<!-- and -->` markers.**
- **The id and class attributes allow you to identify particular elements.**
- **The `<div>` and `<span>` elements allow you to group block-level and inline elements together.**
- **`<iframes>` cut windows into your web pages through which other pages can be displayed.**
- **The `<meta>` tag allows you to supply all kinds of information about your web page.**
- **Escape characters are used to include special characters in your pages such as <, >, and ©.**

### Chapter 17 - HTML5 Layout
 **HTML5 is introducing a new set of elements that help define the structure of a page.**
 - Headers & Footers 
   - `<header> <footer>`, The main header or footer that appears at the top or bottom of every page on the site.
 - Navigation
   - `<nav>`, is used to contain the major navigational blocks on the site such as the primary site navigation.
 - Articles
   - element acts as a container for any section of a page that could stand alone and potentially be syndicated.
 - Asides
   - When the `<aside>` element is used inside an `<article>` element, it should contain information that is related to the article but not essential to its overall meaning.
   - When the `<aside>` element is used outside of an `<article>` element, it acts as a container for content that is related to the entire page.
 - Sections
   - `<section>` element groups related content together, and typically each section would have its own heading.
 - Heading groups
   - ` <hgroup>`  element is to group together a set of one or more `<h1>` through `<h6>` elements so that they are treated as one single heading. 
 - Figures
   - The `<figure>` element should also contain a `<figcaption>` element which provides a text decription for the content of the `<figure>` element.
 - Linking Around Block-Level Elements
   -  `<a>` element around a block level element that contains child elements. This allows you to turn an entire blockinto a link.
  
- **The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.**
- **The new elements provide clearer code (compared with using multiple `<div>` elements).**
- **Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.**
- **To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.**
