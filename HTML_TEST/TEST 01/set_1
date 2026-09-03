______________________________________________________________SECTION---A___________________________________________________________________




Q1. Which attribute is used to provide alternative text for an image?
Ans. alt

Q2. Which element is used to create a table row?
Ans. <tr>

Q3. Which HTML element is used to create hyperlink?
Ans. <a>

Q4. Which of the following is a block-lavel element
Ans. <div>

Q5. Which element is used to display another webpage inside the current webpage?
Ans. <iframe>

Q6. Which tag is used to represent computer code?
Ans. <code>

Q7. Which element represent the main content of a webpage?
Ans. <main>

Q8. Which entity represent the < character?
Ans. &lt;

Q9. Which attribute specifies where from data should be sent?
Ans. method

Q10. Which tag creates an ordered list?
Ans. <ol>




______________________________________________________________SECTION---B___________________________________________________________________




Q11. Explain the differnce between <strong> and <b>. Also explain <em> and <i>.
Ans. Difference Between <strong> vs <b> and <em> vs <i>

The primary difference lies between semantics (meaning/importance) and presentation (visual styling). While both pairs look identical in a web browser by default, their underlying purpose is different.

1. <strong> vs <b>

<strong> (Semantic Tag):

Represents strong importance, seriousness, or urgency of the text.

Screen readers announce it with vocal emphasis to assist visually impaired users.

Example: <strong>Warning:</strong> Do not touch live wires.

<b> (Stylistic Tag):

Used purely to draw visual attention by making text bold without conveying any extra importance.

Screen readers read it like normal, flat text.

Example: The <b>HTML5</b> specification was published in 2014.

2. <em> vs <i>

<em> (Semantic Emphasis Tag):

Indicates stress emphasis on a word or phrase, subtly changing the meaning of the spoken sentence.

Screen readers pronounce the text with a stressed tone or pitch change.

Example: I <em>did</em> lock the door.

<i> (Stylistic/Idiomatic Tag):

Displays text in italics for traditional typographic reasons without adding spoken stress (e.g., technical terms, foreign words, book titles, scientific names).

Screen readers do not change their vocal inflection.

Example: The domestic dog is classified as <i>Canis familiaris</i>.


Q12. What is the differnce between ordered, unordered, and description lists? Give an example of each.
Ans. HTML Lists: Ordered, Unordered, and Description Lists

HTML offers three types of lists based on item sequence and data structure:

1. Ordered List (<ol>)

Concept: Used when the sequence of items is strictly necessary (e.g., step-by-step guides, rankings). If the sequence changes, the logic fails.

Tags: <ol> (Ordered List) and <li> (List Item).

Rendering: Numbers by default (1, 2, 3...).

Example:

HTML
<ol>
  <li>Start the engine.</li>
  <li>Release the brake.</li>
</ol>
2. Unordered List (<ul>)

Concept: Used when the order of items does not matter (e.g., shopping list, features list).

Tags: <ul> (Unordered List) and <li> (List Item).

Rendering: Bullet points by default (•).

Example:

HTML
<ul>
  <li>Coffee</li>
  <li>Milk</li>
</ul>
3. Description List (<dl>)

Concept: Used for key-value pairs, terms and definitions, or metadata (e.g., glossaries, product specifications).

Tags:

<dl>: Defines the description list container.

<dt>: Defines the term/name.

<dd>: Defines the description/value.

Example:

HTML
<dl>
  <dt>HTML</dt>
  <dd>Markup language for web pages.</dd>
</dl>


Q13. Explain the differnce between inline and block-level elements with at least two examples of each
Ans. Block-Level vs Inline Elements in HTML

The primary difference lies in how elements are displayed on a web page and how they occupy space in the document flow.

1. Block-Level Elements

Line Behavior: Always start on a new line and force subsequent elements to the next line.

Width: Automatically take up the full available width of their parent container (100% width).

Dimensions: Fully respect CSS width, height, margin, and padding.

Containment: Can contain inline elements and other block-level elements.

Examples:

<div>: Generic container for grouping content and building layouts.

<p>: Paragraph tag, which always renders on a separate line with vertical spacing.

2. Inline Elements

Line Behavior: Do not start on a new line; they sit in line with surrounding text or elements.

Width: Take up only as much width as their content needs (shrink-to-fit).

Dimensions: Do not respect width and height properties in CSS; vertical margins and padding do not affect surrounding flow.

Containment: Generally contain only text or other inline elements (cannot wrap block-level tags).

Examples:

<span>: Generic inline tag used to style or script a specific section of text.

