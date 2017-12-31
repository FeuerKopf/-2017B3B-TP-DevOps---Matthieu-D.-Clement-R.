#C1. 
De manière à augmenter la qualité du code, le rendre plus lisible serait une première étape importante. Les commentaires devraient être plus précis. 
Pour travailler à plusieurs, les membres ayant accès au code doivent le cloner de manière à développer leur branche. Les développeurs
commitent leur code sur la branche principale ou sur la branche features. Plus tard les features de la branche seront fusionnees a la branche principale.
Si une des étapes échoue, le processus est avorté et une notification d’échec est envoyé au développeur qui a effectué le commit. 
Les membres peuvent utiliser "git pull" pour maintenir leur repo à jour et apporter leurs modifications. Les commandes "git push" et "git merge" vont permettre 
de push les modifications apportées au projet.
Le pipeline CI doit build et tester le code. Il s'assure que le livrable est stable et fonctionnel. Il doit automatiser les tests de manière à être efficace pour
le déployement de l'application. Il existe des solutions open source comme Jenkins.



