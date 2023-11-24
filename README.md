# DATA Analyse - Projet personnel sur les prénoms (données INSEE) (EN COURS)

Ce projet utilise la bibliothèque Python Pandas pour effectuer des opérations d'analyse de données sur les prénoms attribués aux enfants nés en France entre 1900 et 2022. 
Ces données sont disponibles au niveau France et par département.
- Note 1 : Les fichiers recensent les naissances et non pas les personnes vivantes une année donnée.
- Note 2 : Le fichier des prénoms est établi à partir des seuls bulletins de naissance des personnes nées en France (métropole et départements d’outre-mer). En conséquence, l’exhaustivité n’est pas garantie sur toute la période, notamment pour les années antérieures à 1946. Les utilisateurs pourront donc constater des écarts avec le nombre annuel des naissances évalué par l'Insee. Ces écarts, importants en début de période, vont en s’amenuisant. Après 1946, ils sont peu significatifs.
- Note 3 : Conditions portant sur les prénoms retenus
-**1.** Sur la période allant de 1900 à 1945, le prénom a été attribué au moins 20 fois à des personnes de sexe féminin et/ou au moins 20 fois à des personnes de sexe masculin
-**2.** Sur la période allant de 1946 à 2022, le prénom a été attribué au moins 20 fois à des personnes de sexe féminin et/ou au moins 20 fois à des personnes de sexe masculin
-**3.** Pour une année de naissance donnée, le prénom a été attribué au moins 3 fois à des personnes de sexe féminin ou de sexe masculin
Les effectifs des prénoms ne remplissant pas les conditions 1 et 2 sont regroupés (pour chaque sexe et chaque année de naissance) dans un enregistrement dont le champ prénom (PREUSUEL) prend la valeur «_PRENOMS_RARES_». Les effectifs des prénoms remplissant la condition 2 mais pas la condition 3 sont regroupés (pour chaque sexe et chaque prénom) dans un enregistrement dont le champ année de naissance (ANNAIS) prend la valeur «XXXX».

## Aperçu du projet

à venir

## Tech Stack

**Langages:** Python
**Bibliothèque:** Pandas, NumPy, Matplotlib, Seaborn





