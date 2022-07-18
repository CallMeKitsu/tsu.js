# [sync](../) [function](../../) range(stop, start, step)

La fonction `range(stop, start, step)` renvoie un tableau contenant les entiers de l'intervalle `[start;stop[` avec `step` (par défaut = 1) d'écart entre eux.

```js
range(8) // => [0,1,2,3,4,5,6,7]
range(8, 1) // => [1,2,3,4,5,6,7]
range(8,0,2) // [0,2,4,6]
```

### Arguments

* `stop` (int) : entier de fin de l'intervalle, non inclus
* `start` (int) \<optionnel> : entier de début de l'intervalle, inclus
* `step` (int) \<optionnel> : écart séparant deux entiers du résultat 
