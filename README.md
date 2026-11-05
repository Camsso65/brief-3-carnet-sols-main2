# Carnet d'observation des sols

> Projet individuel du SAS DFS, brief 3 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte
Ce outil est conçu pour les techniciens agricoles ainsi qu'aux agronomes dans l'optique de suivre l'évolution des caractéristiques du sol. Par le biais de cette application, ils pourront enregistrer le pH et la texture du sol pour chaque parcelle à temps réel. Le programme affiche un résumé complet des données, trie les parcelles selon leur acidité et génère des alertes pour des sols très acides(pH < inférieur à (5,5)). Par contre l'outil ne génère pas de prévision des rendements de récolte.

## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-3-carnet-sols.git
cd brief-3-carnet-sols
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

✏️ *Cochez seulement ce qui marche : `- [x]`.*

- [ X] Données lues et enregistrées dans `donnees/observations.json`
- [ X] Ajouter une observation, saisies invalides refusées sans arrêter le programme
- [ X] Lister les observations, message si le carnet est vide
- [ X] Rechercher par point ou par parcelle ; filtrer par texture
- [ X] Trier par pH
- [ X] Synthèse : pH minimum et maximum, nombre par texture, points à discuter (pH < 5,5)
- [ X] Bonus : supprimer et modifier une observation (choix 6 et 7)
- [ X] Bonus : tri par pH décroissant, texture la plus fréquente

## Données

| Champ  | Signification                   | Type                       | Règle de validation          | Unité | Exemple |
| `id`   Identifiant unique                | texte                      | non vide, absent des données | —     | ✏️     |
|Parcelle|Identifiant de la parcelle       |Chaine de caractère(string) |non vide                      | -     |  P2
|Texture |Type de texture physique du sol  |chaine de caractère(string) |Non vide                      | -     |argileux|
| pH     | Potentiel hydrogène             | Nombre(number)             |compris entre 0 - 14          | -     | 5,5    |
| etatHumidite | Humidité du sol           |chaine de caractère(string) |Non vide                      | -     |sec     |

## Limites

Le carnet ne nous permet pas de prevoir les recoltes, il ne montre pas non plus la fertilité des parcelles ou encore le géoréferencement de ces parcelles.

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

 CAMARA Salifou, [compte GitHub](https://github.com/Camsso65/brief-3-carnet-sols-main2/commits/main/). Entraide : Mes condisciples de classe, pour la meilleure comprehension du sujet et des syntaxes. J'ai également eu recours à l'IA Gemini, pour mieux comprendre certaines notions et le site Mdn egalement. 