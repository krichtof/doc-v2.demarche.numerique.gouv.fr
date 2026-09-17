# Standard

## Texte court

Ce champ permet à l'usager de répondre de manière libre. Si le nombre de caractères est illimité, ce champ est adapté à une réponse courte.

<figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption><p>Champ "texte", en tant qu'usager</p></figcaption></figure>

## Texte long

Ce champ est similaire au précédent à la différence qu'il est adapté à une réponse longue et structurée. Le nombre de caractères est aussi illimité.

<figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption><p>Champ "texte long", en tant qu'usager</p></figcaption></figure>

## Nombre entier

L'usager doit renseigner un nombre entier.

<figure><img src="../../.gitbook/assets/image (46).png" alt=""><figcaption><p>Champ "nombre entier", en tant qu'usager</p></figcaption></figure>

## Nombre décimal

L'usager doit renseigner un nombre qui peut être décimal.

<figure><img src="../../.gitbook/assets/image (54).png" alt=""><figcaption><p>Champ "nombre décimal", en tant qu'usager</p></figcaption></figure>

## Champ formaté

Vous avez la possibilité de formater un champ selon le format de votre choix. Deux options s'offrent à vous:

* Le mode simple: vous pouvez formater un champ en choisissant le nombre de caractères que comportera ce champ, mais aussi s'il comporte des chiffres, des lettres et/ou des caractères spéciaux.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-03-07 à 17.58.48.png" alt=""><figcaption><p>Champ formaté en mode "choix simple"</p></figcaption></figure>

* Le mode avancé: vous pouvez formater un champ selon une expression régulière en définissant le nombre de caractères, l'ordre des caractères, etc. Attention, à n'utiliser que si vous êtes sur du format du champ car si le format renseigné par l'usager ne correpond pas à l'expression régulière, ce dernier ne pourra déposer le dossier.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-03-26 à 12.03.28.png" alt=""><figcaption><p>Champ formaté en mode "avancé"</p></figcaption></figure>

Voici le résultat en prévisualisant le formulaire

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-03-26 à 11.45.30.png" alt=""><figcaption></figcaption></figure>

Voici l'écran en cas d'erreur dans la saisie, bloquant le dépôt du dossier.

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-03-26 à 12.05.51.png" alt=""><figcaption></figcaption></figure>

## Date

L'usager doit renseigner une date au format jj/mm/aaaa.

<figure><img src="../../.gitbook/assets/image (91).png" alt=""><figcaption><p>Champ "date" , en tant qu'usager</p></figcaption></figure>

## Date et Heure

L'usager doit renseigner une date et un horaire.

<figure><img src="../../.gitbook/assets/image (45).png" alt=""><figcaption><p>Champ "date et heure" en tant qu'usager</p></figcaption></figure>

## Pièce à joindre

Ce champ permet à l'usager d'ajouter au dossier un document. La taille de chaque pièce justificative doit être inférieure à 200 Mo.\
Vous pouvez désormais choisir la nature de la pièce à joindre entre:

* **Relevé d'identité bancaire (RIB)** : Le contenu du fichier joint par l’usager sera analysé automatiquement afin de récupérer et retranscrire à l’instructeur les informations suivantes : **Nom du titulaire, Adresse du titulaire** (si présente sur le fichier), **IBAN, Code BIC, Nom de la banque**.
*   **Titre d'identité :** ce champ permet à l’usager de joindre une carte d'identité (uniquement le recto), passeport, titre de séjour ou autre justificatif d’identité. Formats acceptés : jpg/png, taille maximale : 20 Mo

    De plus, pour des raisons relatives au RGPD, le titre d'identité sera filigrané et automatiquement supprimé une fois le dossier terminé (faisant l'objet d'une décision finale).\
    À noter : le titre d’identité ne sera ni disponible dans les zip de dossiers, ni téléchargeable par API.
* **Non spécifié:** Tout autre document

<figure><img src="../../.gitbook/assets/Capture d’écran 2026-02-04 à 16.05.04.png" alt=""><figcaption></figcaption></figure>

Il est également possible de limiter la pièce à joindre à certains formats de fichier (visible au survol) et de paramétrer la suppression automatique de la pièce une fois le dossier instruit.

<figure><img src="../../.gitbook/assets/Capture d’écran 2026-02-04 à 16.40.42.png" alt=""><figcaption></figcaption></figure>

Vous avez la possibilité de joindre un modèle de pièce justificative que les usagers peuvent télécharger et remplir pour joindre à leur dossier. Cela est particulièrement utile dans les démarches impliquant par exemple l'utilisation de fichiers tableurs.

<figure><img src="../../.gitbook/assets/image (87).png" alt=""><figcaption><p>Champ "pièce justificative" avec modèle en tant qu'usager</p></figcaption></figure>

## Bloc répétable

Ce champ permet à l'usager de saisir un certain nombre de champs autant de fois qu'il le souhaite. Pour savoir comment l'utiliser, je vous invite à vous rendre sur la page dédiée en cliquant [ici](https://faq.demarches-simplifiees.fr/article/48-les-blocs-repetables).

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption><p>Exemple de "bloc répétable", en tant qu'usager</p></figcaption></figure>

## Lien vers un autre dossier

Ce type de champ donne la possibilité de relier deux dossiers déposés sur **demarche.numerique.gouv.fr** entre eux.

Exemple : je fais une demande de subvention en 2019 et en 2020, je dois en faire le bilan. En choisissant ce type de champ, l’usager indique seulement le numéro du dossier 2019 dans son dossier 2020, et l’instructeur peut alors accéder facilement à la demande grâce à un lien présent dans le bilan.

<figure><img src="../../.gitbook/assets/image (77).png" alt=""><figcaption><p>Champ "lien vers un autre dossier" en tant qu'usager</p></figcaption></figure>

Pour accéder au premier dossier déposé par l'usager, l'instructeur de la seconde démarche devra également être instructeur de la première démarche. Il lui suffira alors de cliquer sur le lien du dossier, comme ci-dessous :

<figure><img src="../../.gitbook/assets/image (141).png" alt=""><figcaption><p>Champ "lien vers un autre dossier", en tant qu'instructeur</p></figcaption></figure>
