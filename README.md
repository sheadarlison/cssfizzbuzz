cssfizzbuzz
===========

CSS implementation of the infamous FizzBuzz

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
