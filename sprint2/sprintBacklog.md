# Sprint 2

## Selected backlogs
1. Estimation : 10
> [En tant que conseiller, je veux pouvoir me connecter à mon espace sécurisé](https://www.notion.so/En-tant-que-conseiller-je-veux-pouvoir-me-connecter-mon-espace-s-curis-3eae2111b9a64994800b1c004300585a)
- Créer vue de connexion avec formulaire de connexion.

2. Estimation : 30
> [En tant que conseiller, je veux visualiser mes derniers biens en vente afin de pouvoir travailler dessus](https://www.notion.so/En-tant-que-conseiller-je-veux-visualiser-mes-derniers-biens-en-vente-afin-de-pouvoir-travailler-de-cbbd1c764aff4690aea91f61000ea6da)
- Créer une vue sécurisée (accessible pour user de rôle conseiller dans le backoffice) pour "Tous les biens"
    - affiche la liste par récence de toutes les biens avec un lien "Editer" pour chacun d'entre eux
- Créer une vue sécurisée avec un formulaire (Update) pour modifier chacun des propriétés du bien choisi.

3. Estimation : 15
> [En tant que visiteur, je veux contacter le conseiller en charge d'un bien afin de lui demander des précisions](https://www.notion.so/En-tant-que-visiteur-je-veux-contacter-le-conseiller-en-charge-d-un-bien-afin-de-lui-demander-des-p-80acebbd056b4a1e9f514f4c57901a57)
- Mise en place d'un serveur mail
- Ajout d'un formulaire de contact dans la vue d'un bien seul. Il contient les champs suivants :
    - Mail de l'expéditeur
    - Input texte
    - Nom et prénom du conseiller ayant créé la fiche bien en question
    - le message est envoyé à l'adresse mail du conseillé lié au bien.

4. Estimation : 35
> [En tant que conseiller, je veux visualiser les messages envoyés par les acheteurs afin de répondre à leurs questions](https://www.notion.so/En-tant-que-conseiller-je-veux-visualiser-les-messages-envoy-s-par-les-acheteurs-afin-de-r-pondre--1b6039a3a3724ba1825d59e1ae79eeca)
- Création d'une vue sécurisée (dans le backoffice, accessible au users de rôle "conseiller") la liste des derniers messages envoyés depuis la page d'un bien spécifique.

5. Estimation : 2
> [En tant que visiteur, je veux faire une proposition afin d'acheter un bien](https://www.notion.so/En-tant-que-visiteur-je-veux-faire-une-proposition-afin-d-acheter-un-bien-782f97dae6f64d17aa4ba12a1bd90ef8)
- Ajout d'un champ "proposition" (input de type number) dans le formulaire de contact d'un bien spécifique.

5. Estimation : 2
> [En tant que vendeur, je veux consulter les propositions reçus pour mon bien afin de les étudier](https://www.notion.so/En-tant-que-vendeur-je-veux-consulter-les-propositions-re-us-pour-mon-bien-afin-de-les-tudier-ea2db3ddb6a146558d9a85ab3baa151c)
- Ajout à la vue sécurisée "liste des messages" la valeur contenu dans le champ "proposition" du message du visiteur, associé à un bien spécifique.

6. Estimation : 30
> [En tant que vendeur, je veux consulter les propositions reçus pour mon bien afin de les étudier](https://www.notion.so/En-tant-que-vendeur-je-veux-consulter-les-propositions-re-us-pour-mon-bien-afin-de-les-tudier-ea2db3ddb6a146558d9a85ab3baa151c)
- Création d'une vue spécifique à un bien et protégée par un mot de passe
    - Renseignement de toutes les propositions faites pour ce bien