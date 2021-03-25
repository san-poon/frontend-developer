# What is CSS?

CSS (Cascading Style Sheets) is a language for specifying how documents are presented to users - how they are styled, laid out, etc.

A **document** is usually a text file structured using a markup language - HTML is the most common markup language, but you may also come across other markup languages such as **SVG** or **XML**.

**Presenting** a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge, are designed to present documents visually, for example, on a computer screen, projector or printer.

## Main Points:

* Accessibility mainly refers to the requirement for our webpages to be understandable and usable by everyone.

* **descendant combinator** : Takes the form of a space between two other selectors.

```css
li em {
    color: rebeccapurple;
}
````

Here, `em` is inside `li`.

<br>

* **adjacent sibling combinator** : Takes `+` between the selectors.

```css
h1 + p {
    font-size: 200%;
}
```

Here, `p` comes directly after `h`.
