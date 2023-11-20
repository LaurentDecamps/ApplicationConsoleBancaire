# Application console bancaire

## Consignes
S'il vous manque une information, faites un choix et restez cohérent avec celui-ci.
*Faites attention à la taille de vos commits et leurs messages.*

**Il n'y a pas de "bonne" façon de réaliser ce Kata, nous sommes intéressés par votre choix d'implémentation, votre technique et le respect des contraintes.**

## Livraison
Le brief devra être livré sous forme d'un repository Github.
Votre repository doit être suffixé avec vos initiales. 
Vore repository doit également contenir un fichier readme.md qui explique les possibles subtilités de votre implémentation et comment lancer votre projet.

## Enoncé 

En que developpeur professionel .NET, on vous demande de créer rapidement la toute première version d'une application bancaire. Pour aller au plus simple, ce sera une application console.

Imaginez une classe compte (account). La banque possède un seul client qui n'a pas besoin de s'identifier.

Réaliser l'implémentation de chacune de ces histoires utilisateurs (User Story) sur une branche séparée à fusionner (merge) sur la branche principale.

### User Story 1
En tant que banque, j'offre la possibilité à mon client de consulter le solde de son compte (initalisé à 0€).
L'application doit dès le lancement afficher le solde du compte.

### User Story 2
En tant que banque, j'accepte le dépôt d'argent d'un client vers son compte, s'il est supérieur à 0,01€ et avec deux décimales maximum.

L'application doit ajouter 200€ par exemple et afficher le solde avant et après l'opération.
L'application doit essayer de retirer 2,201€ par exemple, générer un message d'erreur et afficher le solde avant et après l'opération (elle ne doit pas avoir changé)

### User Story 3
En tant que banque, j'accepte le retrait d'argent d'un client depuis son compte, s'il n'utilise pas le découvert.

### User Story 4
En tant que banque, j'offre la possibilité à mon client de consulter l'historique des transactions du dernier mois sur son compte

## Ressources

* Les bases du C# https://learn.microsoft.com/fr-fr/dotnet/csharp/
* Le modèle console de la commande dotnet https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new-sdk-templates#console