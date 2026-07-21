# Politique de confidentialité — Ecole en Ligne

_Dernière mise à jour : juillet 2026_

## En résumé

L'application ne collecte rien. Aucune donnée ne quitte votre téléphone, sauf
pour se connecter au portail de votre établissement — exactement comme si vous
ouvriez son site dans un navigateur.

Il n'y a **aucun serveur intermédiaire**, aucun compte à créer chez nous,
aucune analyse d'usage, aucune publicité, aucun traceur.

## Ce qui est stocké, et où

Tout reste sur l'appareil.

| Donnée | Emplacement | Pourquoi |
|---|---|---|
| Identifiant et mot de passe du portail | Trousseau iOS (Keychain), chiffré par le système | La session du portail expire après ~10 minutes ; sans eux, il faudrait ressaisir le mot de passe en permanence |
| Cookies de session | Trousseau iOS | Maintenir la connexion entre deux écrans |
| Bulletins, absences, documents | Stockage local de l'application | Afficher les données sans réseau et éviter de re-télécharger à chaque ouverture |
| Préférence de thème | Stockage local | Se souvenir du mode clair ou sombre |

Les identifiants sont enregistrés avec l'option `WHEN_UNLOCKED_THIS_DEVICE_ONLY` :
ils ne sont accessibles que lorsque l'appareil est déverrouillé, et ne sont
jamais inclus dans une sauvegarde iCloud ni transférés vers un autre appareil.

## Qui reçoit vos données

Personne d'autre que le portail de votre établissement
(`www*.ecoleenligne.be`, le numéro dépendant de l'école choisie), auquel
l'application se connecte directement en HTTPS avec vos identifiants.

Nous ne recevons rien. Nous n'exploitons aucun serveur.

## Notifications

Les notifications sont **locales** : l'application compare les données du
portail avec la version précédente stockée sur l'appareil et affiche une alerte
si quelque chose a changé. Aucun jeton de notification distante n'est créé,
aucun message ne transite par un service tiers.

## Suppression

Le bouton **Déconnexion** efface immédiatement et définitivement :

- les identifiants du trousseau,
- les cookies de session,
- toutes les données mises en cache.

Désinstaller l'application produit le même effet.

## Enfants

L'application affiche des informations scolaires concernant des mineurs, mais
elle est destinée aux parents. Ces informations proviennent du portail de
l'établissement, en restent la propriété, et ne sont ni copiées ni transmises
ailleurs.

## Indépendance

Ecole en Ligne est une application indépendante. Elle **n'est ni éditée, ni
approuvée, ni affiliée** à eConcept sprl ou à tout autre éditeur du portail
EcoleEnLigne. Les marques citées appartiennent à leurs titulaires respectifs.

## Contact

Pour toute question : _(à compléter avant publication)_
