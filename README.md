# formulaire_primo_standalone

Crée un formulaire HTML permettant d'interroger spécifiquement certaines bibliothèques et types de documents.

Code adapté au paramétrage de Primo Université Cote d'Azur.

Fonctionne avec Primo BO. Le code serait à réactualiser pour Primo VE.

Le code en dans la branche main ne filtre sur aucune bibliothèque.

La constante code_bibliotheque doit contenir le code Primo de la bibliothèque sur laquelle faire le filtre

La constante label_bibliotheque doit contenir le nom de la bibliothèque sur laquelle faire le filtre (affiché dans le menu)

La constante recherche_reseau doit contenir true pour permettre la recherche sur l'ensemble du réseau, en complément de la recherche filtré sur la bibliothèque

Aller dans la branche "draguignan" et "ljad" pour obtenir le code filtré sur la BU Draguignan ou le LJAD.
