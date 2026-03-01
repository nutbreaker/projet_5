# Veille Marché - Learn@Home

## Introduction

Cette veille identifie 5 acteurs du marché du soutien scolaire et de la mise en relation éducative afin d'en dégager les tendances et les meilleures pratiques pour le projet Learn@Home.

---

| Acteur                                       | Positionnement                   | Fonctionnalités principales                               | Tendances de design                                        |
|----------------------------------------------|----------------------------------|-----------------------------------------------------------|------------------------------------------------------------|
| [**Acadomia**](https://www.acadomia.fr/)     | Leader du soutien scolaire       | Cours particuliers à domicile, soutien personnalisé       | Interface claire, accès rapide aux réservations            |
| [**Kartable**](https://www.kartable.fr/)     | Support scolaire en ligne        | Cours virtuels, exercices interactifs, revisons en ligne  | Interface épurée, design mobile-friendly                   |
| [**Maxicours**](https://www.maxicours.com/)  | Ressources éducatives en ligne   | Cours en vidéo, exercices, plateformes collaboratives     | Design interactif et engageant, contenu multimédia         |
| [**MySherpa**](https://www.mysherpa.be)      | Plateforme de mise en relation   | Cours particuliers en ligne, évaluation des élèves        | Design démodé mais fonctionnel                             |
| [**Apprentus**](https://www.apprentus.ch/)   | Cours particuliers variés        | Cours à domicile ou en ligne dans plusieurs matières      | Interface simple, options de filtrage par matière et tarif |

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
