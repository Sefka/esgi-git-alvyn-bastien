# esgi-git-alvyn-bastien

il est préférable d'utiliser le workflow gitflow car il est plus complet et plus securisé avec les deux branches principales qui sont  :

- Master : qui servira de branche de prod oû tous les fichiers du projet sont normalement stables.

- Develop : cette branche servira de developpement pour le projet donc c'est dans celle-ci que s'effectuera tous les changements avec une version stable
pour la prochaine release 



il y a néemoins certaines branches secondaires nécessaire au bon fonctionnement du projet :

- Feature : qui est une branche que l'on va créer à partir de develop et qui servira pour une partie du projet en particulier. une fois le travail terminé,
on l'a merge dans develop pour qu'elle soit etudie puis ajouté ensuite dans la branche develop.

- Release : qui servira à isoler et stabiliser la version de prod de la release

- Hotfix : cette branche est créer a partir de master et permet de fixer un bug en urgence sur une release en production
