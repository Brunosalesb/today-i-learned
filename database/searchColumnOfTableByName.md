When you search a column using this query:

```
SELECT [col.name](http://col.name/) AS 'ColumnName', [tab.name](http://tab.name/) AS 'TableName'

FROM sys.columns col

JOIN sys.tables tab ON col.object_id = tab.object_id

WHERE [col.name](http://col.name/) LIKE '%estoque%'

ORDER BY TableName,ColumnName;
};
```