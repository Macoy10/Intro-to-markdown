#  INTRUDUCTION TO MARKDOWN

<!---->
# HEADING 1

## HEADING 2

### HEADING 3

#### HEADING 4

##### HEADING 5

###### HEADING 6

---

<!-- Italics-->

_this is going to be paragraph that is using italic styling_

*this is going to be paragraph that is using italic styling*

---

<!-- Strong-->

This is an example of  **strong text** , anything between the two opening asterisk and two closin will be displayed as strong text

This is another example of the way to have _strong text_ in your document. anything between the two double opening underscore and closing underscore will be displayed as __strong text__

<!--Strike Through-->

This is an example of ~~strikethrough~~ text , anything in between the double tilde opening characters and closing double tilde characters will be display strikethrough


---
<!--Horizontal Rule-->

We can add tripple hypens to be able to create a horizontal rule for seperating content.

Another way to add __HORIZONTAL RULES__ in our document markdown is by using three underscores.

---

<!-- Escape Character Rule using Backslash-->

This is an example of a *text with an asterisk* . When we don't want it to be italicized. We want to use the backlash \ to escape the rule of using an opening 
\*asterisk* and closing \*asterisk*  to inclose the text text content

---

<!-- Blockqoute Rule -->

> We use the greater than symbol to display a block of text as a quoate withd a back ground and line on the left side.

> We don't have to be great to start , but you need to start to be great, "* - __Unknow Author__

---

<!--Links Rule-->

**NOTE**: We would want to put the link description inside square brackets and the link to the resource inside of the two open and close parenthesis
[MC-pexel profile](https://www.pexels.com/@marco-marvilla-451554328/)


__NOTE__: We can add a ballon title description to our link by using double quotes after the link to the resource
[MC-pexel profile](https://www.pexels.com/@marco-marvilla-451554328/ "This is MC-pexel profile")

---

<!-- List item rules -->


<!-- UNODERLIST list -->

* Item 1 - this is going to be our list item 1
  *  This is our list item 1 child item 1
  *  This is our list item 2 child item 2
* Item 1 - this is going to be our list item 2
  *  This is our list item 2 child item 1
  *  This is our list item 2 child item 2
* Item 1 - this is going to be our list item 3
  *  This is our list item 3 child item 1
  *  This is our list item 3 child item 2
* Item 1 - this is going to be our list item 4
  *  This is our list item 4 child item 1
  *  This is our list item 4 child item 2
* Item 1 - this is going to be our list item 5
  *  This is our list item 5 child item 1
  *  This is our list item 5 child item 2


<!-- ORDER LIST -->
1. Item 1 - this is going to be our list item 1

    1.1  This is our list item 1 child item 1
  
    1.2  This is our list item 2 child item 2
  
2. Item 1 - this is going to be our list item 2

    2.1  This is our list item 2 child item 1
    
    2.2    This is our list item 2 child item 2
    
    
3. Item 1 - this is going to be our list item 3

   3.1  This is our list item 3 child item 1
    
   3.2    This is our list item 3 child item 2
     
4. Item 1 - this is going to be our list item 4

   4.1 This is our list item 4 child item 1
  
   4.2  This is our list item 4 child item 2
    
5. Item 1 - this is going to be our list item 5
 
   5.1  This is our list item 5 child item 1
    
   5.2  This is our list item 5 child item 2
   
 
---

<!-- Code block inline Example Rule-->

***NOTE**:*Backtics will allow us to show the code block or the paragraph tags . its is located below the tilde character and on the top of the tab key*

`<p> This is a paragraph tag with a code inline code block example opening and closing tags </p>`

---
<!--GITHUB FLAVOR SET OF CODE BLOCK-->


<!--CODE BLOCKS FOR GIT HUB DOCUMENTATION-->

```bash
npm install

npm start
```

**NOTE**: You can specify some syntax code blocks for different languages

```javascript
function jsAdd(num1,num2){
  return num1 + num2;
}
```

```python
def pythonAdd(num1,num2):
  return num1 + num2;
```

```C#
public static int Sum(int num1, int num2)
   {
     int total;
     total = number1 + numb2;
     return total;
   }

```
