# Fonds de réarmement agricole — suivi sur Démarche Numérique

Ce dépôt publie le suivi du déploiement du plan CASI (Climat, Adaptation, Sécheresse, Incendies) et de son fonds de réarmement agricole sur la plateforme Démarche Numérique : une carte des dossiers déposés par département et un tableau de suivi des démarches.

Site publié : https://emsnytech.github.io/dn-fonds-rearmement-agricole/

## Source

Extraction des démarches publiées sur [demarche.numerique.gouv.fr](https://demarche.numerique.gouv.fr/) au 16/10/2026, périmètre collectivités et quatre ministères dont l'agriculture (114 démarches dans l'extraction brute, 79 démarches retenues pour le plan CASI). Le rattachement territorial des démarches vient de l'export open data de data.gouv.fr (jeu de données `descriptif-des-demarches-publiees-sur-demarche-numerique-gouv-fr`, résolu le 7 octobre 2026).

## Limites

- Un dossier déposé n'est **ni instruit ni payé** : ces chiffres mesurent le dépôt, pas l'issue des demandes.
- **Aucun montant** n'est présent dans les sources utilisées.
- Cinq guichets ont leurs effectifs **figés au 7 octobre 2026** (non rafraîchis lors de l'extraction du 16/10) : Marne, Charente, Île-de-France, Ardèche, Somme.
- La **Martinique** est absente de la carte (`carte-dossiers.html`), qui ne couvre que la métropole ; ses dossiers restent comptés dans les totaux et dans le suivi des démarches (`suivi-demarches.html`).

## Licence

Les données sont publiées sous licence [Etalab 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/).
