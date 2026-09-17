# Localisation

## Adresse

L'usager doit entrer une adresse avec une auto-complétion - l'adresse se complète sans que l'usager n'ait besoin de l’écrire entièrement - grâce à la connexion à la Base Adresse Nationale (BAN).

<figure><img src="../../.gitbook/assets/image (194).png" alt=""><figcaption><p>Champ "adresse",en tant qu'usager</p></figcaption></figure>

## Communes, départements, régions, pays, EPCI

Ces types de champ sont des menus déroulants dont les valeurs sont préétablies. Il n'est pas possible de les modifier.

Le champ « Pays » comporte des pays qui ont existé dans le passé, ou dont la reconnaissance internationale est contestée, pour permettre à des usagers de répondre à la question « Quel est votre pays de naissance ? »

Les champs _Régions_, _Département_, _Communes_ et _EPCI_ utilisent des valeurs provenant de l’[API Géo](https://api.gouv.fr/les-api/api-geo). Il s’agit des régions, départements et communes de France métropolitaine et des DROM. Les communes des TOM ne sont donc pas incluses.

Pour le champ « Communes », les usagers doivent dans un premier temps entrer par auto-complétion leur département puis un second champ dédié à la commune s'affichera.

<figure><img src="../../.gitbook/assets/image (81).png" alt=""><figcaption><p>Champ "commune" , en tant qu'usager</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (83).png" alt=""><figcaption><p>Champ "commune", en tant qu'usager</p></figcaption></figure>

## Carte

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

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-10-28 à 10.24.08.png" alt=""><figcaption></figcaption></figure>

Ce champ permet de faire appel à l’API géo. Sur un fond de carte, l’usager peut dessiner la localisation de son projet. Sont alors automatiquement ressortis les champs sélectionnés au préalable (Réserves naturelles, cadastres, etc) . Vous pouvez consulter le tutoriel dédié en cliquant [ici.](https://doc.demarches-simplifiees.fr/pour-aller-plus-loin/cartographie)

<figure><img src="../../.gitbook/assets/image (100).png" alt=""><figcaption><p>Champ "Carte" en tant qu'usager</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Capture d’écran 2025-10-28 à 10.40.49.png" alt=""><figcaption></figcaption></figure>

