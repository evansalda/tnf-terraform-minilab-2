# Exercice 6

- A l’aide du Meta-Argument **for_each** (inspirez-vous de l’exemple [ici](https://developer.hashicorp.com/terraform/language/meta-arguments/for_each#chaining-for_each-between-resources)), créez 5 instances EC2 avec les caractéristiques suivantes :

    - 1ère instance
        - AMI : ami-0f82b13d37cd1e8cc
        - Type d’instance : t2.micro
        - Availability Zone : eu-west-3a
        - Adresse IP publique : Oui
        - Valeur du tag Name : nuumfactory-ec2-for-each-XX

    - 2eme instance
        - AMI : ami-0f82b13d37cd1e8cc
        - Type d’instance : t2.small
        - Availability Zone : eu-west-3b
        - Adresse IP publique : Oui
        - Valeur du tag Name : nuumfactory-ec2-for-each-XX

    - 3eme instance
        - AMI : ami-0f82b13d37cd1e8cc
        - Type d’instance : t2.medium
        - Availability Zone : eu-west-3c
        - Adresse IP publique : Oui
        - Valeur du tag Name : nuumfactory-ec2-for-each-XX

    - 4eme instance
        - AMI : ami-0f82b13d37cd1e8cc
        - Type d’instance : t2.large
        - Availability Zone : eu-west-3b
        - Adresse IP publique : Non
        - Valeur du tag Name : nuumfactory-ec2-for-each-XX
        
    - 5eme instance
        - AMI : ami-0f82b13d37cd1e8cc
        - Type d’instance : t2.xlarge
        - Availability Zone : eu-west-3b
        - Adresse IP publique : Non
        - Valeur du tag Name : nuumfactory-ec2-for-each-XX

- Supprimez les 5 instances via la commande **terraform destroy -auto-approve**.