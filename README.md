######## STRUCTURE DU DOSSIERS PAGES
Le dossier `pages` est divisé en 3 grandes parties
#### Fichier à la racine
 ### Fichier `index.vue`
Ce ficher désigne la page d'acceuil de notre site.
On y présentera aussi une liste des ssociétés les mieux notés. 
 ### Fichier `_id.vue`
Ce fichier nous permettra de voir les informations des sociétés les mieux notés.

#### Dossier `back-office`
Ce dossier renvoit a l'arborescence de tous les fichiers et dossier qui toucheront aux administrateurs.



#### Dossier `front-office`
Ce dossier quand à lui gère les pages des utilisateurs 
Il est composé de DEUX GRANDS DOSSIERS: 
- Dossiers societes
- Dossiers visiteurs

    ### Dossier `societes`
Dans ce dossier seront gérés tous les dossiers et fichiers des sociétés inscrites sur le site.
        ## `index.vue` se trouvant à la racine
C'est le chier de connexion qui contiendra le formulaire de connexion.
        ## Dossier `compte`
            # `_id.vue`
Dans ce fichier nous auront tous les informations relatives à au compte de la société connectée.
        ## Dossier `modifier_business`
            # `_id.vue`
Dans ce fichier, nous donneront la possibilité aux sociétés de modifier leur informations.
    ### Dossier `visiteurs`
Dans ce dossier nous geront les fichiers que les visiteurs pourront consulter. Autrement dit, ces pages ne requièrent aucune connexion pour etre vus.
        ## Dossier `blog`
            # `index.vue`
Nous y listerons tous les articles postés sur le blog.
            # `_id.vue`
Cet fichier renverra l'integralité de l'article qu'un utilisateur aura choisi.
        ## Dossier `recherche`
C'est le lieu de donner la possibilité aux visiteurs de rechercher un service via une des société référencé sur lnotre plateforme.
            # `lieux.vue`
Dans ce fichier la recherche se fera par lieu.
            # `secteur.vue`
Ici le visiteurs aura la possibilité de faire une recherche en fonction du secteur d'activité des sociétés.
            # `_id.vue`
Consulter les informations d'une société apres recherche
        ## `apropos.vue`
Une présentation de la plateforme:
    - Ses objectifs
    - Ses attentes
    etc...
        ## `inscription.vue`
Page via laquelle une société pourra s'inscrire sur la plateforme.


