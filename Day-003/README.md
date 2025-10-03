# Day - 3 : HTML Phase - 1
## Chapter-4: Text Formatting Tags
HTML provides two categories of formatting tags: Physical Tags (visual appearance) and Semantic Tags (meaning and importance).

## Bold and Strong Text

    <strong>This is Strong Tag</strong>  <!-- Semantic: Important content -->
**Output**:  <strong>This is Strong Tag</strong> 

    <b>This is bold tag</b>              <!-- Physical: Visual bold only -->
**Output**:  <b>This is bold tag</b>  

**Discription :**
- `<strong>`: Indicates important content, typically displayed bold

- `<b>`: Makes text visually bold without semantic meaning

## Italic and Emphasis

    <i>This is italic tag</i>           <!-- Physical: Visual italic -->
**Output**: <i>This is italic tag</i> 

    <em>This is emphasized</em>          <!-- Semantic: Emphasized content -->
**Output**: <em>This is emphasized</em>

**Discription :**
- `<em>`: Adds semantic emphasis, usually rendered italic

- `<i>`: Makes text visually italic without implied emphasis

## Text Decoration Tags

    <u>This is underline</u>            <!-- Underlined text -->
**Output**: <u>This is underline</u>            <!-- Underlined text -->

    <ins>This is insert tag</ins>       <!-- Inserted/added content -->
**Output**: <ins>This is insert tag</ins>       <!-- Inserted/added content -->

    <mark>This is highlighted text</mark> <!-- Highlighted text -->
**Output**: <mark>This is highlighted text</mark> <!-- Highlighted text -->

    <small>This is small tag</small>     <!-- Smaller font size -->
**Output**: <small>This is small tag</small>     <!-- Smaller font size -->

    <del>This is deleted text</del>      <!-- Deleted/strikethrough -->
**Output**: <del>This is deleted text</del>      <!-- Deleted/strikethrough -->

## Subscript and Superscript

    <p>H<sub>2</sub>O</p>               <!-- Chemical formula -->
**Output**: <p>H<sub>2</sub>O</p>               <!-- Chemical formula -->

    <p>E = mc<sup>2</sup></p>           <!-- Mathematical equation -->
**Output**: <p>E = mc<sup>2</sup></p>           <!-- Mathematical equation -->
**Discription :**
- `<sub>`: Creates subscript text (below baseline)

- `<sup>`: Creates superscript text (above baseline)

## Pre-formatted and Special Tags

    <pre>
        Name:     John Doe
        Age:      25
        City:     New York
    </pre>
**Output**: 
<pre>
    Name:     John Doe
    Age:      25
    City:     New York
</pre>

    <p>Press <kbd>Alt</kbd> + <kbd>Tab</kbd> to switch windows.</p>
**Output**: <p>Press <kbd>Alt</kbd> + <kbd>Tab</kbd> to switch windows.</p>

    <p>This uses <abbr title="HyperText Markup Language">HTML</abbr></p>
**Output**: <p>This uses <abbr title="HyperText Markup Language">HTML</abbr></p>

**Discription**
- `<pre>`: Preserves whitespace and formatting

- `<kbd>`: Represents keyboard input

- `<abbr>`: Defines abbreviations with tooltips

## HTML Lists
### Unordered Lists

    <ul type="circle">
        <li>Apple</li>
        <li>Mango</li>
        <li>Orange</li>
    </ul>
**Output**: <ul type="circle">
    <li>Apple</li>
    <li>Mango</li>
    <li>Orange</li>
</ul>
Types: disc (default), circle, square, none

### Ordered Lists

    <ol type="I">
        <li>Open the door</li>
        <li>Wash your hands</li>
        <li>Go to bed</li>
    </ol>
**Output**: <ol type="I">
    <li>Open the door</li>
    <li>Wash your hands</li>
    <li>Go to bed</li>
</ol>

Types: 1 (numbers), A (uppercase), a (lowercase), I (Roman uppercase), i (Roman lowercase)

### Description Lists

    <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets</dd>
    </dl>
**Output**: <dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>
    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
</dl>

**Discription :**
- `<dl>`: Description list container

- `<dt>`: Description term

- `<dd>`: Description definition


## Links and Anchor Tags
### Basic Link Types

    <!-- Internal page section -->
    <a href="#section1">Go to Section 1</a>
**Output**: <a href="#section1">Go to Section 1</a>

    <!-- External website -->
    <a href="https://www.google.com">Google</a>
**Output**: <a href="https://www.google.com">Google</a>

    <!-- New tab/window -->
    <a href="https://www.google.com" target="_blank">Google (New Tab)</a>
**Output**: <a href="https://www.google.com" target="_blank">Google (New Tab)</a>

    <!-- SEO-optimized external link -->
    <a href="https://www.google.com" target="_blank" rel="noopener noreferrer">
**Output**: <a href="https://www.google.com" target="_blank" rel="noopener noreferrer">
        Secure Google Link
    </a>

### Special Link Types

    <!-- Email link -->
    <a href="mailto:support@example.com" title="Contact Support">
        Send Email
    </a>
**Output**: <a href="mailto:support@example.com" title="Contact Support">Send Email</a>

    <!-- Phone link -->
    <a href="tel:+1234567890" title="Call Us">
        Call Now
    </a>
**Output**: <a href="tel:+1234567890" title="Call Us">Call Now</a>

    <!-- Button with JavaScript Navigation -->
    <button type="button" onclick="window.location.href='https://www.google.com'">
        Google Button
    </button>
**Output**: <button type="button" onclick="window.location.href='https://www.google.com'">Google Button</button>

### Important Link Attributes:

- `target="_blank"`: Opens in new tab

- `rel="noopener noreferrer"`: Security and SEO best practice for external links

- `title`: Provides tooltip text

## HTML Tables
### Complete Table Structure

    <table border="1">
        <thead>
            <tr>
                <th>EID</th>
                <th>Name</th>
                <th>Age</th>
                <th>Department</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>15678</td>
                <td>Rajesh</td>
                <td>37</td>
                <td rowspan="3">IT</td>
            </tr>
            <tr>
                <td>12213</td>
                <td>Rakesh</td>
                <td>42</td>
            </tr>
            <tr>
                <td>65651</td>
                <td>Monika</td>
                <td>22</td>
            </tr>
        </tbody>
    </table>
**Output**: 
<table border="1">
    <thead>
        <tr>
            <th>EID</th>
            <th>Name</th>
            <th>Age</th>
            <th>Department</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>15678</td>
            <td>Rajesh</td>
            <td>37</td>
            <td rowspan="3">IT</td>
        </tr>
        <tr>
            <td>12213</td>
            <td>Rakesh</td>
            <td>42</td>
        </tr>
        <tr>
            <td>65651</td>
            <td>Monika</td>
            <td>22</td>
        </tr>
    </tbody>
</table>


**Discription :**

- `<table>`: Table container with border attribute

- `<thead>`: Table header section

- `<tbody>`: Table body content

- `<tr>`: Table row

- `<th>`: Table header cell (bold, centered by default)

- `<td>`: Table data cell

- `rowspan="3"`: Cell spans 3 rows vertically

- `colspan="2"`: Cell spans 2 columns horizontally (not shown in example)

# #Day 3 competed