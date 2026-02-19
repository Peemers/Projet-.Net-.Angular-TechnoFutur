Projet-.Net-.Angular-TechnoFutur
Le projet de "fin d'étude" pour TechnoFutur. Un site destiné aux assoss. En tout cas celle dont je fais partie.

"ASBL CONNECT'"
Projet : Site pour l'ASBL Covaldys

Le site actuel est un WordPress pas très "friendly" à utiliser. Les gens qui s'occupent de poster sur le site sont, en plus, très nuls en informatique et c'est galère pour eux.
Front-End

    Design : Épuré et modulable (black-theme, daltonien, grande police si désiré).

    Affichage : Les actualités et les projets se font automatiquement avec le calendrier ou après les posts de la personne en charge des événements.

    Accessibilité : Clairement lisible avec, encore une fois, des options d'accessibilité (switch contraste élevé, gros texte, daltonisme).

    Fonctionnalités : * Éventuellement intégrer un système de don déjà existant (mais je n'y connais rien là, pour le coup).

        Je pourrais faire un bouton qui imprime l'attestation fiscale ?

Partie Admin / Utilisateur / Auteur

Un véritable outil de gestion d'asso, pas juste le site front :

    Tableau de bord : Le plus simplifié possible.

    Interface : Des champs simples, une façon de poster simple (à réfléchir), un gestionnaire de média (glisser-déposer, etc.).

    Gestion des membres : Savoir qui est inscrit et qui a payé.

    Calendrier d'événements : * Gestion en DB des places disponibles et système d'inscription.

        Modifiable par les admins : si quelqu'un s'inscrit par téléphone, l'admin pourra facilement consommer une place disponible dans la DB.

		Imprimer des tracts normalisés ou non avec les "valeurs" des evenements ?

Publication d'articles ou d'événements

Utilisation de grosses cartes cliquables :

    "Publier une nouvelle" -> champs simples, drop de photos.

    "Qui est inscrit ?" -> combien de places reste-t-il sur l'événement ?

    "Envoyer un mail aux membres" -> champs simples et envoi à tous les membres automatiquement.

Back-End (.NET)

Relations et Tables :

    Users

    Roles ?

    Articles

    Événements

    Inscriptions / Adhésions

    Documents

    Donations ???

    Settings ??? (pour facilement changer des champs relatifs à l'asso : tel, réseaux sociaux, mail et compagnie).
	
	
------------------------------------------------------------------------------------------
Acteurs ??

-Admin
-auteur/rédacteur
-visiteurs
-membres
-développeur ahah ?



Une ou deux users stories

En tant qu'admin, je veux cliquer sur une grosse carte 'Publier une nouvelle' pour accéder directement à un formulaire simplifié sans menus compliqués

En tant qu'admin, je veux pouvoir inscrire manuellement quelqu'un qui m'a appelé par téléphone afin de mettre à jour instantanément le nombre de places restantes en base de données

En tant que rédacteur, je veux glisser-déposer une photo directement dans mon article pour ne pas avoir à gérer un dossier de médias complexe

En tant que membre, je veux m'inscrire à un événement en ligne et recevoir une confirmation automatique si des places sont encore disponibles

Maintenant je vais tenter de faire un peu d'uml 😂😂

