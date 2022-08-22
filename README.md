# OCR_P2_Appli_Sante
Objectifs du projet : 
1) Traiter le jeu de données afin de repérer des variables pertinentes pour les traitements à venir. 

2) Tout au long de l’analyse, produire des visualisations afin de mieux comprendre les données. Effectuer une analyse univariée pour chaque variable intéressante, afin de synthétiser son comportement.
L’appel à projets spécifie que l’analyse doit être simple à comprendre pour un public néophyte. Soyez donc attentif à la lisibilité : taille des textes, choix des couleurs, netteté suffisante, et variez les graphiques (boxplots, histogrammes, diagrammes circulaires, nuages de points…) pour illustrer au mieux votre propos.

3) Confirmer ou infirmer les hypothèses  à l’aide d’une analyse multivariée. Effectuer les tests statistiques appropriés pour vérifier la significativité des résultats.

4) Élaborer une idée d’application. Identifier des arguments justifiant la faisabilité (ou non) de l’application à partir des données Open Food Facts.

Idéée d'application : 
Application BYJ (Biscuits-Yogurts-(fruit)Juices) 
BUT : Aide pour le choix du goûter des enfants
CONTEXTE : Recommandation du Programme National Nutrition Santé
Goûter : 1 à 2 portions à choisir parmi
produit céréalier => « biscuits » 
fruits => « fruit_juices » 
produit laitier => « yogurts »
COMMENT : Pour un même type de produit => proposer un produit avec un meilleur nutri-score et moins/autant d’additifs
Si 2 portions choisies => la 2ème portion doit avoir un aussi bon nutri-score et moins/autant d’additifs

Une analyse en composantes principales (ACP) a permis de montrer que additives_n est une variable «à part» et peut être utilisée pour classer les produits en plus du Nutri_label

Un test du Chi2 d'indépendance a été effectué et a montré que Nutri_label n’est pas indépendant de type_gouter au risque de 5%. 
