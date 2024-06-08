# Tp_symfony
Objectif : Créer une application de gestion de portfolio permettant aux utilisateurs de gérer leurs projets  professionnels ou personnels.

Fonctionnalités :
1. Création de contrôleurs et routes :
o Créer un contrôleur ProjectController avec les routes nécessaires pour 
lister, ajouter, modifier et supprimer des projets.
o Créer un contrôleur UserController pour gérer les utilisateurs (afficher les 
détails et lister les utilisateurs).
2. Vues Twig :
o Créer des vues Twig pour afficher la liste des projets et les détails des 
utilisateurs.
o Créer des formulaires d’ajout et de modification pour les projets avec Twig.
3. ORM Doctrine :
o Créer les entités Project et User avec les relations appropriées (un utilisateur 
peut avoir plusieurs projets).
o Utiliser les repositories de Doctrine pour effectuer les opérations CRUD sur les 
projets et les utilisateurs.
4. Formulaires Symfony :
o Créer des formulaires Symfony pour ajouter et modifier des projets.
o Gérer la validation des formulaires et afficher les erreurs dans les vues Twig.
Détails supplémentaires à implémenter:  Un projet doit avoir un titre, une description, une date de début, une date de fin, un 
statut (en cours, terminé) et un utilisateur responsable.  Un utilisateur doit avoir un nom, un email et un mot de passe.  Implémenter une fonctionnalité de recherche par titre de projet et de filtrage par statut.
