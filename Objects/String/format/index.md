# [String](../).prototype.format(...vars)

La méthode `format` renvoie la chaîne de caractères sur laquelle elle est appliquée en remplaçant chaque `"{}"`, respectivement, par les valeurs passées en arguments.

```js
let string = "{} quick brown {} jumps over the lazy {}."
string.format(1, 'fox', "dog") 
console.log(string) // => "1 quick brown fox jumps over the lazy dog."
```

### Arguments

* `...vars` (rest args) : variables ou objets à placer
