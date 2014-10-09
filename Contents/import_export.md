# Import et Export {#param-inline-help:8df0928f-473f-4cce-86b9-d1b7496237cb}

## Contexte {#param-inline-help:2b4acf74-1523-407a-b9f0-5b7d6f24f1b5}

La création d'un ensemble cohérent d'aide en ligne est bien souvent un processus itératif qui couvre l'ensemble de
la durée de vie du projet du développement à la production.

Dans ce cas, il est nécessaire de savoir transmettre un document d'aide en ligne d'un contexte de recette à un 
contexte de production.

## Export {#param-inline-help:8e46d481-65d3-47ec-87ef-49c00eea21f2}

Les documents d'aide en ligne sont des documents Dynacase, ils peuvent donc suivre la même logique d'import/export que
les documents standard.

La procédure d'export est la suivante :

* Allez dans l'administration `admin.php` : `Gestion des documents` > `Explorateur de documents`

![Explorateur de document](export_help_1.png)

* Cliquez ensuite sur `Recherche` > `Recherche Simple` (en haut au milieu de l'écran)

![Recherche Simple](export_help_2.png)

* Cliquez ensuite sur `Plus d'options` et sur `Inclure les documents système`

![Recherche Simple : document système](export_help_3.png)

* Cliquez ensuite sur `famille` : `Aide en ligne` et sur `Lancer la recherche`, en bas à gauche apparaît la liste des
 aides en ligne existantes.
 
![Liste des aides](export_help_4.png)

* Faites ensuite un clique droit sur l'aide en ligne que vous souhaitez exporter et sur `Ajouter au porte-documents`

![Liste des aides : porte document](export_help_5.png)

* La fenêtre suivante s'ouvre et cliquez sur `Outils` > `Exportation du dossier` 

NB: Vous pouvez exporter plusieurs documents en un seul fichier en renouvellement l'opération de sélection de l'aide dans
la liste.

![Export](export_help_6.png)

* Cliquez ensuite sur `Exporter` et un fichier CSV vous ai répondu avec le contenu de l'aide en ligne.

![Export](export_help_7.png)

## Import {#param-inline-help:dfffe2d4-ab53-4545-8677-14c448dc110b}

Vous pouvez ensuite importer l'aide en ligne soit :

* en l'ajoutant dans votre webinst,
* en utilisant l'application `admin.php` : `Gestion des documents` > `Importation de documents`