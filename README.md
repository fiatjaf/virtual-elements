Use [virtual-hyperscript](https://github.com/Matt-Esch/virtual-dom/tree/master/virtual-hyperscript) with individual elements:

```coffeescript
{div, button, h1} = require 'virtual-elements'

vtree = (div {},
  (h1 {}, 'alôu')
  (button {},
    'beleza'
  )
) 
```
Good for using with Coffeescript, as you would do with the _lispy_-React pattern exampled in http://html2react.alhur.es/.

---

## Warning: this requires `virtual-dom`, but it is not set as a dependency so you can render its pool of incompatibility yourself. Please install it manually.
