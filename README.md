# Projet_Git

# Easter GIT

## Step 1

- Initialiser le projet git, inviter le / les coéquipiers.

 => Création du répo, puis partage du répo. 
 	Le projet est structuré suivant le gitFlow : 
 		- une branche master 
 		- une branche de développement
 		- chaque feature se développe sur une branche tiré depuis la branche développement
 		- Le passage en production se fait depuis une branche release tirée dupusi la branche de développement, puis mergée sur la branche master.

- Créer la landing page "Easter Git Project 2023".

=> Initialisation du projet : push home_page.html et le fichier Readme

- Permettre à chaque coéquipier de cloner le repo en local.

=> Clonage du projet dupuis gitKraken

## Step 2

- Pour la 1ère feature, on vous demande de créer une page qui souhaite un "happy Easter" en français, et ajouter un lien vers cette page depuis la landing page.

=> On créer une branche "happy_easter_fr" depuis la branche de développement, dans laquelle on ajoute un fichier "happy_easter_fr.html".
    On commit les changements sur la branche de feature.
    On merge la branche de feature sur la branche de développement
=> On respecte ce protocole pour ajouter le lien dans la landing page : branche feature, modification, commit, merge

- Pas de release pour la production ne doit encore être faite.

=> On ne créer pas de branche de de release.

## Step 3

Pour les features suivantes, on vous demande de :
- créer une page qui souhaite un "happy Easter" en Anglais
- créer une page qui souhaite un "happy Easter" en Espagnol
- créer une page qui souhaite un "happy Easter" en Italien
- ajouter des liens vers ces pages sur votre landing page

Une release avec ces features est mise en production.

Prenez les bonnes décisions :
- créer des branches pour ces features ou pas ?
- si oui, où créer ces branches ?
- si oui, où merger ces branches ?
- comment matérialiser le fait qu'une release avec ces features est partie en production ?

## Step 4

Pour les features suivantes, on vous demande de :
- créer une page qui souhaite un "happy Easter" en Portugais
- créer une page qui souhaite un "happy Easter" en Allemand
- créer une page qui souhaite un "happy Easter" en Polonais
- ajouter des liens vers ces pages sur votre landing page

=> On créer une branche de feature depuis la branche de développement pour chaque feature : "happy_easter_pt", "happy_easter_de", "happy_easter_po",  et une branche pour ajouter les lien dans la landing page.
    On push les modifications sur les branches respectives, puis on merge les branches de features sur la branche de développmement.

- Pour le moment aucune release avec ces features n'est mise en production.

=> On ne créer pas de branche release

## Step 5

Une correction urgente doit être faite sur la production ! (release faite au step 3)

Remplacer la page Italienne par une page Russe, et remplacer le lien sur la landing page.

Prenez les bonnes décisions :
- comment créer un hotfix (d'où tirer la branche) ?
- où la merger ?
- comment matérialiser le fait qu'une release avec cette correction est mise en production ?

## Step 6

Alors que la release preparée au step 4 n'est toujours pas en production, on commence à travailler sur la release suivante.

Pour les features suivantes, on vous demande de :
- créer une page qui souhaite un "happy Easter" en Hollandais
- ajouter un lien vers cette page sur votre landing page

=> On continue de développer sur la branche de développement, on tire une branche de feature "happy_easter_nl", on créer la page en Hollandais, on ajoute le lien dans la landing page.
    On push les modifications, on merge la branche de feature sur la branche de développement.

## Step 7

Une amélioration indispensable sur la release preparée au step 4 doit être faire :
- créer une page qui souhaite un "happy Easter" en serbe
- ajouter un lien vers cette page sur votre landing page

Une release avec ces features est mise en production (mais sans la page en Hollandais donc).

## Step 8

- Préparez une release pour la production avec la feature ajoutée au step 6 (la page en hollandais).

=> On tire une branche de release depuis la dernière instance de la branche de développement pour avoir les modifications de la page en Hollandais. On merge la branche de release sur la branche master.