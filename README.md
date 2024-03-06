# azure-terraform-project

* Ce dépôt contient le code, la configuration et les pipelines requis pour déployer les ressources azure dans un envronnement de test Azure.

## Utilisation

* Valider les variables dans les paramètres du repo;
* Ajuster le fichier tfvars selon les besoins du test.


## Automatisation

* Chaque commit va lancer le pipeline de plan terraform;
* Une fois le code validé par le pipeline, veuiller faire un PR;
* Un merge dans la branche principale (main) va lancer un terraform apply.
