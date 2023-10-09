# Exercice 1

- A l’aide du Meta-Argument « count », créez avec terraform 5 buckets S3 avec les caractéristiques suivantes :

    - Nom : nuumfactory-s3-count-XX-\<index de count\>
    - Versioning : activé
    - Un tag nommé **count-index** avec pour valeur l’index de count du bucket

- Exécutez la commande **terraform init**.

- Exécutez la commande **terraform plan** et analysez le plan d'exécution.

- Exécutez la commande **terraform apply -auto-approve** et vérifiez la présence de vos 5 buckets S3 sur la console AWS. Vérifiez également que la valeur du tag count-index est correcte.

Supprimez les bucket S3 à l'aide de la commande **terraform destroy -auto-approve**.