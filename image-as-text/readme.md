# Fill text with an image

this uses the following essential CSS (see the .html file for more styling) on an `h1` tag:

```css
h1 {
  background: url(background.png) center;
  background-size: cover;
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}
```

For now, you need the `-webkit` prefix, but be sure to add `background-clip: text;` for the future.