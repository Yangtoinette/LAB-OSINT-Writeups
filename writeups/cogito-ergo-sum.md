---
title: "Cogito Ergo Sum"
platform: "LAB'OSINT"
category: "CTF Perce le front numérique by GMP"
difficulty: "Easy"
date: "14 juillet 2026"
points: "10"
---

# Cogito Ergo Sum — OSINT Write-up

---

| Plateforme | Catégorie | Difficulté | Date | Points |
|:-----------|:----------|:-----------|:-----|-------:|
| LAB'OSINT | CTF Perce le front numérique by GMP | Easy | 14 juillet 2026 | 10 |

---

## Énoncé

> "Retrouvez le nom de la personne juste en dessous de l’acte de naissance de Nicole Girard-Mangin ?"

---

## Outils

| Outil | Rôle |
|:------|:-----|
| `Google` | Recherche d'informations |
| `Site des archives de Paris` | Découverte du flag |

---

## Résolution

<details>
<summary>Voir la démarche complète</summary>

### [01] — Recherche Google

La recherche de l'acte de naissance de Nicole-Girard-Mangin doit être accompagnée de guillemets.
En effet, nous recherchons le terme exact "acte de naissance", pour ne pas avoir des résultats trop grands.
En filtrant par image, nous tombons sur un pdf qui nous parle d'un acte de naissance.
Le pdf nous indique même tout ce dont nous avons besoin pour trouver le flag.

> **Résultat :** Dr janinetissot.fdaf.org

---

### [02] — Site des archives de Paris

Grâce à l'étape précédente, nous cherchons sur le site des archives de Paris, dans l'acte numéroté 4536, à la page 30/31.
Le flag est le nom juste en dessous de celui de Mangin.

</details>

---

## Flag

```
LABOSINT{L******}
```

---
