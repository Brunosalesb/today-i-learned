To get unique values in javascript array, you can combine ```filter()``` + ```indexOf()```:

```
const unique = (value, index, self) => {
 return self.indexOf(value) === index
}

const ages = [26, 27, 26, 26, 28, 28, 29, 29, 30]
const uniqueAges = ages.filter(unique)
```
