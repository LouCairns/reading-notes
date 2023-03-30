# Code 201 - FOundations of Software Development - Class 03 - Read 03

HTML Lists, Control Flow with JS, and the CSS Box Model

Reading

- [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- [Unordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

1.  When should you use an `unordered list` in your HTML document?

Unordered lists are for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless.

2.  How do you change the `bullet style` of unordered list items?

The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the `list-style-type` property.

3.  When should you use an `ordered list` vs an `unorder list` in your HTML document?

The <ol> and <ul> elements both represent a list of items. They differ in that, with the <ol> element, the order is meaningful. To determine which one to use, try changing the order of the list items; if the meaning is changed, the <ol> element should be used, otherwise you can use <ul>.

4.  Describe two ways you can change the numbers on list items provided by an ordered list?

- Roman Numberal Type - Changes numbers into roman numerals. Example below:

<ol type="i">
  <li>Introduction</li>
  <li>List of Grievances</li>
  <li>Conclusion</li>
</ol>

- Start attribute - starts the numbers of an ordered list at the position stated. Example below lists contestants 4, 5 and 6:

<p>Finishing places of contestants not in the winners' circle:</p>

<ol start="4">
  <li>Speedwalk Stu</li>
  <li>Saunterin' Sam</li>
  <li>Slowpoke Rodriguez</li>
</ol>

- [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
- [The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

1.  Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?

Making up a block box in CSS we have the:

Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
Padding box: The padding sits around the content as white space; size it using padding and related properties.
Border box: The border box wraps the content and any padding; size it using border and related properties.
Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.
The below diagram shows these layers:

![Parts of a box](CODE-201-FoundationsOfSoftwareDevelopment/Images/PartsOfABox.png)

2.  List and describe the **four** parts of an HTML elements box as referred to by the `box model`.

- Content box
- Padding box
- Border box
- Margin box

- [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
- [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- [Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
- [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

1.  What `data types` can you store inside of an `Array`?

    - strings
    - numbers
    - objects
    - arrays

2.  Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?

```
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```

You can access he values stored in a multidimensional array by chaining two sets of square brackets together.

3.  List **five** shorthand operators for assignment in javascript and describe what they do.

Assignment x = f() x = f()
Addition assignment x += f() x = x + f()
Subtraction assignment x -= f() x = x - f()
Multiplication assignment x _= f() x = x _ f()
Division assignment x /= f() x = x / f()

4.  Read the code below and evaluate the last `expression` and explain what the result would be and why.

let a = 10;
let b = 'dog';
let c = false;

// evaluate this
(a + c) + b;

**TBD NEED TO HAVE A LOOK AT THIS ONE**

5.  Describe a real world example of when a conditional statement should be used in a JavaScript program.

If a user in a particular country, present pricing in the local currency.

6.  Give an example of when a Loop is useful in JavaScript.

Loops are useful if you want to run the same code over and over again, each time with a different value.
