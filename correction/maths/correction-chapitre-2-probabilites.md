# Correction - Chapitre 2 (Probabilités)

## Exemple complet du cours (probabilité totale + Bayes)
Données :
- P(M) = 0,01 et P(non M) = 0,99
- P(+|M) = 0,95
- P(+|non M) = 0,05

Étape 1 - Probabilité totale :
- P(+) = P(+|M)P(M) + P(+|non M)P(non M)
- P(+) = 0,95*0,01 + 0,05*0,99 = 0,059

Étape 2 - Bayes :
- P(M|+) = [P(+|M)P(M)] / P(+)
- P(M|+) = (0,95*0,01) / 0,059 = 0,161 soit 16,1%

Interprétation :
- Un test positif n'implique pas automatiquement une forte probabilité d'être malade.
- La fréquence de base (prévalence) joue un rôle majeur.

## Exercice 1
Lancer d'un dé :
- Omega = {1,2,3,4,5,6}
- A = "pair" = {2,4,6}
- B = "> 4" = {5,6}

## Exercice 2
- A inter B = {6}
- A union B = {2,4,5,6}

## Exercice 3
Si P(A)=0,35 :
- P(A barre) = 1 - 0,35 = **0,65**

## Exercice 4
P(A inter B)=0,18 et P(B)=0,30
- P(A|B)=P(A inter B)/P(B)=0,18/0,30=**0,60**

## Exercice 5
- P(A|B) : probabilité de A sachant B.
- P(B|A) : probabilité de B sachant A.
Ce ne sont pas les mêmes quantités.

## Exercice 6
- P(A)P(B)=0,4*0,5=0,2
- P(A inter B)=0,2
Comme P(A inter B)=P(A)P(B), A et B sont **indépendants**.

## Exercice 7
- P(conforme)=0,70
- P(détectée conforme | conforme)=0,90
- P(conforme et détectée conforme)=0,70*0,90=**0,63**

## Exercice 8
Ateliers : A1=60%, A2=40%
- P(defaut)=P(A1)P(defaut|A1)+P(A2)P(defaut|A2)
- =0,60*0,02 + 0,40*0,05
- =0,012 + 0,020 = **0,032** (3,2%)

## Exercice 9
Parmi les défauts :
- Contribution A1 : 0,60*0,02 = 0,012
- Contribution A2 : 0,40*0,05 = 0,020
A2 contribue davantage.
- P(A2|defaut)=0,020/0,032=**0,625** (62,5%)

## Exercice 10
Prévalence faible (1%) + faux positifs non nuls (4%) =>
un test positif ne garantit pas une forte probabilité d'être malade.

Exemple sur 10 000 personnes :
- Malades : 100 -> positifs vrais : 95
- Non malades : 9 900 -> faux positifs : 396
- Positifs totaux : 491
- P(malade|test+) = 95/491 ≈ **19,3%**
