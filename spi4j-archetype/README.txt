Ce module est un archetype Maven permettant, apr�s son installation dans le repository Maven local,
de g�n�rer la structure et la configuration Maven et Eclipse d'un projet type
et bas� sur Spi4J et Pacman.

Pour g�n�rer un nouveau projet, il suffit alors d'ex�cuter la commande Maven suivante, en pr�cisant la version de l'archetype:
mvn archetype:generate -DarchetypeGroupId=fr.spi4j -DarchetypeArtifactId=spi4j-archetype -DarchetypeVersion=0.23
puis de r�pondre � quelques questions (par exemple : groupId=fr.test, artifactId=test, version=1.0-SNAPSHOT, package=fr.test, spi4jVersion=0.23)

Le but de cet archetype est d'aider � d�marrer la structure d'un projet bas� sur Spi4J et Pacman,
notamment pour les projets n'ayant pas d'autre exemple que l'application blanche de Spi4J.
La configuration g�n�r�e pourra ensuite �tre adapt�e selon les besoins � la version de Maven ou d'Eclipse
ou par exemple pour la cr�ation d'un autre module pour une application web (jsf, jsp, gwt, client RDA, etc)
comme les exemples dans le r�pertoire appwhite1.
