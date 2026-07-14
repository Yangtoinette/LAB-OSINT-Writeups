---
title: "Hippocrate"
platform: "LAB'OSINT"
category: "Pour débuter"
difficulty: "Medium"
date: "14 juillet 2026"
points: "25"
---

# Hippocrate — OSINT Write-up

---

| Plateforme | Catégorie | Difficulté | Date | Points |
|:-----------|:----------|:-----------|:-----|-------:|
| LAB'OSINT | Pour débuter | Medium | 14 juillet 2026 | 25 |

---

## Énoncé

> " Récupérer le numéro RPPS d'un médecin afin de prouver s'il exerce légalement.
- Voici les informations que nous détenons :
- Le numéro du cabinet commence par 02 99 27 44 XX
- Le médecin est spécialisé dans la gériatrie
- Le médecin exerce à Rennes
- Son prénom commence par M
Quel est son numéro RPPS ?"

---

## Outils

| Outil | Rôle |
|:------|:-----|
| `Google` | Recherche classique d'informations |

---

## Résolution

<details>
<summary>Voir la démarche complète</summary>

### [01] — Recherche Google 1/2

Nous pouvons nous concentrer sur certains termes de l'énoncé : "gériatre".
Si nous le cherchons suivi du numéro de téléphone avec la recherche exacte de Google (avec les guillemets), le premier lien nous permet de trouver le nom et le prénom du médecin.

> **Résultat :** Dr M**** C****

---

### [02] — Recherche Google 2/2

Une fois la personne identifiée, nous pouvons nous concentrer sur le numéro RPPS.
Une simple recherche du nom, prénom et le terme rpps permet de trouver.
Le premier lien nous renvoie sur la page où le numéro est affiché. 
Cela nous permet de trouver le flag.

</details>

---

## Flag

```
LABOSINT{1**********}
```

---
