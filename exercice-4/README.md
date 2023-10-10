# Exercice 4

- A l’aide du Meta-Argument **ignore_change**, créez un bucket S3 nommé nuumfactory-s3-ignore-changes-XX avec un tag nommé **club-de-football** dont la valeur (de votre choix) ne sera pas trackée par terraform.

- Depuis la console AWS, modifiez la valeur du tag **club-de-football** puis exécutez la commande **terraform plan** : constatez que terraform n’atteste d’aucun changement.

- Modifiez avec terraform la valeur du tag **club-de-football** en indiquant une 3e valeur.

- Exécutez la commande terraform plan et notez que terraform n’atteste toujours d’aucun changement.

Supprimez le bucket S3 à l'aide de la commande **terraform destroy -auto-approve**.