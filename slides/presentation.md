---
marp: true
theme: default
---

# Projet 5

[![bg contain right:45%](./learn@home_logo.png)](https://github.com/nutbreaker/projet_5)

## Learn@Home

### _OpenClassrooms_

_Par André M._

---

## Veille Marché & Stratégie

Analyse de 5 acteurs clés (Acadomia, Kartable, etc.) pour définir notre positionnement.

- **Tendances UI/UX** : Simplicité, interfaces épurées, approche "Mobile-First".
- **Stack Technique retenue** :
  - **PocketBase** : Backend "all-in-one" (Auth, DB, Temps réel via SSE).
  - **Alpine.js** : Frontend réactif et léger.
  - **Hébergement** : VPS OVHcloud pour le rapport performance/prix.
- **Objectif** : Fluidifier les échanges asynchrones entre bénévoles et élèves.

---

## Design & Prototypage (Figma)

L'utilisation de **Figma** a été centrale dans la conception du MVP.

- **Bénéfices** :
  - Itération rapide sur l'expérience utilisateur (UX) sans coder.
  - Validation visuelle de l'accessibilité et du contraste.
  - Export facilité des assets (icônes, couleurs) pour l'intégration.
- **Lien Prototype** : [Consulter les maquettes](https://www.figma.com/design/rzfaz8OFn4R0JooQFZDOHL/Learn-Home)

---

## Diagrammes de Cas d'Usage

Le système s'articule autour de deux acteurs (Élève / Bénévole) et 5 modules clés :

1. **Connexion** : Authentification et gestion de compte sécurisée.
2. **Chat** : Communication instantanée et gestion des contacts.
3. **Calendrier** : Planification de séances de soutien scolaire.
4. **Tâches** : To-do list (Auto-gestion pour l'élève / Assignation pour le bénévole).
5. **Dashboard** : Vue agrégée des priorités et notifications.

---

## User Stories (Besoins fonctionnels)

Résumé des engagements clés par module :

- **Accès** : Inscription, connexion sécurisée et réinitialisation de mot de passe.
- **Communication** : Envoi de messages, historique et accusés de lecture ("Vu").
- **Organisation** : Création d'événements synchronisés sur les deux agendas.
- **Accompagnement** : Le bénévole peut créer des devoirs directement dans la liste de l'élève.
- **Pilotage** : Centralisation des messages non lus et des échéances proches sur l'accueil.

---

## Organisation du Projet (Kanban)

Développement découpé en **4 Sprints** (Mars - Avril 2026) :

- **Sprint 1 : Sécurité & Accès** (Auth, Login, Signup).
- **Sprint 2 : Tâches & Dashboard** (Cœur de la gestion de travail).
- **Sprint 3 : Communication & Calendrier** (Temps réel et planification).
- **Sprint 4 : Finitions & Notifications** (UX, Accusés de lecture, Mot de passe oublié).

**Outils** : GitHub Projects pour le suivi des issues et Milestones.

---

## Conclusion

Le projet **Learn@Home** est prêt à passer à l'étape de réalisation.
