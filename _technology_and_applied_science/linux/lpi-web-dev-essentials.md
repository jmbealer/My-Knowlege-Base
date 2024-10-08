---
title: Web Development Essentials
author: Justin Bealer
date_created: 2024-08-30, 02-07-31
date_modified: 2024-09-17, 09-29-59
reference: 
description: 
aliases: 
tags: 
---
# Web Development Essentials

## Links

## Books

## Objectives

        4.1 031 Software Development and Web Technologies
            4.1.1 031.1 Software Development Basics (weight: 1)
            4.1.2 031.2 Web Application Architecture (weight: 2)
            4.1.3 031.3 HTTP Basics (weight: 3)
        4.2 032 HTML Document Markup
            4.2.1 032.1 HTML Document Anatomy (weight: 2)
            4.2.2 032.2 HTML Semantics and Document Hierarchy (weight: 2)
            4.2.3 032.3 HTML References and Embedded Resources (weight: 2)
            4.2.4 032.4 HTML Forms (weight: 2)
        4.3 033 CSS Content Styling
            4.3.1 033.1 CSS Basics (weight: 1)
            4.3.2 033.2 CSS Selectors and Style Application (weight: 3)
            4.3.3 033.3 CSS Styling (weight: 2)
            4.3.4 033.4 CSS Box Model and Layout (weight: 2)
        4.4 034 JavaScript Programming
            4.4.1 034.1 JavaScript Execution and Syntax (weight: 1)
            4.4.2 034.2 JavaScript Data Structures (weight: 3)
            4.4.3 034.3 JavaScript Control Structures and Functions (weight: 4)
            4.4.4 034.4 JavaScript Manipulation of Website Content and Styling (weight: 2)
        4.5 035 NodeJS Server Programming
            4.5.1 035.1 NodeJS Basics (weight: 1)
            4.5.2 035.2 NodeJS Express Basics (weight: 4)
            4.5.3 035.3 SQL Basics (weight: 3)

Minimally Qualified Candidate

The candidate has a basic understanding of software development, the principle of the world wide web and web applications. The candidate is able to use semantic markup to create simple web sites and extend these websites with links, media elements and forms. The candidate is able to define how these contents are displayed and placed on a website. Furthermore, the candidate is familiar with core programming concepts such as variables, conditions, loops and functions. The candidate can create simple programs which run in a web browser. The candidate is also able to develop server-side programs which can process data submitted from a website, persist this data in a database and generate dynamic web sites based on the database contents.

Version Information

These objectives are A DRAFT FOR version 1.0.0.

Translations of Objectives

The following translations of the objectives are available on this wiki:

    English
    Brazilian Portuguese
    Chinese (Simplified)
    Chinese (Traditional)
    Dutch
    French
    German
    Italian
    Japanese
    Spanish

Objectives
031 Software Development and Web Technologies
031.1 Software Development Basics (weight: 1)

Weight
 1

Description
 
The candidate should be familiar with the most essential concepts of software development and be aware of important programming languages.

