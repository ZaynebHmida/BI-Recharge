
                                                    A power BI Dashboard for subscriptions





Le Dashboard actuel contient 4 pages :

La première page :
La première page s'occupe des abonnements par mois. J’ai créé une colonne (Active subscription) qui est égale à 1 si seulement les trois champs (status, nb abonnements active et méthode de payement) sont réglés (status= active & nb abonnements active=1 & méthode de payement= valide) pour s'assurer à 100% que chaque abonnement est actif. D’après le mois d’abonnement de chaque cliente, il dégage la moyenne des mois d’abonnement pour la totalité.

![1](https://user-images.githubusercontent.com/47888237/107131708-256ca080-68d9-11eb-9cd3-f6465db71b93.PNG)

 
Donc, on dispose aujourd'hui de 52 abonnements actifs. 
Dans la deuxième partie de la page1, on a deux graphiques en cascades.
La première représente les abonnements toujours actifs par mois et la deuxième représente celles en mois actuel (mai) pour le moment.


![2](https://user-images.githubusercontent.com/47888237/107131709-26053700-68d9-11eb-8b2f-e0f7aca7d3f7.PNG)

 
Dans la troisième partie, on s’occupe des désabonnements. Aussi, il existe deux graphiques en cascades. La première illustre les désabonnements par mois et la deuxième s’occupe de celles du mois actuel.
 

![3](https://user-images.githubusercontent.com/47888237/107131710-269dcd80-68d9-11eb-9e2e-b7b554540098.PNG)


La deuxième page :
On va s'occuper de ces abonnements qui sont à 100% valides (filtre pour les abonnements dont "Active abonnement=1").
Un autre filtre est exercé ici pour laisser seulement les produits de type sérum pour calculer le nb flacons réalisés.
J'ai mis un petit tableau selon la taille du flacon : flacons de 12 ml, de 30ml et le dernier est de 60 ml. Suite à ce petit tab, j’ai mis un histogramme empilé qui permet de visualiser les flacons récurrents par mois.



![4](https://user-images.githubusercontent.com/47888237/107131699-1f76bf80-68d9-11eb-8739-c87609f2590b.PNG)


 
Enfin, il existe un petit histogramme pour les flacons récurrents pour le mois actuel.


 ![5](https://user-images.githubusercontent.com/47888237/107131700-20a7ec80-68d9-11eb-8e03-c127c5a16174.PNG)


La troisième page :
 Cette page s’occupe des flacons vendus en total. Elle illustre dans le premier tableau tous les ventes en quantité et prix récurrents puis hors taxe pour arriver à calculer le chiffre d’affaire en totalité.
 
 
 ![6](https://user-images.githubusercontent.com/47888237/107131701-21408300-68d9-11eb-8bf5-ee10d2e35b08.PNG)


 
Par la suite, pour une meilleure vision, j’ai mis un graphique en cascade et un tableau pour visualiser l’évolution du CA HT par mois dés la création de la boutique.
 
 
 ![7](https://user-images.githubusercontent.com/47888237/107131752-96ac5380-68d9-11eb-9145-ebcd5518cc3e.PNG)


 
Vers la fin de cette page, j’ai mis un tableau qui illustre le CA HT pour le reste du mois actuel en cas d’absence des désabonnements.



![8](https://user-images.githubusercontent.com/47888237/107131704-230a4680-68d9-11eb-96cf-745c3b1beed6.PNG)



La quatrième page :

Dans cette dernière page, on s’occupe des détails des prévisionnels flacons récurrents pour le reste du mois actuel ainsi que pour le mois prochain.

![9](https://user-images.githubusercontent.com/47888237/107131705-243b7380-68d9-11eb-8bc6-06fbb24f9172.PNG)




