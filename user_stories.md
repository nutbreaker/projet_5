# User Stories - Learn@Home

Ce document détaille les besoins fonctionnels sous forme de récits utilisateurs, accompagnés de leurs critères d'acceptation (GIVEN / WHEN / THEN).

---

## 1. Page de Connexion & Gestion de compte

| ID | User Story | Critères d'acceptation (GIVEN / WHEN / THEN) |
| :--- | :--- | :--- |
| **US1.1** | **En tant qu'** utilisateur, **je veux** me connecter **afin d'** accéder à mon espace sécurisé. | - **GIVEN** : Je suis sur la page de connexion.<br>- **WHEN** : Je saisis un e-mail valide, un mot de passe correct, et je valide.<br>- **THEN** : Je suis authentifié et redirigé vers le Tableau de bord. |
| **US1.2** | **En tant qu'** utilisateur, **je veux** réinitialiser mon mot de passe **afin de** retrouver mon accès en cas d'oubli. | - **GIVEN** : Je suis sur la page de connexion.<br>- **WHEN** : Je clique sur "Mot de passe oublié" et soumets mon adresse e-mail.<br>- **THEN** : Je reçois un e-mail contenant un lien de réinitialisation si le compte existe. |
| **US1.3** | **En tant que** visiteur, **je veux** créer un compte **afin de** rejoindre l'association. | - **GIVEN** : Je suis sur le formulaire d'inscription.<br>- **WHEN** : Je remplis les champs obligatoires et clique sur "S'inscrire".<br>- **THEN** : Mon compte est créé et une notification de succès s'affiche. |
| **US1.4** | **En tant qu'** utilisateur connecté, **je veux** me déconnecter **afin de** sécuriser l'accès à mon compte. | - **GIVEN** : Je suis connecté à mon compte sur l'application.<br>- **WHEN** : Je clique sur le bouton "Déconnexion".<br>- **THEN** : Ma session sécurisée est fermée et je suis immédiatement redirigé vers la page de connexion. |

---

## 2. Interface de Chat

| ID | User Story | Critères d'acceptation (GIVEN / WHEN / THEN) |
| :--- | :--- | :--- |
| **US2.1** | **En tant qu'** utilisateur, **je veux** envoyer un message instantané **afin de** discuter avec mon binôme. | - **GIVEN** : Je suis sur l'interface de chat dans une conversation active.<br>- **WHEN** : Je saisis un texte et appuie sur "Envoyer".<br>- **THEN** : Le message s'affiche dans l'historique avec mon avatar et l'horodatage. |
| **US2.2** | **En tant qu'** expéditeur, **je veux** voir un accusé de lecture **afin de** savoir si mon message a été lu. | - **GIVEN** : J'ai envoyé un message à mon contact.<br>- **WHEN** : Le contact ouvre la conversation sur son écran.<br>- **THEN** : L'indicateur sous mon message passe à l'état "Vu" (ex: double coche). |
| **US2.3** | **En tant qu'** utilisateur, **je veux** gérer mes contacts **afin de** garder mon carnet d'adresses à jour. | - **GIVEN** : Je consulte ma liste de contacts dans la barre latérale du chat.<br>- **WHEN** : Je clique sur l'icône "Supprimer" à côté d'un contact et confirme.<br>- **THEN** : Le contact disparaît de ma liste. |

---

## 3. Page Calendrier

| ID | User Story | Critères d'acceptation (GIVEN / WHEN / THEN) |
| :--- | :--- | :--- |
| **US3.1** | **En tant qu'** utilisateur, **je veux** visualiser mon planning **afin de** m'organiser pour mes séances. | - **GIVEN** : Je suis connecté sur l'application.<br>- **WHEN** : Je navigue vers la page "Calendrier".<br>- **THEN** : Le calendrier affiche les événements prévus sur le mois (ou la semaine). |
| **US3.2** | **En tant qu'** utilisateur, **je veux** programmer un rendez-vous **afin de** planifier une séance de soutien. | - **GIVEN** : Je suis sur la vue Calendrier.<br>- **WHEN** : Je clique sur un jour, remplis le formulaire d'événement et sauvegarde.<br>- **THEN** : L'événement apparaît sur mon calendrier et est synchronisé pour mon binôme. |

---

## 4. Gestionnaire de Tâches

| ID | User Story | Critères d'acceptation (GIVEN / WHEN / THEN) |
| :--- | :--- | :--- |
| **US4.1** | **En tant qu'** élève, **je veux** créer une tâche pour moi-même **afin de** lister mes devoirs. | - **GIVEN** : Je suis sur la page des tâches (connecté en Élève).<br>- **WHEN** : Je rédige l'intitulé de la tâche et valide.<br>- **THEN** : La tâche s'ajoute à ma liste, sans option d'assignation à un tiers. |
| **US4.2** | **En tant que** bénévole, **je veux** assigner une tâche à mon élève **afin de** le guider dans son travail. | - **GIVEN** : Je suis sur la fenêtre de création de tâche (connecté en Bénévole).<br>- **WHEN** : Je sélectionne le nom de mon élève dans le champ "Assigner à" et je valide.<br>- **THEN** : La tâche est envoyée dans la To-do list de l'élève. |
| **US4.3** | **En tant qu'** utilisateur, **je veux** cocher une tâche comme terminée **afin de** suivre ma progression. | - **GIVEN** : J'ai une liste de tâches actives devant moi.<br>- **WHEN** : Je clique sur la case à cocher (checkbox) d'une tâche.<br>- **THEN** : La tâche se barre visuellement et passe dans le statut "Terminée". |

---

## 5. Tableau de Bord (Dashboard)

| ID | User Story | Critères d'acceptation (GIVEN / WHEN / THEN) |
| :--- | :--- | :--- |
| **US5.1** | **En tant qu'** utilisateur, **je veux** voir un résumé de mes obligations **afin de** connaître mes priorités dès la connexion. | - **GIVEN** : Je viens de réussir mon authentification.<br>- **WHEN** : La page d'accueil (Dashboard) se charge.<br>- **THEN** : Je vois ma To-do list à jour et la liste de mes prochains rendez-vous. |
| **US5.2** | **En tant qu'** utilisateur, **je veux** être alerté des nouveaux messages **afin de** ne rater aucune communication. | - **GIVEN** : Je suis sur le Dashboard et un contact m'a écrit.<br>- **WHEN** : Je regarde la section "Chat" ou la barre de navigation.<br>- **THEN** : Un compteur rouge indique précisément le nombre de messages non lus. |