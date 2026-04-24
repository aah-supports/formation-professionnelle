# Correction - Sujet Maths (dispersion et probabilites)

## Partie A - Dispersion

1. Etendue: `17 - 8 = 9`.
2. A: `7 - 3 = 4`, B: `9 - 1 = 8` donc B plus dispersee.
3. Serie B plus dispersee (A constante, dispersion nulle).
4. Serie `2,4,6,8`: moyenne `5`; variance (division par n) `5`.
5. Ecart-type: `sqrt(5) ~= 2,24`.
6. `Q1=5`, mediane `=7`, `Q3=12` (convention usuelle niveau Bac).
7. IQR: `Q3 - Q1 = 12 - 5 = 7`.
8. Indicateur recommande: IQR (presence d'une valeur extreme `40`).
9. IQR `= 15 - 8 = 7`; asymetrie a droite (moustache superieure plus longue).
10. Indicateur robuste conseille: mediane + IQR.

## Partie B - Probabilites

11. `Omega={1,2,3,4,5,6}`, `A={2,4,6}`, `B={5,6}`.
12. `A inter B={6}`, `A union B={2,4,5,6}`.
13. `P(A complementaire)=1-0,35=0,65`.
14. `P(A|B)=0,18/0,30=0,60`.
15. `P(A|B)` = probabilite de A sachant B; `P(B|A)` = probabilite de B sachant A.
16. Test independance: `P(A)P(B)=0,4*0,5=0,2 = P(A inter B)` donc independants.
17. Probabilite "conforme et detectee conforme": `0,70*0,90=0,63`.
18. `P(defaut)=0,60*0,02 + 0,40*0,05 = 0,032` (3,2%).
19. Atelier le plus probable parmi les defectueux: A2 (contribution `0,02` vs `0,012`).
   Calcul: `P(A2|defaut)=0,02/0,032=0,625` soit 62,5%.
20. Explication: la prevalence (frequence de base) est faible; les faux positifs peuvent etre nombreux.
   Exemple sur 10 000 personnes:
   - malades: 100 -> positifs: 95
   - non malades: 9 900 -> faux positifs: 396
   - positifs totaux: 491
   donc `P(malade|test+) = 95/491 ~= 19,3%`.

## Projet final - Pistes de correction

- Partie dispersion: verifier calculs (etendue, quartiles, IQR) et interpretation.
- Partie probabilites: verifier arbre, probabilite totale, interpretation conditionnelle.
- Conclusion: langage clair, distinction explicite entre `P(A|B)` et `P(B|A)`.
