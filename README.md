# HTML Foundations

In this guide, based on the Pareto principle, I will be showcasing 20% of HTML that you will end up using the most.

Let's start with what HTML is. HTML stands for HyperText Markup Language. I like to think of HTML as the skeleton of my web apps. Hence, things related to structure of a web app, you can accomplish using html.

## Terminologies

There are a few terminologies you should understand when working with HTML.

- tags: keywords in HTML that defines what element you want to create. Tags has a start tag and end tag.

example below:
`<tagname> ...content </tagname>`

- elements: Everything from the beginning of a tag to the end of the tag is considered an element. For example if you have no content inside your tags, that is called an empty element.

- attributes: provides additional information about an element. They are specified in the start tag. Example below. Attributes usually are defined with a name="value". tags have varying attributes so look out for that.

example below:
`<tagname attributes="value"> ...content </tagname>`

- DOM (Document Object Model): The DOM is a programming interface for HTML and XML documents. It represents your HTML markup as nodes and objects inside a web app. The DOM is what allows us to alter the behavior of our web app with Javascript and other scripting languages. We will have another lesson on the DOM itself. For now just understand that your HTML markup will get parsed to create the DOM.

## Tags

In this section we will go over the most common tags

### Basic Tags / Meta Tags

- <html>: this tag is considered to be the root element. It is always at the very top and bottom of the document. It denotes to the website that this document is a html document.
- <head>: reserved for meta information about the website such as title, scripts, and style sheet tags
- <title>: defines the title of the page, helps for seo search, and also puts the title into the title bar. When you bookmark a page this is what gets stored as the title of the website
- <meta>: additional information that is very important for seo and other reason that are not visible to the users. website description, keywords, and other information like these will live here.  
- <body>: All of the content that needs to be shown to the users will live here.
- <style>: css code for styling lives here. You can also link a path to your styles.
- <script>: this is where your javascript or other scripts live. You can link a path your your script as well.

### Formatting Tags

- <div>: this is a generic container. We will be using this a lot.
- <h1>: h1 goes up to h6 but it denotes a heading textblock
- <p>: this is a paragraph tag that denotes where generic text should live
- <span>: this is an inline block container
- <br>: this break tag creates a line break.

### Text Tags

- <b>: this tag bolds the text
- <strong>: this is another way to bold your text
- <i>: this tag italics your text
- <em>: the emphasis tag is used to emphasis your text. In most browsers it will just italics your text
- <strike>: This take strikes through your tag

### Link and Img Tags:

- <a>: The anchor tag is the base for creating a hyperlink. You will need to pass it a href attribute with a link address to make this work
- <img>: The image tag displays images from a source.

### List Tags:

- <ol>: This is an order list. We use this tag when the order of the list is important.
- <ul>: This tag is an unordered list. This tag is used when the order of the list is not important
- <li>: the list item tag denotes each item of in the list.

### Form Tags:

- <form>: The form tag creates a form that can be submitted to some service
- <label>: labels tags are form legends that act as captions to your fieldsets.
- <input>: the input tag allows us to capture user input.
- <textarea>: similar to the input tag, but it can collect a multiline input
- <select>: creates a dropdown with options for user input
- <option>: denotes each option that users can select from
- <button>: the button when embedded in a form will submit the form.

### Table Tags:

- <table>: This tag creates that table element and houses all of its contents
- <thead>: denotes that table headers which is used to describe each columns contents
- <tbody>: the table body tag contains the main table's data
- <tfoot>: the table footer is used to describe the footer content
- <tr>: the table row contains information that should be included in a single row of a table
- <th>: the table header item contains information about a single header item
- <td>: the table data tag contains information about a single table cell
- <col>: the table column defines the information for a single column of a table

### HTML5 tags:

- <header>: defines a area for where the header content should go
- <footer>: defines a area for where the footer content should go
- <main>: defines a area for where the main content should go
- <section>: used to logically break up the website into sections

## Summary:

## Challenges:
