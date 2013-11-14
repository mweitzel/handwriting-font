handwriting-font
================

I turned my handwriting into a font.

Here is an example

![example image](https://raw.github.com/mweitzel/handwriting-font/master/example.png "My that sure is a dandy looking font!")


kind of a mess, spacing is way off, but you can use on your site by including this in your css:

```
@font-face {
  font-family: "weitzel";
  src: url( https://github.com/mweitzel/handwriting-font/raw/master/weitzel.otf ) format("truetype");
}

*{
  font-family:weitzel;
  letter-spacing: -5px;
}
```
