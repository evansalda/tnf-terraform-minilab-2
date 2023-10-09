# Exercice 3

- Créez avec terraform un security group dans le VPC nuumfactory-vpc avec le Meta-Argument **prevent_destroy** paramétré à true :

    - Nom : nuumfactory-sg-create-before-destroy-XX
    - Valeur du tag “Name” : nuumfactory-create-before-destroy-XX
    - Description : La description de votre choix
    - Règles : aucune, ou celles de votre choix

- Modifiez la description du security group et exécutez la commande **terraform plan**.

- Exécutez la commande **terraform apply -auto-approve** et observez le message que terraform vous retourne.

- Retirez le Meta-Argument **prevent_destroy** du code et supprimez le security group avec la commande **terraform destroy -auto-approve**.