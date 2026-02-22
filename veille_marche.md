# Veille Marché - Learn@Home

## Introduction

Cette veille identifie 5 acteurs du marché du soutien scolaire et de la mise en relation éducative afin d'en dégager les tendances et les meilleures pratiques pour le projet Learn@Home.

---

## 1. Acadomia

**Type :** Leader du soutien scolaire privé.

- **Fonctionnalités clés :** Suivi personnalisé, interface parent/élève, tableau de bord de progression.
- **Interface :** Très institutionnelle, couleurs rassurantes (bleu/blanc), navigation claire.
- **Point fort :** La rigueur du suivi et la clarté des bilans.

## 2. Kartable

**Type :** Plateforme de ressources pédagogiques en ligne.

- **Fonctionnalités clés :** Cours complets, exercices interactifs, gestionnaire de planning.
- **Interface :** Moderne, épurée, responsive design exemplaire, usage intensif d'icônes.
- **Point fort :** L'accessibilité mobile et l'aspect ludique de l'apprentissage.

## 3. Maxicours

**Type :** Soutien scolaire 100% en ligne.

- **Fonctionnalités clés :** Vidéos de cours, tutorat par chat en fin de journée.
- **Interface :** Colorée, adaptée aux enfants, tableaux de bord de gamification.
- **Point fort :** Le chat avec des enseignants en direct, similaire au besoin de Learn@Home.

## 4. MySherpa

**Type :** Mise en relation tuteur/élève.

- **Fonctionnalités clés :** Recherche par critères (matière, lieu), messagerie interne, calendrier partagé.
- **Interface :** Simple, centrée sur la relation humaine, photos des tuteurs mises en avant.
- **Point fort :** Facilité de mise en relation et transparence sur le profil des bénévoles/tuteurs.

## 5. Apprentus

**Type :** Marketplace de mise en relation pour cours particuliers.

- **Fonctionnalités clés :** Moteur de recherche multicritères, système de messagerie sécurisée pour organiser les cours, calendrier de disponibilités des tuteurs.
- **Interface :** Style "Plateforme de services" (similaire à Airbnb). Très efficace pour la prise de contact rapide.
- **Point fort :** La gestion simplifiée de la prise de rendez-vous via le calendrier partagé.

---

## Synthèse pour Learn@Home

### Tendances de l'interface

- **Simplicité :** Les interfaces sont épurées pour ne pas distraire l'élève.
- **Identité visuelle :** Couleurs vives mais professionnelles. Pour Learn@Home, le rouge du logo devra être utilisé par touches (boutons d'action, indicateurs) sur un fond blanc/gris clair pour rester lisible.
- **Accessibilité :** Priorité au mobile (responsive design) car beaucoup d'élèves utilisent leur smartphone ou tablette.

### Fonctionnalités recommandées

- **Gamification légère :** Un compteur de tâches terminées ou de rendez-vous honorés pour motiver l'élève.
- **Indicateurs de présence :** Savoir quand le tuteur est en ligne dans le chat.
- **Centralisation :** Un tableau de bord qui résume tout au premier coup d'oeil.

---

## Recommandations Techniques

Suite à l'analyse des besoins (chat temps réel, gestion d'utilisateurs, base de données simple), la stack technique suivante est recommandée pour un développement rapide et efficace :

- **Frontend :** Un framework simple et minimaliste tel que **Alpine.js** pour une interface réactive et responsive.
- **Backend & Database : PocketBase**.
  - **Pourquoi PocketBase ?**
    - Centralise l'authentification, la base de données et le stockage de fichiers.
    - Support natif du temps réel via SSE, idéal pour la fonctionnalité de **Chat**.
    - Facilité de déploiement (un seul fichier exécutable).
    - Interface d'administration intuitive pour que l'association puisse gérer les utilisateurs si besoin.
- **Design :** **Figma** pour le prototypage des maquettes avant intégration.
