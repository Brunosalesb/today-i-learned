When you have CPF field, you can format it using:

```
Convert.ToUInt64(CPF).ToString(@"000\.000\.000\-00")
```

Also you can remove it using: 

```
CNPJ.Replace(".", string.Empty).Replace("-", string.Empty).Replace("/", string.Empty)
```