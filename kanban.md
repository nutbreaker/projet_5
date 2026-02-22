# Kanban du Projet - Learn@Home (Finalisé)

Ce document présente l'organisation détaillée du projet, découpée en blocs de fonctionnalités, avec une traçabilité vers les User Stories (US).

---

## 1. ANALYZE (Cadrage & Conception) - DONE

| Tâche | Description | Page concernée | US Réf. |
| :--- | :--- | :--- | :--- |
| Veille marché | Identification de 5 concurrents et tendances. | N/A | N/A |
| Cas d'usage | Diagrammes d'interaction Élève/Bénévole. | Toutes | US1.1 - US5.2 |
| User Stories | Rédaction GIVEN/WHEN/THEN. | Toutes | US1.1 - US5.2 |
| Maquettes | Structure Desktop & Mobile. | Toutes | N/A |

---

## 2. DÉVELOPPEMENT (Backlog / To Do)

### A. Bloc Authentification

- [ ] **B-01 : Base de données** | Création schéma (Users, Sessions). | Connexion | US1.1, US1.3, US1.4 |
- [ ] **B-02 : Login UI** | Intégration Desktop/Mobile du formulaire. | Connexion | US1.1 |
- [ ] **B-03 : Recovery** | Système de reset mot de passe. | Connexion | US1.2 |
- [ ] **B-04 : Logout** | Implémentation de la déconnexion. | Toutes | US1.4 |

### B. Bloc Communication

- [ ] **C-01 : Socket Setup** | Mise en place chat temps réel. | Chat | US2.1 |
- [ ] **C-02 : Contacts** | Ajouter/Supprimer des binômes. | Chat | US2.3 |
- [ ] **C-03 : UI Chat** | Fenêtre de discussion et historique. | Chat | US2.1, US2.4 |
- [ ] **C-04 : Statuts** | Indicateur de lecture "vu". | Chat | US2.2 |

### C. Bloc Organisation

- [ ] **O-01 : Calendar Engine** | Gestion des créneaux et RDV. | Calendrier | US3.1, US3.2 |
- [ ] **O-02 : To-do List** | Système de tâches avec attribution. | Tâches | US4.1, US4.2 |
- [ ] **O-03 : Permissions** | Restriction élève sur attribution tâches. | Tâches | US4.2 |

### D. Bloc Synthèse

- [ ] **D-01 : Global UI** | Layout Dashboard et Sidebar. | Dashboard | US5.1, US5.2 |
- [ ] **D-02 : Widgets** | Intégration compteurs et raccourcis. | Dashboard | US5.1, US5.2 |

__Légende des préfixes__

Pour faciliter la lecture, chaque tâche utilise un préfixe correspondant à son bloc fonctionnel :

- **B-** : Bloc Authentification (Base/Backend)
- **C-** : Bloc Communication (Chat/Contacts)
- **O-** : Bloc Organisation (Outils/Calendrier/Tâches)
- **D-** : Bloc Synthèse (Dashboard/Design global)

---

## 3. Priorisation (Roadmap)

1.  **Sprint 1 (Fondations) :** Authentification et Dashboard (Widgets vides).
2.  **Sprint 2 (Social) :** Chat complet et gestion des contacts.
3.  **Sprint 3 (Outils) :** Calendrier et Gestionnaire de tâches.
4.  **Sprint 4 (Polissage) :** Responsive final et tests d'accessibilité.

---

## Liens Utiles

- **User Stories :** `user_stories.md`
- **Maquettes :** `maquettes_structure.md`