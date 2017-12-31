#C1. 
De mani�re � augmenter la qualit� du code, le rendre plus lisible serait une premi�re �tape importante. Les commentaires devraient �tre plus pr�cis. 
Pour travailler � plusieurs, les membres ayant acc�s au code doivent le cloner de mani�re � d�velopper leur branche. Les d�veloppeurs
commitent leur code sur la branche principale ou sur la branche features. Plus tard les features de la branche seront fusionnees a la branche principale.
Si une des �tapes �choue, le processus est avort� et une notification d��chec est envoy� au d�veloppeur qui a effectu� le commit. 
Les membres peuvent utiliser "git pull" pour maintenir leur repo � jour et apporter leurs modifications. Les commandes "git push" et "git merge" vont permettre 
de push les modifications apport�es au projet.
Le pipeline CI doit build et tester le code. Il s'assure que le livrable est stable et fonctionnel. Il doit automatiser les tests de mani�re � �tre efficace pour
le d�ployement de l'application. Il existe des solutions open source comme Jenkins.



