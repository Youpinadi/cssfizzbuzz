CSS FizzBuzz
===========

CSS implementation of the infamous FizzBuzz. No counter used. You can check the result [here](http://youpinadi.github.com/cssfizzbuzz/fizzbuzz.html)

Reminder of the rules:

For numbers 1 through 100,
* if the number is divisible by 3 print Fizz;
* if the number is divisilbe by 5 print Buzz;
* if the number is divisible by 3 and 5 (15) print FizzBuzz;
* else, print the number.


CSS:

```css
ol
{
    list-style-position: inside;
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
