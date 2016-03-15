# extends_sequentially
Multiple inheritance for CoffeeScript, Python-style

With this lib, you can inherit several classes at once and have everything resolved left-to-right:

```coffeescript
class Tesla extends sequentially ElectroEngineMixin, TouchscreenMixin, Car
  accelerationTime: ->
    if options.ludicrous_mode? then 2.8 else 3.1
```

## Install

Copy it, `require` it into your code. That's it.

## Authorship

Code written by @darrrk: https://gist.github.com/darrrk/75d6a6a4d431e7182888.
