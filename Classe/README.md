Fait par Hassanatou Diallo && Fulbert Sossa.

# Gestion_Location_Residence
Projet BMO sur la modélisation UML d'une application web de gestion de la location de résidences à courte durée.

 Diagramme de Classes

Objectif :

Le diagramme de classes modélise la structure du système et les relations entre ses entités.

 Nous avons Choisi :

La Conservation de Tarif comme classe : permet une gestion flexible des prix selon la saison.

Nous avons aussi désigné Indisponibilité comme un attribut sous forme de tableau, simplifiant la gestion des périodes bloquées.

Relations principales :

Un Gestionnaire gère plusieurs Résidences.

Une Résidence regroupe plusieurs Éléments (chambres, studios, etc.).

Une Réservation concerne un ou plusieurs Éléments et peut inclure des Options.

Contraintes métiers intégrées :

Respect des durées minimales de séjour.

Disponibilités saisonnières des éléments.

NB: Nous avons des associations qui ne sont pas visibles sur la capture d'écran mais qui existent bel et bien. Cela étant dû au fait qu'on ai importé le fichier depuis les ordinateurs de l'université et donc nous n'avons pas pu les faire réapparaite d'ailleurs c'est pour la même raison q'il n'y aura peut-être pas de screenshot du diagrammes des cas d'utilisation.