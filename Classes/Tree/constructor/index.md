# [Tree](../)(config)

Le constructeur de la classe `Tree` prend en compte un objet de configuration qui définira la manière de rendre l'arbre de représentation.

```js
let tree = new Tree({
  sequence: {
    foo: [
      { 
        name:"bar", childs: {
          dang: [
            1,2,3
          ]
        }
      },
      { 
        name:"mom", childs: [ "baby"]
      }
    ]
  }
})
```
```js
console.log(tree.string) // => ci-dessous
```
```
root
└────foo                                          
     ├────bar                                     
     │    └────dang                               
     │         ├────1                             
     │         ├────2                             
     │         └────3                             
     └────mom                                     
          └────baby
```

### Arguments

* `config` (obj) : objet contenant l'ensemble des paramètres appliqués à l'arbre
  * `.sequence` (arr | obj) : une séquence de données à représenter
  * `.line_width` (int) <optionnel> : définit la largeur de chaque ligne de l'arbre
  * `.child_property` (str) <optionnel> : décide du nom de la propriété listant les "enfants" d'un élément
  * `.double_indent`(bool) <optionnel> : décide si on affiche l'arbre avec plus ou moins de lisibilité
  * `.rootname` (str) <optionnel> : le nom d'affichage de la racine de l'arbre (par défaut "root")
  * `.rootchilds` (bool) <optionnel> : décide si la clé de l'objet ou la valeur de `name` est utilisée comme nom
