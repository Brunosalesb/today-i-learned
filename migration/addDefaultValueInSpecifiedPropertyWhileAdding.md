You can set a default value for something property while you're adding it, using ```defaultValue:```:

```
AddColumn("dbo.report", "newProperty", c => c.String(nullable: false, defaultValue: value"));
```