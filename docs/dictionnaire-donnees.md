# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | ✏️ |
|  Parcelle|  Identifiant de la parcelle|Chaine de caractère(string) |non vide | P2 |
| Texture |Type de texture physique du sol |chaine de caractère(string) |Non vide | -  |argileux|
| pH | Potentiel hydrogène| Nombre(number) |compris entre 0 - 14| - | 5,5|
| etatHumidite | Humidité du sol |chaine de caractère(string) |Non vide |- |sec |

**Listes de valeurs autorisées** : 
 *texture : [argileux, sableux, limoneux]
 *humidite : [sec, humide, intermediaire]

**Sources** : Carnet d'observation du sol