<a>: Anchor tag used for hyperlinks without breaking the text flow.


Q14.   What are semantic HTML elements? Explain any  four semantic elements with their purpose. 
Ans. Semantic HTML Elements

Semantic HTML elements are tags that clearly convey their meaning and purpose to both the browser and the developer. Instead of acting as generic containers (like <div> or <span>), they indicate the type and role of the content they enclose, which enhances SEO, code readability, and screen reader accessibility.

Four Common Semantic Elements and Their Purpose

1. <header>

Purpose: Represents introductory content or navigational aids for an entire webpage or a specific section.
Usage: Commonly contains the website logo, main title/heading (`<h1>`), and author/meta information.

2. <nav>

Purpose: Defines a dedicated block containing major navigation links.
Usage: Used for site navigation bars, menus, breadcrumbs, and tables of contents to help users and screen readers quickly jump across sections.

3. <article>

Purpose: Encloses self-contained, independent content that makes complete sense on its own outside the webpage context.
Usage: Commonly used for blog posts, news stories, forum threads, product listings, or user comments.

4. <footer>

Purpose: Defines the concluding bottom section for the whole page or a related section.
Usage: Typically holds copyright notices, privacy policy links, terms of use, contact information, and sitemaps.


Q15. What is an  <iframe>  ? 
Ans. What is an <iframe>?

An <iframe> (short for Inline Frame) is an HTML element used to embed an independent, secondary HTML document inside the current web page. It acts as an isolated rectangular viewing window on a webpage that pulls in and renders content directly from another internal or external source URL.

Core Characteristics & Working Mechanism

Separate Browsing Context: An <iframe> operates in its own completely isolated environment (global window context). It processes its own DOM tree, executes its own JavaScript, and evaluates its own CSS styles separately from the host document.

Non-Blocking Display: The parent page loads its own markup while the browser fetches and executes the source of the frame in parallel.

Syntax: It is written with an opening and closing tag, populated with a source attribute:

HTML
<iframe src="https://example.com" width="600" height="400" title="Example Frame"></iframe>
Common Use Cases

Third-Party Content Embedding: Integrating external widgets such as YouTube videos, interactive Google Maps, or audio players.

Payment Gateways: Hosting secure, PCI-compliant payment forms (e.g., Stripe, PayPal) so sensitive credit card inputs do not touch the host site's servers.

Advertisement Displays: Serving third-party ad networks in segregated spaces without risking site layout disruptions.

Sandboxed Previews: Displaying email previews, live code snippets, or user-submitted HTML safely without compromising the main application.




______________________________________________________________SECTION---C___________________________________________________________________




Q16. Create an HTML page that contains: 
 ●  A heading  "My Favorite Website"
 ●  An image with appropriate  src  and  alt  attributes.
 ●  Add a normal hyperlink to another page. 
Ans. <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Favorite Website</title>
</head>
<body>
    <h1>My Favorite Website</h1>

    <img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Wikipedia-logo-v2.svg" 
         alt="Wikipedia official globe logo" 
         width="200" 
         height="200">

    <p>
        Visit the website directly here: 
        <a href="https://www.wikipedia.org" target="_blank">Go to Wikipedia</a>
    </p>

</body>
</html>


Q17. Create the following table using HTML: Student Rahul  Priya  Aman  Neha  Subject  HTML  CSS  JavaScript HTML  Requirements: Marks  Grade 85  92  78  88  A A+ B+ A 
 ●  Use  <table>  ,  <tr>  ,  <th>  , and  <td>  .
 ●  Add a suitable table heading.
 ●  Use  border  to make the table visible. 

 Ans. <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Marks Table</title>
</head>
<body>
    <table>
        <caption><h3>Student Performance Report</h3></caption>
        <thead>
            <tr>
                <th>Student</th>
                <th>Subject</th>
                <th>Marks</th>
                <th>Grade</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Rahul</td>
                <td>HTML</td>
                <td>85</td>
                <td>A</td>
            </tr>
            <tr>
                <td>Priya</td>
                <td>CSS</td>
                <td>92</td>
                <td>A+</td>
            </tr>
            <tr>
                <td>Aman</td>
                <td>JavaScript</td>
                <td>78</td>
                <td>B+</td>
            </tr>
            <tr>
                <td>Neha</td>
                <td>HTML</td>
                <td>88</td>
                <td>A</td>
            </tr>
        </tbody>
    </table>

</body>
</html>


