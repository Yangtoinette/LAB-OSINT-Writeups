---
title: "Le lieu suspect"
platform: "LAB'OSINT"
category: "PEAKY BLINDERS : OPERATION BLUE VEIL"
difficulty: "Medium"
date: "juillet 2026"
points: "25"
---

# Le lieu suspect — OSINT Write-up

---

| Plateforme | Catégorie | Difficulté | Date | Points |
|:-----------|:----------|:-----------|:-----|-------:|
| LAB'OSINT | PEAKY BLINDERS : OPERATION BLUE VEIL | Medium | juillet 2026 | 25 |

---

## Énoncé

> "Une source interne nous a transmis une image d’un lieu suspect, affirmant que cet endroit concentre des investissements récents inhabituels.
>
> Votre première mission ? Identifier avec précision le site en question."

---

## Outils

| Outil | Rôle |
|:------|:-----|
| `Google` | Recherche d'informations |
| `Google maps` | Découverte du flag |

---

## Résolution

<details>
<summary>Voir la démarche complète</summary>

### [01] — Recherche inversée avec Google photos

Nous pouvons effectuer une recherche inversée sur la photo fournie.
Mais cette recherche ne donne pas vraiment de pistes, il existe beaucoup de photos d'une route avec une entrée et des buissons.

> **Résultat :** RAS

---

### [02] — Google maps

Nous pouvons nous concentrer sur les détails de la photo.
Nous remarquons que la voiture roule à gauche, nous sommes donc dans un pays anglo-saxon.
Les arbres donnent l'impression que la photo a été prise au Royaume-Uni, mais cela doit être vérifié.

En recherchant le nom écrit sur la route : B3400, nous en avons la confirmation.
Nous recherchons un établissement en rapport avec l'alcool ou une distillerie.
En regardant à quelques mètres à l'ouest sur la route, nous trouvons l'établissement recherché.

> **Résultat :** B***** S******* D*********

</details>

---

## Flag

```
LABOSINT{B***** S******* D*********}
```

---
