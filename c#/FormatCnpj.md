When you have CNPJ field, you can format it using:

```
Convert.ToUInt64(CNPJ).ToString(@"00\.000\.000\/0000\-00")
```

Also you can remove it using: 

```
CNPJ.Replace(".", string.Empty).Replace("-", string.Empty).Replace("/", string.Empty)
```