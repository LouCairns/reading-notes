# Code 201 - FOundations of Software Development - Class 02 - Read 02

## Assignment Instructions

- Begin with a statement addressing why this topic matters as it relates to what you are studying in this module.
- Answer each and every question or prompt presented.
- If there are no questions provided, summarize and explain this topic via an analogy from your previous work or home experience.
- Make a section in your notes titled ## Things I want to know more about, and anytime a question arises in your mind, or something catches your curiosity, note it under this heading.
- If you utilize any content directly from the reading sources, be sure to identify what you are quoting, and cite the source.

## THINGS I WANT TO KNOW MORE ABOUT

-
-
-
-

## Basics of HTML, CSS & JS

### Reading

- Continue Reading [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/)
- [HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
- [HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

1.  Why is it important to use semantic elements in our HTML?

    - The semantic HTML tags help the search engines and other user devices to determine the importance and context of web pages.
    - The pages made with semantic elements are much easier to read.
    - It has greater accessibility. It offers a better user experience

2.  How many levels of headings are there in HTML?

There are 6 levels of headings in HTML

3.  What are some uses for the `<sup>` and `<sub>` elements?

You will occasionally need to use superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning. The `<sup>` and `<sub>` elements handle this job.

4.  When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?

<abbr> — is used to wrap around an abbreviation or acronym. When including either, provide a full expansion of the term in plain text on first use, along with the <abbr> to mark up the abbreviation. This provides a hint to user agents on how to announce/display the content while informing all users what the abbreviation means.

If providing the expansion in addition to the abbreviation makes little sense, and the abbreviation or acronym is a fairly shortened term, provide the full expansion of the term as the value of title attribute:

Example:

```
<p>
  We use <abbr>HTML</abbr>, Hypertext Markup Language, to structure our web
  documents.
</p>
```

### Learn CSS

[How CSS Is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

1.  What are ways we can apply CSS to our HTML?

    - External stylesheet
    - Internal stylesheet
    - Inline styles

2.  Why should we avoid using inline styles?

3.  Review the block of code below and answer the following questions:

    1.  What is representing the selector?

    h2

    2.  Which components are the CSS declarations?

    color: black
    padding: 5px

    3.  Which components are considered properties?

    color
    padding

```
   h2 {
     color: black;
     padding: 5px;
   }
```

### Learn JS

Continue reading [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics). Start at “Comments” and read through “Events” section.

1.  What data type is a sequence of text enclosed in single quote marks?

String

2.  List 4 types of JavaScript operators.

    - Addition "+"
    - Assignment "="
    - Multiplication "\*"
    - Strictly Equals "==="

3.  Describe a real world Problem you could solve with a Function.

Creating formulas to analyse costs in a finance table.

[Making Decisions In Your Code – Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

1.  An if statement checks a **CONDITION** and if it evaluates to **TRUE/FALSE**, then the code block will execute.

2.  What is the use of an `else if`?

`if else` provided us with two choices, or outcomes — but what if we want more than two?

There is a way to chain on extra choices/outcomes to your if...else — using `else if`. Each extra choice requires an additional block to put in between if () { } and else { }

3.  List 3 different types of comparison operators.

    - "==" Equal to
    - "===" Equal value and equal type
    - "!=" Not Equal
    - "!==" Not Equal value or not equal type
    - ">" Greater than
    - "<" Less than
    - ">=" Greater than or equal to
    - "<=" Less than or equal to

4.  What is the difference between the logical operator `&&` and `||`?

The && operator returns true if both expressions are true, otherwise it returns false.

The || returns true if one or both expressions are true, otherwise it returns false.

### Bookmark and Review

https://chris.beams.io/posts/git-commit/
