# A drop initial capital letter with 

this uses the following essential CSS (see the .html file for more styling) in a `.dropcap` class that can be applied to any paragrpah or other text block (e.g. `blockquote`):

```css
.dropcap::first-letter {
  font-size: 2.6em;
  float: left;
}
```

Older version of some browsers [only support the deprecated](https://caniuse.com/#search=first-letter) `:first-letter` pseudo-class, not the `::first-letter` pseudo-element.
