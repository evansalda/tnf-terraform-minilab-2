# Exercice 2

- A l’aide du Meta-Argument « provider », créez 4 instances EC2 de type t2.micro dans 4 régions différentes :

    - Seul l’AMI et le type de l’EC2 suffisent pour créer une EC2
    - Sélectionnez l’AMI de votre choix parmi celles listées dans le menu correspondant*
    - Valeur du tag Name : nuumfactory-ec2-multiple-provider-XX (en remplaçant XX par votre digit)

*Pour une même AMI, l'ID change en fonction de la région dans laquelle cette AMI se trouve.

- Supprimez les 4 instances à l'aide de la commande **terraform destroy -auto-approve**.