# Read: 01 - Learning Markdown SUMMARY

### 1 - What is Markdown?
***

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by [John Gruber](https://en.wikipedia.org/wiki/John_Gruber) in 2004, Markdown is now one of the world’s most popular markup languages.

Using Markdown is different than using a [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG) editor. In an application like Microsoft Word, you click buttons to format words and phrases, and the changes are visible immediately. Markdown isn’t like that. When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.

For example, to denote a heading, you add a number sign before it (e.g., # Heading One). Or to make a phrase bold, you add two asterisks before and after it (e.g., **this text is bold**). It may take a while to get used to seeing Markdown syntax in your text, especially if you’re accustomed to WYSIWYG applications. The screenshot below shows a Markdown file displayed in the [Visual Studio Code](https://www.markdownguide.org/tools/vscode/) text editor.

![Screenshot of Markdown file displayed in VS Code](https://mdg.imgix.net/assets/images/vscode.png?auto=format&fit=clip&q=40&w=1080)

You can add Markdown formatting elements to a plaintext file using a text editor application. Or you can use one of the many Markdown applications for macOS, Windows, Linux, iOS, and Android operating systems. There are also several web-based applications specifically designed for writing in Markdown.

Depending on the application you use, you may not be able to preview the formatted document in real time. But that’s okay. [According to Gruber](https://daringfireball.net/projects/markdown/), Markdown syntax is designed to be readable and unobtrusive, so the text in Markdown files can be read even if it isn’t rendered.

>The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions.

### 2 - Why do we use Markdown?
***

You might be wondering why people use Markdown instead of a WYSIWYG editor. Why write with Markdown when you can press buttons in an interface to format your text? As it turns out, there are several reasons why people use Markdown instead of WYSIWYG editors.

- **Markdown can be used for everything.**   
People use it to create: 
    - websites
    - documents
    - notes
    - books
    - presentations
    - email messages
    - technical documentation.

- **Markdown is portable.**  
    Files containing Markdown-formatted text can be opened using virtually any application. If you decide you don’t like the Markdown application you’re currently using, you can import your Markdown files into another Markdown application. That’s in stark contrast to word processing applications like Microsoft Word that lock your content into a proprietary file format.

- **Markdown is platform independent.**   
    You can create Markdown-formatted text on any device running any operating system.

- **Markdown is future proof.**   
    Even if the application you’re using stops working at some point in the future, you’ll still be able to read your Markdown-formatted text using a text editing application. This is an important consideration when it comes to books, university theses, and other milestone documents that need to be preserved indefinitely.

- **Markdown is everywhere.**  
    Websites like Reddit and GitHub support Markdown, and lots of desktop and web-based applications support it.

### 3 - What symbol will create a heading in Markdown?
***
In order to create a heading you will use the '#' symbol, followed by a space and then the name of your heading.  

So, to write a heading, in bold, that reads "I AM A LOVELY BIG HEADING" you would see the following code

    `### **I AM A LOVELY BIG HEADING**`

Which will present like this when rendered:

### **I AM A LOVELY BIG HEADING**


### 4 & 5 - How many `#` do you need to create the largest heading and the smallest heading?
***

There are 6 heading levels in Markdown, each demonstrated below:

`# Heading level 1`     
# Heading level 1

`## Heading level 2`     
## Heading level 2

`### Heading level 3`     
### Heading level 3

`#### Heading level 4`     
#### Heading level 4

`##### Heading level 5`     
##### Heading level 5

`###### Heading level 6`     
###### Heading level 6

### 6 - When making text bold or italicized for emphasis, it is best practice to use which symbol?
***

Whilst underscores can be used to create bold or italicized text, best practice is to use asterisks. This is because Markdown applications do not agree on how to handle underscores in the middle of a word. For compatability asterisks are used.

###### To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters. 

`I love **bold text**`

would render as:

I love **bold text**

###### To italicize text, add one asterisk or underscore before and after a word or phrase. 

`I love *italicized text*`

would render as: 

I love *italicized text*

###### To emphasize text with bold and italics at the same time, add three asterisks before and after a word or phrase. 

`I love ***bold italicized text***`

would render as:

I love ***bold italicized text***

###### To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

`I love **bold*italicized*text**`

would render as:

I love **bold*italicized*text**

### 7 - How do you create a link with Markdown?
***

To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

The rendered output looks like this:

My favourite search engine is [Duck Duck Go](https://duckduckgo.com)

### 8 - What are the three symbols you can use to create an unordered (bulleted) list with Markdown?
***


