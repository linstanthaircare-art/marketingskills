# Audit Complet du Site — L'Instant Haircare
## Optimisations prioritaires par page et par levier

> Basé sur l'analyse du site linstanthaircare.com, du contenu indexé, et du contexte produit `.agents/product-marketing.md`.
> **Note :** Le site retourne une erreur 403 aux crawlers automatiques — voir point SEO technique ci-dessous.

---

## Score global estimé

| Dimension | Score | Priorité |
|-----------|-------|----------|
| CRO / Conversion | 5/10 | 🔴 Critique |
| SEO technique | 4/10 | 🔴 Critique |
| Contenu & messaging | 7/10 | 🟡 Moyen |
| UX & navigation | 6/10 | 🟡 Moyen |
| Preuve sociale | 6/10 | 🟡 Moyen |
| Email capture | 4/10 | 🔴 Critique |
| Vitesse & mobile | Inconnu | ⚪ À mesurer |

---

## 🔴 PROBLÈME CRITIQUE — Le site bloque les crawlers (403)

**Constat :** Le site retourne une erreur HTTP 403 à tous les robots d'exploration (Googlebot inclus potentiellement, selon la configuration). Cela a été confirmé lors de l'analyse.

**Impact :**
- Si Googlebot est bloqué → zéro indexation → zéro trafic organique
- Si seuls les crawlers tiers sont bloqués → pas de problème SEO, mais vérifier via Google Search Console

**Action immédiate :**
1. Ouvrir Google Search Console → "Inspection d'URL" → tester les URL clés
2. Vérifier le fichier `robots.txt` : `linstanthaircare.com/robots.txt`
3. Si Cloudflare est activé : désactiver le "Bot Fight Mode" ou créer une règle d'exception pour Googlebot
4. Vérifier dans Shopify : Apps → éventuellement une app de protection qui bloque les crawlers

---

## Page d'accueil (Homepage)

### Ce qui existe (contenu identifié)

**Texte hero trouvé :**
> *"un cuir chevelu apaisé par un booster d'hydratation sous forme de gel fluide, texture légère qui glisse entre les doigts et distribue l'hydratation sur toute la fibre, avec l'énergie de l'améthyste qui équilibre, l'extrait de melon qui nourrit et éveille, la kératine végétale qui soutient et protège"*

**Sections identifiées :**
- Présentation sensorielle du produit (poétique)
- Définition "cheveux texturés"
- Définition "locks / dreadlocks"
- Définition "cuir chevelu"
- Section "beauté holistique"
- Feed Instagram (sur la page À propos)

---

### Problèmes identifiés & corrections

#### Problème 1 — Hero trop sensoriel, pas assez orienté conversion

**Actuel :** Texte immersif et poétique sur l'expérience produit. Beau, mais pas convertissant.

**Pourquoi c'est un problème :** Une visiteuse qui arrive pour la première fois ne sait pas encore ce que c'est, pour qui c'est, et combien ça coûte. Elle repart avant d'avoir trouvé ces réponses.

