Use [virtual-hyperscript](https://github.com/Raynos/virtual-hyperscript) with individual elements:

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
