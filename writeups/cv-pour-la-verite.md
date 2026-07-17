---
title: "Un cv pour la vérité "
platform: "LAB'OSINT"
category: "FOOTPRINTING"
difficulty: "Medium"
date: "juillet 2026"
points: "25"
---

# Un cv pour la vérité  — OSINT Write-up

---

| Plateforme | Catégorie | Difficulté | Date | Points |
|:-----------|:----------|:-----------|:-----|-------:|
| LAB'OSINT | FOOTPRINTING | Medium | juillet 2026 | 25 |

---

## Énoncé

> "Un cabinet spécialisé en chasseur de tête vous a demandé de vérifier pour qui Vianney Brenac (né en 2000), travaillait en Décembre 2020."

---

## Outils

| Outil | Rôle |
|:------|:-----|
| `Google` | Recherche d'informations |
| `Linkedin` | Découverte du flag |

---

## Résolution

<details>
<summary>Voir la démarche complète</summary>

### [01] — Recherche avec Google

En recherchant simplement le nom de la personne, nous pouvons tomber sur son profil Linkedin.
Dans son parcours, nous pouvons voir qu'il a été assistant parlementaire au Sénat pendant la période demandée.
Nous devons trouver plus d'informations sur le poste et son contexte pour trouver le flag

> **Résultat :** Dr assistant parlementaire au Sénat

---

### [02] — Trouver un concert et le groupe

En ajoutant les mots "assistant parlemantaire" à son prénom et nom sur Google, nous pouvons avoir plus de contexte.
Le deuxième lien notamment, nous montre un post qui nous permet de voir le nom de la personne avec laquelle il a travaillé.

> **Résultat :** S***** T*****-P*****

</details>

---

## Flag

```
LABOSINT{S***** T*****-P*****}
```

---