**Règle des 5 secondes :** En 5 secondes, la visiteuse doit pouvoir répondre à :
- Qu'est-ce que c'est ? ✗ (trop flou)
- Pour moi ? ✗ (types de cheveux non mentionnés d'emblée)
- Combien ? ✗ (prix absent)
- Fiable ? ✗ (pas de proof visible)

**Correction — Structure hero recommandée :**

```
[Image : cheveux texturés/locksés hydratés, résultat visible]

Ta nouvelle normalité commence ici.

UPCYCURL — Sérum cuir chevelu sans rinçage
Pour cheveux bouclés, frisés, crépus & locksés

⭐⭐⭐⭐⭐  [X avis]  |  96/100 Yuka  |  Fabriqué en France

[ Découvrir UPCYCURL — 18€ → ]
```

Le texte sensoriel actuel peut rester **plus bas dans la page**, après que la visiteuse ait compris ce qu'elle regarde.

---

#### Problème 2 — Sections éducatives non reliées au produit

**Actuel :** Les définitions (cheveux texturés, locks, cuir chevelu) sont présentées comme du contenu informatif isolé.

**Opportunité :** Chaque section éducative doit se terminer par un pont vers UPCYCURL.

**Exemple de correction :**

```
Le cuir chevelu des cheveux texturés a des besoins spécifiques en hydratation
et équilibre du sebum que la plupart des produits ignorent.

→ C'est exactement pour ça qu'UPCYCURL a été formulé par une chimiste R&D.
   [En savoir plus]
```

---

#### Problème 3 — Capture email absente ou insuffisante

**Constat probable :** Pas de popup ou de section de capture email visible au premier plan.

**Coût :** Chaque visiteuse qui repart sans laisser son email est perdue. Pour une marque DTC au stade actuel, c'est la fuite la plus coûteuse.

**Solution — 3 points de capture à ajouter :**

1. **Popup de sortie** (exit-intent) :
   ```
   Avant de partir —
   Reçois l'e-book "Cuir chevelu apaisé en 15 min/jour" gratuitement.
   [Mon email]  [Je veux mon e-book →]
   ```

2. **Section intégrée homepage** (milieu de page) :
   ```
   Tu veux une routine cuir chevelu qui marche ?
   Reçois l'e-book gratuit + nos conseils capillaires.
   [Email]  [Envoyer →]
   ```

3. **Footer** : champ email discret, toujours présent

**Objectif :** Capturer 3–5% des visiteurs en email → nourrir avec la séquence de bienvenue → convertir.

---

#### Problème 4 — Preuve sociale absente sur la homepage

**Constat :** Les avis clients ne semblent pas mis en avant sur la page d'accueil.

**Correction — Ajouter un bloc "Ce qu'elles en disent" :**

Afficher 3 avis en rotation ou en colonnes, avec le plus fort en premier :

> *"Je l'utilise depuis deux mois et ma vie a changé."* — Rana, locksée ⭐⭐⭐⭐⭐

> *"Pas de résidus blancs, pas de fini gras. Je revis."* — Rana, locksée ⭐⭐⭐⭐⭐

> *"Même partie en tour du monde avec."* — Noellie, Google ⭐⭐⭐⭐⭐

---

## Page Produit UPCYCURL

*(Voir l'audit détaillé dans `.agents/cro-page-produit.md`)*

**Résumé des 5 priorités :**
1. Badges Yuka + INCI visibles sans scroller
2. Types de cheveux ciblés dans le titre
3. Bundle 22€ proposé comme "recommandé"
4. Avis Rana en premier (le plus émotionnel)
5. FAQ objections rédigée (résidus, type de cheveux, famille)

---

## Page À propos

### Ce qui existe

- Histoire de la fondatrice Amandine RAFFIN, chimiste R&D
- Feed Instagram intégré
- Mission et valeurs de la marque

### Problèmes & Corrections

#### Problème 1 — La fondatrice est un actif sous-exploité

Amandine est chimiste R&D cosmétique — c'est une crédibilité rare dans la cosmétique capillaire indépendante. La page À propos doit transformer cette expertise en confiance.

**Structure recommandée pour la page À propos :**

```
1. Photo d'Amandine (authentique, pas corporate)
2. "Pourquoi j'ai créé L'Instant Haircare" — 150 mots, première personne,
   ton personnel. Inclure : le problème qu'elle a vécu ou observé,
   la décision de créer, la promesse.
3. Son expertise : "Chimiste spécialisée en R&D cosmétique —
   voilà ce que ça change dans une formule"
4. Les valeurs : sur-recyclage, holisme, science, respect culturel
5. CTA : "Découvrir UPCYCURL" ou "Lire notre histoire sur Instagram"
```

#### Problème 2 — Feed Instagram = abandon de la page

Intégrer un feed Instagram sur la page À propos fait cliquer les visiteuses vers Instagram — et elles ne reviennent pas.

**Alternative :** Remplacer par une sélection de 3 posts clés présentés en images statiques avec légendes, sans lien sortant. Mettre le lien Instagram uniquement dans le footer.

---

## Page Boutique / Collection

### Problèmes probables

#### Problème 1 — Peu de produits = risque de "vitrine vide"

Avec 3–4 références (UPCYCURL, applicateur, bundle, e-book gratuit), la page boutique risque de sembler limitée.

**Solutions :**
- Mettre le bundle en position 1 (plus haute valeur perçue)
- Ajouter des badges visuels sur chaque produit : "Bestseller", "⭐ 96/100 Yuka", "Kit complet"
- Montrer clairement le prix avant et après bundle pour faire ressentir l'économie

#### Problème 2 — L'e-book gratuit mélangé aux produits payants

Si l'e-book gratuit apparaît dans la boutique, il crée de la confusion (boutique = on achète).

**Solution :** L'e-book doit être un lead magnet sur la homepage et en popup — pas un article de boutique. Le sortir de la liste produits ou le placer clairement à part avec le label "Gratuit — s'inscrire".

---

## SEO — Audit & Recommandations

### Problèmes techniques

| Problème | Impact | Correction |
|----------|--------|------------|
| 403 sur les crawlers | 🔴 Bloque l'indexation | Vérifier Search Console + robots.txt |
| Pas de blog visible | 🔴 Zéro trafic organique informationnel | Créer un blog Shopify |
| Titres de page inconnus | 🟡 Potentiel SEO non exploité | Optimiser les balises `<title>` |
| Pas de schema markup produit | 🟡 Absence de rich snippets | Ajouter schema Product + Review |

### Requêtes cibles à capturer (trafic organique)

| Requête | Volume estimé | Page cible |
|---------|---------------|------------|
| "soin cuir chevelu cheveux crépus" | Moyen | Page produit ou article |
| "hydratation cheveux locksés" | Moyen | Article blog |
| "gel capillaire naturel france" | Moyen | Page produit |
| "produit capillaire 96 yuka" | Faible | Article ou page produit |
| "routine cuir chevelu sans rinçage" | Moyen | Article blog |
| "soin post grossesse cheveux" | Faible-Moyen | Article blog |

### Structure de blog recommandée

Créer un blog Shopify avec 2 articles/mois :

**Articles prioritaires :**
1. *"Cuir chevelu texturé : pourquoi il a besoin d'un soin différent"*
   → Cible "soin cuir chevelu cheveux texturés/crépus", CTA vers UPCYCURL
2. *"18/20 sur INCI Beauty : voici exactement ce qu'il y a dans UPCYCURL"*
   → Cible les chercheuses de transparence, construit la confiance
3. *"Ma routine wash day en 15 minutes avec UPCYCURL"*
   → Cible "routine wash day", contenu evergreen
4. *"Prendre soin de ses locks : ce que personne ne vous dit sur le cuir chevelu"*
   → Cible "soin locks", niche peu servie en France

### Balises title & meta description recommandées

**Homepage :**
- Title : `UPCYCURL — Sérum cuir chevelu naturel pour cheveux texturés | L'Instant Haircare`
- Meta : `Soin hydratant sans rinçage pour cheveux bouclés, frisés, crépus et locksés. 96/100 Yuka · Fabriqué en France · Sur-recyclage français.`

**Page produit UPCYCURL :**
- Title : `UPCYCURL — Sérum hydratant cuir chevelu | 96/100 Yuka | L'Instant Haircare`
- Meta : `Gel fluide sans rinçage pour cuir chevelu texturé et locksé. 96% naturel, fabriqué en France. Dès 18€. Avis clients : ⭐⭐⭐⭐⭐`

---

## Navigation & UX

### Problèmes probables & Corrections

#### Menu principal — Structure recommandée

```
[Logo]    Boutique    Notre histoire    Blog    [Panier]
```

Pas plus de 4 éléments dans le menu principal. Le bouton "Boutique" doit être le premier lien — c'est là que l'argent se fait.

#### Footer — Ce qu'il doit contenir

```
Colonne 1 : Navigation
- Boutique
- À propos
- Blog
- Contact / FAQ

Colonne 2 : Confiance
- 96/100 Yuka
- Fabriqué en France
- Sur-recyclage français
- Convient dès 5 ans

Colonne 3 : Communauté
- [Instagram] [TikTok] [YouTube]
- Inscription newsletter (champ email)

Colonne 4 : Légal
- CGV · Politique de confidentialité · Mentions légales
```

---

## Checklist de mise en œuvre — Priorités absolues

### Semaine 1 — Actions critiques (impact immédiat)

- [ ] Vérifier l'indexation Google via Search Console — corriger le 403 si Googlebot est bloqué
- [ ] Ajouter les badges Yuka (96/100) et INCI (18/20) visibles sans scroller sur la page produit
- [ ] Ajouter un popup exit-intent avec l'e-book comme lead magnet
- [ ] Revoir le texte hero de la homepage : clarifier ce que c'est + pour qui + prix

### Semaine 2 — Conversion

- [ ] Restructurer la page produit selon le spec dans `cro-page-produit.md`
- [ ] Mettre le bundle en "recommandé" avec économie visible
- [ ] Ajouter un bloc avis clients sur la homepage (Rana en premier)
- [ ] Ajouter une FAQ sur la page produit (5 objections rédigées)

### Semaine 3–4 — SEO & Contenu

- [ ] Créer le blog Shopify
- [ ] Publier le premier article cible (cuir chevelu texturé)
- [ ] Optimiser les balises title et meta description de toutes les pages
- [ ] Ajouter le schema markup Product + Review sur la page UPCYCURL

### Mois 2 — Fidélisation & croissance

- [ ] Mettre en place la séquence email post-achat (voir stratégie marketing)
- [ ] Restructurer la page À propos (histoire fondatrice + CTA)
- [ ] Supprimer le feed Instagram de la page À propos
- [ ] Ajouter un champ email dans le footer

---

## Résumé — Gains attendus par action

| Action | Effort | Impact estimé |
|--------|--------|---------------|
| Corriger le 403 Googlebot | Faible | 🔴 Critique — indexation SEO |
| Badges Yuka sur page produit | Faible | +15–25% taux de conversion |
| Popup exit-intent e-book | Faible | +3–5% capture email |
| Hero homepage restructuré | Moyen | +10–20% taux de clic vers boutique |
| Bundle "recommandé" | Faible | +20–30% panier moyen |
| FAQ objections page produit | Faible | -30% taux d'abandon |
| Blog SEO (2 articles/mois) | Moyen | +trafic organique dès mois 3–6 |
| Page À propos restructurée | Moyen | +confiance, -bounce rate |

---

_Audit réalisé le 2026-05-16 — Sources : contenu indexé linstanthaircare.com, analyses Search Engine, best practices DTC cosmétique._
