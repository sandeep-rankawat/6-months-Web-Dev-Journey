# Chapter 2 | HTML Foundations 


### Basic HTML5 Template Structure

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Day-002 | Foundations</title>
    </head>
    <body>
        <!-- Content goes here -->
    </body>
    </html>


## 📚 Concepts Demonstrated

### 1. **HTML Comments**
**Comments** - Comments are the code or any text info that must not be displayed on screen only for developer understanding what going on in web page

    <!-- This is comment in html -->
    <!--! These are the headings in html -->
    <!--* Inline documentation comments -->

Above all are example of comments.
In html single line and multiline comment having same syntax.
**Syntax:** `<!-- comment text -->`
**Purpose:** Code documentation and inline explanations

### -*Types*
**1. Code Documentation & Info**

    <!-- Header Start Here -->
    <p>Hello Web</p> <!-- This is first para -->`

**2. Section Division**

    <!-- ========== HEADER SECTION ========== -->
    <header></header>

    <!-- ========== MAIN CONTENT ========== -->
    <main></main>

    <!-- ========== FOOTER SECTION ========== -->
    <footer></footer>


**3. Temporary Code Removal**

    <p>This paragraph is visible</p>
    <!-- 
    <p>This paragraph is hidden for testing</p>
    <button>Hidden button</button>
    -->
    <p>This paragraph is also visible</p>

**4. Debugging Help**

    <!-- TODO: Add form validation here -->
    <!-- FIXME: Email validation not working -->
    <form>
    <input type="email" name="email">
    </form>



### 2. **HTML Heading Hierarchy (h1-h6)**
**Heading** - They tell the browser that this text is heading not an odrinary text and have style built in like font size, weight etc

    <h1>This is heading H1</h1>   <!-- Most Important -->
    <h2>This is heading H2</h2>   <!-- Secondary -->
    <h3>This is heading H3</h3>   <!-- Tertiary -->
    <h4>This is heading H4</h4>   <!-- Fourth Level -->
    <h5>This is heading H5</h5>   <!-- Fifth Level -->
    <h6>This is heading H6</h6>   <!-- Least Important -->
**SEO Importance:** Proper heading hierarchy improves search rankings and SEO.


### 3. **Paragraph Element**
**Para**- para tag to write para  and info about something that can be better understand by browser.

    <p>This is para graph</p>

**Function:** Defines paragraph blocks with automatic spacing


### 4. **Breaking Elements**

#### Horizontal Rule (HR)
    <hr> <!-- Thematic break/separator -->

**Purpose:** Creates horizontal line for content separation for thementic break. It can used as section devision that shown to user or for styling to appeal well.


#### Line Break (BR)  

    <br> <!-- Line break within content -->
**Purpose:** Forces line break without creating new paragraph. When we need the next word start from new line and dont want to use another para to write it then br tag used


### 5. **Universal Container Element**

    <div title="div">
        This is universal or global tag used anywhere without restriction.
        It can be used for paragraphs, grouping other tags and elements,
        making container and many more use.
    </div>

**DIV Element Properties:**
- **Block-level element** that spans full width
- **Generic container** for grouping content
- **No semantic meaning** - purely for layout/styling
- **Most flexible element** in HTML structure


### 6. **HTML Attributes Demonstration**
**Attributes** are the specific keyword that are written in the openning tag of element and this have some specific function 

    <p id="para" class="para" title="para">
        Here is Example of Attributes: id, class, title and many more
    </p>

In This html code id, class, title  all are attributes and para is value of corresponding attributes. Here these value are same it can be differect acc to need.
**Attributes Explained:**
- **`id`**: Unique identifier for element, use to target element when styling or scripting of done on the element.
- **`class`**: CSS styling hook for grouping, same like id but not unique a class have many values seprated by space and different element have same classes.
- **`title`**: Tooltip text on hover on element.

**Types & Categories** -Mainly two types of attributes
**1. Global Attributes**- These attribute are global means can be used in any tag no restriction.
Example:-  id, class, title, hidden, etc 

**2. Element Specific Attributes**- These attributes are made only for specific elements of tags.
Example:- href, onclick, type, placeholder, action, auto play, alt, etc
#