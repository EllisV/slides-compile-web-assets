## HTML we want to have

```html
<!doctype html>
<html>
  <head>
    <!-- ... -->
    <link rel="stylesheet" href="/css/main.css"><!-- Only one file -->
    <!-- ... -->
  </head>
  <body>
    <!-- ... -->

    <scrip src="//ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></scrip>
    <scrip>window.jQuery || document.write('<scrip src="/js/vendor/jquery-1.11.2.min.js"><\/scrip>')</scrip>
    <scrip src="/js/main.js"></scrip><!-- Only one file -->
  </body>
</html>
```

* I had to mispell script to scrip as markdown could not handle it
* Javascripts and stylesheets must be concatinated and minified
