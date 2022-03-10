# Markdown(.md) syntax Here.

# 1. Normal text

---

This is normal text .you can just write text and it's call normal text .That's having no syntax.Just write text.

# 2. Heading

<!-- You can use HTML tag or Markdown syntax for heading-->

---

> ## 2.1 Html syntax :

> ---

<h1>Ahanab Habib Fahad</h1>
<h2>Ahanab Habib Fahad</h2>
<h3>Ahanab Habib Fahad</h3>
<h4>Ahanab Habib Fahad</h4>
<h5>Ahanab Habib Fahad</h5>
<h6>Ahanab Habib Fahad</h6>

---

> ## 2.2 Markdown syntax :

---

# Ahanab Habib Fahad

## Ahanab Habib Fahad

### Ahanab Habib Fahad

#### Ahanab Habib Fahad

##### Ahanab Habib Fahad

###### Ahanab Habib Fahad

---

# 3. Paragraph

---

> ## 3.1 Line brake

---

> > ### 3.1.1 Html syntax

---

You can use html br tag like </br>
for brake a line .

---

> > ### 3.1.2 Markdown syntax

---

Just use double space when you want to end a line  
new line atomatically brake where you given double space

---

> ## 3.2 Horizental Line

---

> > ### 3.2.1 Html syntax

---

You can use hr tag to make horizental line.<hr>

> > ### 3.2.2 Markdown syntax

---

You can use --- triple dash in new line to make horizental line.

---

> ## 3.3 Paragraph

---

> > ### 3.3.1 Html syntax

---

<p>You can use p tag to make paragraph1</p>
<p>You can use p tag to make paragraph2</p>

> > ### 3.3.2 Markdown syntax

---

You can generally write paragraph .Multiple paragraph use double line space it's first one

You can generally write paragraph .Multiple paragraph use double line space it's second one

---

> ## 3.4 Italic text

---

> > ### 3.4.1 Html syntax

---

<i>You can use i or em tag for italick text</i>  
<em>You can use i or em tag for italick text</em>

---

> > ### 3.4.2 Markdown syntax

---

_You can take your text bbtween 2 star like this._

---

> ## 3.5 Bold text

---

> > ### 3.5.1 Html syntax

---

<b>Use b tag for bold text like this </b>

---

> > ### 3.5.2 Markdown syntax

---

**Use double underscore after & before to your text**

---

> ## 3.6 Bold & Italic text

---

> > ### 3.6.1 Html syntax

---

<b><i>Use b tag for bold & i tag or em tag for italic text like this</i> </b>

<b><em>Use b tag for bold & i tag or em tag for italic text like this</em> </b>

---

> > ### 3.6.2 Markdown syntax

---

**_Use double underscore for bold & star for italic after & before to your text_**

---

> ## 3.7 Strikethrough

---

> > ### 3.7.1 Html syntax

---

<del>You can use del tag for strikethrough</del>

---

> > ### 3.7.2 Markdown syntax

---

~~You can use double difference sign for strikethrough like this~~

---

> ## 3.8 Nested blockqute

---

> > ### 3.8.1 Markdown syntax

---

> You can use grater than sign to make indentation
>
> > You can use grater than sign to make indentation
> >
> > > You can use grater than sign to make indentation

---

> ## 3.9 Under line

---

> > ### 3.9.1 Html syntax

---

<u>You can use u tag to make underline text </u>

---

# 4. Code Block

---

> ## 4.1 Inline Code Block

---

> > ### 4.1.1 Markdown syntax

---

<!-- Use single back tic to make inline block code-->

`<h1> Bangladesh</h1>`  
`<p> Bangladesh is a small country</p>`

---

> ## 4.2 Multipule line Code Block with set Language

---

> > ### 4.2.1 Markdown syntax

---

<!-- use triple back tic to make multipule line block code -->

```
<html>
<head></head>
<body></body>
</html>
```

```html
<html>
  <head></head>
  <body></body>
</html>
```

```javascript
let x = "Ahanab Habib Fahad";

const name = (x) => {
  console.log(x);
};

name(x);
```

---

# 5. List

---

> ## 5.1 Order List

---

> > ### 5.1.1 Html syntax

---

<!-- using html tag to make order list -->
<ol>
  <li> Item 1</li>
  <li> Item 2</li>
  <li> Item 3</li>
</ol>

---

> > ### 5.1.2 Markdown syntax

---

<!-- use number and a dot and a space like this  -->

1. Iteam 1
1. Iteam 2
1. Iteam 3

---

> ## 5.2 Unorder List

---

> > ### 5.2.1 Html syntax

---

<!-- use html tag to make a unorder list -->
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

---

> > ### 5.2.2 Markdown syntax

---

<!-- use a dash  and a space like this  -->

- Item 1
- Item 2
- Item 3

---

> ## 5.3 Nested List

---

> > ### 5.3.1 Html syntax

---

<ol>
  <li>Item 1
    <ol>
      <li> Item 1.1</li>
      <li> Item 1.2</li>
      <li> Item 1.3</li>
    </ol>
  </li>
  <li> Item 2</li>
  <li> Item 3</li>
  <li> Item 4
    <ul>
      <li>Item 4.1</li>
      <li>Item 4.2</li>
      <li>Item 4.3</li>
    </ul>
  </li>
</ol>

---

> > ### 5.3.2 Markdown syntax

---

1. Iteam 1
   - Item 1.1
   - Item 1.2
   - Item 1.3
1. Iteam 2
1. Iteam 3
   1. Iteam 3.1
   1. Iteam 3.2
   1. Iteam 3.3
1. Iteam 4

---

> ## 5.4 Task List

---

> > ### 5.4.1 Markdown syntax

---

- [x] Task 1 // complete task
- [x] Task 2 // complete task
- [] Task 3 // incomplete task

---

# 6. Links

---

> ## 6.1 Automatic link

---

<!-- just paste link -->

https://www.google.com  
https://www.facebook.com

---

> ## 6.2 disable link

---

<!-- just use back tic -->

`https://www.google.com`  
`https://www.facebook.com`

---

> ## 6.3 Markdown link syntax

---

[Google](googlelink)  
[Facebook](facebooklink)  
[Github](githublink)

<!-- all link is here  like variable-->

[googlelink]: http://www.studywithanis.com
[facebooklink]: http://www.studywithanis.com
[githublink]: http://www.studywithanis.com

---

> ## 6.4 set link title

---

[Google](googlelink "title of google")  
[Facebook](facebooklink "title of facebook")  
[Github](githublink "title of github")

---

# 7. Image Linking

---

> ## 7.1 Html syntax

---

<img src="./image/fahad.jpg" width="200px" height="250px" alt="Fahad" title="Fahad"/>

---

> ## 7.2 Markdown syntax

---

<!-- can not handle the with height property -->
<!-- ![alt text](image url "title it's optional") -->

![Fahad](./image/fahad.jpg "Fahad")

---

# 8. Emoji

---

<!-- just copy an emoji and paste here -->

😯😯😯😯😯😯😯

---

# 9. Table

---

> ## 9.1 Html syntax

---

<table>
  <caption>Simple table</caption>
  <tr>
    <th>Name</th>
    <th>age</th>
  </tr>
  <tr>
    <td>Habib</td>
    <td>22</td>
  </tr>
  <tr>
    <td>Fahad</td>
    <td>20</td>
  </tr>
</table>

---

> ## 9.2 Markdown syntax

---

| Name  | Age |
| ----- | --- |
| Habib | 22  |
| Fahad | 20  |

---

<p style="font-size:20px; color: hotpink">This is enough for Markdown.
You can also learn from google to know more about Markdown as you need.</p>
