# Module Security

## Entité et tests unitaires:

- Créer l'entité avec les props suivantes:
  - email
  - mot de passe
  - nom
  - prenom
  - date de naissance
  - date de creation
  - user actif
  - user actif depuis
  - user suspendu
  - user suspendu depuis
  - user supprime
  - user supprime depuis
  
## Tests unitaires:

- Sur nom / prenom
- Mot de passe : minimum 8 caracteres , 1 Maj , 1Chiffre
- Date de naissance : doit avoir au mois 18 ans le jour de l'inscription
- Si user suspendu , date de suspension doit etre remplie
- idem pour supprimé et actif.
- email doit etre un email au bon format

## Tests fonctionnels et creation du formulaire d'enregistrement:

### Etape 1 : Formulaire d'enregistrement

- Création du formulaire de création de compte utilisateur : utilisation du composant Form
- Mise en place des différentes validations : utilisation du composant Validator
- Développement en TDD : 1 test -> 1 echec -> 1 code

### Etape 2: Formulaire de connexion

- Mise en place du composant security
- Creation du formulaire de connexion
- Mise en place de l'authentification
Tout ca en TDD.

  
