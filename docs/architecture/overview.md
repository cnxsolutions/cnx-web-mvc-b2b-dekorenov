# Architecture Technique – Plateforme Web Dekorenov.pro

## Vue d’ensemble
La plateforme Dekorenov.pro repose sur une architecture web hybride,
conçue pour répondre à des enjeux **SEO, performance, maintenabilité
et conversion B2B**.

Le projet combine :
- un **site web MVC sur mesure** pour un contrôle total de la logique métier
- un **back-office WordPress** pour l’administration des contenus
- une **boutique B2B** dédiée à la vente de marbre en gros pour professionnels

Cette architecture permet de séparer clairement :
- la logique applicative
- la gestion de contenu
- les enjeux commerciaux

---

## Architecture Globale

### Composants principaux
- Frontend Web MVC (HTML, CSS, JS)
- Backend applicatif MVC
- WordPress (administration des contenus)
- Base de données MySQL
- Module boutique B2B (catalogue & devis)
- Serveur web optimisé SEO

---

## Flux Fonctionnels

1. L’utilisateur accède au site public (services, catalogue, contenus)
2. Le frontend MVC affiche les pages optimisées SEO
3. Les contenus dynamiques sont administrés via WordPress
4. Les professionnels accèdent à l’espace B2B
5. Les demandes de devis et interactions commerciales sont centralisées

---

## Performance & Infrastructure

L’architecture a été pensée pour garantir de bonnes performances
et répondre aux exigences SEO :

- Optimisation du temps de réponse serveur (TTFB)
- Cache serveur et cache applicatif
- Chargement optimisé des ressources
- Architecture compatible Core Web Vitals

---

## Sécurité & Accès

- Accès administrateur WordPress sécurisé
- Séparation des rôles (admin / professionnel / public)
- Accès restreint à l’espace B2B
- Protection contre les accès non autorisés

---

## Justification des Choix Techniques

- **Architecture MVC** : clarté, maintenabilité, performance
- **WordPress en back-office** : autonomie du client
- **Solution hybride** : équilibre entre sur-mesure et pragmatisme
- **Base SEO-friendly** : structure propre et évolutive

---

## Évolutivité

L’architecture permet :
- Extension de la boutique B2B
- Connexion à un CRM ou ERP
- Ajout de nouvelles zones géographiques
- Montée en charge sans refonte complète
