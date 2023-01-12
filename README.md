# Test22

le problème d'ajout de frais hors forfait venez de ligne 234 du fichier class.pdogsb.inc.php
il manquer tout se qui doit etre dans une paranthese apres INSERT INTO LigneFraisHorsForfait

$req = "insert into LigneFraisHorsForfait(idVisiteur,mois,libelle,date,montant)
		values('$idVisiteur','$mois','$libelle','$dateFr','$montant')";
