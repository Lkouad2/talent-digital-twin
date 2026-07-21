# Grille d’analyse

## Champs par unité de preuve

| Champ | Description |
|---|---|
| `preuve_id` | Identifiant unique |
| `source_id` | Entretien ou source secondaire |
| `question` | Question concernée |
| `observation` | Paraphrase anonymisée |
| `codes` | Codes descriptifs |
| `directivite` | 0 à 3 |
| `qualite` | 1 à 5 |
| `pertinence_cible` | 0,5 à 2 |
| `polarite` | Soutient, nuance, contredit, neutre |
| `decision` | Conserver, revoir, rejeter |

## Pertinence de la réponse

| Score | Signification |
|---:|---|
| 1 | information faible ou très indirecte |
| 2 | indice partiel |
| 3 | réponse exploitable |
| 4 | preuve forte |
| 5 | preuve directe, détaillée et proche de la cible |

## Règle

Une réponse absente est codée `MISSING_DATA`. Elle ne doit jamais être interprétée comme une réponse négative.
