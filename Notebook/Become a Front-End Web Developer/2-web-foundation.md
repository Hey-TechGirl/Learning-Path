### URL
-----
URL - Universal Resource Locator
An URL is quite literally a locator following a universal standard that points at a specific resource somewhere on the web.

A URL is entered in the address bar. When the user hits Return or touches the button on their phone or something else, the browser sends a get request to this URL, which asks the server on the other side to send back all the data it has.

DNS - Domain Name Server

The URL is sent to a domain name server, known more commonly as DNS. The DNS figures out which IP address the domain is pointing at, and passes the request to the server on that IP address. The server retrieves all the data, aka the resource, and sends it back to the browser. 

The URL is sent to a domain name server, known more commonly as DNS. The DNS figures out which IP address the domain is pointing at, and passes the request to the server on that IP address. The server retrieves all the data, aka the resource, and sends it back to the browser. 

### Page Struture
-----
Look a little bit deeper, and what we find is a carefully-structured document displayed as a collection of boxes with different properties.

  - there's a header section containing the site title, logo, and a navigation menu. 
  - there's the main section containing an article which in turn contains a heading or collection of paragraphs and an image.
  - there's a sidebar section with some advertising.
  - there's a footer section with company information. 

**The web browser is an advanced viewer for web documents.**

### The structure of a web document
-----
When looking at the contents in the browser, it's not immediately obvious that everything is a box within a box within a box. This nesting of elements serves two purposes. On the code end, it allows the author to create a highly-structured document with clear relationships between different elements. This allows servers, browsers, and other applications to figure out how the content is structured without needing to understand the content itself. 

On the display end, nesting allows for style inheritance. Using the property of style inheritance, you can position elements relative to their parent elements, create flexible boxes and grid layouts, create interactions that impact parent, child or sibling elements, and control every detail of every piece of content in the document.

Any time a browser is asked to display an HTML document, it creates a ***document object model*** or **DOM**, which is a structural representation of the elements in the document and their relationships. Every element is a box, and that every box is a node on the tree connected to its parents, siblings, and descendants via branches is key to understanding how the browser sees the Web and how you can give the browser sufficient information to do what you want.

### HTML
-----
HTML was created to allow humans to write highly-structured documents which could be interpreted consistently and universally by any rendering engine supporting the language. HTML is a declarative markup language, meaning it describes the contents of a document. HTML does not provide instructions about the control flow or processing or interactions with that content.

**The web was created to allow everyone to share information through documents over the internet. The web was built to make information accessible, shareable, and linkable.**

### Purpose of Web Code
-----
When writing for the web, you're writing for two audiences, the human being accessing the content and the technology used to access that content. HTML is a declarative, semantic, markup language, meaning we can use it to communicate meaning to whatever client application opens the document. 

In addition to the standard content and markup, all web documents contain metadata that further describes the document and it's contents. Metadata describes sections, elements and contents within the documents, adds structure to the data, and in some cases, describes the behavior of these sections, elements and contents. This includes schema, microformat, ARIA and other tools. 

All of these tools are designed to do the same thing. To assist humans in finding and accessing the content they are looking for, and to assist clients, search engines and other tools in cleaning meaningful data about the document and it's content, again, to assist human users. 

**ARIA - Accessible Rich Internet Application attributes.**

### Web browser
-----

The inherent challenge of the browser is that it is an interpreter and only recently have we gotten to a point that most browsers interpret the same code in more or less the same way. Every browser has its idiosyncrasies and opinions about how the web should work and all browsers and constantly competing for market dominance so they add new features and try to introduce new standards all the time.

For web designers and developers, this means it's not enough to test your code in one browser, it has to be tested in as many browsers and browser versions as possible.

The browser is a tool for humans to access and browse web content.

### Code Editor
-----
Technically you can write code for the web in any application that allows you to write and save plain text files, but a code editor is a tool specifically designed for editing code, so it's the best tool for the job.

They are used to write or develop the code that powers the web and since that code, HTML, CSS, JavaScript, and so on, is open and uncompiled, it doesn't matter which code editor you use and you can open the same files and work with them in any code editor at any time. In other words, for the most part, code editor preference is exactly that, a preference. 

First, there is the syntax highlighting. The point of syntax highlighting is to make sure the developer can see, at a glance, what a certain string of code is doing and whether it's doing the right thing. Secondly, most code editors provide code hinting. Start typing something and the editor will provide you with a list of similar available options, making your process quicker and less error-prone. Thirdly, most code editors provide project management, allowing you to define a folder as a project and work within it. This includes project navigation to access all project files, project-wide debugging, and more.

