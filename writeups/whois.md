---
title: "Whois"
platform: "LAB'OSINT"
category: "Learning track"
difficulty: "Medium"
date: "14 juillet 2026"
points: "50"
---

# Whois — OSINT Write-up

---

| Plateforme | Catégorie | Difficulté | Date | Points |
|:-----------|:----------|:-----------|:-----|-------:|
| LAB'OSINT | Learning track | Medium | 14 juillet 2026 | 50 |

---

## Énoncé

> "Quel est l’hébergeur du site ege.fr ?"

---

## Outils

| Outil | Rôle |
|:------|:-----|
| `Whois` | Recherche d'image inversée |

---

## Résolution

<details>
<summary>Voir la démarche complète</summary>

### [01] — Ligne de commande

En ligne de commande, sur un OS Linux, la commande whois est déjà disponible. 
Elle permet rapidement de trouver l'hébergeur d'un site.

```
whois NOM_DU_SITE
```

Cela permet de tester le nom de domaine donné : ege.fr.

```
whois ege.fr
[...]
e-mail:tech@XXX.net
registrar:XXX
```

> **Résultat :** La réponse est directement dans la ligne registrar.

</details>

---

## Flag

```
LABOSINT{***}
```

---
