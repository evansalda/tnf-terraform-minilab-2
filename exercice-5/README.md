# Exercice 5

- Dans votre fichier **main.tf**, déclarez le security group suivant :

    - Nom : nuumfactory-sg-replace-triggered-by-XX
    - Valeur du tag “Name” : nuumfactory-sg-replace-triggered-by-XX
    - Description : La description de votre choix
    - Règles : aucune, ou celles de votre choix

- Déclarez un bucket S3 nommé nuumfactory-s3-replace-triggered-by-XX dans votre fichier main.tf et utilisez le Meta-Argument **replace_triggered_by** pour déclencher le remplacement du bucket lorsque la description du security group est modifiée.

- Exécutez la **terraform apply** pour créer les 2 ressources.

- Modifiez avec terraform la description de votre security group et exécutez la commande **terraform plan** : Notez que le remplacement du security group ET du bucket S3 sont planifiés.

- Exécutez la commande **terraform apply** pour remplacer vos 2 ressources.

Supprimez le bucket S3 et le security group via la commande **terraform destroy -auto-approve**.