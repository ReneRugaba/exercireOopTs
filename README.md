### ExercireOopTs

> Le but de l'exercice est de créer un filtre, l'aide d'un select, permettant d'afficher des véhicules par leur
> type dans une page web, de pouvoir en ajouter, modifier et supprimer. Lors du premier chargement de la page, tous les datas devront être affichées sans distinction
> de types. Les trois types à afficher sont:
> * Voiture
> * Moto
> * Bateau 

> Ces types devront partager un même parent et seront des classes distinctes. Les propriétés de ces classes doivent être différentes. La classe permettant de
> récupérer les datas à afficher n'est pas parent de ces derniers
> et devra disposer d'une methode permettant de recuperer chaque data, une méthode pour récupérer par type les datas, une méthode permettant d'ajouter un 
> véhicules par son type et une permettant d'en supprimer un.

## Contraintes:
- [x] Trouver le moyen de sécuriser les valeurs du select lors du choix du type (on ne fait jamais confiance à un utilisateur).
- [x] Toutes les propriétés de classe devront être en privées, sauf pour les classes parentes pour lesquelles on aura des propriétés protégées.
- [x] Il est interdit d'utiliser les constructeurs.
- [x] Seuls les mutateurs et accesseurs sont autorisés. 
- [x] Il est strictement interdit de créer des fonctions en dehors des classes.
- [x] Il est interdit de répéter du code (DRY).
- [X] Toutes vos classes devront être specialisées (chaque methode devra être en lien avec la classe qui l'implemente).
- [x] Toutes les méthodes, de la classe par laquelle on affiche les datas, devront préalablement être défini par une interface.
- [x] La classe mère des types de Véhicule ne devra jamais être instanciable. 
- [x] Une propriété devra être partagée par les Types de véhicule et devra être définit à l'instanciation de ceux-ci. Cette propriété est **Moteur** et représente une     instance de cette classe.



_Cet exercice doit être fait en **TS** bien-sûr et pas de tests car le but ici est de monter en compétence sur 
la **Programmation Orientée Objet**_ :heavy_exclamation_mark::heavy_exclamation_mark:

