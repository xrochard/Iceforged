---
title: "Encaisser des blessures"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
bookCollapseSection: true
# bookComments: false
# bookSearchExclude: false
# bookHref: ''
# bookIcon: ''
---
<!-- LTeX: language=fr-->

<!-- LTeX: enabled=false -->
**Lorsque vous subissez une blessure physique, de la fatigue ou une maladie**, 
subissez *-1 santé* pour un dégât mineur, *-2 santé* pour un dégât majeur 
ou *-3 santé* pour un dégât grave. 
Si votre santé atteint 0, [perdez du momentum]({{< ref "docs/suffer/momentum" >}}) d’un chiffre égal 
aux dégâts restant.
<!-- LTeX: enabled=true -->

Ensuite, si votre *santé est à 0* ou si vous *choisissez de résister aux dégâts*, 
lancez *+Santé* ou *+Puissance* (le plus élevé des deux). 

En cas de **réussite majeure**, choisissez l’une des deux options.

<!-- LTeX: enabled=false -->
- Se remettre: si vous n’êtes pas **blessé**, gagnez *+1 santé.*
- Accepter la douleur: gagnez *+1 momentum*.

En cas de **réussite mineure**, si vous n’êtes pas **blessé**, 
vous pouvez [perdre du momentum]({{< ref "docs/suffer/momentum" >}}) (-1) en échange de *+1 santé*.
Sinon, continuez.

En cas **d’échec**, la situation est pire que prévu. 
Vous subissez *-1 santé* supplémentaire ou [perdez du momentum]({{< ref "docs/suffer/momentum" >}}) (-2). 
<!-- LTeX: enabled=true -->

Si votre *santé est à 0*, vous devez également marquer que vous êtes **blessé** ou **mutilé**, 
ou lancer un dé pour le tableau ci-dessous.

<!-- LTeX: enabled=false -->
| d100     | Résultat     |
| :---:    | :---         |
| 1 – 10   | Vous subissez des dégâts mortels. [Affrontez la mort]({{< ref "docs/threshold/death" >}}).|
|11 – 20   | Vous êtes mourant. Dans une heure ou deux, vous devez [vous soigner]({{< ref "docs/restore/heal" >}}) et remonter votre santé au-dessus de 0, ou [affronter la mort]({{< ref "docs/threshold/death" >}}).|
|21 – 35   | Vous êtes inconscient et hors de combat. Si vous êtes laissé seul, vous reprenez vos esprits en une heure ou deux. Si vos blessures sont susceptibles de s’aggraver, [affronter la mort]({{< ref "docs/threshold/death" >}}).|
|36 – 50   | Vous êtes chancelant. Si vous vous engagez dans une activité vigoureuse avant de reprendre votre souffle, relancez dans ce tableau (avant de résoudre l’autre action).|
|51 – 100  | Vous êtes toujours debout.  |
<!-- LTeX: enabled=true -->
