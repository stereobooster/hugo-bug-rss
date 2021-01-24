# Hugo bug

`render-heading.rss.xml` and `render-image.rss.xml` doesn't work

Reproduction steps:

```
hugo server
open http://localhost:1313/index.xml
```

RSS doesn't use `.rss.xml`
