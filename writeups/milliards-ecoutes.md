---
title: "Milliards d'écoutes"
platform: "LAB'OSINT"
category: "STEGANO"
difficulty: "Medium"
date: "juillet 2026"
points: "50"
---

# Milliards d'écoutes — OSINT Write-up

---

| Plateforme | Catégorie | Difficulté | Date | Points |
|:-----------|:----------|:-----------|:-----|-------:|
| LAB'OSINT | STEGANO | Medium | juillet 2026 | 50 |

---

## Énoncé

Le monde entier l’a écouté.
Et en quatre ans, après sa sortie en 2013, ce titre a dépassé le palier des milliards d’écoutes…

Lequel est-il ?"

---

## Outils

| Outil | Rôle |
|:------|:-----|
| `Picasion` | Découpe du gif |
| `Google` | Recherche d'informations |
| `Wikipedia` | Découverte du flag |

---

## Résolution

<details>
<summary>Voir la démarche complète</summary>

### [01] — Travailler avec le gif

Nous pouvons voir furtivement que le gif donné possède des caractères en différents endroits (dans les coins et au milieu à droite).
Nous devons pouvoir créer des images à partir du Gif, pour pouvoir décoder les caractères.
Nous pouvons utiliser le site https://picasion.com/split-animated-gif pour faire cela.

> **Résultat :** Dr https://picasion.com/split-animated-gif

---

### [02] — Traduction des caractères

Les caractères sont du morse, que nous pouvons traduire lettre par lettre.
Nous obtenons différents mots qui nous donnent des indices sur ce qui semblent être un événement.

> **Résultat :** ACCOR, 7 OCTOBRE, PARIS, 2025

---

### [03] — Trouver un concert et le groupe

Nous recherchons un concert qui se serait produit le 7 octobre 2025 à l'Accord Arena à Paris.
Le groupe qui s'est produit ce soir la est donc l'auteur de la chanson que nous cherchons.

> **Résultat :** OneRepublic

---

### [04] — Trouver la chanson

La chanson a été populaire après sa sortie. Simplement chercher une chanson en 2013 ne donnera pas de résultats. En revanche, cherchez les chansons les plus écoutées dans une période doit donner la solution.
Nous pouvons par exemple utiliser cette page : https://en.wikipedia.org/wiki/List_of_Spotify_streaming_records qui permet de repérer rapidement le groupe dans la liste, et le flag correspondant.

> **Résultat :** le flag

</details>

---

## Flag

```
LABOSINT{C******* S****}
```

---
