# 2 - Metadata in HTML
[MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)
the head's job is to contain metadata about the document.
## the <meta> element
Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the `<meta> `element. 

Many `<meta>` elements include name and content attributes:

- `name` specifies the type of meta element it is; what type of information it contains.
- `content` specifies the actual meta content.

The description is also used on search engine result pages. Let's go through an exercise to explore this

**can be use to design short description for you web**

## ICON
Adding the following line into your HTML's `<head>` block to reference it:
```html
<link rel="icon" href="favicon.ico" type="image/x-icon">
```

## Setting the primary language of the document
```html
<html lang="en-US">
```