### ExercireOopTs

> Le but de l'exercice est de créer un filtre permettant d'afficher des véhicules par leur
> type dans une page web, de pouvoir en ajouter, modifier et supprimer. Lors du premier chargemen de la page, tous les datas devront être affichées sans disinctions
> de types. Les trois types à afficher sont:
> * Voiture
> * Moto
> * Bateau 

> Ces types devront partager un même parent et serons des classes distinctes. Les propriétés de ces classes doivent être différentes. La classe permettant de
> recuperer les datas à afficher n'est pas parent de ces derniers
> et devra disposer d'une methode permettant de recuperer chaque data, une methode pour récupérer par type les datas, une methode permettant d'ajouter un 
> vehicules par son type et une permettant d'en supprimer un.

## Contraintes:
- [x] Toutes les propriétées de classe devront être en privées, sauf pour les classes parents pour lesquelles on aura des propriétés protégées.
- [x] Il est interdit d'utiliser les constructeurs.
- [x] Seul les mutateurs et accesseurs sont autorisés. 
- [x] Il est strictement interdit de creer des fonction en dehors des classes.
- [x] Il est interdit de répéter du code (DRY).
- [X] Toutes vos classes devront être specialisées (chaque methode devra être en lien avec la classe qui l'implemente).
- [x] Touts les methodes de classe par laquelle on affiche les données devront préalablement être définit par une interface.
- [x] La classe mère des type de Vehicule ne devra jamais être instantiable. 
- [x] Une propriété devra être partagé par les Type de vehicule et devra être definit à l'instantiation de ceux-ci. Cette proriété est Moteur et reprente une     instance de classe classe  

