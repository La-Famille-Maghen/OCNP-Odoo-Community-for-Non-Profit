# OCNP — Odoo Community For Non Profit

**Un projet open source porté par La Famille Maghen pour aider les associations à réunir leurs principaux outils de gestion dans un environnement intégré, fondé sur Odoo Community. La version interne actuelle a été conçue et développée par MAGHEN NEGOU Rostant, le président de l'association.**

> [!IMPORTANT]
> **État du projet : première version en test interne.** OCNP n'est pas encore publié comme distribution stable et prête à installer. Le dépôt public est en cours de préparation. Les fonctionnalités, les modules complémentaires, les licences, la sécurité et la documentation doivent être vérifiés avant une première diffusion. Aucune date de publication n'est annoncée.

<p align="center">
  <img src="https://maghen.fr/assets/img/lfm-ocnp-odoo-community-for-non-profit.webp" alt="OCNP — Odoo Community For Non Profit" width="600" />
</p>

<p align="center">
  <strong>Unir pour bâtir, ensemble pour toujours.</strong><br>
  <em>Solidarité · Travail · Développement</em>
</p>

---

## OCNP en bref

| | |
|---|---|
| **Nom** | Odoo Community For Non Profit (OCNP) |
| **Porteur** | La Famille Maghen (LFM), association loi 1901 à but non lucratif |
| **Socle technique visé** | Odoo Community 19.0 |
| **Public prioritaire** | Associations françaises, quelle que soit leur taille |
| **Langue de la première version** | Français |
| **Objectif** | Une solution de gestion associative intégrée, librement déployable et documentée |
| **Mode d'utilisation visé** | Auto-hébergement sur l'infrastructure choisie par l'association |
| **Statut** | Première version en test interne ; pas encore de version stable publique |
| **Code source** | La distribution publique est en préparation dans ce dépôt |
| **Contact** | [contact@maghen.eu](mailto:contact@maghen.eu) |

## Sommaire

