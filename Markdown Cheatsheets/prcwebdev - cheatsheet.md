###### Day 14 of #100DaysOfCode - Markdown Cheatsheet

<!-- # 1. Official Markdown -->

## Headings

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

## Italic

_This text_ is italic
_This text_ is italic

<!-- To escape the * use \ before it -->

\*This text\* is no longer italic because i used \ before the \*

## Strong

**This text** is italic
**This text** is italic

## Strikethrought

~~This text~~ is strikethrought

## Horizontal Rule

3- \---

---

sau
3\_ \_\_\_

---

## Blockquote

> This is a (block) quote
> This is a (block) quote with a cite tag -- <cite> Cpt. Anonymous </cite>
> This is a (block) quote without a cite tag -- Cpt. Anonymous
> same result with or without the cite tag <cite></cite>

## Links

[Traversy Media](https://www.traversymedia.com/)

for title add "" with text inside them
[Traversy Media](https://www.traversymedia.com/ "Traversy Media")

## Unordered Lists

cu \*

- Item 1
- Item 2
- Item 3
  - tab to make Nested Item 1
  - Nested Item 2
  - Nested Item 3

sau cu \-

- Item 1
- Item 2
- Item 3
  - tab to make Nested Item 1
  - Nested Item 2
  - Nested Item 3

oricum le schimba VS Code Extension in minus -

## Ordered Lists

cu cifra urmata de punct \.

1. Item 1
2. Item 2
3. Item 3
4. dff
   1.1. dfsdf
   2.2. sdsd
   33.33. hmmm
   45.2345. okay...
5. asdfd
6. 3df
7. sdfgg

## Images

![Markdown Icon](https://upload.wikimedia.org/wikipedia/commons/5/5e/Font_Awesome_5_brands_markdown.svg)

## Code

`I just wrote some code`

<!-- # 2. GitHub Markdown -->

## Code Blocks

```bash
npm install

npm start
```

```javascript
function add(num1, num2) {
  return num1 + num2;
}
```

```python
  def add(num1, num2) {
    return num1 + num2
  }
```

\```bash, \```javascript, \```python - special highlights for the specificaly used programming language syntax

## Tables

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

| Name     | Email             |
| -------- | ----------------- |
| Jane Doe | janedoe@gmail.com |
| John Doe | johndoe@yahoo.com |

## Task Lists

- [x] Task 1
- [ ] Task 2
- [ ] Task 3
- [ ] Self updating Task List
- [ ] Check the boxes in preview mode to see the code update itself

## Footnotes

Here's a sentence with a footnote. [^1]
Here's another sentence with another footnote. [^2]

[^1]: This is the footnote.
[^2]: This is another footnote.

## Adding HTML tags to Markdown

###### For example - the details tag:

<details>
  <sumary> This is a test</sumary>
  <p> Pragraph #1
  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
  </p>
  <p>
    Paragraph #2
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Accusantium
    dolor at sequi obcaecati cupiditate. Voluptates repellendus cupiditate
    aperiam! Incidunt amet quo neque.
  </p>  
  No paragraph - same as with paragraph tag
  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Accusantium dolor at sequi obcaecati cupiditate. Voluptates repellendus cupiditate aperiam! Incidunt amet quo neque.
  
- Item 1
- Item 2
- Item 3
</details>

## Emojis

🙏 😍 ❤ 😂 🔥 🚀
&#9800; &#9801; &#9802; &#9803; &#9804; &#9808;
