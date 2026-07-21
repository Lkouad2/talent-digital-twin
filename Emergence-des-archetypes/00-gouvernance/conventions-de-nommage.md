# Conventions de nommage

## Identifiants

| Objet | Format | Exemple |
|---|---|---|
| Entretien anonymisé | `ENT-XXX` | `ENT-004` |
| Source secondaire | `SRC-XXX` | `SRC-012` |
| Preuve | `PREUVE-XXXX` | `PREUVE-0048` |
| Hypothèse problème | `H1` à `H7` | `H5` |
| Hypothèse solution | `S1` à `S5` | `S3` |
| Décision | `DEC-XXX` | `DEC-006` |
| Dimension | `R1` à `R4` | `R3` |
| Test | `TEST-XX` | `TEST-01` |

## Fichiers

- minuscules ;
- mots séparés par des tirets ;
- aucun nom de personne ;
- aucune date de naissance ;
- aucun employeur ;
- aucune information permettant une recherche inversée.

Exemple :

```text
ent-004.md
preuves-r3.md
correspondance-problemes-solutions.md
```

## Contenu d’un entretien public

Un fichier d’entretien contient uniquement :

- une tranche d’âge ;
- une famille de rôle ;
- un type de source ;
- une paraphrase ;
- les codes utiles ;
- le niveau de preuve ;
- les limites.

Il ne contient ni citation exacte, ni URL individuelle, ni combinaison de détails permettant d’identifier la personne.
