## Coffeescript

```coffeescript
(($) ->
    'use strict'

    $(document).on 'click.dropdown.data-api', '.dropdown', (e) ->
        e.preventDefault()
        $(this).toggle()

)(window.jQuery)
```

```javascript
(function($) {
  'use strict';
  return $(document).on('click.dropdown.data-api', '.dropdown', function(e) {
    e.preventDefault();
    return $(this).show();
  });
})(window.jQuery);
```