- [Présentation complète du projet](./docs/OCNP_presentation_publique_complete.md)
- [Pourquoi OCNP ?](#pourquoi-ocnp-)
- [Genèse du projet](#genèse-du-projet)
- [Ce qu'OCNP veut couvrir](#ce-quocnp-veut-couvrir)
- [Notre méthode : le besoin associatif, le socle Odoo](#notre-méthode--le-besoin-associatif-le-socle-odoo)
- [Architecture et principes techniques](#architecture-et-principes-techniques)
- [État d'avancement](#état-davancement)
- [Installation et utilisation](#installation-et-utilisation)
- [Contribuer au projet](#contribuer-au-projet)
- [Qui porte OCNP ?](#qui-porte-ocnp-)
- [Sécurité et protection des données](#sécurité-et-protection-des-données)
- [Licence et marques](#licence-et-marques)
- [Questions fréquentes](#questions-fréquentes)
- [Contact et liens](#contact-et-liens)

---

## Pourquoi OCNP ?

Les associations assurent des missions très diverses : accueillir des adhérents, mobiliser des bénévoles, collecter des dons, gérer des cotisations, répondre à des appels à projets, suivre des subventions, organiser des événements, tenir leur comptabilité et conserver leurs documents.

Pour beaucoup de structures, ces activités sont suivies au moyen d'une juxtaposition de tableurs, de formulaires, de boîtes mail et de services spécialisés. Cette organisation peut entraîner des ressaisies, une dispersion de l'information, des difficultés de coordination et une dépendance à plusieurs fournisseurs.

Les associations n'ont pas toutes les mêmes moyens humains, financiers ou numériques. Les outils de gestion intégrés peuvent être coûteux à déployer ou demander un accompagnement technique important. À l'inverse, les outils simples et spécialisés ne couvrent parfois qu'une partie des besoins.

**OCNP cherche à apporter une autre possibilité : un environnement de gestion associative construit sur un ERP libre et modulaire, avec une priorité donnée aux fonctionnalités existantes, aux modules communautaires et à la maîtrise de l'installation et des données.**

OCNP ne prétend pas être la seule solution possible ni convenir à toutes les associations. Le choix d'un outil dépend de la taille de la structure, de ses activités, de ses compétences et de ses contraintes. Notre objectif est de proposer une alternative supplémentaire aux associations qui recherchent une solution intégrée fondée sur Odoo Community.

## Genèse du projet

### Un besoin concret au sein de La Famille Maghen

OCNP est d'abord né d'un besoin interne de La Famille Maghen : disposer d'un environnement de gestion adapté à ses propres activités associatives et préparer notamment l'organisation de ses futurs recrutements de bénévoles.

La version interne actuelle a été conçue et développée initialement par **MAGHEN NEGOU Rostant**, pour répondre à ce besoin. Le choix s'est porté sur Odoo Community 19, dont les fonctionnalités ont été étudiées, paramétrées et, lorsque cela était nécessaire, complétées par des modules de l'écosystème communautaire.

### D'un outil interne à un projet ouvert

En échangeant avec d'autres responsables associatifs, LFM a retrouvé des difficultés comparables : des outils dispersés, des besoins transversaux et la difficulté de trouver une solution unique qui réponde à l'ensemble de leurs activités.

Puisque la solution avait déjà dû être conçue pour les besoins de LFM, l'association a souhaité transformer progressivement ce travail en un projet open source public. L'objectif est de permettre à d'autres associations d'en bénéficier, de l'évaluer, de l'adapter dans le respect de sa licence et, à terme, de participer à son amélioration.

La version interne constitue un point de départ, et non une distribution publique prête à l'emploi. Le passage à une version publique exige un travail spécifique de vérification, de nettoyage des dépôts, de documentation, de tests, de clarification des licences et de préparation d'une installation reproductible.

## Ce qu'OCNP veut couvrir

OCNP vise à réunir les principaux besoins de gestion d'une association dans un environnement cohérent. Le périmètre fonctionnel envisagé pour la première version est présenté ci-dessous. **Il s'agit d'objectifs fonctionnels en cours de vérification, et non d'une liste de fonctions toutes disponibles et validées dans le dépôt à ce jour.**

| Besoin associatif | Objectif fonctionnel | État de vérification |
|---|---|---|
| **Dons ponctuels** | Enregistrer et suivre les dons, avec un parcours adapté aux usages associatifs | Paramétrage d'une fonction e-commerce envisagé ; à valider dans Community 19 |
| **Dons réguliers** | Suivre les engagements périodiques, les échéances et les interruptions | Module complémentaire à identifier et vérifier pour la version 19.0 |
| **Cotisations et adhésions** | Gérer les cotisations, les renouvellements et le suivi des adhérents | Fonctionnalité et module à confirmer dans l'environnement Community 19 |
| **Subventions** | Suivre un dossier de la demande au versement et aux justificatifs | Appui envisagé sur les projets et la comptabilité analytique ; cadrage à finaliser |
| **Bénévolat** | Organiser les projets, missions, tâches et disponibilités | Réutilisation envisagée des fonctions de gestion de projet ; scénarios à tester |
| **Stages et conventions** | Suivre les dossiers, documents, échéances et bilans | Paramétrage à confirmer à partir des fonctions disponibles |
| **Événements et boutique** | Gérer les événements, inscriptions et ventes associatives | Disponibilité des modules et limites Community à vérifier |
| **Comptabilité associative** | Répondre aux besoins comptables et de suivi financier des associations françaises | Exigences et modules complémentaires à confirmer à partir du cahier de paramétrage interne |
| **Signature électronique** | Faire signer des documents et conserver les éléments de traçabilité utiles | Exigences, module et portée probatoire à confirmer à partir du cahier de paramétrage interne |

### Une précision importante sur Odoo Community

Odoo Community et Odoo Enterprise ne proposent pas exactement le même périmètre fonctionnel. Une application ou une fonction documentée dans l'écosystème Odoo n'est donc pas nécessairement disponible dans l'édition Community.

OCNP s'interdit de présenter une fonctionnalité Enterprise comme une fonctionnalité native Community. Pour chaque besoin, le projet doit identifier le module réellement utilisé, son origine, sa version, sa licence, ses dépendances et les tests permettant de confirmer son fonctionnement.

OCNP n'est pas un cabinet d'expertise comptable, un cabinet juridique ou un conseil fiscal. Le logiciel peut faciliter l'organisation et le suivi ; chaque association demeure responsable de ses obligations et de la validation de ses procédures par les professionnels compétents.

## Notre méthode : le besoin associatif, le socle Odoo

Notre philosophie est simple : **c'est à l'organisation humaine de s'adapter autant que possible à l'ERP, et non à l'ERP de se plier à chaque organisation par des personnalisations difficiles à maintenir.**

Nous voulons tirer le meilleur parti du logiciel existant avant d'ajouter du code. Pour chaque besoin, l'ordre de priorité est le suivant :

1. **Fonctionnalités natives d'Odoo Community** : paramétrer et réutiliser le socle officiel, y compris en détournant intelligemment certaines fonctions lorsque leur logique s'y prête.
2. **Modules de l'Odoo Community Association (OCA)** : compléter le socle avec des modules libres communautaires lorsque le natif ne suffit pas.
3. **Modules gratuits tiers** : retenir uniquement des modules dont la licence, la compatibilité, la qualité, les dépendances et la maintenance sont vérifiables.
4. **Développement spécifique en ultime recours** : ne créer un module propre à OCNP que lorsqu'aucune solution précédente ne répond à un besoin indispensable, notamment lorsqu'une exigence réglementaire ou juridique le rend nécessaire. Un tel module devra être documenté, testé, maintenu et publié selon les règles du projet.

Les détournements de fonctions sont assumés lorsqu'ils restent compréhensibles et sûrs. Par exemple, un produit e-commerce peut être présenté à l'utilisateur comme un **« Don »** ou une **« Cotisation annuelle »**, si le paramétrage et les traitements associés sont correctement vérifiés. Le libellé doit parler le langage de l'association ; la documentation doit expliquer le fonctionnement réel et ses limites.

## Architecture et principes techniques

### Un socle officiel, sans modification du cœur

- Socle visé pour la première version : **Odoo Community 19.0**.
- Aucun patch du cœur Odoo n'est prévu.
- Pas de copie d'un module cœur pour le modifier localement.
- Les extensions doivent privilégier les mécanismes prévus par Odoo : paramétrage, héritage, modules séparés et interfaces documentées.
- Les dépendances doivent être recensées et suivies.

L'absence de modification du cœur facilite la maintenance, mais ne garantit pas automatiquement la compatibilité de l'ensemble. Les modules complémentaires, vues, intégrations, données et procédures doivent être testés à chaque changement de version. Aucune compatibilité future n'est promise avant vérification.

### Une distribution publique construite proprement

La version publique ne doit pas être obtenue en publiant une copie de la base de production de LFM après une simple suppression manuelle des informations sensibles.

L'objectif est de construire une distribution reproductible à partir des dépôts de code, des modules et du paramétrage générique versionnés, avec une base de démonstration créée spécifiquement et contenant uniquement des données synthétiques.

Le processus de publication devra inclure notamment :

- la vérification des droits sur le code, le thème, la documentation et les autres ressources ;
- l'inventaire des modules et dépendances ;
- la vérification des licences des composants ;
- la construction depuis un environnement propre ;
- des données de démonstration fictives ;
- des tests d'installation et de non-régression ;
- des contrôles de sécurité et de détection de secrets ;
- une revue avant publication et un journal de version.

### Données fictives et personnalisation

La distribution pourra proposer un jeu de démonstration représentant une association fictive : identité, coordonnées, projets, produits, profils et opérations d'exemple. Ces données devront être clairement identifiées comme fictives et faciles à remplacer.

Le thème graphique de la version interne — notamment sa palette brique terre cuite — fait partie des éléments envisagés pour la distribution. Il devra être isolé, documenté et vérifié comme composant du projet avant publication.

### Sécurité et protection des données

OCNP est conçu pour être installé sur l'infrastructure choisie par l'association utilisatrice. L'auto-hébergement donne la maîtrise du lieu d'installation, mais ne rend pas automatiquement l'instance sûre ou conforme.

Les principes de sécurité visés comprennent :

- des rôles et droits d'accès suivant le principe du moindre privilège ;
- la protection des secrets et identifiants d'exploitation ;
- l'absence de secrets et de données personnelles réelles dans les dépôts ou les distributions publiques ;
- des connexions sécurisées et une authentification adaptée ;
- des sauvegardes régulières et des tests de restauration ;
- une politique de mises à jour et de traitement des vulnérabilités ;
- une documentation des responsabilités de l'association qui exploite sa propre instance.

L'association utilisatrice reste responsable de la configuration, de l'hébergement, des accès, des sauvegardes, des mises à jour et des traitements de données qu'elle met en œuvre.

## État d'avancement

**La première version est actuellement en test interne au sein de La Famille Maghen.** Le dépôt GitHub public sert à préparer l'ouverture du projet ; il ne constitue pas encore une version stable installable.

Les grandes étapes envisagées sont les suivantes :

1. **Inventorier l'existant** : modules, paramétrages, dépendances, fonctions, licences et limites.
2. **Vérifier les composants** : disponibilité réelle dans Odoo Community 19.0, compatibilité des modules OCA et tiers, tests fonctionnels.
3. **Clarifier le cadre de publication** : licences, droits de contribution, attribution, documentation et règles de sécurité.
4. **Construire une distribution propre** : code versionné, données fictives, installation reproductible et contrôles automatisés.
5. **Documenter et tester** : installation vierge, parcours associatifs, non-régression, accessibilité et sécurité.
6. **Ouvrir les essais à des associations pilotes** : retours d'utilisation, corrections et amélioration de la documentation.
7. **Publier une première version** lorsque les conditions techniques, juridiques et documentaires seront réunies.

Aucune date de publication n'est annoncée. Le projet préfère une diffusion vérifiée et documentée à une mise à disposition prématurée.

## Installation et utilisation

### Le projet n'est pas encore prêt à être installé

À ce stade, le dépôt ne contient pas encore une distribution complète, stable et accompagnée d'une procédure d'installation. Les instructions d'installation seront ajoutées lorsque les composants, dépendances et procédures auront été vérifiés.

Merci de ne pas utiliser la version interne de LFM en production dans une autre organisation et de ne pas considérer la présente page comme une garantie de fonctionnement.

### Le modèle d'utilisation visé

L'objectif est de proposer une solution librement téléchargeable et utilisable en auto-hébergement, sur un serveur administré par l'association ou par l'hébergeur de son choix. L'association garde ainsi la maîtrise de son environnement et de ses données.

L'usage du logiciel en auto-hébergement est destiné à être gratuit. Cela ne signifie pas que l'exploitation d'une instance est sans coût : hébergement, nom de domaine éventuel, sauvegardes, supervision, maintenance, mises à jour et accompagnement peuvent nécessiter du temps ou des dépenses.

## Contribuer au projet

OCNP est aujourd'hui à un stade précoce de son ouverture publique. Le projet a besoin de compétences diverses : la qualité d'un ERP associatif ne repose pas uniquement sur le développement logiciel.

### Profils et contributions recherchés

| Profil | Exemples de contributions |
|---|---|
| **Développeurs Python / Odoo** | Analyse des modules, paramétrage, extensions, corrections et tests automatisés |
| **Spécialistes Odoo Community / OCA** | Vérification des modules, dépendances, licences, branches et compatibilités |
| **Infrastructure et DevOps** | Environnements de test, conteneurisation, CI/CD, sauvegardes, supervision et construction reproductible |
| **Testeurs et QA** | Scénarios de test, recette fonctionnelle, tests de non-régression et signalement des anomalies |
| **UI/UX et accessibilité** | Ergonomie, cohérence de l'interface, responsive design et accessibilité |
| **Rédacteurs et formateurs** | Documentation d'installation, guides utilisateurs, tutoriels et FAQ |
| **Juristes et spécialistes RGPD** | Licences, droits d'auteur, accords de contribution, protection des données et conformité |
| **Comptables et gestionnaires associatifs** | Validation des besoins, scénarios comptables, suivi des dons, cotisations et subventions |
| **Associations pilotes** | Essais d'installation, retours métiers, tests en conditions réelles et priorisation des besoins |

### Notre manière de travailler

- Les missions doivent être décrites avec un objectif, un périmètre et des critères de validation compréhensibles.
- Les contributions sont volontaires et les disponibilités sont choisies librement.
- Chaque contribution doit respecter les règles de licence, de sécurité et de confidentialité du projet.
- Les changements proposés sont relus avant leur intégration.
- Les retours d'usage des personnes non développeuses sont essentiels : ils permettent de vérifier que la solution répond réellement aux pratiques associatives.

**La participation au projet est bénévole et ne constitue aucune promesse d'emploi, de mission rémunérée ou de résultat professionnel.** Une attestation pourra, selon les modalités de LFM, décrire les contributions réellement effectuées. Une mention publique du contributeur est facultative et nécessite son accord.

### Comment manifester son intérêt

Pour proposer votre aide, indiquez :

1. votre domaine de compétence ;
2. le type de contribution qui vous intéresse ;
3. vos disponibilités approximatives ;
4. les sujets ou tâches sur lesquels vous souhaiteriez travailler.

Contact : [contact@maghen.eu](mailto:contact@maghen.eu). Les demandes de contribution et les issues publiques seront organisées progressivement à mesure que les règles de contribution et les premiers lots de travail seront publiés.

### Contribuer sans programmer

Il est possible d'aider sans écrire de code : tester les parcours, décrire les besoins de son association, relever les difficultés de compréhension, relire les guides, vérifier les libellés, proposer des scénarios comptables ou participer à l'évaluation de l'accessibilité.

## Qui porte OCNP ?

### La Famille Maghen

**La Famille Maghen (LFM)** est une association loi 1901 à but non lucratif, reconnue de l'Économie Sociale et Solidaire (ESS) et signataire de la Charte de la Diversité.

Elle s'appuie sur son **Laboratoire d'Innovation Familiale (LIF)**, qui conçoit et développe des solutions solidaires d'inclusion sociale et de lutte contre la fracture numérique. OCNP s'inscrit dans cette démarche aux côtés d'autres projets portés par LFM, dont e-PhotoID Express, Lien Social et Afrik Digital.

La version actuelle d'OCNP a été réalisée initialement par MAGHEN NEGOU Rostant pour un besoin interne de LFM. Son ouverture vise à en faire progressivement un projet collectif, documenté et accessible à la communauté associative et technique.

### Une organisation pluridisciplinaire

LFM s'organise autour de cinq Divisions. La **DINIS** assure le pilotage technique d'OCNP ; les autres expertises contribuent aux besoins fonctionnels, à la conformité et à l'expérience des utilisateurs.

- **DINIS — Division de l'Ingénierie Numérique et de l'Innovation Sociale** : infrastructure, réseau et cloud ; développement logiciel ; intelligence artificielle ; UI/UX ; test et assurance qualité ; gestion de projet IT.
- **DRH — Division des Ressources Humaines** : recrutement et gestion des talents ; formation et développement des compétences ; relations sociales et juridique RH ; santé, sécurité et qualité de vie au travail.
- **DAJCP — Division des Affaires Juridiques, du Contentieux et des Partenariats** : affaires juridiques et vie associative ; contentieux et assurances ; partenariats et contractualisation ; commande privée, publique et subventions ; éthique et conformité RGPD.
- **DAF — Division de l'Administration et des Finances** : comptabilité et fiscalité ; contrôle de gestion, budget, trésorerie et financement ; achats, moyens généraux et logistique.
- **DRIDP — Division des Relations Institutionnelles, Donateurs et Partenariats** : relation donateurs et collecte ; relations institutionnelles et subventions publiques ; partenariats avec les entreprises, fondations et mécènes.

La feuille de route d'OCNP relève de La Famille Maghen, selon les règles de gouvernance de l'association. Les suggestions et contributions externes sont encouragées ; elles ne remplacent pas le processus de décision du projet.

## Sécurité et protection des données

La sécurité est une responsabilité partagée entre le projet logiciel et l'organisation qui exploite une installation.

- **Dans ce dépôt :** ne publiez jamais de mot de passe, jeton, clé privée, donnée personnelle ou information confidentielle.
- **Dans les issues :** utilisez des données fictives pour reproduire un problème. Ne joignez pas de données de production.
- **Pour un problème de sécurité :** ne publiez pas les détails exploitables dans une issue publique ; contactez [contact@maghen.eu](mailto:contact@maghen.eu) en précisant qu'il s'agit d'un signalement de sécurité.
- **Dans votre installation :** appliquez les mises à jour, limitez les privilèges, protégez les accès et testez vos sauvegardes.

Les instructions détaillées de signalement et de traitement des vulnérabilités seront publiées dans une politique `SECURITY.md` avant la première diffusion stable.

## Licence et marques

Le dépôt comporte un fichier [`LICENSE`](./LICENSE), que GitHub identifie actuellement comme **GPL-3.0**. Consultez ce fichier pour connaître les conditions déclarées pour les éléments du projet qu'il couvre. Ce marqueur ne dispense pas LFM de finaliser l'inventaire juridique de la distribution avant sa première publication.

Les dépendances et composants tiers — notamment Odoo Community, les modules OCA et les autres bibliothèques — peuvent être distribués sous des licences différentes. Chaque composant doit être identifié, sa compatibilité examinée et les mentions requises conservées. La présence d'un fichier `LICENSE` à la racine ne signifie pas que tous les composants tiers sont placés sous cette même licence.

**Odoo** est une marque d'Odoo S.A. OCNP est un projet de La Famille Maghen ; il n'est ni édité, ni sponsorisé, ni approuvé par Odoo S.A. L'utilisation du nom « Odoo » sert uniquement à décrire le socle logiciel sur lequel le projet est construit.

## Questions fréquentes

### OCNP est-il déjà disponible au téléchargement ?

Non. La première version est en test interne. Le dépôt public prépare l'ouverture du projet ; aucune distribution stable installable n'est publiée à ce stade.

### OCNP est-il gratuit ?

L'objectif est une distribution librement accessible et gratuite à utiliser en auto-hébergement. L'hébergement, l'administration, les sauvegardes, la maintenance et l'accompagnement éventuel restent à la charge de l'association qui exploite l'instance.

### Est-ce une version d'Odoo Enterprise ?

Non. Le socle visé est Odoo Community 19.0. OCNP ne doit pas intégrer de code Enterprise ni présenter des fonctions réservées à Enterprise comme des fonctions natives de Community.

### OCNP modifie-t-il le cœur d'Odoo ?

Non. Le principe est de conserver le cœur officiel et de privilégier le paramétrage, les modules distincts et les extensions compatibles.

### Toutes les fonctionnalités sont-elles déjà disponibles ?

Non. Les besoins fonctionnels sont identifiés, mais la disponibilité et le fonctionnement de chaque module doivent être vérifiés pour Odoo Community 19.0. Le tableau de périmètre de ce README indique l'état de vérification connu.

### Faut-il être développeur pour contribuer ?

Non. Les tests, retours d'utilisation, la documentation, l'accessibilité, les analyses fonctionnelles, comptables et juridiques sont également utiles.

### Peut-on installer OCNP sans compétences techniques ?

L'installation et la maintenance d'Odoo nécessitent des compétences techniques. Une documentation destinée aux associations non techniques est prévue, mais elle ne remplace pas l'administration d'un serveur ni l'accompagnement d'une personne compétente.

### OCNP garantit-il la conformité comptable, fiscale ou RGPD de mon association ?

Non. OCNP vise à fournir des outils de gestion et de suivi. Chaque association demeure responsable de ses obligations et doit faire valider ses procédures par les professionnels compétents.

### Quand la première version sera-t-elle publiée ?

Aucune date n'est annoncée. La publication dépendra de la réussite des vérifications techniques, juridiques, de sécurité et de documentation.

### Qui décide de la feuille de route ?

La Famille Maghen, selon la gouvernance de l'association. La communauté peut proposer des évolutions, signaler des défauts et contribuer à leur réalisation.

## Contact et liens

- **Dépôt GitHub :** [La-Famille-Maghen/OCNP-Odoo-Community-for-Non-Profit](https://github.com/La-Famille-Maghen/OCNP-Odoo-Community-for-Non-Profit)
- **Organisation :** [La Famille Maghen sur GitHub](https://github.com/La-Famille-Maghen)
- **Site web :** [https://maghen.eu](https://maghen.eu)
- **Contact :** [contact@maghen.eu](mailto:contact@maghen.eu)
- **Mentions légales :** [https://maghen.eu/mentions-legales/](https://maghen.eu/mentions-legales/)
- **Présentation complète :** [docs/OCNP_presentation_publique_complete.md](./docs/OCNP_presentation_publique_complete.md)
- **Contribuer :** [CONTRIBUTING.md](./CONTRIBUTING.md)
- **Code de conduite :** [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
- **Sécurité :** [SECURITY.md](./SECURITY.md)
- **Odoo Community Association (OCA) :** [https://odoo-community.org/](https://odoo-community.org/)
- **Documentation Odoo 19.0 :** [https://www.odoo.com/documentation/19.0/](https://www.odoo.com/documentation/19.0/)

---

<p align="center">
  <strong>OCNP — Odoo Community For Non Profit</strong><br>
  Un projet de La Famille Maghen<br>
  <em>Solidarité · Travail · Développement</em>
</p>
