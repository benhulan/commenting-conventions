commenting-conventions
======================

I. The Basics

A. Comments
Comments are an essential part of programming. At very least, your comments need to help you read what you have written! But comments should be clear to anyone. Comments should also be used to give credit for others' work, such as linking source code you did not write and attributing credit to photographers and designers whose work you are incorporating.

1. HTML comments <br />
`<!-- use these characters for single or multi-line HTML comments -->`<br />
a. Here is a simple comment to indicate linking an external library:<br />
`<!-- this is the link for jQuery -->`<br />
`<script src="path.to.source.files"></script>`<br />
b. Here is an example giving credit to a photographer:<br />
`<!-- image from [URL], by [PHOTOGRAPHER_NAME] -->`<br />
`<img src="path_to_source_of_image.jpg" alt="do not forget the alt tag" />`

2. CSS comments<br />
a. There is only one way to write CSS comments:<br />
`/* This is the CSS comment syntax */`<br />
b. ...but you will often see something like this:<br />
`/***** several asterisk (*) characters can help organize your file ****/`<br />

3. JS comments<br />
a. `// Use double forward-slash for single-line comments`<br />
b. `/* Use this style for single OR multi-line comments */`

4. PHP Comments follow the same rules as JS<br />
NOTE:  If you comment out a block of HTML containing PHP script, you need to add comments inside the PHP tags, like this:  
`<!-- <h1><?php /* include ('title.php') */ ?></h1> -->`<br />
Otherwise the PHP script will run without the HTML.

B. Naming Conventions
Just as designers follow a visual style guide, you need to be consistent in the way you write all your code, from classes to functions. For example, if you use double quotes to indicate a string of characters at one point in your document, you should stick to double quotes throughout the project. If you use camelCase to name your functions and variables, try to avoid mixing in underscore_case names. When you name a class or id, use a unique one- or two-word phrase that makes sense.

C. Best Practices

Capitalize your function or method prototype

II. Advanced concepts

Here we will define and describe commenting conventions for more advanced students. We will not require students to follow these suggestions but we think they're pretty cool and want our students to be able to read and understand these conventions when they stumble across them.

JSDoc

Comments in other scripting languages
