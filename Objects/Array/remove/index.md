# [Array](../).prototype.remove(...indexes)

La méthode `remove` renvoie le tableau sur lequel elle est appliquée en lui retirant les éléments situés aux indices passés en arguments.

```js
let testArray = [1, 2, 3, 4, 5]
testArray.remove(1, 3) // renvoie [1, 3, 5]
```

### Arguments

* `...indexes` (rest args) : indices des éléments à retirer du tableau
