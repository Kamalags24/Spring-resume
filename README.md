# Spring-resume

POM (Project Object Model) est un élément central dans les projets Java qui utilise maven comme outil de gestion de projet et de construction. Il sert à configurer le projet, à gérer les dépendances et définir lea manière dont le projet doit être construit et déployé. 

En un mot, le fichier pom.xml décrit le projet Maven, les dépendances nécessaires, les plugins à utiliser et les diverses configurations pour la construction et le déploiement.
Les éléments important du ``pom.xml``

&glt project>: la balise racine du fichier 
&glt modelVersion>: la version du model du POM
&glt groupId>: l'id de groupe du projet, qui suit généralement la convention de nommage inversé de l'URL du site (example: com.example)
&glt artifactId>: le nom uniaque de l'appli ou du module (ex: myapp)
&glt version>: lea version du projet (1.0.0-SNAPSHOT). Il est courant de mettre le suffixe "SNAPSHOT" pour indiquer que la version n'est pas définitive et que le projet est en cours de developpement.
&glt dependencies>: contient lea liste des dépendances 
&glt build>: contient les infos sur la manière de construire les projets. C'est ici que les plugins Maven sont souvent définis
&glt properties>: définit les propriétés personnalisés qui peuvent être définis dans le POM par example, vous pouvez définir les version dépendances.
