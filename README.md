# Chaque fois que vous clonez un dépôt Terraform ou que vous ajoutez un nouveau module, il suffit d'exécuter init.
$ terraform init

# La commande validate vérifie et valide votre configuration. Exécutez cette commande avant d'appliquer vos modifications.
$ terraform validate


# La commande plan crée un plan d'exécution, qui vous permet de prévisualiser les changements que Terraform prévoit d'apporter à votre infrastructure.
$ terraform plan


#La commande apply exécute les actions proposées dans un plan Terraform 
$ terraform plan
or 
$ terraform apply --auto-approve


# La commande destroy détruit toute notre configuration. Ne l'exécutez pas maintenant.
$ terraform destroy
or 
$ terraform destroy --auto-approve
