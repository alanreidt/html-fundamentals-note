# HTML Fundamentals note

## Semantics
Each element, attribute and attribute value of HTML has certain meaning. This allows HTML processors, such as Web browsers and screen readers to present and use documents in different contexts. That's why it's very important to use HTML elements, attributes and attribute values as intended.

### Case-insensitive
The names of elements and their attributes are case-insensitive.

### The DOCTYPE element
A DOCTYPE is a required preamble.

DOCTYPEs are required for legacy reasons. They inform browsers which rendering mode to use. When the DOCTYPE is included in a document, it guarantees, that the browser makes a best-effort at following the relevant specifications.

It should be represented as this (case-insensitively):
```html
<!DOCTYPE html>
```

### The html element
The html element represents the root element of an HTML document.

Authors are encouraged to use `lang` attribute of the element, specifying a language of a document.

### The title element
The title element represents the document's title or name.

The document's title is often different from its first heading, since the first heading does not have to stand alone when taken out of context.

The next page might be a part of the same site. Note how the title describes the subject matter unambiguously, while the first heading assumes the reader knows what the context is and therefore won't wonder if the dances are Salsa or Waltz:
```html
<title>Dances used during bee mating rituals</title>
  ...
<h1>The Dances</h1>
```

### The article element
!!!

### The hgroup element
Use hgroup element for “heading and subheading” situation:
```html
<body>
 <hgroup>
  <h1>ACME Corporation</h1>
  <h2>The leaders in arbitrary fast delivery since 1920</h2>
 </hgroup>
 ...
```
