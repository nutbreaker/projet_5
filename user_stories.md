# User Stories - Learn@Home

Ce document détaille les besoins fonctionnels sous forme de récits utilisateurs, accompagnés de leurs critères d'acceptation (GIVEN / WHEN / THEN).

---

## 1. Page de Connexion & Gestion de compte

| ID | User Story | Critères d'acceptation |
| :--- | :--- | :--- |
| **US1.1** | **En tant qu'** utilisateur, **je souhaite** me connecter **afin d'** accéder à mes outils. | - **GIVEN** : Je saisis un email valide et le bon mot de passe.<br>- **WHEN** : Je clique sur "Connexion".<br>- **THEN** : Je suis redirigé vers le Dashboard. |
| **US1.2** | **En tant qu'** utilisateur, **je souhaite** réinitialiser mon mot de passe **afin de** ne pas perdre mon accès. | - **GIVEN** : Je clique sur "Mot de passe oublié".<br>- **WHEN** : Je renseigne mon email.<br>- **THEN** : Je reçois un lien de récupération. |
| **US1.3** | **En tant que** nouvel utilisateur, **je souhaite** m'inscrire **afin de** rejoindre la plateforme. | - **GIVEN** : Je remplis tous les champs obligatoires du formulaire.<br>- **WHEN** : Je valide l'inscription.<br>- **THEN** : Mon compte est créé. |
| **US1.4** | **En tant qu'** utilisateur connecté, **je souhaite** me déconnecter **afin de** sécuriser mon accès. | - **GIVEN** : Je suis sur n'importe quelle page.<br>- **WHEN** : Je clique sur "Déconnexion" dans le menu profil.<br>- **THEN** : Ma session est détruite et je reviens à la page de Login. |

---

## 2. Interface de Chat

| ID | User Story | Critères d'acceptation |
| :--- | :--- | :--- |
| **US2.1** | **En tant qu'** utilisateur, **je souhaite** envoyer un message **afin de** discuter avec mon binôme. | - **GIVEN** : Je saisis un texte dans la zone de saisie.<br>- **WHEN** : J'appuie sur "Entrée" ou le bouton "Envoyer".<br>- **THEN** : Le message apparaît instantanément avec l'heure et mon avatar. |
| **US2.2** | **En tant qu'** expéditeur, **je souhaite** voir si mon message a été lu **afin d'** être informé. | - **GIVEN** : Le destinataire a ouvert la discussion.<br>- **WHEN** : Le message passe de l'état envoyé à lu.<br>- **THEN** : Une icône visuelle (ex: double check) confirme la lecture. |
| **US2.3** | **En tant qu'** utilisateur, **je souhaite** gérer mes contacts **afin de** choisir mes interlocuteurs. | - **GIVEN** : Je suis dans l'annuaire.<br>- **WHEN** : Je clique sur "Ajouter" ou "Supprimer".<br>- **THEN** : Ma liste de contacts est mise à jour. |

---

## 3. Page Calendrier

| ID | User Story | Critères d'acceptation |
| :--- | :--- | :--- |
| **US3.1** | **En tant qu'** utilisateur, **je souhaite** voir mes cours prévus **afin de** m'organiser. | - **GIVEN** : Je suis sur la page Calendrier.<br>- **WHEN** : La page charge la vue actuelle.<br>- **THEN** : Mes cours sont affichés par créneau horaire. |
| **US3.2** | **En tant qu'** utilisateur, **je souhaite** programmer un cours **afin de** fixer un rendez-vous. | - **GIVEN** : Je sélectionne une date et une heure.<br>- **WHEN** : Je valide l'ajout de l'événement.<br>- **THEN** : Le cours apparaît dans mon calendrier et celui de mon binôme. |

---

## 4. Gestionnaire de Tâches

| ID | User Story | Critères d'acceptation |
| :--- | :--- | :--- |
| **US4.1** | **En tant qu'** élève, **je souhaite** créer une tâche **afin de** lister mes devoirs. | - **GIVEN** : Je saisis le libellé de la tâche.<br>- **WHEN** : Je valide l'ajout.<br>- **THEN** : La tâche apparaît dans ma To-do list. |
| **US4.2** | **En tant que** bénévole, **je souhaite** assigner une tâche à mon élève **afin de** l'aider. | - **GIVEN** : Je sélectionne mon élève.<br>- **WHEN** : Je crée la tâche pour lui.<br>- **THEN** : L'élève reçoit la tâche dans sa liste avec la mention du tuteur. |
| **US4.3** | **En tant qu'** utilisateur, **je souhaite** marquer une tâche comme faite **afin de** suivre mon progrès. | - **GIVEN** : Je coche la case d'une tâche.<br>- **WHEN** : La validation est effectuée.<br>- **THEN** : La tâche est barrée ou déplacée dans la liste "Terminée". |

---

## 5. Tableau de Bord

| ID | User Story | Critères d'acceptation |
| :--- | :--- | :--- |
| **US5.1** | **En tant qu'** utilisateur, **je souhaite** voir mes notifications **afin de** ne rien rater. | - **GIVEN** : J'ai reçu des messages ou tâches.<br>- **WHEN** : Je suis sur le Dashboard.<br>- **THEN** : Des badges de notification indiquent les nouveaux éléments. |
| **US5.2** | **En tant qu'** utilisateur, **je souhaite** un accès rapide aux outils **afin de** gagner du temps. | - **GIVEN** : Je clique sur un widget du Dashboard (ex: Calendrier).<br>- **WHEN** : L'action est déclenchée.<br>- **THEN** : Je suis redirigé directement vers le module complet correspondant. |
