# HTML Basics

## What is HTML?

HTML (Hypertext Markup Language) is a *markup language* that defines the structure of your content. HTML consists of a series of *elements*, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way.

## `img` element

* `img` elements are self-closing.

* If the image is purely decorative, using an empty `alt` attribute is a best practice. Ideally, the `alt` attribute should not contain special characters unless needed.

## `a` (anchor) element

* To create an *internal link*, you assign a link's `href` attribute to a hash symbol `#` plus the value of the `id` attribute for the element that you want to internally link to, usually further down the page. 
Example :

```html
<h2 id="contacts-header">Contacts</h2>
```

* The value `target="_blank"` specifies to open the link in a new tab.

* Use `href="#"` to create a dead link.
