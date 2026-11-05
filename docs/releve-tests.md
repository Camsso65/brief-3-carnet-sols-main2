# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** : refaites à la main les résultats de référence de `SUJET.md`, puis comparez avec votre programme. ✏️

**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action                     | Attendu                                                 | Obtenu             | Testeur           |
|                            | ---                                                     | ---        ---     |                   |
|Ajouter avec les pH 0 et 14 |acceptés(bornes comprises)                               |     conforme       |      auto-test   |
| Ajouter S04(doublon),texture sable,pH |Une ligne d'erreur non respectée, menu revient|     conforme       |       auto-test   |
|Rechercher s01, puis s99    | Ligne de S04;" Observertion" introuvable                |     conforme       |      auto-test    |
|Rechercher la parcelle p3 et la texture argileux | 2 observations;3 observations      |     conforme       |      auto-test    |

**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : ✏️
