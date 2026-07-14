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

<<<<<<< HEAD
> "- Voici les informations que nous détenons :
- Le numéro du cabinet commence par 02 99 27 44 XX
- Le médecin est spécialisé dans la gériatrie
- Le médecin exerce à Rennes
- Son prénom commence par M
  
Quel est son numéro RPPS ?"
=======
> "Google|Recherche d'informations"
>>>>>>> e26c8e4 (update writeup)

---

## Outils

| Outil | Rôle |
|:------|:-----|
| `Google` | Recherche classique d'informations |

---

## Résolution

<details>
<summary>Voir la démarche complète</summary>

### [01] — Recherche Google 2/2

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
