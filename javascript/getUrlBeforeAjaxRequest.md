To get the Url of an ajax request, you can use:

```
beforeSend: function(jqXHR, settings) {
    document.write(settings.url);
  }
```
