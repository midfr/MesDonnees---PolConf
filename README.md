
# Politique de confidentialité — MesDonnees

**MesDonnees ne collecte aucune donnée personnelle.**

## En résumé

MesDonnees est une application personnelle d'exploration de l'open data français. Elle **ne collecte aucune donnée personnelle**, **ne crée aucun profil**, **ne nécessite aucun compte** et **n'utilise aucun outil de mesure d'audience**. Toutes les données générées par votre utilisation restent stockées **uniquement sur votre appareil**.

## Données stockées sur l'appareil

- **Favoris** : titre, organisation et identifiant des jeux de données que vous épinglez (SwiftData).
- **Historique** : 20 derniers thèmes et 20 derniers jeux de données consultés, avec leur titre et la date de consultation.
- **Cache hors ligne** : copie des fichiers CSV que vous avez ouverts, stockée dans le dossier `Caches` de l'application. Permet de relire un jeu de données sans réseau.
- **Préférences d'affichage** : ordre et visibilité des colonnes, filtres saisis dans le tableau, sélection de tags — non synchronisés.

Toutes ces données sont supprimées si vous désinstallez l'application. Vous pouvez aussi les effacer manuellement depuis l'onglet **Historique** (cache + entrées d'historique) ou depuis l'onglet **Favoris** (glisser pour supprimer).

## Connexions réseau

### data.gouv.fr
**Finalité :** catalogue des thèmes / jeux de données, téléchargement des fichiers CSV.
**Contenu transmis :** aucune information identifiante. Les requêtes contiennent uniquement votre recherche, vos filtres et les identifiants de ressource.

### api-adresse.data.gouv.fr (Base Adresse Nationale)
**Finalité :** uniquement lorsque vous activez le filtre « Autour de moi ».
**Contenu transmis :** vos coordonnées GPS approximatives (précision ≈ 100 m) sont envoyées pour obtenir le code INSEE du département correspondant. Aucun identifiant utilisateur n'est joint à la requête.

## Localisation

Le filtre « Autour de moi » nécessite votre position. L'application demande l'autorisation **« Lorsque l'app est utilisée »**, ne récupère votre position **qu'au moment où vous activez le filtre**, et ne la conserve pas après la requête. Vous pouvez révoquer cette autorisation à tout moment depuis **Réglages → MesDonnees → Position**.

## Intelligence artificielle (résumé IA)

La génération du résumé en langage naturel utilise le framework **Foundation Models** d'Apple. Le modèle s'exécute **entièrement sur votre appareil** (Apple Intelligence). **Aucune donnée n'est envoyée à un serveur distant**, ni à Apple, ni à un tiers. Cette fonctionnalité n'est disponible qu'à partir d'iOS 26 sur les appareils éligibles à Apple Intelligence.

## Ce que nous ne faisons PAS

- Aucun compte utilisateur, aucune authentification.
- Aucun cookie, aucun identifiant publicitaire (IDFA).
- Aucun outil d'analytique tiers (Google Analytics, Firebase, Mixpanel, etc.).
- Aucun SDK de tracking ou de publicité.
- Aucune transmission de vos favoris ou de votre historique à un serveur.
- Aucune vente ni partage de données avec des tiers.

## Vos droits

Comme aucune donnée personnelle n'est collectée par l'application ni transmise à un tiers, il n'y a **rien à demander, à modifier ou à supprimer** auprès d'un responsable de traitement.

Pour les données publiées sur data.gouv.fr, adressez-vous directement à l'éditeur du jeu de données concerné (chaque fiche dataset l'identifie).

## Modifications de cette politique

Cette politique peut être mise à jour pour refléter les évolutions de l'application. La date ci-dessous sera actualisée à chaque modification substantielle.

**Dernière mise à jour : 25 juin 2026**
