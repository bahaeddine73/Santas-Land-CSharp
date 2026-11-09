# Compte rendu d’activité – Semaine du 15/12/2025

# Binôme : ACHOUR Bahaeddine – MAATALA Souhail

# Travail réalisé cette semaine

# Finalisation du projet et correction des éléments manquants lors du dernier dépôt.

# • Finalisation de la simulation :

# • Ajout du calcul des pièces d’or par heure dans la méthode AvancerUneHeure(),

# conformément au sujet. (MAATALA Souhail)

# • Mise en place du coût total et de l’historique des coûts horaires, qui avaient été oubliés

# lors du dernier dépôt.

# • Gestion des périodes de repos :

# • Ajout de l’attribut HeureDebutRepos dans les classes Lutin et Nain, afin de respecter

# les contraintes temporelles du sujet (12h pour les lutins, 24h pour les nains). (ACHOUR

# Bahaedinne et MAATALA Souhail respectivement)

# • Méthodes de gestion du personnel :

# • Implémentation de la méthode ModifierNombreLutins().

# 'Elle permet de mettre des lutins en repos ou d’en rappeler en respectant les règles du

# sujet. (ACHOUR Bahaeddine)

# • Implémentation de la méthode ModifierNombreNains(), sur le même principe que celle

# des lutins, avec la contrainte des 24 heures de repos.(MAATALA Souhail)

# • Nous avons ajouté une variable HeureGlobale afin de corriger un problème dans la

# gestion du repos des lutins et des nains. L’utilisation de HeureActuelle, réinitialisée à

# chaque changement de jour, empêchait le rappel des employés après 12 ou 24 heures.

# HeureGlobale, incrémentée à chaque heure et non réinitialisée, permet désormais de

# calculer correctement la durée du repos et d’assurer le passage de l’état repos à actif.





