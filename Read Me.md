# Formation de Data visualisation power bi 
    1. Recuillir et traiter des données à partir d'une page web

        Le navigateur de power bi recupere toute les tables de la page web "https://fr.wikipedia.org/wiki/D%C3%A9mographie_de_la_France"
        On choisie la table source 
        On raffine les données d'abord par Power Query
        On prends la premiere ligne comme ligne d'en-tête
        On applique nos modifications faire sur Power Query Acceuil->Appliquer
        On raffine nos données sur power bi en supprimant quelques colognes inutiles
        Power Bi et Power Query sont synchronosié automatiquement
        On passe a l'onglet rapport et dans visualisation on choisie type de grpahe a aficher
        On choisie graphique en courbes histogrammes
        On chosie les données qu'on veut afficher "année, population, taux de mortalité, taux de natalité"
        Axe partagé -> Année
        Valeur de cologne -> population
        Taux de mortalité -> en ligne
        Taux de natalité -> en ligne
        Sur format on va changer un peut notre graphe pour qu'il soit plus lisible

    2.  Recuillir et traiter des données à partir d'un fichier EXCEL

        On cliquant sur obetenir des données -> excel sur le naviagteur power bi nous chargeons le fichier sur notre dossier local "Primeur A.xlsx"
        On choisie la table Primeur A
        On tranforme les données par Power Query
        On supprime la premiere ligne du haut qui est inutile
        Et on transpose notre table ligne 1 -> cologne 1
        On clique sur transformer "toujours dans power query" apres Transposer 
        Notre premiere ligne devienne la ligne des en-têtes
        On change le nom de la premeiere cologne vers Mois
        On ferme power Query et applique
        On passe a Power Bi
        Si on a fermer par erreur power query on fait un clique droit sur une cologne et on choisie modifier moi ma requete
        On modifie la cologne des mois pour afficher seul le mois et l'année "ce qu'il nous interesse seulement"
        Clique sur cologne -> modifier format de date
        Apres on ira en Rapport -> choisir un visuel -> courbe
        Axe -> Mois
        Valeurs -> autre cologne
        On affiche que les mois sur le graphe
        Pour un mieux affichage claire on on modifie dans format les ligne on mettra des lignes en points cotinues
         




