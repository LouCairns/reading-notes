# Code 201 - FOundations of Software Development - Class 01 - Read 01

## READ 01 INFO

### Reading

- [Getting Started](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/)
- Skim [How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- Skim [Website Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
- Read the following sections of [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
  - Start at “What is JavaScript?”, read through “Comments” section.

1.  Compose a short poem describing how HTTP sends data between computers.
2.  Describe how HTML, CSS, and JS files are “parsed” in the browser.
3.  How can you find images to add to a Website?
4.  How do you create a `String` vs a `Number` in JavaScript?
5.  What is a `Variable` and why are they important in JavaScript?

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/)

Read the beginning of [Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started). Start from the beginning and read through section “Anatomy of an HTML document”.

[HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
[Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

1.  What is an HTML attribute?

    - HTML attributes provide additional information about HTML elements.
    - All HTML elements can have **attributes**
    - Attributes provide **additional information** about elements
    - Attributes are always specified in **the start tag**
    - Attributes usually come in name/value pairs like: **name="value"**

2.  Describe the Anatomy of an HTMl element.

![Anatomy Of An HTML Element](Images/AnatomyHTMLElement.png)

3.  What is the Difference between `<article>` and `<section>` element tags?

The section tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document. The article tag specifies independent, self-contained content.

4.  What Elements does a “typical” website include?

    - header: `<header>`
    - navigation bar: `<nav>`
    - main content: `<main>`, with various content subsections represented by `<article>`, `<section>`, and `<div>` elements.
    - sidebar: `<aside>`; often placed inside `<main>`
    - footer: `<footer>`

5.  How does metadata influence Search Engine Optimization?

Meta tags are snippets of code that tell search engines important information about your web page, such as how they should display it in search results.

6.  How is the `<meta>` HTML tag used when specifying metadata?

```
<meta attribute="value">
```

or

```
<meta attribute="value" attribute="value, value, value">
```

### Miscellaneous

[How to start to design a Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

1.  What is the first step to designing a Website?

Define what you want to accomplish with it

2.  What is the most important question to answer when designing a Website?

How will a website help me reach my goals?

[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

1.  Why should you use an <h1> element over a <span> element to display a top level heading?

> `<h1>` produces a top level heading.

By default, most browser's user agent stylesheet will style an h1 with a large font size to make it look like a heading (although you could style it to look like anything you wanted).

On the other hand, you could make any element look like a top level heading. Consider the following:

> `<span style="font-size: 32px; margin: 21px 0;">Not a top-level heading!</span>`

This will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is therefore a good idea to use the right HTML element for the right job.

HTML should be coded to represent the data that will be populated and not based on its default presentation styling. Presentation (how it should look), is the sole responsibility of CSS.

2.  What are the benefits of using semantic tags in our HTML?

    - Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
    - Screen readers can use it as a signpost to help visually impaired users navigate a page
    - Finding blocks of meaningful code is significantly easier than searching through endless `div`s with or without semantic or namespaced classes
    - Suggests to the developer the type of data that will be populated
    - Semantic naming mirrors proper custom element/component naming

[What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

1.  Describe 2 things that require JavaScript in the Browser?

    - dynamically updating content
    - control multimedia

2.  How can you add JavaScript to an HTML document?

JavaScript is applied to your HTML page in a similar manner to CSS. Whereas CSS uses <link> elements to apply external stylesheets and <style> elements to apply internal stylesheets to HTML, JavaScript only needs one friend in the world of HTML — the <script> element

## LAB 01

[Code-201-Lab-01-Demo-Repository](https://github.com/LouCairns/Code-201-Lab-01-Demo)

# Code-201-Lab-01-Demo

### Problem Domain

Create a webpage that accepts user input and, based on that input, displays messages back to the user.

### Instructions

Set up the HTML document <body> with <header>, <main>, and <footer> elements.

1. In the <main> of the file, place a <h1> tag with the content “Class 1 Lab”.

```
<h1>Class 1 Lab</h1>
```

2. Style this element with text and background colors via an internal <style> element placed in the <head> of your document.

```
    <style>
      h1 {
        font-family: cursive;
        color: pink;
        background-color: blueviolet;
        border: 3px solid pink;
        text-align: center;
        text-decoration-line: underline;
        padding: 20px;
      }
    </style>
```

3. In the HTML portion of the file, place the four questions within a series of <p> tags so that they are listed on the screen.

Give each <p> tag a different text color and background color by using inline styling.

```
<p style="color: red; background-color: beige" script="function">
        What is your favourite size adjective? (e.g. huge, big, large, tiny,
        enormous, little, tall, long, gigantic)
      </p>

      <p style="color: orange; background-color: beige">
        What is your favourite shape adjective? (e.g. flat, round, square,
        triangular, rectangular etc)
      </p>

      <p style="color: green; background-color: beige">
        What is your favourite colour? (e.g. blorange, red, orange, yellow,
        green, blue etc)
      </p>

      <p style="color: blue; background-color: beige">
        What is your favourite amphibian? (e.g. frog, newt, toad)
      </p>
```

4.  - Using a total of four JavaScript ‘prompt’ statements along the lines of our class demo, have a user answer four questions.

    - The user’s response to each question (input) should be stored in a separate variable. Name your variables carefully and let to define your variables.

    - Using these responses, return an alert to the user (output) that concatenates their response into some kind of reply like we did in class.

    - Strive to have your alert for each question utilize the responses to all of the prior questions such that by the fourth question, your response would look something like, “Greetings, Iggy from Ipanema, I also like to eat bananas while on vacation in Paris.”

    - Be creative and have fun with your questions/responses! They can be whatever you want so long as the input/output requirements are met.

    - In addition, for each response, create a console.log() message that indicates the nature of the question and the user’s response, as we did in class.

```
<script>
        let FaveSize = prompt(
          "What is your favourite size adjective? e.g. huge, big, large, tiny, enormous, little, tall, long, gigantic"
        );
        console.log("Our visitors favourite size adjective is " + FaveSize);
        console.log(typeof name);

        let FaveShape = prompt(
          "What is your favourite shape adjective? e.g. flat, round, square, triangular, rectangular"
        );
        console.log("Our visitors favourite shape adjective is " + FaveShape);
        console.log(typeof name);

        let FaveColour = prompt(
          "What is your favourite colour adjective? e.g. blorange, red, orange, yellow, green, blue"
        );
        console.log("Our visitors favourite colour adjective is " + FaveColour);
        console.log(typeof name);

        let FaveAmphibian = prompt(
          "What is your favourite amphibian? e.g. frog, toad, newt, axolotl"
        );
        console.log(
          "Our visitors favourite colour adjective is " + FaveAmphibian
        );
        console.log(typeof name);

        alert(
          "Oh my god, that's so weird. I collect " +
            FaveSize +
            ", " +
            FaveShape +
            ", " +
            FaveColour +
            " " +
            FaveAmphibian +
            "s!"
        );
      </script>
```

5.  - Using Lighthouse in the Chrome DevTools, analyze the accessibility of your application.

    - The following options to generate a Lighthouse report should be selected
      - Mode: Navigation
      - Device: Desktop
      - Categories: Accessibility
      - A score between 50-65 is a great place to start for this first lab.

![Lighthouse Accessibility Score](Images/Code201-Lab01-LighthouseAccessibility.jpg)

### Resources

Refer to the code demo from today as a starting point for this lab assignment.

### Submission Instructions

- Go to https://gist.github.com.
- In the “Gist description…” field, put your name.
- In the “Filename including extension…” field put ‘index.html’.
- Copy-paste your code into the big input field for the Gist.
- Select the button that says “Create secret gist”.
- Choose the “Share” option in the drop down list next to the link.
- Copy the link from the Gist screen for submission in the URL field below.
