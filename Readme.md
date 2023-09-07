## **Table of Contents:**

---

- [Creating New Line](#giving-new-line-in-markdown-file)
- [Creating Comments](#using-comments-in-markdown-file)
- [Creating Horizontal Line](#using-horizontal-line-in-markdown-file)
- [Creating Heading Style](#heading-style-h1-h6)
- [Creating Single Line Code-Block](#single-line-code-block-example-of-git-initialization)
- [Creating Multiple Line Code-Block](#creating-multiple-line-code-block)
- [Formatting](#formating-in-markdown)
  - [Formating Italic Text](#formating-italic-text)
  - [Formating Bold Text](#formating-bold-text)
  - [Formating 'strikethrough/delete text'](#formating-strikethroughdelete-text)
- [Creating List Items](#creating-list-items)
  - [Unordered List](#using-unordered-list-in-markdown-file)
  - [Ordered List](#using-ordered-list-in-markdown-file)
  - [Task List](#using-task-list-in-markdown-file)
- [Creating Link](#using-link-in-markdown-file)
  - [Automatic Link](#automatic-link)
  - [Disable Link](#disable-link-use-two-backticks)
  - [Markdown Syntax Link](#main-markdown-link-creation)
- [Adding Image](#adding-image)
  - [Markdown Syntax for adding Image](#markdown-syntax-for-adding-image-alt-textimage-source)
  - [Using Markdown Syntax](#using-markdown-syntax)
  - [Using HTML Image Tag](#using-html-image-tag)
- [Adding Emoji](#adding-emoji)
- [Creating Blockquotes](#using-of-blockquotes-in-markdown-file)
  - [Use of Blockquote [ Design a Callout ]](#using-of-blockquotes-to-make-a-callout)
- [Creating Toggle](#using-toggle-in-markdown-file)
- [Creating Table](#using-table-in-markdown-file)
  - [Table-01 [Simple Table]](#table-01--simple-table)
  - [Table-02 [Left Align Table]](#table-02--left-align-table)
  - [Table-03 [Center Align Table]](#table-03--center-align-table)
  - [Table-04 [Right Align Table]](#table-04--right-align-table)
  - [Table-05 [Left, Center and Right Align Table]](#table-05--left-center-and-right-align-table)

</br>

## **Giving 'New Line' in Markdown file**

---

For creating a new line we can use HTML **_'br'_** tag or use **_'two whitespace'_**.

#### **Example-01 [Using br tag]:**

---

```HTML

This is 1st Line <br>
This is 2nd Line

```

#### **Example-02 [Using two whitespace tag]:**

---

```

This is 1st Line
This is 2nd Line

```

## **Using Comments in Markdown file**

---

Comment in Markdown language is similar with HTML comment.  
Example:

```HTML

<!--This is a simple comment-->

```

## **Using Horizontal line in MarkDown File**

---

<!-- This symbol 3-underscores (___) or 3-hypens (---) is for creating a horzontal in markdown language -->

```

---

```

<!-- This is similar to HTML 'hr' tag -->

<!-- Heading Style -->

## **Heading Style [H1-H6]:**

---

---

# This is Heading-01 <!-- This similiar to 'h1' tag -->

## This is Heading-02 <!-- This similiar to 'h2' tag -->

### This is Heading-03 <!-- This similiar to 'h3' tag -->

#### This is Heading-04 <!-- This similiar to 'h4' tag -->

###### This is Heading-05 <!-- This similiar to 'h5' tag -->

###### This is Heading-06 <!-- This similiar to 'h6' tag -->

---

<!-- This is inline code block-->

## **Single line code block [Example of Git Initialization]:**

`git init`

</br>

## **Creating Multiple Line Code-Block:**

---

</br>

`<!-- This is Multiple line code block -->`

<!-- This for JavaScript -->

## **Example001** <!--This is bold -->

---

```JS

// This is 'Javascript' programming lanugage's example.

let text4 = "Please visit Microsoft and Microsoft!";
let newtxt2 = text4.replace("Microsoft", "Google");

console.log(`3. The previous sentence: ${text4}`);
console.log(`4. The replaced sentence: ${newtxt2}`);

```

## **Multiple Line Code-Block Example-02:** <!--This is bold -->

---

```HTML

 <!-- This is 'HTML' markup lanugage's example -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <script src="./practiceAccordingToW3SchoolsDocumentation.js"></script>

</body>
</html>

```

## **Multiple Line Code-Block Example-03:** <!--This is bold -->

---

```C

// This is 'C' programming lanugage's example

#include <stdio.h>
int main(){
    int a,b;
    printf("I love my country");
    return 0;
}

```

## <u>**Formating in MarkDown:**</u>

## **Formating Italic Text**

---

<!-- Jototuku italic korte chai, thik tototuku ongsho tuku underscore othoba akta asterisk symbol er moddhe rakhte (As much as we want to italicize, put those portions between one underscore or asterisk symbol) -->

`<!-- This is similar to HTML 'em/i' tag-->`

_This is an Italic Text_  
_This is also an Italic Text_

## **Formating Bold Text**

---

<!-- Jototuku bold korte chai, thik tototuku ongsho tuku underscore othoba duita asterisk symbol er moddhe rakhte (As much as we want to bold, put those portions between two underscore or asterisk symbol) -->

`<!-- This is similar to HTML 'strong/b' tag-->`

**This is a bold text**  
**This is also a bold text**

<!-- If we want to use bold and italic both in a sentence we can do this like this (3 asterisk symbol)/or like the below exaple:-->

**_This is bold and Italic sentence_**

## **Formating 'strikethrough/delete text'**

---

<!-- Jototuku strikethrough/delete korte chai, thik tototuku ongsho tuku duita tilde symbol er moddhe rakhte (As much as we want to delete/strikethrough, put those portions between two tilde symbol) -->

`<!-- This is similar to HTML 'delete' tag-->`

~~This is a deleted line~~  
Old Price of this Package: ~~100$~~  
Current Price of this Package: 80$

## <u>**Creating List Items:**</u>

</br>

## **Using Unordered List in MarkDown File:**

---

1.  Item-01
    1. Sub Item-01
    2. Sub Item-02
    3. Sub Item-03
       1. Sub-Sub Item-01
       2. Sub-Sub Item-02
       3. Sub-Sub Item-03
2.  Item-02
3.  Item-03

## **Using Ordered List in MarkDown File:**

---

- Item-01
  - Sub Item-01
  - Sub Item-02
  - Sub Item-03
    - Sub-Sub Item-01
    - Sub-Sub Item-02
    - Sub-Sub Item-03
- Item-02
- Item-03

</br>

## **Using Task List in MarkDown File:**

---

- [x] Task-01 Completed.
- [x] Task-02 Completed.
- [ ] Task-03 Not completed yet.

## <u>**Creating Link in MarkDown:**</u>

</br>

## **Using Link in 'Markdown File'**

---

### **Automatic Link**:

1.  https://www.google.com
2.  https://10minuteschool.com

### **Disable Link [Use two backticks]**:

<!-- It will also syntax for single line code -->

1.  `https://www.google.com`
2.  `https://10minuteschool.com`

### **Main Markdown Link Creation**

Syntax: `[title](Link)`

- [Google](https://www.google.com)
- [10MS](https://www.10minuteschool.com)
- [10MS Main Page](https://www.facebook.com/10minuteschool)

<!-- We can also define a link in an one place and theme give the name in that link-->

### **Example:**

<!-- My links -->

[Google's Website]: https://www.google.com
[10MS's Website]: https://www.10minuteschool.com
[10MS's Main Page Link]: https://www.facebook.com/

#### **_Replacing link in below:_**

- [Google][Google's Website]
- [10MS][10MS's Website]
- [10MS Main Page][10MS's Main Page Link]

<!-- This will creates also some beauty -->

</br>

## <u>**Adding Image:**</u>

</br>

## **Using Image in MarkDown File:**

---

### **Markdown Syntax for adding Image:** `![Alt text](Image Source)`

```HTML

<!-- But Using this markdown symbol we can just get the image. But we can't modify it. Like, we can't add any height or width of this image -->
<!-- But if we use 'HTML Image Tag' in this. Then we can also modify the image. -->

```

### **Using Markdown Syntax:**

![Nature's Image](./images/imageNature.jpg)

</br>

### **Using HTML Image Tag:**

<img src = "./images/imageNature.jpg" alt ="Nature's Image" width = "900px" height = "300px" title = "Nature's Image">

---

</br>

`<!-- Markdown does not have a direct syntax for underlining text.But we can do it with HTML 'u' tag -->`

</br>

## **Adding Emoji:**

---

`<!-- We can add emoji by copy and pasting-->`

This is a simple text. 😊

</br>

## **Using of 'Blockquotes' in MarkDown File:**

---

> Blockquotes can also be nested
>
> > by using additional greater-than signs right next to each other
> >
> > > or with spaces between arrows.

<br>

## **Using of 'Blockquotes' to make a 'Callout':**

---

`<!-- Here I have made a callout feature using 'Markdown Blockquote'-->`

### **Callout**

> 💡 **Tip:** Here is an important tip to remember!

</br>

`<!-- Space diye kora ar space na dewa eki. Ekvbae korlei holo. -->`

## **Using Toggle in MarkDown File:**

---

`<!-- We can make toggle by using 'HTML details Tag' -->`

<details>
<summary> Click here to see the items </summary>
    - Item-01 </br>
    - Item-02 </br>
    - Item-03 </br>
</details>

</br>

## **Using Table in MarkDown File:**

---

### **We will see _'05 type of Table'._**

1. **Simple Table:** A very simple table.
2. **Left Align Table:** _'Left Align Table'_ means **_Contents of Table are aligned left._**
3. **Center Align Table:** _'Center Align Table'_ means **_Contents of Table are aligned left._**
4. **Right Align Table:** _'Right Align Table'_ means **_Contents of Table are aligned left._**
5. **Left, Center and Right Align Table:** _'Left, Center, Right Align Table'_ means **_Contents of Table are aligned left, center and right._**

</br>

### **Table-01 [ Simple Table ]**:

---

| Packages   | Description          | Version |
| ---------- | -------------------- | ------- |
| React      | JavaScript Framework | v18.0   |
| Next.js    | React Framework      | v12.0   |
| Express JS | Node.js Framework    | v4.18   |

</br></br>

### **Table-02 [ Left Align Table ]**:

---

| Packages   | Description          | Version |
| :--------- | :------------------- | :------ |
| React      | JavaScript Framework | v18.0   |
| Next.js    | React Framework      | v12.0   |
| Express JS | Node.js Framework    | v4.18   |

</br></br>

### **Table-03 [ Center Align Table ]**:

---

|  Packages  |     Description      | Version |
| :--------: | :------------------: | :-----: |
|   React    | JavaScript Framework |  v18.0  |
|  Next.js   |   React Framework    |  v12.0  |
| Express JS |  Node.js Framework   |  v4.18  |

</br></br>

### **Table-04 [ Right Align Table ]**:

---

|   Packages |          Description | Version |
| ---------: | -------------------: | ------: |
|      React | JavaScript Framework |   v18.0 |
|    Next.js |      React Framework |   v12.0 |
| Express JS |    Node.js Framework |   v4.18 |

</br></br>

### **Table-05 [ Left, Center and Right Align Table ]**:

---

| Packages   |     Description      | Version |
| :--------- | :------------------: | ------: |
| React      | JavaScript Framework |   v18.0 |
| Next.js    |   React Framework    |   v12.0 |
| Express JS |  Node.js Framework   |   v4.18 |

```HTML

<!-- In table-05 Our-
Packages column: `Left Aligned`,
Description column: `Center Aligned` and
Version Column: `Right Aligned` -->

```
