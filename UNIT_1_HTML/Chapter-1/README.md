# Chapter 1: Introduction

## What I Learned Today?
**1. What is HTML?**
    HTML stands for "Hyper Text Markup Language"
    HyperText - The text that contains links to another websites, documents and texts.
    Markup - Way to give instruction to computer about how content should be displayed and organized
    Language - Means language that a coupter , server or browser interpret and understand

**2. HTML Syntax :- What are tags, opening & closing tag, elements?**

- **Tag** - HTML tags wo keywords hain jo angle brackets < > ke andar likhte hain. Ye browser ko batate hain ki content ko kaise display karna hai or unka kuch special meaning h jo SEO mein use hote h. Example- `<h1></h1>`

- **Opening Tag** - Html tag ke aage wale hise ko opening tag kehte h. Example- `<h1>, <p>, <div>`, etc.

- **Closing Tag** - HTML Tag ke end wale hise ko closing tag kehte h. Jo content ki boudery set kerta h. Example- `</h1>, </p>, </div>`, etc

- **Elements** - HTML Tag ko hi element kehte h lekin keval tab jab unke ander content ho. Example- `<h1>This is an Element.</h1>` ye pura ek element h.

- **Bonus**
    *Self-Closing Tag* - Ye wo html tag jinka koi closing tag nhi hota or inke ander content nhi likha jata but atrribute hote h, inka sytax thoda alag hota.
        *Example* - `<br>, <img>, <video>, <hr>, <meta>, <link>`, etc.

### HTML Boilerplate Structure
Here learned the essential HTML boilerplate that forms the foundation of every web page. The boilerplate is the basic HTML structure that every HTML document should have.

### Basic HTML Boilerplate Code

### HTML CODE - EXPLAIN

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day-001 | The Boiler Plate Basics</title>
    </head>
    <body>
        <!-- Code written here -->
    </body>
    </html>

### How to Write Boiler Plate Code?
*"This boiler plate code can we written manually but in vscode(currently using) ther is two way to write in with no minutes"*
#### 1. First Way - html:5
Write html you see 3 suggestions and click on "html:5" option and you will see that it will automatically writen

#### 2. Second way - !
Just type ! from your keyboard and hit enter and you see the boiler plate code writen automatically like copy and paste.

### Breaking Down Each Component
#### 1. `<!DOCTYPE html>`

Tells the browser this is an HTML5 document

Must be the first line in any HTML file

Not case-sensitive but typically written in uppercase

#### 2. `<html lang="en">`

Root element that wraps all content

lang="en" specifies the language (English)

Helps screen readers and search engines

#### 3. `<head>`

Contains metadata (information about the document)

Not visible to users on the webpage

Includes important information for browsers and search engines

#### 4. `<meta charset="UTF-8">`

Specifies character encoding

UTF-8 supports all characters and symbols

Prevents display issues with special characters

#### 5. `<meta name="viewport">`

Makes the website responsive on mobile devices

width=device-width sets width to device screen width

initial-scale=1.0 sets initial zoom level

#### 6.  `<title>`

Text that appears in browser tab

Important for SEO (Search Engine Optimization)

Should be descriptive and unique for each page

#### 7.  `<body>`

Contains all visible content

Where all HTML elements like headings, paragraphs, images go

#