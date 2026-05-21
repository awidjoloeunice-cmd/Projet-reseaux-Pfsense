# Projet-reseaux-Pfsense-haute disponibilité 
## Objectif 
Mettre en place une infrastructure réseaux tolérante 
aux pannes grâce à la haute disponibilité
## Préréquis
2 Pfsense , un contrôleur de domaine ,
d'un login mots de passe et d'une station windows placée en client DHCP
# Protocoles utilisés
Pfsync 
XLMRPC
CARP
## Fonctionnalités 
Configuration de deux firewalls pfsense
Mise en place du failover
Synchronisation automatique 
Tests de basculement réseau 
## Résultat
Le réseaux reste accessible même lorsqu'un firewall tombe en panne
