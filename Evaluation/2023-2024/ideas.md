# Idées de questions à choix fermées

** [* Les bons et les mauvais tests *] - Cochez les assertions vraies
- une unique classe de test est nécessaire pour un programme comportant plusieurs classes
- on doit tester les accesseurs des classes (getters et setters)
+ on teste uniquement le comportement observable d'un objet
+ un test doit pouvoir être répété automatiquement
- un test peut avoir un résultat qui varie
+ faire réussir un test ne doit pas introduire de bug dans le programme principal

** [* Les bonnes pratiques de test *] - Cochez les assertions qui selon vous correspondent à de bonnes pratiques de test :
- faire uniquement des affichages dans la console
- tester uniquement les valeurs les plus fréquemment rencontrées
- tester uniquement les cas nominaux
- tester uniquement les cas d'erreurs/cas limites
+ manque bonne réponse...




# Idées de questions ouvertes

## Questions "pratiques"
* Voici un test :
```
//When a stack is created
//Then an item can be pushed on top of the stack
```
1. Expliquer en quoi ce test est mal écrit.
2. Proposer une réécriture correcte de ce test.

* Variante *

Pour tester la méthode push de la classe SimpleStack, un développeur propose cela :
```
//When a stack is created
//Then an item can be pushed on top of the stack
```
1. En quoi ce test n'est pas satisfaisant ?
2. Proposer les tests unitaires pour tester de manière satisfaisante la méthode push.