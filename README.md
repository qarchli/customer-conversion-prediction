# customer-conversion-prediction

Dans le monde de la publicité en ligne, l’un des principaux objectifs est de diffuser des publicités aux utilisateurs pour entraîner une "conversion". Une conversion se produit lorsque quelqu'un voit votre annonce et prend ensuite une action que vous avez définie comme utile pour votre entreprise.

Pour optimiser les dépenses de diffusion des annonces, nous allons construire des modèles qui prennent les caractéristiques de certaines publicités affichées et prédire s’il y aura conversion ou non.

Les données recueillies représentent un demi million d’observations d’une campagne publicitaire, les caractéristques anonymisées ainsi que le résultat (Ici l'événement de conversion est le clic).

L'objectif donc est de créer un modèle pour prédire la conversion en fonction des caractéristques de la publicité.


Informations sur le dataset :

- fold_positon : correspond à la position de la publicité sur la page
- buyer_bid : correspond au prix de l'enchère effectuée
- geo_region : identifiant de région
- advertiser_frequency, advertiser_recency, creative_freq, creative_rec : Variables quantitatives liées aux précédents points de contact avec un utilisateur.
- creative_id : identifiant de la publicité affichée
- click : 1 si clic, 0 sinon
