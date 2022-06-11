# [String](../).prototype.without(chars)

La méthode `without` renvoie la chaîne de caractères sur laquelle elle est appliquée en y retirant les caractères demandés.

```js
let forbiddenChars = ["0", " ", ".", "-"]
let resultat = "L'0rang-Outan mange.".without(forbiddenChars) 
console.log(resultat) // => "L'rangOutanmange"
```

### Arguments

* `chars` (arr) : tableau contenant les caractères à retirer
