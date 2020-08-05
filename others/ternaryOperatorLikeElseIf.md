by default, we create a ternary operators like this:

```html
x == y ? '1' : '2' 
```

but we can create a ternary operator with more than two possibilities, like an else if, using:


```html
x == y ? '1' : (x == z ? '3' : '2')
```