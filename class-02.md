## **Structural markup:**  the elements that you can use to describe both headings and paragraphs.

- ### HTML has six "levels" of headings:

   - `<h1>` ***is used for main headings***
   - `<h2>` ***is used for subheadings***
   - ***If there are further sections
under the subheadings then the
`<h3>` element is used, and so
on***
![](https://1.bp.blogspot.com/-Srnw_8jBHSY/XvHQqaCppZI/AAAAAAAAOuU/cikYtvXLix8dNc-qFMG4j50e-94FCpzLgCLcBGAsYHQ/s1600/heading%2B1%2Bto%2B6.jpg)

- ### To create a paragraph, surround the words that make up the paragraph with an opening `<p>` tag and closing `</p>` tag .

- ### `<b>`By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.

- ### `<i>` By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic.

- ### The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 2<sup>2.

- ### The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H2<sub>0

- ### In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines. 

```html
<p>The moon is drifting away from Earth.</p>
<p>The moon       is drifting away from Earth.</p>
<p>The moon is drifting away from
 Earth.</p>
```

- ### `<br />` , the browser will automatically show each new paragraph or heading on a new line.

- ### `<hr />` you can add a horizontal rule between sections using the `<hr />` tag.

- ### The `<blockquote>` element is used for longer quotes that take up an entire paragraph.

- ### The `<q>` element is used for shorter quotes that sit within a paragraph.

- ### If you use an abbreviation or an acronym, then the `<abbr>` element can be used.

- ### When you are referencing a piece of work such as a book, film or research paper, the `<cite>` element can be used to indicate where the citation is from.

- ### The `<dfn>` element is used to indicate the defining instance of a new term.

- ### The `<address>` element has quite a specific use: to contain contact details for the author of the page.

- ### The `<ins>` element can be used to show content that has been inserted into a document, while the `<del>` element can show text that has been deleted from it.

## INTRODUCING CSS
- ### CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

- ### Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).

- ### Different types of selectors allow you to target your rules at different elements.

- ### Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.

- ### CSS rules usually appear in a separate document,although they may appear within an HTML page.


## ***From the Duckett JS book:***

### Basic javascript instruction
- ### A script is made up of a series of statements. Each statement is like a step in a recipe.

- ### Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.

- ### Variables are used to temporarily store pieces of information used in the script.

- ### Arrays are special types of variables that store more than one piece of related information.

- ### JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).

- ### Expressions evaluate into a single value.

- ### Expressions rely on operators to calculate a value.

## Decisions and Loops :

### ***Use the `if` statement to specify a block of JavaScript code to be executed if a condition is true.***

```script
if (time < 10) {
  greeting = "Good morning";
} else if (time < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```

### `for` loops through a block of code a number of times

```script
for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```
### `while` loops through a block of code while a specified condition is true

```script
while (i < 10) {
  text += "The number is " + i;
  i++;
}
```

