**Key Knowledge Areas:**

    Understand what source code is
    Understand the principles of compilers and interpreters
    Understand the concept of libraries
    Understand the concepts of functional, procedural and object-oriented programming
    Awareness of common features of source code editors and integrated development environments (IDE)
    Awareness of version control systems
    Awareness of software testing
    Awareness of important programming languages (C, C++, C#, Java, JavaScript, Python, PHP)

031.2 Web Application Architecture (weight: 2)

Weight
 2

Description
 
The candidate should understand common standards in web development technology and architecture.

**Key Knowledge Areas:**

    Understand the principle of client and server computing
    Understand the role of web browsers and be aware of commonly used web browsers
    Understand the role of web servers and application servers
    Understand common web development technologies and standards
    Understand the principles of APIs
    Understand the principle of relational and non-relational (NoSQL) databases
    Awareness of commonly used open source database management systems
    Awareness of REST and GraphQL
    Awareness of single-page applications
    Awareness of web application packaging
    Awareness of WebAssembly
    Awareness of content management systems

Files, terms, and utilities:

    Chrome, Edge, Firefox, Safari, Internet Explorer
    HTML, CSS, JavaScript
    SQLite, MySQL, MariaDB, PostgreSQL
    MongoDB, CouchDB, Redis

031.3 HTTP Basics (weight: 3)

Weight
 3

Description
 
The candidate should be familiar with the basics of HTTP. This includes understanding HTTP headers, content types, caching, and status codes. Furthermore, the candidate should understand the principles of cookies and their role for session handling and be aware of advanced HTTP features.

**Key Knowledge Areas:**

    Understand HTTP GET and POST methods, status codes, headers and content types
    Understand the difference between static and dynamic content
    Understand HTTP URLs
    Understand how HTTP URLs are mapped to file system paths
    Upload files to a web server's document root
    Understand caching
    Understand cookies
    Awareness of sessions and session hijacking
    Awareness of commonly used HTTP servers
    Awareness of HTTPS and TLS
    Awareness of web sockets
    Awareness of virtual hosts
    Awareness of common HTTP servers
    Awareness of network bandwidth and latency requirements and limitations

Files, terms, and utilities:

    GET, POST
    200, 301, 302, 401, 403, 404, 500
    Apache HTTP Server ("httpd"), NGINX

032 HTML Document Markup
032.1 HTML Document Anatomy (weight: 2)

Weight
 2

Description
 
The candidate should understand the anatomy and syntax of an HTML document. This includes creating basic HTML documents.

**Key Knowledge Areas:**

    Create a simple HTML document
    Understand the role of HTML
    Understand the HTML skeleton
    Understand the HTML syntax (tags, attributes, comments)
    Understand the HTML head
    Understand meta tags
    Understand character encoding

Files, terms, and utilities:

    <!DOCTYPE html>
    <html>
    <head>
    <body>
    <meta>, including the charset (UTF-8), name and content attributes

032.2 HTML Semantics and Document Hierarchy (weight: 2)

Weight
 2

Description
 
The candidate should be able to create HTML documents with a semantic structure.

**Key Knowledge Areas:**

    Create markup for contents in an HTML document
    Understand the hierarchical HTML text structure
    Differentiate between block and inline HTML elements
    Understand important semantic structural HTML elements

Files, terms, and utilities:

    <h1>, <h2>, <h3>, <h4>, <h5>, <h6>
    <p>
    <ul>, <ol>, <li>
    <dl>, <dt>, <dd>
    <pre>
    <blockquote>
    <strong>, <em>, <code>
    <b>, <i>, <u>
    <span>
    <div>
    <main>, <header>, <nav>, <section>, <footer>

032.3 HTML References and Embedded Resources (weight: 2)

Weight
 2

Description
 
The candidate should be able to link an HTML document with other documents and embed external content, such as images, videos and audio in an HTML document.

**Key Knowledge Areas:**

    Create links to external resources and page anchors
    Add images to HTML documents
    Understand key properties of common media file formats, inlcuding PNG, JPG and SVG
    Awareness of iframes

Files, terms, and utilities:

    id attribute
    <a>, including the href and target (_blank, _self, _parent, _top) attributes
    <img>, including the src and alt attributes 

032.4 HTML Forms (weight: 2)

Weight
 2

Description
 
The candidate should be able to create simple HTML forms containing input elements of various types.

**Key Knowledge Areas:**

    Create simple HTML forms
    Understand HTML form methods
    Understand HTML input elements and types

Files, terms, and utilities:

    <form>, including the method (get, post), action, and enctype attributes
    <input>, including the type (text, email, password, number, date, file, range, radio, checkbox, hidden) attribute
    <button>, including the type (submit, reset, hidden, button) attribute
    <textarea>
    common form element attributes (name, value, id)
    <label>, including the for attribute

033 CSS Content Styling
033.1 CSS Basics (weight: 1)

Weight
 1

Description
 
The candidate should understand the various ways to style an HTML document using CSS. This includes the structure and syntax of CSS rules.

**Key Knowledge Areas:**

    Embedding CSS within an HTML document
    Understand the CSS syntax
    Add comments to CSS
    Awareness of accessibility features and requirements

Files, terms, and utilities:

    HTML style and type (text/css) attributes
    <style>
    <link>, including the rel (stylesheet), type (text/css) and src attributes
     ;
    /*,*/

033.2 CSS Selectors and Style Application (weight: 3)

Weight
 3

Description
 
The candidate should be able to use selectors in CSS and understand how CSS rules are applied to elements within an HTML document.

**Key Knowledge Areas:**

    Use selectors to apply CSS rules to elements
    Understand CSS pseudo-classes
    Understand rule order and precedence in CSS
    Understand inheritance in CSS

Files, terms, and utilities:

    element; .class; #id
    a, b; a.class; a b;
     :hover, :focus
    !important

033.3 CSS Styling (weight: 2)

Weight
 2

Description
 
The candidate should use CSS to add simple styles to the elements of an HTML document.

**Key Knowledge Areas:**

    Understand fundamental CSS properties
    Understand units commonly used in CSS

Files, terms, and utilities:

    px, %, em, rem, vw, vh
    color, background, background-*, font, font-*, text-*, list-style, line-height

033.4 CSS Box Model and Layout (weight: 2)

Weight
 2

Description
 
The candidate should understand the CSS box model. This includes defining the position of elements on a website. Additionally, the candidate should understand the document flow.

**Key Knowledge Areas:**

    Define the dimension, position and alignment of elements in a CSS layout
    Specify how text flows around other elements
    Understand the document flow
    Awareness of the CSS grid
    Awareness of responsive web design
    Awareness of CSS media queries

Files, terms, and utilities:

    width, height, padding, padding-*, margin, margin-*, border, border-*
    top, left, right, bottom
    display: block | inline | flex | inline-flex | none
    position: static | relative | absolute | fixed | sticky
    float: left | right | none
    clear: left | right | both | none

034 JavaScript Programming
034.1 JavaScript Execution and Syntax (weight: 1)

Weight
 1

Description
 
The candidate should be able to execute JavaScript files and inline code from an HTML document and understand basic JavaScript syntax.

**Key Knowledge Areas:**

    Run JavaScript within an HTML document
    Understand the JavaScript syntax
    Add comments to JavaScript code
    Access the JavaScript console
    Write to the JavaScript console

Files, terms, and utilities:

    <script>, including the type (text/javascript) and src attributes
     ;
    //, /* */
    console.log

034.2 JavaScript Data Structures (weight: 3)

Weight
 3

Description
 
The candidate should be able to use variables in JavaScript code. This includes understanding values and data types. Furthermore, the candidate should understand assignment operators and type conversion and be aware of variable scope.

**Key Knowledge Areas:**

    Define and use variables and constants
    Understand data types
    Understand type conversion/coercion
    Understand arrays and objects
    Awareness of the variable scope

Files, terms, and utilities:

    =, +, -, *, /, %, --, ++, +=, -=, *=, /=
    var, let, const
    boolean, number, string, symbol
    array, object
    undefined, null, NaN

034.3 JavaScript Control Structures and Functions (weight: 4)

Weight
 4

Description
 
The candidate should be able to use control structures in JavaScript code. This includes using comparison operators. Furthermore, the candidate should be able to write simple functions and understand function parameters and return values.

**Key Knowledge Areas:**

    Understand truthy and falsy values
    Understand comparison operators
    Understand the difference between loose and strict comparison
    Use conditionals
    Use loops
    Define custom functions

Files, terms, and utilities:

    if, else if, else
    switch, case, break
    for, while, break, continue
    function, return
    ==, !=, <, <=, >, >=
    ===, !==

034.4 JavaScript Manipulation of Website Content and Styling (weight: 2)

Weight
 2

Description
 
The candidate should understand the HTML DOM. This includes manipulating HTML elements and CSS properties through the DOM using JavaScript as well as using DOM events in simple scenarios.

**Key Knowledge Areas:**

    Understand the concept and structure of the DOM
    Change the contents and properties of HTML elements through the DOM
    Change the CSS styling of HTML elements through the DOM
    Trigger JavaScript functions from HTML elements

Files, terms, and utilities:

    document.getElementById(), document.getElementsByClassName(), document.getElementsByTagName(),document.querySelector(), document.querySelectorAll()
    innerHTML, setAttribute(), removeAttribute() properties and methods of DOM elements
    classList, classList.add(), classList.remove(), classList.toggle() properties and methods of DOM elements
    onClick, onMouseOver, onMouseOut attributes of HTML elements

035 NodeJS Server Programming
035.1 NodeJS Basics (weight: 1)

Weight
 1

Description
 
The candidate should understand the basics of NodeJS. This includes running a local development server as well as understanding the concept of NPM modules.

**Key Knowledge Areas:**

    Understand the concepts of Node.js
    Run a NodeJS application
    Install NPM packages

Files, terms, and utilities:

    node [file.js]
    npm init
    npm install [module_name]
    package.json
    node_modules

035.2 NodeJS Express Basics (weight: 4)

Weight
 4

Description
 
The candidate should be able to create a simple dynamic website with the Express web framework. This includes defining simple Express routes as well as serving dynamic files through the template engine EJS.

**Key Knowledge Areas:**

    Define routes to static files and EJS templates
    Serve static files through Express
    Serve EJS templates through Express
    Create simple, non-nested EJS templates
    Use the request object to access HTTP GET and POST parameters and process data submitted through HTML forms
    Awareness of user input validation
    Awareness of cross-site Scripting (XSS)
    Awareness of cross-site request forgery (CSRF)

Files, terms, and utilities:

    express and body-parser node module
    Express app object
    app.get(), app.post()
    res.query, res.body
    ejs node module
    res.render()
    <% … %>, <%= … %>, <%# … %>, <%- … %>
    views/

035.3 SQL Basics (weight: 3)

Weight
 3

Description
 
The candidate should be able to create individual tables in an SQLite database and add, modify and delete data using SQL. Furthermore, the candidate should be able to retrieve data from individual tables and execute SQL queries from NodeJS. This does not include referencing or combining data between multiple tables.

**Key Knowledge Areas:**

    Establish a database connection from NodeJS
    Retrieve data from the database in NodeJS
    Execute SQL queries from NodeJS
    Create simple SQL queries excluding joins
    Understand primary keys
    Escape variables used in SQL queries
    Awareness of SQL injections

Files, terms, and utilities:

    sqlite3 NPM module
    Database.run(), Database.close(), Database.all(), Database.get(), Database.each()
    CREATE TABLE
    INSERT, SELECT, DELETE, UPDATE

Navigation menu

    Page Discussion View source History 

    Log in 

Exam Objectives

    Linux Essentials v1.6
    Security Essentials v1.0
    Web Development Essentials v1.0
    Open Source Essentials v1.0
    LPIC-1 v5.0
    LPIC-2 v4.5
    300 Objectives v3.0
    303 Objectives v3.0
    305 Objectives v3.0
    306 Objectives v3.0
    DevOps Tools Engineer Objectives v1.0
    BSD Specialist Objectives v1.0

Search

Navigation

    Main page
    Recent changes
    LPI Website

Tools

    What links here
    Related changes
    Special pages
    Printable version
    Permanent link
    Page information

Powered by MediaWiki

    This page was last modified on 11 June 2020, at 05:05. About LPI Wiki 
