CSS FizzBuzz
===========

CSS implementation of the infamous FizzBuzz. No counter used.

CSS:

```css
ol
{
    list-style-position:inside;
}
li:nth-child(3n),
li:nth-child(5n)
{
    list-style: none;
}
li:nth-child(3n):before
{
    content: 'Fizz';
}
li:nth-child(5n):after
{
    content: 'Buzz';
}
```

HTML:
```html
<ol>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ol>
```
