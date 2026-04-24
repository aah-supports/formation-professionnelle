# Correction - Chapitre 1 (Dispersion)

## Rappel de vocabulaire
- **IQR** signifie **InterQuartile Range** en anglais.
- En français : **écart interquartile**.
- Formule : **IQR = Q3 - Q1**.
- Interprétation : c'est l'étalement des **50% centraux** des données.

## Exercice 1
Série : 8, 10, 12, 13, 17
- Étendue = 17 - 8 = **9**
- **Justification** : l'étendue regarde uniquement les deux valeurs extrêmes (minimum et maximum).

## Exercice 2
- Série A : étendue = 7 - 3 = **4**
- Série B : étendue = 9 - 1 = **8**
Conclusion : la série **B** est plus dispersée.
- **Justification** : plus l'étendue est grande, plus l'intervalle global des valeurs est large.

## Exercice 3
- Série A : 10, 10, 10, 10 -> dispersion nulle.
- Série B : 7, 9, 11, 13 -> valeurs étalées autour de 10.
Conclusion : la série **B** est plus dispersée.
- **Justification** : avoir la même moyenne ne suffit pas ; la dispersion mesure l'écart des valeurs autour du centre.

## Exercice 4
Série : 2, 4, 6, 8
- Moyenne : (2 + 4 + 6 + 8) / 4 = **5**
- Écarts à la moyenne : -3, -1, 1, 3
- Carrés : 9, 1, 1, 9 -> somme = 20
- Variance (convention Bac, division par n) : 20 / 4 = **5**
- **Justification** : on met les écarts au carré pour éviter que les écarts négatifs compensent les positifs.

## Exercice 5
- Écart-type = sqrt(variance) = sqrt(5) ≈ **2,24**
- **Justification** : l'écart-type est la racine de la variance pour revenir à l'unité initiale (ici, la même unité que la série).

## Exercice 6
Série ordonnée : 2, 3, 5, 6, 7, 9, 12, 13, 15
- Médiane : 5e valeur = **7**
- Q1 (convention usuelle niveau Bac) = 3e valeur = **5**
- Q3 = 7e valeur = **12**
- **Justification** : les quartiles découpent la série en quatre zones d'effectifs proches.

## Exercice 7
- IQR = Q3 - Q1 = 12 - 5 = **7**
- **Justification** : cet indicateur ignore les extrêmes et se concentre sur la zone centrale de la distribution.



## Exercice 8
Série : 11, 12, 12, 13, 14, 40
- La valeur 40 est extrême.
- L'écart-type est sensible aux valeurs extrêmes.
Conclusion : l'indicateur le plus `robuste` est **IQR** (avec médiane).
- **Justification** : une valeur extrême augmente fortement la variance (car écarts au carré), alors que l'IQR varie peu.



## Exercice 9
Données : min=4, Q1=8, médiane=11, Q3=15, max=28
- IQR = 15 - 8 = **7**
- Moustache haute : 28 - 15 = 13
- Moustache basse : 8 - 4 = 4
Conclusion : asymétrie probable vers la droite.
- **Justification** : la queue à droite est plus longue, ce qui indique des valeurs plus étalées vers les grandes valeurs.




## Exercice 10
Indicateur recommandé : **médiane + IQR**
- Plus robustes que moyenne + écart-type en présence de trajets atypiques.
- **Justification** : en contexte réel (trajets, délais), quelques valeurs exceptionnelles existent souvent ; médiane + IQR donnent une vue plus stable.
