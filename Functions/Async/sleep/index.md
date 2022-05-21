# [async](../) [function](../) sleep(ms)

La fonction `sleep` arrête l'éxécution d'une fonction asynchrone pendant la durée voulue.

```js
async function test() {
  let a = 1
  await sleep(1000) // l'éxécution attend une seconde
  return a + 1
}

test() // renvoie 2 au bout d'une seconde
```

### Arguments

* `ms` (int) : temps à attendre en millisecondes
