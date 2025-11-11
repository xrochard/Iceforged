---
title: "Subir des dommages (véhicules)"
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
**Lorsque votre véhicule est confronté à une situation ou un environnement dommageable**, 
subissez *-1 intégrité* pour des dommages mineurs, *-2 intégrité* pour des dommages majeurs 
ou *-3 intégrité* pour des dommages graves. 
Si *son intégrité atteint zéro*, [perdez du momentum]({{< ref "docs/suffer/momentum" >}}) d’un chiffre égal 
à la valeur des dommages restant.
<!-- LTeX: enabled=true -->

Si son intégrité est égale à zéro ou si vous choisissez de résister,
lancez *+Intégrité*. 
En cas de **réussite majeure**, choisissez l’une des deux options.

<!-- LTeX: enabled=false -->
- Contournement: si votre véhicule n’est pas **endommagé**, gagnez *+1 intégrité*.
- Surmonter la situation: gagnez *+1 momentum*.

En cas de **réussite mineure**, si votre véhicule n’est pas **endommagé**, 
vous pouvez [perdre du momentum]({{< ref "docs/suffer/momentum" >}}) (-1) et lui donner *+1 intégrité*. 
Sinon, continuez.

En cas **d’échec**, la situation est pire que prévu. 
Il subit *-1 intégrité* supplémentaire ou vous [perdez du momentum]({{< ref "docs/suffer/momentum" >}}) (-2). 
Si son intégrité est égale à 0, vous subissez également un coût selon le type de véhicule:

- **Véhicule de commandement**: marquez le véhicule comme **endommagé** ou **maudit**, 
marquez un module comme **brisé**, détruisez un module brisé en le défaussant 
ou effectuez un jet de dés sur le tableau ci-dessous. 
Si le véhicule de commandement est détruit, [surmontez sa destruction]({{< ref "docs/threshold/destruction" >}}).
- **Véhicule de soutien**: marquez le véhicule comme **endommagé** ou effectuez un jet de dés sur le tableau ci-dessous. 
Si le véhicule est détruit, défaussez l’élément.
- **Véhicule secondaire**: faites un jet de dés sur le tableau ci-dessous.

| d100     | Résultat     |
| :---:    | :---         |
| 1 – 10   | Destruction catastrophique immédiate. Tous les occupants doivent [souffrir de blessures]({{< ref "docs/suffer/health" >}}) ou [affronter la mort]({{< ref "docs/threshold/death" >}}), selon les cas.  |
|11 – 25   | La destruction est imminente et inévitable. Les occupants qui n'ont pas les moyens ou l’intention de s'enfuir doivent [souffrir de blessures]({{< ref "docs/suffer/health" >}}) ou [affronter la mort]({{< ref "docs/threshold/death" >}}), selon les cas.  |
|26 – 40   | La destruction est imminente, mais peut être évitée [en réparant]({{< ref "docs/restore/repair" >}}) votre véhicule et en augmentant son intégrité au-dessus de 0. En cas d’échec, voir 11 – 25.  |
|41 – 55   | Vous ne pouvez pas [réparer]({{< ref "docs/restore/repair" >}}) ce véhicule tant que vous ne vous êtes pas [ravitaillé]({{< ref "docs/restore/supply" >}})  et obtenu une pièce de rechange essentielle. Si vous avez déjà obtenu ce résultat avant cela, voir 11 – 25.  |
|56 – 70   | Le véhicule est accidenté ou hors service. Pour le remettre en service, vous devez le [réparer]({{< ref "docs/restore/repair" >}}) et augmenter son intégrité au-dessus de 0.  |
|71 – 85   | Le véhicule est malmené. Toutes les personnes à bord doivent [souffrir de blessures]({{< ref "docs/suffer/health" >}}) , [subir du stress]({{< ref "docs/suffer/stress" >}}) ou avoir un [compagnon touché]({{< ref "docs/suffer/companion" >}}), en conséquence d’un coût majeur (-2).  |
|86 – 95   | Vous avez perdu du carburant, de l’énergie ou du chargement. [Sacrifiez des ressources]({{< ref "docs/suffer/resources" >}}) (-2).  |
|96 – 100 | Contre toute attente, le véhicule tient bon.  |
<!-- LTeX: enabled=true -->
