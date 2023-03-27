# Code 102 - Intro to Software Development - Class 06 - Read 06 - Activate Web Pages with JavaScript
***

### Reflection and Discussion

Below is a collection of resources of varying types and lengths which describe the topics for the upcoming lecture.

Go through these resources, and create a page in your reading-notes repo that summarizes the topics you learned as though you were presenting the material to a non-technical friend interested in learning about it.

Reminder: all your reading-notes assignments should be done locally, in VS Code. New files and changes will reflect in GitHub using your new Git-flow skills! (Remember… A-C-P)

### Read

- [JS Intro Paragraph](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Introduction to JavaScript - basic output](https://code-maven.com/introduction-to-javascript)
[JavaScript input with prompt and confirm](https://code-maven.com/javascript-input-with-prompt-and-confirm)

### Read and Demo
git add- [Variables](https://www.w3schools.com/js/js_variables.asp)

### Bookmark

Check out these great explainer videos, in order. In less than 30 minutes, you’ll gain new insights into how computers are actually working! Watch all 6 videos, and create your reading-notes page based on your top 3 most significant readings.

- [How Computers Work - Playlist](https://www.youtube.com/playlist?list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-)


### Answer

1. What are variables in JavaScript?

Variables are containers for storing data (storing data values).

In this example, x, y, and z, are variables, declared with the var keyword:

>Example
>var x = 5;
>var y = 6;
>var z = x + y;


In the following example, x, y, and z are variables.
The value of z is: 11

```
<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Variables</h2>

<p>In this example, x, y, and z are variables.</p>

<p id="demo"></p>

<script>
let x = 5;
let y = 6;
let z = x + y;
document.getElementById("demo").innerHTML =
"The value of z is: " + z;
</script>

</body>
</html>
```


2. What does it mean to declare a variable?

Creating a variable in JavaScript is called "declaring" a variable.

You declare a JavaScript variable with the var or the let keyword:

>var carName;
or:
>let carName;

After the declaration, the variable has no value (technically it is undefined).

To assign a value to the variable, use the equal sign:

>carName = "Volvo";

You can also assign a value to the variable when you declare it:

>let carName = "Volvo";

In the example below, we create a variable called ```carName``` and assign the value "Volvo" to it.

Then we "output" the value inside an HTML paragraph with id="demo":

Example
```
<p id="demo"></p>

<script>
let carName = "Volvo";
document.getElementById("demo").innerHTML = carName;
</script>
```

3. What is an “assignment” operator, and what does it do?

The Assignment Operator (```=```) assigns a value to a variable:

Assignment Examples

```
let x = 10;
// Assign the value 5 to x
let x = 5;
// Assign the value 2 to y
let y = 2;
// Assign the value x + y to z:
let z = x + y;
```

4. What is information received from the user called?
