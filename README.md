# Ontologie_Cereales

####Bienvenue sur l’ontologie Kernel Information Retrieval Cereals

## Objectif

Ce projet vise à formuler une ontologie sur les espèces céréalières. Le but est de former une classification permettant d’associer des individus observés à des classes au sein de l’ontologie et ainsi être capable de leur associer des valeurs de composition physico-chimique. Elle s’inscrit dans un projet coréalisé entre des étudiants de la promotion de IODAA 2025 d’AgroParisTech et l’Association Française de Zootechnie (AFZ).

## Méthode

La méthode de réalisation de cette ontologie est la suivante : à partir d’une base de données de référence fourni par l’AFZ, une classification hiérarchique a été réalisée sur les instances appartenant à la catégorie « Céréales » de cette structure initiale de données.
Notre approche se base sur une classification sémantique des instances. L’ontologie rassemble un total de 197 instances réparties sur 25 classes (ex. Avoine, Blé, etc.).
Ensuite, pour chaque classe est établi un nombre différent de niveau de sous-hiérarchies en fonction des espèces répertoriées ou de la présence d’un traitement ou non sur les instances. Nous observerons par exemple un découpage spécifique au Blé qui se partagera ensuite en trois sous-classes : Blé tendre, Blé dur et Autres blés. Ce découpage en sous-classes est propre à chaque espèce et déterminé en fonction de rassemblements que nous avons jugés pertinent. 

## Pistes d’amélioration de l’ontologie

Ce projet reste incomplet en l’état pour une exploitation généralisable. Les pistes d’amélioration de cette ontologie sont les suivantes :
- préciser les propriétés physico-chimiques dans l’onglet « DataProperty » et les configurer pour chaque instance
- lier les concepts de cette ontologie à celles communément utilisées dans la recherche à ce jour (ex. AGROVOC, NALT)
- compléter cette ontologie avec les autres catégories, comme les tourteaux par exemple. 

## Remerciements

- Liliana Ibanescu, chercheuse à l’INRAE, équipe EKINOCS
- Gilles Tran et Valérie Heuzé, Association Française de Zootechnie

*Travail collaboratif réalisé par Pierre-Jean Gouze, Baptiste Granier et Valentine Michelet.*
