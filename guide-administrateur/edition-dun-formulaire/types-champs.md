# Les différents types de champ

## Les champs structurels "Structure des champs" :\*\*

### Titre de section

Le titre de section permet de segmenter et de structurer votre formulaire. En effet, la construction de ce dernier étant linéaire par empilement de champs, il convient de le structurer afin de le rendre plus facilement lisible par l’usager. Il existe plusieurs niveaux de titre de section (avec des tailles de police différentes). Cela permet également d'avoir un menu de navigation qui vous permet d'aller facilement d'une section à l'autre.

### Bloc répétable

Ce champ permet à l'usager de saisir un certain nombre de champs autant de fois qu'il le souhaite. Pour savoir comment l'utiliser, je vous invite à vous rendre sur la page dédiée en cliquant [ici](https://faq.demarches-simplifiees.fr/article/48-les-blocs-repetables).

### Lien vers un autre dossier

Ce type de champ donne la possibilité de relier deux dossiers déposés sur **demarche.numerique.gouv.fr** entre eux.

Exemple : je fais une demande de subvention en 2019 et en 2020, je dois en faire le bilan. En choisissant ce type de champ, l’usager indique seulement le numéro du dossier 2019 dans son dossier 2020, et l’instructeur peut alors accéder facilement à la demande grâce à un lien présent dans le bilan.

Pour accéder au premier dossier déposé par l'usager, l'instructeur de la seconde démarche devra également être instructeur de la première démarche. Il lui suffira alors de cliquer sur le lien du dossier, comme ci-dessous :

### Explication

Ce type de champ présente un texte sans possibilité de réponse qui vous permet de détailler un point spécifique, de guider l'usager ou bien d'introduire des sous-titres de section.

Il est possible d'afficher un texte complémentaire affichable au clic ainsi qu'une pièce jointe.

## Les champs relatifs à l'état civil

### Civilité

L'usager peut choisir entre « Madame » ou « Monsieur ».

### email

L'usager doit renseigner un e-mail.

### Téléphone

L'usager doit renseigner un numéro de téléphone.

## Les champs relatifs à la localisation

### Adresse

L'usager doit entrer une adresse avec une auto-complétion - l'adresse se complète sans que l'usager n'ait besoin de l’écrire entièrement - grâce à la connexion à la Base Adresse Nationale (BAN).

### Communes, départements, régions, pays

Ces quatre types de champ sont des menus déroulants dont les valeurs sont préétablies. Il n'est pas possible de les modifier.

Le champ « Pays » comporte des pays qui ont existé dans le passé, ou dont la reconnaissance internationale est contestée, pour permettre à des usagers de répondre à la question « Quel est votre pays de naissance ? »

