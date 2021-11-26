# Sprint 1
- Remarque : on définit comem accomplie ("done" une fonctionnalité fonctionnant sur notre projet local, les tests en déploiement seront effectué dans un autre sprint)
## Selected backlogs

1. Estimation : 10
> [En tant que visiteur, je veux visualiser les derniers biens en vente afin de découvrir les nouveautés de l'agence](https://www.notion.so/En-tant-que-visiteur-je-veux-visualiser-les-derniers-biens-en-vente-afin-de-d-couvrir-les-nouveaut--3e895b3f2c254f17b79d066a35a5c5f4)
- Création d'une table "bien" (soit une propriété immobilière)
- Création d'une vue "nouveautés" affichant tous les biens.
    - Trier l'affichage de la plus récente à la plus ancienne.  

2. Estimation : 10
> [En tant qu'administrateur je veux créer de nouveaux utilisateurs](https://www.notion.so/En-tant-qu-administrateur-je-veux-cr-er-de-nouveaux-utilisateurs-ff0d3c92900f479f99f712cc6e589091)
- Création d'une table users et avec les propriétés suivantes :
        - Identifiant / Mot de passe / Nom / Prénom / Rôle
- Implémentation d'une vue sécursiée pour administrateur avec un formulaire de création d'utilisateur.  

3. Estimation : 15
> [En tant qu'administrateur, je veux attribuer un rôle à un utilisateur](https://www.notion.so/En-tant-qu-administrateur-je-veux-attribuer-un-r-le-un-utilisateur-c37755c16e7f413f82883710196c8505)
- Création d'un formulaire sécurisé permettant d'assigner un rôle "conseiller" à un user.  

4. Estimation : 10
> [En tant que conseiller, je veux créer un nouveau bien afin d'améliorer sa visibilité](https://www.notion.so/En-tant-que-conseiller-je-veux-cr-er-un-nouveau-bien-afin-d-am-liorer-sa-visibilit-960ea2666ab943a9b1276ad8653ef961)
- Création d'un backoffice pour les users de rôle "conseiller" permettant la création d'un bien via une formulaire sur une vue sécurisée.  

5. Estimation : 20
>[En tant que visiteur, je veux visualiser les détails d'un bien afin de le découvrir](https://www.notion.so/En-tant-que-visiteur-je-veux-visualiser-les-d-tails-d-un-bien-afin-de-le-d-couvrir-d4852ad2ef1d47b481b2b54ccb6d86db)
- Ajout des propriétés suivantes à la table "bien"
    - Adresse
    - Photos (max 6)
    - Description
    - Données quantitatives
        - Taille m2
        - Nombre de pièces
        - Nombre de chambres
        - Nombre de salles de bain
    - Liste d'éléments important du bien
    - Avis du conseiller
- Création d'une vue pour un bien seul.