Q18.Create a webpage containing:
 1.  An ordered list of  5 programming languages  .
 2.  An unordered list of  5 HTML topics  .
 3.  Use at least four formatting elements such as: ○  <strong> ○  <em> ○  <mark> ○  <del> ○  <sup> ○  <sub> 
 Ans. <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Webpage with Lists and Formatting</title>
</head>
<body>

    <h2>Top Programming Languages</h2>
    <ol>
        <li>Python (rated <strong>#1</strong> for beginners)</li>
        <li>JavaScript</li>
        <li>Java</li>
        <li>C++ (runs at <em>O(log n)</em> speed in optimal search)</li>
        <li>C#</li>
    </ol>

    <hr>

    <h2>Essential HTML Topics</h2>
    <ul>
        <li>HTML Document Structure</li>
        <li>Forms and <mark>Input Validation</mark></li>
        <li>Semantic Tags (<del>HTML4 Divs</del> replaced by HTML5 elements)</li>
        <li>Tables and Lists</li>
        <li>Media Elements (Audio, Video, and Canvas)</li>
    </ul>

    <hr>

    <h2>Formatted Examples</h2>
    <p>
        <strong>1. Strong:</strong> <strong>Important:</strong> Always close open HTML tags.<br>
        <em>2. Emphasis:</em> Practice <em>daily</em> to build muscle memory.<br>
        <mark>3. Mark:</mark> Web accessibility (a11y) is a <mark>core requirement</mark>.<br>
        <del>4. Delete:</del> The old standard was <del>HTML 4.01</del> HTML5.<br>
        <sup>5. Superscript:</sup> Mathematical expression: x<sup>2</sup> + y<sup>2</sup> = z<sup>2</sup><br>
        <sub>6. Subscript:</sub> Chemical formula for water: H<sub>2</sub>O
    </p>

</body>
</html>


Q19.Create a webpage that displays:
 HTML <h1>Hello World</h1>
 as  text  , rather than allowing the browser to interpret  it as HTML.
 Also display:
 ●  <
 ●  >
 ●  &
 ●  © 
 using appropriate HTML entities. 

Ans. <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Entities Display</title>
</head>
<body>

    <h2>Displaying HTML as Plain Text</h2>
    <p>
        Code representation: 
        <code>&lt;h1&gt;Hello World&lt;/h1&gt;</code>
    </p>

    <hr>

    <h2>Required HTML Entities</h2>
    <ul>
        <li>Less Than (&lt;): <code>&amp;lt;</code> displays as <strong>&lt;</strong></li>
        <li>Greater Than (&gt;): <code>&amp;gt;</code> displays as <strong>&gt;</strong></li>
        <li>Ampersand (&amp;): <code>&amp;amp;</code> displays as <strong>&amp;</strong></li>
        <li>Copyright (&copy;): <code>&amp;copy;</code> displays as <strong>&copy;</strong></li>
    </ul>

</body>
</html>


Q20. Create a webpage using the following semantic structure:
 None
 Header
 Navigation
 Main
 Section
 Article
 Aside
 Footer
 Use the appropriate HTML5 semantic elements.   

Ans. <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic HTML5 Webpage</title>
</head>
<body>

    <header>
        <h1>My Personal Tech Blog</h1>
        <p>Sharing tutorials, tips, and modern web development practices</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#articles">Articles</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <main id="home">

        <section id="articles">
            <h2>Featured Tutorials</h2>

            <article>
                <h3>Mastering Semantic HTML5</h3>
                <p>Published on: <time datetime="2026-09-03">September 3, 2026</time></p>
                <p>Semantic tags define clear meaning for content rather than just presentation, making sites faster to parse, cleaner to read, and universally accessible.</p>
            </article>

            <article>
                <h3>CSS Grid vs Flexbox</h3>
                <p>Published on: <time datetime="2026-08-15">August 15, 2026</time></p>
                <p>Flexbox works best for 1D alignments, while Grid handles complex 2D full-page structures with effortless syntax.</p>
            </article>
        </section>
        <aside>
            <h3>Related Links & Author Bio</h3>
            <p>Written by Alex, an open-source advocate and front-end developer.</p>
            <ul>
                <li><a href="https://developer.mozilla.org" target="_blank">MDN Web Docs</a></li>
                <li><a href="https://w3.org" target="_blank">W3C Standards</a></li>
            </ul>
        </aside>

    </main>

    <footer>
        <p>&copy; 2026 My Personal Tech Blog. All rights reserved.</p>
        <p><a href="#privacy">Privacy Policy</a> | <a href="#terms">Terms of Service</a></p>
    </footer>

</body>
</html> 