Les champs « Régions », « Département » et « Communes » utilisent des valeurs provenant de l’[API Géo](https://api.gouv.fr/les-api/api-geo). Il s’agit des régions, départements et communes de France métropolitaine et des DROM. Les communes des TOM ne sont donc pas incluses.

Pour le champ « Communes », les usagers doivent dans un premier temps entrer par auto-complétion leur département puis un second champ dédié à la commune s'affichera.

## Les champs relatifs au paiement et à l'identification

### Le numéro Iban

Ce champ permet uniquement de collecter les numéros Iban valides français.

### Le numéro Siret

Ce champ permet de collecter le numéro Siret ainsi que les informations administratives reliées à ce numéro grâce à l'API Entreprise. Vous trouverez également la liste des informations remontées automatiquement.

Le numéro SIRET doit comporter exactement 14 chiffres.

## Les champs standards

### Texte court

Ce champ permet à l'usager de répondre de manière libre. Si le nombre de caractères est illimité, ce champ est adapté à une réponse courte.

### Texte long

Ce champ est similaire au précédent à la différence qu'il est adapté à une réponse longue et structurée. Le nombre de caractères est aussi illimité.

### Nombre décimal

L'usager doit renseigner un nombre qui peut être décimal.

### Nombre entier

L'usager doit renseigner un nombre entier.

### Date

L'usager doit renseigner une date au format jj/mm/aaaa.

### Date et Heure

L'usager doit renseigner une date et un horaire.

### Champ formaté

Vous avez la possibilité de formater un champ selon le format de votre choix. Deux options s'offrent à vous:

* Le mode simple: vous pouvez formater un champ en choisissant le nombre de caractères que comportera ce champ, mais aussi s'il comporte des chiffres, des lettres et/ou des caractères spéciaux.
* Le mode avancé: vous pouvez formater un champ selon une expression régulière en définissant le nombre de caractères, l'ordre des caractères, etc. Attention, à n'utiliser que si vous êtes sur du format du champ car si le format renseigné par l'usager ne correpond pas à l'expression régulière, ce dernier ne pourra déposer le dossier.

Voici le résultat en prévisualisant le formulaire

Voici l'écran en cas d'erreur dans la saisie, bloquant le dépôt du dossier.

### Le champ "pièce à joindre"

Ce champ permet à l'usager d'ajouter au dossier un document. La taille de chaque pièce justificative doit être inférieure à 200 Mo.\
Vous pouvez désormais choisir la nature de la pièce à joindre entre:

* **Relevé d'identité bancaire (RIB)** : Le contenu du fichier joint par l’usager sera analysé automatiquement afin de récupérer et retranscrire à l’instructeur les informations suivantes : **Nom du titulaire, Adresse du titulaire** (si présente sur le fichier), **IBAN, Code BIC, Nom de la banque**.
*   **Titre d'identité :** ce champ permet à l’usager de joindre une carte d'identité (uniquement le recto), passeport, titre de séjour ou autre justificatif d’identité. Formats acceptés : jpg/png, taille maximale : 20 Mo

    De plus, pour des raisons relatives au RGPD, le titre d'identité sera filigrané et automatiquement supprimé une fois le dossier terminé (faisant l'objet d'une décision finale).\
    À noter : le titre d’identité ne sera ni disponible dans les zip de dossiers, ni téléchargeable par API.
* **Non spécifié:** Tout autre document

Il est également possible de limiter la pièce à joindre à certains formats de fichier (visible au survol) et de paramétrer la suppression automatique de la pièce une fois le dossier instruit.

Vous avez la possibilité de joindre un modèle de pièce justificative que les usagers peuvent télécharger et remplir pour joindre à leur dossier. Cela est particulièrement utile dans les démarches impliquant par exemple l'utilisation de fichiers tableurs.

## Les champs relatifs aux choix

### Case à cocher seule

Ce type de champ insère à gauche du libellé du champ une case que l'usager peut cocher.

### Choix simple

#### Manuelle

L'usager doit choisir l'une des valeurs paramétrées par l'administrateur. Pour créer des valeurs, il vous suffit de les ajouter dans la partie « options de la liste » .

Vous pouvez également proposer à l'usager une option « autre » avec un texte libre afin de laisser la possibilité à l'usager de cocher cette valeur si les autres valeurs ne correspondent pas à sa situation.

#### Import référentiel

Lorsque la liste de choix est trop grande, vous avez la possibilité d'intégrer un fichier de référentiel à importer en csv. L'usager ne verra que la première colonne présente dans le fichier. L'instructeur en revanche verra toutes les autres colonnes.

Le fichier ne doit pas contenir plus de 5000 lignes et doit peser maximum 1 Mo

### Choix multiple

Le principe est le même que le champ précédent à la différence que l'usager pourra sélectionner plusieurs valeurs simultanément.

À noter : lorsque plus de six champs sont ajoutés, le champ choix multiple est affiché sous forme de liste déroulante.

### Deux menus déroulants liés

Ce champ autorise un premier niveau de conditionnalité, c'est-à-dire que le contenu du second menu change en fonction du choix fait par l’usager dans le premier.

Exemple : si mon premier menu propose les choix A, B, C et que l’usager fait le choix B, un second menu déroulant apparaît avec les choix B1, B2, B3.

Pour l'utiliser, remplissez l'encadré « Liste déroulante » en suivant le modèle ci-dessous :

Les titres des menus déroulant liés doivent donc être encadrés par des doubles tirets "--" sans espace tandis que les choix du second menu doivent être laissés tels quels.

### Oui/Non

L'usager peut répondre « Oui » ou « Non » à la question posée dans le libellé du champ.

## Les champs relatifs aux référentiels externes

### L'annuaire de l'éducation

Il s'agit d'un référentiel spécifique de l’Éducation nationale permettant d'accéder aux caractéristiques et aux informations de contact des établissements de l'Éducation nationale grâce à son [API ](https://api.gouv.fr/les-api/api-annuaire-education)dédiée.

### RNA

Ce champ permet aux associations d'indiquer leurs numéros RNA. Les données liées aux numéros RNA seront alors automatiquement récupérées via l’API Répertoire des Associations (RNA).

### Carte

Du point de vue de l'administrateur, lorsque le champ "carte" est sélectionné, il peut choisir de faire figurer les informations suivantes:

* Unesco
* Arrêtés de protection
* Conservatoire du littoral
* Réserve nationales de chasse et faune sauvage
* Réserves biologiques
* Réserves naturelles
* Natura 2000
* Zones humides d'importance internationale
* ZNIEFF (La zone naturelle d’intérêt écologique, faunistique et floristique)
* Cadastres
* RPG (registre des parcelles graphiques)

Ce champ permet de faire appel à l’API géo. Sur un fond de carte, l’usager peut dessiner la localisation de son projet. Sont alors automatiquement ressortis les champs sélectionnés au préalable (Réserves naturelles, cadastres, etc) . Vous pouvez consulter le tutoriel dédié en cliquant [ici.](https://doc.demarches-simplifiees.fr/pour-aller-plus-loin/cartographie)

### Référentiel à configurer (avancé)

Nous vous renvoyons à la [documentation](/broken/pages/2GU4EMGbGK67PIG1TiFU) spécifique à ce type de champ.
