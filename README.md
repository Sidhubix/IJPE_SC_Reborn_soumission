# Article SC-Reborn pour IJPE : version de soumission

Projet LaTeX unique (modèle Elsevier CAS) contenant deux documents :

- `manuscrit.tex` : manuscrit principal (introduction, état de l'art condensé, démarche Simuler / Mesurer / Apprendre, résultats majeurs, discussion, conclusion, déclarations). Sous 10 000 mots ; 15 pages bibliographie comprise en mode anonyme (`\anonymetrue`).
- `supplement.tex` : matériel supplémentaire (S1 revue détaillée de la littérature, S2 à S4 compléments de modélisation des trois blocs, S5 résultats complémentaires, S6 vue détaillée de la démarche, S7 reproductibilité des figures).

Le manuscrit renvoie au supplément par des mentions explicites (« voir le matériel supplémentaire, section S2.3 »). Les deux documents partagent `commun.tex` (couleurs, colonnes), `references.bib` et le dossier `figures/`.

## Compiler sur Overleaf

Importer le dépôt, puis choisir le document principal dans Menu, « Main document » : `manuscrit.tex` ou `supplement.tex`.

## Interrupteurs dans `manuscrit.tex`

- `\anonymetrue` : version en double aveugle (auteurs, affiliations, CRediT et financement masqués).
- `\suivifalse` : retire la liste de suivi des dépôts placée en fin de document.

## Origine

Restructuration de la version relue du dépôt `IJPE_SC_Reborn-reviewed-1-` (8 octobre 2026).
