# OCNP — Odoo Community For Non Profit

> **Un projet open source au service des associations : rapprocher les outils de gestion dans un environnement intégré, fondé sur Odoo Community.**
>
> **Statut du projet — novembre 2026 : première version en test interne au sein de La Famille Maghen.** Le projet n'est pas encore ouvert au téléchargement public. Aucune date de publication n'est annoncée. La priorité est de vérifier les fonctions, les dépendances, la sécurité, les droits de diffusion et la documentation avant toute mise à disposition.

**OCNP** est un projet de La Famille Maghen (LFM), association loi 1901 à but non lucratif, reconnue de l'Économie Sociale et Solidaire (ESS) et signataire de la Charte de la Diversité.

- **Projet :** Odoo Community For Non Profit (OCNP)
- **Socle technique visé :** Odoo Community 19.0
- **Public prioritaire :** associations françaises, quelle que soit leur taille
- **Langue de la première version :** français
- **Mode de diffusion visé :** code source ouvert, sous une licence libre qui sera précisée avant la première publication
- **Mode d'utilisation visé :** installation sur l'infrastructure choisie par chaque association (auto-hébergement)
- **État actuel :** première version en test interne
- **Porteur :** La Famille Maghen — Laboratoire d'Innovation Familiale (LIF)
- **Contact :** [contact@maghen.eu](mailto:contact@maghen.eu)
- **GitHub :** [https://github.com/La-Famille-Maghen/OCNP-Odoo-Community-for-Non-Profit/](https://github.com/La-Famille-Maghen/OCNP-Odoo-Community-for-Non-Profit/)
---

## En un coup d'œil : les 5 questions essentielles

| Question | Réponse |
|---|---|
| **Quoi ?** | Un projet de solution de gestion associative intégrée, construite sur Odoo Community 19 et adaptée aux besoins des associations. |
| **Pourquoi ?** | Pour aider les associations à réduire la dispersion de leurs outils, à mieux organiser leurs activités et à conserver la maîtrise de leur logiciel et de leurs données. |
| **Pour qui ?** | Les associations françaises, leurs dirigeants, bénévoles, équipes administratives et financières, ainsi que les personnes et organisations qui souhaitent contribuer à un logiciel utile au secteur associatif. |
| **Qui porte le projet ?** | La Famille Maghen. La version interne actuelle a été conçue et développée par MAGHEN NEGOU Rostant, le président de l'association. |
| **Où en est-on ?** | La première version est testée en interne. La publication publique interviendra après les vérifications techniques, juridiques, de sécurité et de documentation. |

## Sommaire

1. [La genèse du projet](#1-la-genèse-du-projet)
2. [Le besoin auquel OCNP veut répondre](#2-le-besoin-auquel-ocnp-veut-répondre)
3. [La vision, la mission et les objectifs](#3-la-vision-la-mission-et-les-objectifs)
4. [À qui s'adresse OCNP ?](#4-à-qui-sadresse-ocnp-)
5. [Ce qu'OCNP ambitionne de couvrir](#5-ce-quocnp-ambitionne-de-couvrir)
6. [Le choix d'Odoo Community](#6-le-choix-dodoo-community)
7. [Les principes de conception et de développement](#7-les-principes-de-conception-et-de-développement)
8. [Architecture, sécurité, données et protection de la vie privée](#8-architecture-sécurité-données-et-protection-de-la-vie-privée)
9. [Gouvernance et organisation du projet](#9-gouvernance-et-organisation-du-projet)
10. [La Famille Maghen, porteuse du projet](#10-la-famille-maghen-porteuse-du-projet)
11. [Où se déroule le projet et comment l'utiliser ?](#11-où-se-déroule-le-projet-et-comment-lutiliser-)
12. [Calendrier, étapes et état d'avancement](#12-calendrier-étapes-et-état-davancement)
13. [Gratuité, coûts et limites de responsabilité](#13-gratuité-coûts-et-limites-de-responsabilité)
14. [Contribuer à OCNP](#14-contribuer-à-ocnp)
15. [Demande de bénévoles développeurs via GitHub for Nonprofits](#15-demande-de-bénévoles-développeurs-via-github-for-nonprofits)
16. [Transparence : ce qu'OCNP ne promet pas](#16-transparence-ce-quocnp-ne-promet-pas)
17. [Questions fréquentes](#17-questions-fréquentes)
18. [À propos de La Famille Maghen](#18-à-propos-de-la-famille-maghen)
19. [Glossaire](#19-glossaire)
20. [Ressources et sources](#20-ressources-et-sources)

---

# 1. La genèse du projet

## 1.1. À l'origine : un besoin concret de La Famille Maghen

OCNP n'est pas né d'une étude théorique ni d'une idée de logiciel conçue sans utilisateur. Le projet trouve son origine dans un besoin opérationnel rencontré par La Famille Maghen : disposer d'un environnement de gestion suffisamment structuré pour suivre ses activités associatives et préparer notamment ses futurs recrutements de bénévoles.

Comme de nombreuses associations, LFM devait articuler plusieurs fonctions : les candidatures et dossiers de bénévolat, les missions et les tâches, les projets, les relations avec les membres et partenaires, les activités administratives et financières, ainsi que la production et le suivi de documents.

La recherche d'une solution adaptée a conduit à retenir **Odoo Community 19** comme socle. La version interne actuelle a ensuite été conçue et développée par **MAGHEN NEGOU Rostant**, seul, pour répondre au besoin de LFM. Le travail a consisté à exploiter autant que possible les fonctionnalités déjà disponibles dans Odoo Community, à les paramétrer pour les usages associatifs et à étudier les compléments nécessaires lorsque le socle ne suffisait pas.

Cette origine est importante : la première version d'OCNP s'appuie sur une solution qui a été élaborée pour répondre à un besoin réel de l'association porteuse. Le projet public ne part donc pas d'une page blanche ; il vise à transformer progressivement cet existant interne en une distribution open source propre, documentée, vérifiable et réutilisable.

## 1.2. Du besoin de LFM à un besoin partagé

Au fil des échanges avec d'autres responsables associatifs, un constat s'est précisé : les difficultés rencontrées par LFM ne lui sont pas propres. Beaucoup d'associations doivent combiner plusieurs outils pour gérer les dons, les cotisations, les adhésions, les subventions, les événements, les bénévoles, les documents et la comptabilité.

Cette dispersion peut entraîner des ressaisies, des informations éparpillées, une visibilité partielle sur l'activité et une dépendance à plusieurs fournisseurs ou services. Elle peut également compliquer la transmission des tâches lorsque les responsabilités changent ou lorsqu'un bénévole quitte l'association.

LFM n'en déduit pas qu'aucune solution associative n'existe. Des logiciels libres, des plateformes spécialisées et des outils commerciaux répondent déjà à différents besoins. Le constat est plus précis : **la solution recherchée par LFM devait couvrir un ensemble étendu de fonctions, rester librement déployable et permettre à l'association de conserver la maîtrise de son environnement.** Les solutions étudiées n'ont pas répondu de manière satisfaisante à l'ensemble de ce besoin interne.

## 1.3. Pourquoi ouvrir le projet ?

Puisque la solution devait de toute façon être conçue pour répondre aux besoins de LFM, l'association a souhaité aller au-delà d'un usage exclusivement interne.

L'idée est de transformer cet investissement en un projet open source public afin que d'autres associations puissent, à terme :

- accéder à une solution de gestion sans licence logicielle payante liée à l'utilisation du code publié ;
- l'installer sur l'infrastructure de leur choix ;
- adapter son paramétrage à leur fonctionnement et à leur organisation ;
- examiner le code et les modules utilisés ;
- contribuer à son amélioration ;
- bénéficier des corrections et améliorations que la communauté pourra produire et documenter.

L'ouverture du projet doit aussi permettre de mutualiser les efforts : plutôt que chaque association reconstruise isolément les mêmes mécanismes, les contributions utiles pourront être partagées dans le respect de la licence qui sera retenue.

## 1.4. Une démarche progressive et transparente

La version actuelle n'est pas présentée comme un produit achevé. Elle constitue une première base fonctionnelle en test interne. Plusieurs fonctionnalités, modules complémentaires, règles comptables et mécanismes de signature doivent encore être vérifiés et documentés avant une diffusion publique.

LFM préfère prendre le temps de vérifier ce qui est effectivement disponible dans Odoo Community 19, d'identifier précisément les modules tiers et leurs licences, de construire une distribution propre et de rédiger une documentation exploitable plutôt que d'annoncer trop tôt une solution supposée complète.

**L'ambition est collective et publique ; la responsabilité de publier un logiciel fiable impose une progression rigoureuse.**

---

# 2. Le besoin auquel OCNP veut répondre

## 2.1. Un tissu associatif important, souvent animé par des bénévoles

Les associations jouent un rôle essentiel dans la vie sociale, culturelle, éducative, sportive, humanitaire et citoyenne. Elles mobilisent des bénévoles, des salariés, des partenaires, des donateurs et des institutions. Leur fonctionnement quotidien nécessite pourtant des outils de gestion adaptés à leurs moyens.

Quelques repères publics permettent de situer l'enjeu :

- **Environ 1,6 million d'associations étaient actives en France en 2025.** Les données relayées par [Recherches & Solidarités](https://www.francegenerosites.org/ressources/la-france-associative-en-mouvement-recherches-et-solidarites-2025/) indiquent également qu'environ neuf associations sur dix fonctionnent sans salarié.
- **En 2026, environ 25 % des Français déclarent donner du temps à une ou plusieurs associations**, soit une estimation de 13 à 13,5 millions de bénévoles, selon [l'étude La France bénévole 2026](https://www.francegenerosites.org/ressources/la-france-benevole-2026-recherches-et-solidarites/). Les formes d'engagement sont diverses : certaines personnes interviennent ponctuellement, d'autres régulièrement.
- **Le numérique est déjà utilisé dans la gestion associative.** L'[étude 2025 de Solidatech et Recherches & Solidarités](https://www.solidatech.fr/ressources/etude-la-place-du-numerique-dans-le-projet-associatif-en-2025/), fondée sur une enquête auprès de 2 285 responsables associatifs, indique que 70 % des associations interrogées utilisent le numérique pour gérer plus efficacement leurs activités. Toutefois, près de 70 % déclarent encore rencontrer des obstacles numériques, notamment humains, techniques, financiers ou stratégiques.
- **Les difficultés numériques concernent aussi le grand public.** Selon l'[Insee](https://www.insee.fr/fr/statistiques/8739245), en 2025, 34 % des personnes âgées de 16 à 74 ans n'utilisent pas Internet ou ne disposent pas des notions de base dans au moins l'un des domaines essentiels de compétences numériques. Cette proportion comprend 7 % de personnes en situation d'illectronisme et 27 % ayant des compétences numériques faibles.

Ces chiffres proviennent d'études dont les champs et les méthodes diffèrent. Ils ne décrivent pas directement le marché potentiel d'OCNP ; ils illustrent le contexte dans lequel les associations doivent organiser leurs activités et accompagner leurs publics.

## 2.2. Les difficultés concrètes rencontrées par les associations

Les besoins évoqués par les responsables associatifs peuvent être regroupés en plusieurs familles :

**Des outils dispersés.** Les dons, les adhésions, la comptabilité, les événements, les documents et les tâches bénévoles sont parfois gérés dans des applications différentes. Les informations doivent alors être rapprochées manuellement.

**Un manque de continuité.** Lorsqu'une personne quitte une fonction, les procédures, les accès, les fichiers et l'historique ne sont pas toujours suffisamment structurés pour permettre une reprise facile.

**Des budgets numériques limités.** Les associations doivent arbitrer entre les dépenses directement liées à leur mission et les dépenses nécessaires au fonctionnement de leurs outils.

**Une forte dépendance à quelques personnes.** Dans certaines structures, une ou deux personnes maîtrisent l'essentiel des outils. Cette situation peut rendre l'organisation fragile et compliquer la transmission des connaissances.

**Des besoins fonctionnels hétérogènes.** Une petite association locale, une association nationale, une structure employeuse ou une organisation qui gère des subventions n'ont pas exactement les mêmes exigences. Un outil doit donc être configurable sans devenir un assemblage de développements spécifiques difficile à maintenir.

## 2.3. La réponse recherchée

OCNP vise à proposer un environnement intégré dans lequel les principaux processus associatifs peuvent être organisés autour d'un même socle logiciel.

L'objectif n'est pas de prétendre qu'un logiciel peut remplacer le projet associatif, les décisions des dirigeants, les compétences des bénévoles ou l'accompagnement des professionnels. Il s'agit de fournir un outil de gestion qui aide à structurer le fonctionnement quotidien, à limiter les ruptures d'information et à rendre les processus plus lisibles.

Le projet repose sur une conviction : **les associations doivent pouvoir choisir leur infrastructure, comprendre les outils qu'elles utilisent et conserver la maîtrise de leurs données.**

## 2.4. Panorama des solutions et positionnement

OCNP s'inscrit dans un environnement où coexistent plusieurs types de solutions :

| Famille de solutions | Exemples ou usages | Points de comparaison utiles |
|---|---|---|
| ERP et CRM libres | Dolibarr, Odoo Community et leurs écosystèmes de modules | Périmètre réel, modules disponibles, documentation, communauté, compétences nécessaires, facilité de maintenance |
| Plateformes spécialisées | Collecte de dons, paiement en ligne, adhésions, billetterie ou gestion d'événements | Tarification, commissions, conditions contractuelles, portabilité des données, dépendance au fournisseur |
| Éditions commerciales | Éditions payantes de logiciels de gestion, dont Odoo Enterprise | Coût récurrent, fonctions supplémentaires, support, conditions de licence |
| Outils indépendants | Tableurs, formulaires, stockage documentaire, outils de paiement et logiciels comptables séparés | Ressaisies, cohérence des données, charge de coordination, continuité en cas de départ d'un bénévole |

OCNP ne cherche pas à déclarer une solution universellement meilleure que les autres. Il propose une approche différente : s'appuyer sur Odoo Community et son écosystème open source pour construire un environnement associatif intégré, paramétrable et auto-hébergeable.

Chaque association doit comparer les solutions selon ses propres besoins, son budget, ses compétences internes et son niveau d'autonomie technique.

---

# 3. La vision, la mission et les objectifs

## 3.1. La vision

**Donner aux associations la possibilité de disposer d'un environnement de gestion intégré, librement déployable et adapté à leurs réalités, sans dépendre obligatoirement d'une licence logicielle propriétaire.**

OCNP souhaite contribuer à un numérique associatif plus accessible, plus maîtrisable et plus collaboratif.

## 3.2. La mission

La mission d'OCNP est de concevoir, documenter, tester et faire évoluer une solution de gestion associative fondée sur Odoo Community, en donnant la priorité aux fonctionnalités existantes et aux composants libres déjà disponibles.

Cette mission comporte plusieurs dimensions :

- **Faciliter la gestion associative :** rapprocher les processus de gestion qui sont souvent répartis entre plusieurs outils.
- **Réduire les barrières financières :** rendre le code et son utilisation en auto-hébergement gratuits, sous réserve des coûts propres à l'infrastructure et à l'exploitation.
- **Favoriser l'autonomie :** permettre à chaque association de choisir son hébergeur, de contrôler sa base de données et d'adapter le paramétrage.
- **Mutualiser les efforts :** partager les corrections, la documentation, les tests et les améliorations sous une licence libre.
- **Développer les compétences :** offrir aux contributeurs un cadre de collaboration sur un projet réel, avec des livrables, une revue des contributions et une documentation.

## 3.3. Les objectifs du projet

Les objectifs de la première version sont les suivants :

1. Reprendre et stabiliser la solution interne d'Odoo Community 19 développée pour LFM.
2. Vérifier la disponibilité et la compatibilité de chaque fonctionnalité dans l'édition Community.
3. Identifier les modules OCA ou tiers nécessaires, leurs versions, leurs dépendances et leurs licences.
4. Documenter les usages associatifs des fonctionnalités natives, y compris lorsqu'une fonction est utilisée pour un besoin différent de son intitulé technique initial.
5. Construire une distribution propre à partir du code et d'un paramétrage générique, sans données opérationnelles réelles de LFM.
6. Préparer des données de démonstration fictives pour rendre la découverte et les tests plus simples.
7. Mettre en place des tests d'installation, de fonctionnement, de sécurité et de non-régression.
8. Rédiger une documentation compréhensible pour les responsables associatifs et suffisamment précise pour les contributeurs techniques.
9. Organiser les premiers essais avec des associations pilotes après la publication d'une version publique adaptée.
10. Construire progressivement une communauté de contributeurs et d'utilisateurs.

## 3.4. Les principes d'impact

OCNP ne mesure pas son utilité uniquement au nombre de lignes de code ou de fonctionnalités publiées. La valeur recherchée est aussi organisationnelle : aider une association à mieux transmettre ses pratiques, à réduire les ruptures d'information, à comprendre ses processus et à conserver la maîtrise de son environnement numérique.

L'impact devra progressivement être évalué à partir de retours d'associations utilisatrices, de la facilité d'installation, de la qualité de la documentation, de la stabilité des fonctions et de la capacité de la communauté à contribuer à la maintenance.

---

# 4. À qui s'adresse OCNP ?

## 4.1. Les associations utilisatrices

La première version vise les associations françaises, quelle que soit leur taille ou leur domaine d'activité : associations de proximité, associations culturelles, sportives, éducatives, sociales, humanitaires, professionnelles ou de solidarité.

OCNP pourra intéresser particulièrement les structures qui :

- souhaitent réunir plusieurs processus de gestion dans un environnement commun ;
- veulent réduire leur dépendance à des outils épars ;
- disposent d'une personne compétente pour installer et administrer un logiciel, ou peuvent s'appuyer sur un prestataire de leur choix ;
- souhaitent garder la maîtrise de l'hébergement et des données ;
- acceptent de participer à une démarche de test et d'amélioration progressive.

La taille de l'association ne garantit pas à elle seule l'adéquation de la solution. Le besoin fonctionnel, les compétences disponibles et la capacité à assurer l'exploitation doivent être examinés avant toute installation.

## 4.2. Les responsables associatifs et les équipes administratives

OCNP vise à faciliter le travail des personnes qui organisent et suivent les activités de l'association : dirigeants, responsables de pôles, secrétariats, trésoriers, équipes administratives, responsables de projets, coordinateurs de bénévoles et gestionnaires de partenariats.

L'objectif est de rendre les informations et les processus plus cohérents, avec des libellés compréhensibles et une documentation qui ne suppose pas que chaque utilisateur soit spécialiste d'Odoo.

## 4.3. Les bénévoles et coordinateurs de missions

Le projet vise également les associations qui doivent organiser les disponibilités, les missions, les tâches, les projets et la transmission des informations entre bénévoles.

Le logiciel doit aider à clarifier les missions et à suivre leur avancement sans transformer le bénévolat en relation de contrôle des horaires ou de subordination. Les règles d'engagement restent celles de chaque association.

## 4.4. Les contributeurs et spécialistes

OCNP est ouvert à des contributions de profils variés :

- développeurs Python et spécialistes Odoo ;
- administrateurs systèmes, spécialistes cloud, bases de données et sécurité ;
- testeurs, analystes QA et rédacteurs de scénarios ;
- designers UI/UX et spécialistes de l'accessibilité ;
- rédacteurs techniques et formateurs ;
- juristes spécialistes du logiciel libre, des contrats et de la protection des données ;
- comptables et spécialistes de la gestion associative ;
- responsables associatifs capables de tester les parcours et de documenter leurs besoins.

La contribution ne se limite donc pas à programmer. Les tests, la documentation, l'analyse fonctionnelle, l'accessibilité et la validation des usages sont indispensables à la qualité du projet.

## 4.5. Les institutions, partenaires et acteurs de l'accompagnement

Les collectivités, établissements publics, réseaux associatifs, acteurs de l'ESS, fondations, organismes d'accompagnement et partenaires académiques peuvent contribuer à faire connaître le projet, à identifier des besoins, à participer à des essais ou à soutenir le développement d'un outil libre d'intérêt associatif.

OCNP souhaite dialoguer avec ces acteurs sans prétendre se substituer à leurs missions de conseil, de contrôle, de financement ou d'accompagnement.

---

# 5. Ce qu'OCNP ambitionne de couvrir

## 5.1. Périmètre fonctionnel envisagé pour la première version

OCNP vise à réunir les principaux besoins de gestion d'une association dans un environnement cohérent. Le tableau ci-dessous distingue l'objectif fonctionnel de l'état réel des vérifications. **La présence d'un besoin dans ce périmètre ne signifie pas que la fonction est déjà finalisée ou disponible dans la version actuellement testée.**

| Domaine | Besoin associatif visé | Approche envisagée | État au stade de présentation |
|---|---|---|---|
| **Dons ponctuels** | Enregistrer et suivre un don, en ligne ou hors ligne, avec une confirmation claire | Réutilisation des fonctions commerciales et e-commerce d'Odoo Community, avec des libellés associatifs explicites | Paramétrage en cours de vérification ; parcours et traitement à valider |
| **Dons réguliers** | Suivre des engagements mensuels ou annuels et leurs échéances | Module complémentaire de la communauté si le besoin n'est pas couvert par le socle Community | Module et compatibilité à vérifier pour Odoo 19.0 |
| **Cotisations et adhésions** | Gérer le paiement, le renouvellement et le suivi des adhérents | Fonction existante ou module complémentaire compatible, selon le résultat de l'étude | Module, règles de gestion et compatibilité à confirmer |
| **Subventions** | Suivre une demande, un financement obtenu, les échéances et les justificatifs par projet | Projets, tâches, documents et analytique d'Odoo Community | Cadrage fonctionnel en cours |
| **Bénévolat** | Organiser les projets, missions, tâches et disponibilités choisies librement | Réutilisation des fonctions natives de projet, tâches et calendrier, dans la limite des fonctions réellement disponibles | Parcours à tester et à documenter |
| **Stages et conventions** | Suivre les jalons, les documents, les interlocuteurs et le bilan | Projets, tâches et pièces jointes | Paramétrage et modèle de suivi à confirmer |
| **Événements et boutique** | Organiser les événements, inscriptions, ventes et billetterie | Modules Community disponibles, sous réserve de vérification des dépendances | Parcours à tester dans l'édition Community |
| **Comptabilité associative** | Organiser les écritures et produire les états et exports nécessaires au périmètre retenu | Modules complémentaires, notamment issus de l'écosystème OCA, et paramétrage spécifique déjà étudié en interne | Exigences et modules à confirmer avant publication |
| **Signature électronique** | Faire signer des documents et conserver les éléments de traçabilité requis | Module complémentaire étudié dans la solution interne | Exigences, niveau de signature, dépendances et portée probatoire à confirmer |

## 5.2. Une précision essentielle sur les dons et les reçus fiscaux

La possibilité d'enregistrer un don dans un ERP ne signifie pas automatiquement que le logiciel peut déterminer si le don ouvre droit à réduction fiscale ou produire un reçu fiscal conforme pour toutes les situations.

La capacité à émettre des reçus fiscaux dépend notamment de la situation de l'organisme bénéficiaire, de la nature du don, du régime applicable et des informations obligatoires à faire figurer sur le document.

OCNP pourra aider à structurer le suivi des dons et, si les exigences sont validées, à produire les documents correspondants. Il ne décidera pas à la place de l'association de son éligibilité fiscale et ne remplacera pas l'avis d'un professionnel compétent.

## 5.3. Des fonctions associatives à partir de composants de gestion existants

Le projet assume une méthode pragmatique : une fonction logicielle peut être utilisée pour couvrir un besoin associatif différent de son intitulé technique d'origine, à condition que le paramétrage soit cohérent, explicite et documenté.

Par exemple, un produit e-commerce peut être présenté à l'utilisateur comme un « Don » ; un mécanisme de facturation récurrente peut être étudié pour le suivi d'un don régulier ou d'une cotisation annuelle.

Le vocabulaire présenté aux utilisateurs doit rester celui de la vie associative. Les termes techniques Odoo sont utiles aux développeurs, mais ne doivent pas imposer leur logique aux bénévoles et responsables associatifs.

Chaque détournement devra toutefois être accompagné d'une fiche décrivant le besoin, la fonctionnalité utilisée, le paramétrage, les limites, les tests et les éventuelles obligations complémentaires. Un intitulé convivial ne doit jamais masquer une limite fonctionnelle, fiscale ou juridique.

## 5.4. Ce qu'OCNP ne cherche pas à faire

OCNP n'a pas vocation à remplacer :

- les décisions des organes statutaires de l'association ;
- l'expertise d'un expert-comptable, d'un commissaire aux comptes ou d'un conseil fiscal ;
- l'analyse juridique propre à chaque association ;
- les organismes de paiement ou les banques ;
- les obligations de conservation, de contrôle et de justification qui incombent à chaque structure ;
- les compétences humaines nécessaires à la conduite d'un projet associatif.

Le logiciel est un outil de gestion et de suivi. Il ne transfère pas à LFM la responsabilité légale de l'association qui l'utilise.

---

# 6. Le choix d'Odoo Community

## 6.1. Un socle libre, modulaire et auto-hébergeable

Odoo Community est l'édition libre et open source d'Odoo. La documentation officielle d'Odoo indique que la version 19 Community est publiée sous licence **GNU LGPL version 3 (LGPLv3)**. Odoo Enterprise relève d'une licence distincte et ne doit pas être confondu avec Community.

OCNP se fonde sur Odoo Community 19.0. Le projet ne vise pas à redistribuer du code Odoo Enterprise ni à reproduire des fonctionnalités propriétaires en copiant des composants auxquels il n'aurait pas droit.

Cette distinction est fondamentale : les fonctions réellement disponibles dans Community doivent être vérifiées avant d'être présentées comme natives d'OCNP.

## 6.2. L'écosystème de l'Odoo Community Association

L'**Odoo Community Association (OCA)** est une organisation à but non lucratif indépendante qui soutient le développement collaboratif de fonctionnalités et de modules pour l'écosystème Odoo. Ses dépôts réunissent des modules développés et maintenus par la communauté.

L'OCA propose notamment des modules fonctionnels, des outils de développement, des conventions de qualité et des projets de migration tels qu'OpenUpgrade.

L'existence d'un module OCA ne suffit toutefois pas à établir qu'il est utilisable dans OCNP. Pour chaque composant retenu, le projet doit vérifier au minimum :

- sa présence dans une branche compatible avec Odoo 19.0 ;
- sa capacité à s'installer et à fonctionner dans une base de test propre ;
- ses dépendances et ses éventuelles contraintes externes ;
- sa licence propre, indiquée dans le manifeste du module ;
- son niveau de maintenance et les tests disponibles ;
- les limites fonctionnelles connues ;
- la stratégie de mise à jour et de rapprochement avec le code amont.

Un dépôt OCA peut contenir des modules ayant des licences différentes. La licence doit donc être examinée module par module, et non déduite du seul nom du dépôt.

## 6.3. Pourquoi ne pas développer un ERP entièrement spécifique ?

Développer et maintenir un ERP complet représente un effort très important : gestion des utilisateurs, droits, bases de données, ventes, paiements, comptabilité, documents, automatisations, rapports, mises à jour et sécurité.

Pour une association qui souhaite consacrer ses ressources à des solutions d'intérêt social, réécrire ce socle serait rarement le meilleur usage des compétences disponibles.

OCNP préfère s'appuyer sur un logiciel déjà structuré et sur son écosystème, puis consacrer l'effort de développement aux besoins associatifs qui ne sont pas correctement couverts.

## 6.4. La compatibilité : une démarche de vérification, pas une promesse absolue

OCNP vise la compatibilité avec la version officielle Odoo Community 19.0 sans modification du cœur.

Le fait de ne pas modifier le cœur facilite la maintenance, mais ne garantit pas à lui seul la compatibilité des modules complémentaires, des vues héritées, des automatisations, des intégrations ou des données. Chaque composant doit être vérifié et testé.

La compatibilité avec les futures versions d'Odoo ne peut pas être promise à l'avance. Elle fera l'objet d'une étude et de tests spécifiques à chaque migration.

---

# 7. Les principes de conception et de développement

## 7.1. Notre règle fondamentale : l'organisation humaine s'adapte à l'ERP

Le principe directeur d'OCNP est le suivant : **c'est l'organisation humaine qui s'adapte à l'ERP, et non l'inverse.**

L'objectif n'est pas de reproduire sans limite chaque particularité de chaque organisation. Une solution trop personnalisée devient difficile à comprendre, à documenter, à mettre à jour et à maintenir.

OCNP cherchera donc à proposer des processus communs, compréhensibles et configurables, tout en laissant aux associations la possibilité de choisir les paramètres adaptés à leur fonctionnement.

## 7.2. Une hiérarchie stricte des choix techniques

Pour chaque besoin, l'ordre de décision est le suivant :

1. **Le cœur officiel d'Odoo Community, en priorité.** Utiliser les fonctions disponibles, y compris en les paramétrant ou en les détournant pour un usage associatif lorsque cela reste cohérent et maintenable.
2. **Les modules de l'Odoo Community Association (OCA).** Lorsque le cœur ne suffit pas, examiner les modules OCA compatibles, maintenus et adaptés au besoin.
3. **Un module gratuit tiers, fiable et maintenu.** Ce recours doit être justifié par une vérification de la qualité, de la licence, des dépendances, de la sécurité et de la continuité de maintenance.
4. **Un module spécifique, en ultime recours.** Il ne doit être envisagé que lorsque les solutions précédentes ne permettent pas de satisfaire un besoin réellement indispensable, en particulier une exigence réglementaire ou juridique qui ne peut être couverte autrement. Le module devra être documenté, testé, maintenu et publié dans le respect des licences applicables.

Cette hiérarchie n'est pas une simple préférence de développement : elle constitue une règle de gouvernance technique destinée à limiter les coûts de maintenance et les incompatibilités.

## 7.3. Pas de modification du cœur Odoo

OCNP ne modifie pas le cœur officiel d'Odoo Community. Le projet doit privilégier le paramétrage, les modules complémentaires, les mécanismes d'héritage et les extensions propres.

Sont écartés par principe :

- les modifications directes du code cœur ;
- la copie d'un module cœur dans le seul but de le modifier localement ;
- la dépendance obligatoire à du code Enterprise ;
- les extensions payantes ou propriétaires indispensables au fonctionnement de la distribution publique ;
- les solutions qui ne peuvent être maintenues raisonnablement dans la durée.

## 7.4. Des modules complémentaires plutôt que des modifications locales opaques

Lorsqu'une extension est nécessaire, elle doit être isolée dans un module identifiable, avec une responsabilité fonctionnelle claire.

Le projet favorisera :

- des modules de taille raisonnable et à périmètre identifiable ;
- des extensions propres plutôt que des copies de modules du cœur ;
- des dépendances déclarées et documentées ;
- des tests automatisés ;
- une documentation technique et fonctionnelle ;
- un historique des changements ;
- un suivi de la compatibilité avec la version d'Odoo visée.

## 7.5. Un thème identifiable, mais indépendant des données réelles de LFM

La version interne utilise un thème personnalisé dans une palette brique terre cuite. Le projet souhaite conserver cette identité visuelle dans la distribution publique, sous réserve de la vérification des droits sur les éléments graphiques et les composants utilisés.

Le thème devra être traité comme un composant maintenable, et non comme une modification du cœur Odoo. Il devra être cohérent sur les écrans, formulaires, documents et emails concernés, tout en respectant les exigences d'accessibilité et de lisibilité.

## 7.6. Des données de démonstration entièrement fictives

La distribution publique pourra proposer un exemple d'association avec des données synthétiques : nom fictif, coordonnées fictives, membres de démonstration, dons fictifs, projets exemples, cotisations et événements de test.

Ces données auront pour objectif de rendre l'installation plus pédagogique. Elles ne devront pas reproduire les données réelles de LFM, de ses bénévoles, donateurs, bénéficiaires, partenaires ou salariés.

---

# 8. Architecture, sécurité, données et protection de la vie privée

## 8.1. Une distribution construite à partir du code

La version publique doit être produite à partir des dépôts de code et des éléments génériques versionnés, et non par la publication d'une copie nettoyée de la base opérationnelle de LFM.

La démarche visée est la suivante :

1. sélectionner une version du code déclarée prête pour publication ;
2. construire l'environnement à partir d'un dépôt propre ;
3. installer les modules et le paramétrage générique ;
4. initialiser une base vierge ;
5. charger uniquement des données de démonstration fictives ;
6. exécuter les tests d'installation et de fonctionnement ;
7. contrôler les dépôts, artefacts, journaux et fichiers produits ;
8. faire relire et valider la publication avant diffusion.

Les scans de secrets et de données personnelles constituent des contrôles supplémentaires. Ils ne remplacent pas la règle principale : aucune base de production ni aucun export opérationnel de LFM ne doit servir de source à la distribution publique.

## 8.2. Protection des secrets

Les mots de passe, clés API, tokens, clés privées et identifiants sensibles ne doivent jamais être publiés dans le code, les dépôts publics, les documentations ou les bases de démonstration.

Les secrets nécessaires à l'exploitation d'une installation doivent être gérés selon un mécanisme adapté au déploiement, avec des droits d'accès restreints, une protection du stockage, une procédure de rotation et une documentation qui ne révèle pas les valeurs secrètes.

Les paramètres nécessaires à l'installation doivent être distingués des secrets d'exploitation. Un identifiant technique ou une valeur de configuration n'est pas automatiquement un secret ; son niveau de sensibilité doit être évalué.

## 8.3. Données personnelles et RGPD

La distribution publique ne doit contenir aucune donnée personnelle réelle issue de LFM.

Pour une association qui installe OCNP, les données traitées dépendront de ses activités et de son paramétrage. L'association utilisatrice reste responsable de déterminer ses finalités, ses bases légales, les informations à fournir aux personnes, les durées de conservation, les droits à traiter et les mesures de sécurité nécessaires.

Le projet devra fournir une documentation permettant de comprendre les fonctionnalités de traitement, les paramètres pertinents et les précautions à prendre. Il ne pourra cependant pas garantir à lui seul la conformité RGPD de chaque installation, car celle-ci dépend aussi des choix et pratiques de l'association utilisatrice.

## 8.4. Sécurité des installations

Les recommandations de sécurité devront notamment couvrir :

- le principe du moindre privilège pour les comptes et les rôles ;
- la séparation des responsabilités d'administration et d'utilisation ;
- l'authentification forte lorsque disponible ;
- le chiffrement des connexions ;
- les mises à jour de sécurité du système et des modules ;
- les sauvegardes régulières et les tests de restauration ;
- la protection des pièces jointes et des exports ;
- la journalisation des opérations sensibles ;
- la gestion et la rotation des secrets ;
- la procédure de signalement des vulnérabilités.

## 8.5. Une sécurité qui dépend aussi de l'exploitation

L'auto-hébergement donne à l'association la maîtrise du choix de son infrastructure, mais cette liberté implique des responsabilités : sécuriser le serveur, contrôler les accès, appliquer les mises à jour, sauvegarder les données, tester les restaurations et surveiller les incidents.

La sécurité ne dépend donc pas uniquement du code d'OCNP. Elle dépend également de la configuration, de l'hébergeur, des logiciels utilisés, des pratiques d'administration et des utilisateurs.

## 8.6. Politique de publication et de signalement

Avant la première publication, le projet devra rendre accessibles :

- la licence et les avis de droits applicables ;
- les consignes de contribution ;
- le code de conduite ;
- les consignes de signalement des vulnérabilités ;
- les versions prises en charge ;
- les procédures de mise à jour et les limites connues.

Les vulnérabilités ne doivent pas être publiées avec des détails exploitables dans une issue publique avant qu'une procédure de traitement appropriée ait été définie. Le contact de sécurité prévu pour la phase de préparation est : [contact@maghen.eu](mailto:contact@maghen.eu).

---

# 9. Gouvernance et organisation du projet

## 9.1. Un projet de La Famille Maghen

OCNP est porté par l'association La Famille Maghen. Il s'inscrit dans le Laboratoire d'Innovation Familiale (LIF), qui conçoit des solutions solidaires d'inclusion sociale et de lutte contre la fracture numérique.

Le projet dispose d'une équipe technique pilote au sein de la DINIS, mais sa qualité et son adoption nécessitent aussi des retours fonctionnels, administratifs, financiers, juridiques et associatifs.

## 9.2. La feuille de route appartient à l'association

La feuille de route d'OCNP est décidée par La Famille Maghen, dans le respect de ses statuts et de ses instances de décision.

Les contributeurs, utilisateurs et associations partenaires peuvent proposer des évolutions, signaler des anomalies et formuler des besoins. Les propositions sont examinées, priorisées et tracées. La participation au projet ne donne pas automatiquement un droit de décision sur la feuille de route.

## 9.3. Une organisation pluridisciplinaire

La contribution des différentes compétences de LFM permet de vérifier que la solution ne soit pas conçue uniquement du point de vue technique.

| Division | Contribution potentielle à OCNP |
|---|---|
| **DINIS — Ingénierie numérique et innovation sociale** | Architecture, infrastructure, développement, modules, intégration, UI/UX, tests, sécurité, documentation technique et gestion de projet IT |
| **DRH — Ressources humaines** | Analyse des besoins liés aux bénévoles, missions, disponibilités, compétences, parcours d'intégration et retours d'utilisation des équipes |
| **DAJCP — Affaires juridiques, contentieux et partenariats** | Vérification des licences, droits de propriété intellectuelle, accords de contribution, RGPD, conditions d'utilisation et partenariats |
| **DAF — Administration et finances** | Analyse des besoins comptables et financiers, contrôle de gestion, budgets, suivi des dépenses et validation des parcours administratifs et financiers |
| **DRIDP — Relations institutionnelles, donateurs et partenariats** | Analyse des besoins de collecte, relations donateurs, subventions, mécénat, partenariats et compréhension des attentes des acteurs institutionnels |

Cette organisation décrit les contributions possibles des Divisions. Elle ne signifie pas que tous les pôles sont déjà mobilisés en permanence ni que chaque fonction est déjà finalisée.

## 9.4. Contributions ouvertes et arbitrage

Les contributions peuvent prendre la forme de propositions fonctionnelles, rapports de test, documentation, tickets, correctifs ou demandes d'évolution.

Elles doivent suivre les règles publiques du dépôt : description claire, périmètre identifié, vérification, tests et revue avant intégration.

Les arbitrages techniques sont instruits par les personnes responsables du projet en appliquant la hiérarchie de choix décrite au chapitre 7. Les arbitrages fonctionnels sont examinés avec les personnes compétentes dans le domaine concerné. Les décisions structurantes de feuille de route restent du ressort de LFM.

## 9.5. Prévention des conflits d'intérêts

Les personnes qui contribuent à plusieurs domaines ou qui disposent de responsabilités différentes doivent déclarer les situations susceptibles de créer un conflit d'intérêts. Les décisions portant sur les droits, la licence, la marque, la sécurité et l'acceptation de contributions sensibles doivent être documentées et faire l'objet d'une revue appropriée.

---

# 10. La Famille Maghen, porteuse du projet

## 10.1. Présentation de l'association

**La Famille Maghen (LFM)** est une association loi 1901 à but non lucratif, reconnue de l'Économie Sociale et Solidaire (ESS) et signataire de la Charte de la Diversité.

LFM développe des projets d'inclusion sociale et de lutte contre la fracture numérique au travers de son **Laboratoire d'Innovation Familiale (LIF)**. L'association mobilise des bénévoles aux profils et compétences variés et organise son travail autour de projets, de missions, de responsabilités et de livrables.

Les projets mentionnés dans le portefeuille du LIF comprennent notamment e-PhotoID Express, Lien Social, Afrik Digital et OCNP. Cette présentation sert à situer OCNP dans l'environnement de LFM ; elle ne signifie pas que ces autres projets font partie du périmètre fonctionnel d'OCNP.

## 10.2. Organisation en Divisions et Pôles

### DINIS — Division de l'Ingénierie Numérique et de l'Innovation Sociale

- Pôle Infrastructure, Réseau et Cloud
- Pôle Développement Logiciel
- Pôle Intelligence Artificielle
- Pôle UI/UX Design
- Pôle Test & Assurance Qualité
- Pôle Gestion de Projet IT

### DRH — Division des Ressources Humaines

- Pôle Recrutement et Gestion des Talents
- Pôle Formation et Développement des Compétences
- Pôle Relations Sociales et Juridique RH
- Pôle Santé, Sécurité et Qualité de Vie au Travail (QVCT)

### DAJCP — Division des Affaires Juridiques, du Contentieux et des Partenariats

- Pôle Affaires Juridiques, Vie Associative et Conseil
- Pôle Contentieux, Précontentieux et Assurances
- Pôle Partenariats, Mécénat et Contractualisation
- Pôle Commande Privée, Publique et Subventions
- Pôle Éthique et Conformité RGPD

### DAF — Division de l'Administration et des Finances

- Pôle Comptabilité et Fiscalité
- Pôle Contrôle de Gestion, Budget, Trésorerie et Financement
- Pôle Achats, Moyens Généraux et Logistique

### DRIDP — Division des Relations Institutionnelles, Donateurs et Partenariats

- Pôle Relation Donateurs et Collecte de Fonds (B2C — Fundraising & Communauté)
- Pôle Relations Institutionnelles et Subventions Publiques (B2G)
- Pôle Partenariats Entreprises, Fondations et Mécénat (B2B)

## 10.3. Une culture de contribution ouverte

LFM souhaite permettre à des personnes aux expériences et parcours différents de participer à des projets concrets. Les bénévoles peuvent choisir les projets, missions et tâches correspondant à leurs compétences, à leurs objectifs d'apprentissage et à leurs disponibilités, dans le cadre de l'organisation de l'association.

Les profils présents ou recherchés peuvent notamment comprendre :

- étudiants en fin de cursus souhaitant contribuer à un projet réel ;
- professionnels expérimentés souhaitant transmettre leurs compétences ;
- personnes retraitées souhaitant rester actives dans leur domaine ;
- personnes en recherche d'emploi, en reconversion ou en reprise d'activité ;
- indépendants et professionnels souhaitant participer à un projet d'intérêt collectif ;
- bénévoles issus du monde associatif et désireux de partager leur expérience.

LFM valorise les contributions réelles et documentées. Une attestation éventuelle décrit les activités effectivement réalisées ; elle ne constitue ni un diplôme, ni une promesse d'emploi, ni l'équivalent juridique d'un stage.

## 10.4. Identité et coordonnées

**La Famille Maghen**  
Solidarité — Travail — Développement  
« Unir pour bâtir, ensemble pour toujours. »

- **RNA :** W343027898
- **SIREN :** 883931222
- **Siège :** 3 B Rue Brueys, 34000 Montpellier
- **Gestion :** 01 Parc de l'Étoile, 67100 Strasbourg
- **Contact :** [contact@maghen.eu](mailto:contact@maghen.eu)
- **Mentions légales :** <https://maghen.eu/mentions-legales/>

---

# 11. Où se déroule le projet et comment l'utiliser ?

## 11.1. Un projet collaboratif en ligne

OCNP est développé et documenté en ligne. Les dépôts de code, les issues, les demandes de fusion, la documentation et les annonces de publication seront rendus accessibles sur les plateformes retenues par le projet.

Les liens définitifs vers le dépôt public, la documentation et les téléchargements seront ajoutés à cette page dès qu'ils seront prêts à être ouverts.

- **Porteur :** La Famille Maghen, Montpellier et Strasbourg, France.
- **Cible initiale :** associations situées en France.
- **Langue de la première version :** français.
- **Installation visée :** sur un serveur ou un hébergement choisi par l'association utilisatrice.

## 11.2. Auto-hébergement

L'auto-hébergement signifie que l'association installe et fait fonctionner sa propre instance OCNP sur l'infrastructure de son choix, ou auprès de l'hébergeur qu'elle a sélectionné.

Ce mode d'utilisation vise à permettre à chaque association de garder la maîtrise :

- de l'emplacement de ses données ;
- des comptes utilisateurs et des droits d'accès ;
- des sauvegardes ;
- des mises à jour ;
- des paramètres de sécurité ;
- du rythme d'évolution de son installation.

Cette autonomie suppose néanmoins une capacité d'administration technique ou le recours à une personne compétente. Une documentation d'installation et d'exploitation fait donc partie des objectifs du projet.

## 11.3. Installation et accompagnement

La première version publique sera destinée à être installée par les associations ou les personnes qu'elles auront mandatées. Les prérequis, versions compatibles, modules et étapes d'installation devront être documentés avant publication.

OCNP n'annonce pas à ce stade de service d'hébergement géré ni de support contractuel. Les associations doivent donc prévoir les compétences et les ressources nécessaires à l'exploitation de leur propre instance.

## 11.4. Téléchargements et liens

À ce stade, aucun téléchargement public stable n'est annoncé. Cette page sera mise à jour lorsque les éléments suivants seront disponibles :

- dépôt officiel du projet ;
- guide d'installation ;
- licence et avis de droits ;
- documentation utilisateur ;
- politique de sécurité et consignes de signalement ;
- version identifiée comme première publication publique.

---

# 12. Calendrier, étapes et état d'avancement

## 12.1. Statut actuel

**La première version est en test interne au sein de La Famille Maghen.** Elle s'appuie sur Odoo Community 19 et sur les paramétrages et composants étudiés pour les usages internes de l'association.

Le projet n'est pas encore présenté comme une version stable prête à être installée par des associations tierces. Les travaux de vérification, de documentation, de contrôle des licences et de préparation de la distribution publique restent nécessaires.

## 12.2. Les étapes prévues

| Étape | Objectif | Principaux travaux |
|---|---|---|
| **1. Inventaire et vérification** | Décrire précisément l'existant | Inventaire des fonctions, modules, versions, dépendances, licences, paramétrages et limites |
| **2. Stabilisation et tests** | Vérifier le fonctionnement réel | Installation propre, scénarios fonctionnels, tests automatisés, non-régression, vérification des modules complémentaires |
| **3. Construction de la distribution publique** | Produire une version reproductible et indépendante des données internes | Construction depuis le code, paramétrage générique, base vierge, données fictives, analyse des secrets et contrôle des artefacts |
| **4. Documentation et cadre de contribution** | Rendre le projet compréhensible et contribuable | Guide d'installation, guides utilisateurs, documentation technique, licence, contribution, code de conduite et politique de sécurité |
| **5. Première publication publique** | Mettre à disposition une version vérifiée | Revue finale, validation des droits, tests, publication du code et de la documentation |
| **6. Associations pilotes** | Évaluer l'utilisation hors de LFM | Installation autonome, retours d'usage, remontée des défauts, amélioration de la documentation |
| **7. Évolution et maintenance** | Faire vivre le projet | Corrections, suivi des versions, étude des montées de version, intégration des contributions et nouvelles fonctions validées |

## 12.3. Aucun calendrier de publication annoncé

Aucune date de publication n'est annoncée à ce stade. Le projet est porté notamment par des bénévoles et doit respecter des exigences de qualité, de droits et de sécurité.

LFM préfère publier une version plus tardive mais vérifiée, documentée et reproductible plutôt qu'une version rapide qui exposerait les associations utilisatrices à des erreurs ou à des risques évitables.

## 12.4. Comment sera évaluée la réussite ?

La première validation repose sur l'utilisation réelle de la solution par LFM et sur la résolution des anomalies détectées par ses Divisions.

Cette validation interne ne suffira toutefois pas à démontrer que la solution est compréhensible et installable par une autre association. Une étape pilote externe devra donc vérifier notamment :

- la possibilité d'installer la distribution depuis une documentation claire ;
- la compréhension des principaux parcours par des personnes non développeuses ;
- le fonctionnement des scénarios de base ;
- la qualité des données de démonstration ;
- l'absence de défaut bloquant ou majeur connu ;
- la capacité à sauvegarder, restaurer et maintenir l'installation.

Les défauts devront être classés selon leur gravité, corrigés ou explicitement documentés. L'objectif est une amélioration continue, et non la promesse irréaliste d'un logiciel exempt de tout défaut mineur.

---

# 13. Gratuité, coûts et limites de responsabilité

## 13.1. Ce qui est destiné à être gratuit

Le modèle de diffusion visé est le suivant :

- code source accessible publiquement après la première publication ;
- licence libre permettant les usages autorisés par ses termes ;
- téléchargement de la distribution publique sans frais de licence OCNP ;
- documentation de base accessible publiquement ;
- installation en auto-hébergement sans redevance d'utilisation à LFM.

La licence exacte sera indiquée avant la publication. Les droits et licences de chaque composant tiers devront être respectés.

## 13.2. Les coûts qui restent à la charge de l'association

Un logiciel libre et gratuit en auto-hébergement n'est pas synonyme d'exploitation sans coût.

L'association utilisatrice doit notamment prévoir, selon son installation :

- un serveur ou un hébergement ;
- un nom de domaine et les certificats nécessaires le cas échéant ;
- du temps d'installation et de paramétrage ;
- l'administration de la base de données ;
- les sauvegardes et tests de restauration ;
- les mises à jour du système et des modules ;
- la surveillance et la sécurité de l'instance ;
- les éventuels services de professionnels qu'elle choisirait de solliciter.

## 13.3. Support communautaire

Le projet vise à organiser progressivement des échanges entre utilisateurs et contributeurs, principalement autour des dépôts et canaux qui seront annoncés à la publication.

Le support communautaire ne constitue pas une garantie de délai de réponse, de disponibilité permanente, de correction immédiate ou de maintien d'une installation particulière.

Les associations qui ont besoin d'un engagement de service, d'un hébergement administré ou d'une assistance contractuelle doivent choisir un prestataire et convenir directement avec lui des conditions correspondantes.

## 13.4. Responsabilités de l'association utilisatrice

L'association qui installe OCNP demeure responsable de son environnement : configuration, comptes, droits, données, sauvegardes, sécurité, mises à jour et conformité de ses traitements.

Elle doit vérifier que les fonctions retenues répondent à ses propres obligations et que ses procédures internes sont adaptées à sa situation.

OCNP est fourni comme logiciel et documentation. Il ne constitue pas un conseil juridique, fiscal, social ou comptable.

---

# 14. Contribuer à OCNP

## 14.1. Pourquoi le projet a besoin de contributeurs

La première version a été conçue et développée initialement par une seule personne pour répondre à un besoin interne. Pour devenir un projet open source durable et utile à d'autres associations, OCNP doit maintenant élargir le cercle des personnes qui peuvent vérifier, tester, documenter et améliorer la solution.

L'ouverture ne consiste pas seulement à publier un dépôt. Elle suppose de rendre le projet compréhensible, d'accueillir les contributions, de répartir les tâches, de relire les propositions et de construire progressivement une capacité de maintenance collective.

## 14.2. Les profils recherchés

| Profil | Contributions possibles |
|---|---|
| **Développeurs Python / Odoo** | Analyse des modules, extensions, paramétrage, correction de défauts, tests automatisés |
| **Administrateurs systèmes et DevOps** | Installation, Docker, PostgreSQL, sauvegardes, supervision, sécurité, construction de la distribution |
| **Testeurs et spécialistes QA** | Scénarios de test, tests d'installation, tests de non-régression, reproduction et qualification des anomalies |
| **Spécialistes OCA** | Vérification des dépôts, branches 19.0, dépendances, licences, maintenance et compatibilité |
| **Designers UI/UX** | Parcours utilisateurs, cohérence des écrans, ergonomie, accessibilité et thème |
| **Rédacteurs techniques** | Guides d'installation, documentation fonctionnelle, FAQ, tutoriels et procédures |
| **Juristes et spécialistes RGPD** | Licence, droits d'auteur, accords de contribution, protection des données, mentions et documentation juridique |
| **Comptables et gestionnaires associatifs** | Analyse des besoins associatifs, scénarios de gestion, vérification des états et des processus comptables |
| **Responsables associatifs et bénévoles utilisateurs** | Retours d'usage, validation des parcours, priorisation des besoins et tests non techniques |
| **Associations pilotes** | Installation, paramétrage, utilisation réelle, retours structurés et identification des points de blocage |

## 14.3. Ce que LFM propose aux contributeurs

Contribuer à OCNP permet de participer à un projet concret qui répond à un besoin associatif réel.

LFM souhaite offrir :

- un périmètre de contribution expliqué et des missions identifiables ;
- la possibilité de choisir des tâches compatibles avec ses compétences et ses disponibilités ;
- un cadre de travail collaboratif avec revue des contributions ;
- la possibilité de développer des compétences techniques, fonctionnelles ou documentaires ;
- une valorisation factuelle des contributions réellement réalisées ;
- une mention publique facultative, sous réserve du consentement de la personne ;
- le cas échéant, une attestation décrivant les contributions effectivement réalisées.

Une mention publique peut utiliser le nom ou le pseudonyme choisi par le contributeur, son rôle et un lien professionnel qu'il souhaite partager. Les coordonnées personnelles, notamment téléphone et adresse électronique privée, ne sont pas publiées par défaut.

## 14.4. Liberté d'engagement et absence de promesse

La participation à OCNP est un engagement bénévole libre. Chacun choisit les missions qu'il souhaite examiner et les disponibilités qu'il peut proposer, dans le cadre des règles de fonctionnement du projet.

**La participation au projet ne constitue aucune promesse d'emploi, de stage, de mission rémunérée, de contrat futur ou de résultat professionnel.** Une attestation décrit les activités réellement réalisées ; elle ne constitue ni un diplôme ni un stage.

## 14.5. Comment participer

Lorsque le dépôt public et les consignes de contribution seront disponibles :

1. consulter la présentation du projet et les consignes du dépôt ;
2. repérer une issue correspondant à ses compétences et à sa disponibilité ;
3. poser les questions nécessaires avant de s'engager ;
4. accepter les règles de contribution et les conditions de licence applicables ;
5. proposer un plan de travail ou une contribution limitée ;
6. soumettre le travail sous la forme demandée, avec tests ou documentation lorsque nécessaire ;
7. participer à la revue et aux corrections éventuelles.

Dans l'intervalle, les personnes intéressées peuvent écrire à [contact@maghen.eu](mailto:contact@maghen.eu) en indiquant leur domaine de compétence, leur expérience, les types de tâches souhaitées et leurs disponibilités.

## 14.6. Protection des contributeurs et des données internes

Les contributions externes devront être réalisées à partir des dépôts et environnements prévus à cet effet. Les bénévoles recrutés via une demande publique n'ont pas besoin d'accéder à l'instance interne de LFM ni à ses données de production.

Les missions publiques seront conçues pour utiliser du code publiable, des données fictives et des environnements de test. Aucun secret, document interne confidentiel ou donnée personnelle réelle ne devra être partagé dans une issue ou une demande de fusion publique.

## 14.7. Les attestations et la valorisation des contributions

LFM peut valoriser les contributions en mentionnant, avec l'accord des personnes concernées, les tâches réalisées, les livrables et les responsabilités effectivement assumées.

Les attestations éventuelles doivent rester descriptives et vérifiables. Elles ne garantissent pas un niveau de compétence déterminé par un organisme externe, ne remplacent pas un diplôme et n'ont pas automatiquement la valeur juridique d'une attestation de stage ou d'un certificat professionnel.

---

# 15. Demande de bénévoles développeurs via GitHub for Nonprofits

## 15.1. Pourquoi solliciter GitHub for Nonprofits ?

OCNP souhaite élargir sa communauté de contributeurs et mobiliser des compétences qui ne sont pas encore disponibles en interne. GitHub for Nonprofits propose un dispositif permettant à des associations vérifiées de présenter des projets open source à des équipes de bénévoles disposant de compétences techniques.

La demande envisagée vise à mobiliser une petite équipe pour contribuer à une étape précise : vérifier les composants OCA et les dépendances sur Odoo 19.0, renforcer les tests automatisés, préparer la construction reproductible de la distribution et améliorer la documentation ainsi que l'accessibilité.

Cette démarche est cohérente avec le statut actuel du projet : une première version interne existe, mais la distribution publique et ses éléments de maintenance doivent encore être préparés.

**La mission demandée doit porter sur des livrables circonscrits, réalisés à partir de dépôts et d'environnements publics ou de test. Aucun accès à l'instance interne de LFM ni à ses données privées n'est requis ou prévu.**

## 15.2. Le parcours GitHub en pratique

La documentation actuelle de GitHub présente les demandes d'équipes bénévoles dans le cadre de **Project Pods** :

1. décrire l'association, sa mission et le besoin du projet ;
2. préparer un dépôt ou une issue détaillée contenant les tâches, les livrables, les compétences et l'estimation de temps ;
3. soumettre la demande depuis l'espace GitHub for Nonprofits de l'organisation vérifiée ;
4. répondre aux demandes de précisions ou de révision de GitHub ;
5. après acceptation, accueillir l'équipe bénévole qui choisit le projet ;
6. répondre aux questions, fournir le contexte utile et relire les contributions dans des délais raisonnables.

GitHub demande notamment un projet suffisamment précis, un dépôt préparé avec un README et des consignes de contribution, ainsi qu'une issue identifiée par le libellé de statut approprié.

**Attention :** la page de connexion de GitHub for Nonprofits est protégée par authentification. Les champs visibles après connexion et les conditions d'accès doivent être vérifiés par le responsable du compte LFM au moment de la soumission. La documentation publique consultée en novembre 2026 utilise les libellés `Project Open for Volunteers`, `Project Claimed` et `Project Complete` pour l'issue associée au Project Pod. Il ne faut donc pas réutiliser automatiquement d'anciens libellés `Team Request` sans vérifier l'interface actuelle.

## 15.3. Objectif de la demande

**Objet proposé :** mobiliser une équipe de trois bénévoles pour vérifier, tester et documenter la première distribution publique d'OCNP fondée sur Odoo Community 19.0.

**Durée indicative :** six à huit semaines après le lancement effectif de la mission, sous réserve de confirmation des bénévoles et du responsable LFM. Il ne s'agit pas d'un calendrier de publication globale du projet.

**Disponibilité indicative :** environ trois à cinq heures par semaine et par bénévole, en mode asynchrone et sans horaires fixes. Cette estimation devra être confirmée avant soumission.

**Périmètre de sécurité :** travail sur des dépôts publics et des données synthétiques uniquement ; aucun accès à la base interne, aux données personnelles, aux secrets ou aux environnements de production de LFM.

## 15.4. Les quatre lots de travail proposés

### Lot A — Matrice de compatibilité des modules OCA avec Odoo 19.0

**Objectif :** établir une cartographie documentée des modules candidats pour les fonctions associatives ciblées.

Les bénévoles devront examiner, besoin par besoin, les composants potentiels portant notamment sur :

- les dons récurrents et mécanismes de paiement récurrent ;
- les adhésions, membres et cotisations ;
- les rapports et fonctions comptables nécessaires au périmètre retenu ;
- la signature électronique ;
- les événements, projets et autres composants utiles.

**Livrable attendu :** un fichier `docs/compat.md` indiquant, pour chaque besoin :

- le module candidat ;
- le dépôt et la branche ;
- la version examinée ;
- la licence indiquée dans le manifeste du module ;
- les dépendances ;
- les informations disponibles sur la maintenance ;
- le statut observé : fonctionne, ne fonctionne pas ou non vérifié ;
- les éléments de preuve : installation, résultat de test, documentation ou issue amont.

**Critère d'acceptation :** chaque besoin étudié dispose d'au moins une conclusion documentée, même si cette conclusion est « aucun module adapté identifié » ou « vérification impossible à ce stade ». Une incertitude doit être explicitement indiquée, et non remplacée par une supposition.

### Lot B — Tests automatisés

**Objectif :** disposer d'une base de tests reproductible pour détecter rapidement les régressions.

Les scénarios à couvrir en priorité sont :

- installation propre sur une base vierge ;
- création et suivi d'un don ponctuel ;
- inscription ou adhésion d'un membre, selon le module effectivement retenu ;
- création et suivi d'un dossier de subvention ou d'un projet ;
- création d'une mission bénévole ;
- inscription à un événement ;
- vérification des dépendances et des principales erreurs de configuration.

Un test de migration ou de mise à niveau pourra être ajouté si un environnement et une version de départ pertinents sont définis.

**Livrable attendu :** des tests exécutables localement et dans GitHub Actions, avec une section README expliquant les prérequis et la procédure d'exécution.

**Critère d'acceptation :** la suite fonctionne depuis un checkout propre et son résultat est visible dans l'intégration continue. Les tests doivent être reproductibles et ne pas nécessiter de données privées.

### Lot C — Construction reproductible de la distribution (objectif complémentaire)

**Objectif :** produire une distribution à partir du dépôt, sans exporter ni nettoyer une base de production.

Le travail pourra comprendre :

- un script d'assemblage de la distribution ;
- une procédure d'installation de modules depuis les sources déclarées ;
- l'initialisation d'une base vierge ;
- le chargement de données de démonstration synthétiques ;
- une tâche CI de construction ;
- des contrôles qui font échouer la construction si un secret de test ou une donnée personnelle interdite est détecté dans les fichiers et artefacts analysés.

**Livrable attendu :** une procédure de construction reproductible et une tâche CI documentée.

**Critère d'acceptation :** une construction depuis un checkout propre produit la distribution attendue, et un secret de test volontairement introduit dans un environnement de test déclenche bien l'échec du contrôle.

Ce lot est un objectif complémentaire : il ne doit pas mettre en danger la réalisation des lots A, B et D.

### Lot D — Documentation et accessibilité

**Objectif :** faciliter la prise en main par les associations et identifier les principaux obstacles d'accessibilité.

Les contributions pourront inclure :

- un guide d'installation ;
- un guide de démarrage ;
- des explications courtes pour les parcours associatifs prioritaires ;
- une documentation des erreurs fréquentes ;
- un examen de l'interface de démonstration à partir des critères WCAG 2.1 AA, dans la mesure où le périmètre de test le permet.

**Livrable attendu :** documentation intégrée au dépôt et compte rendu des problèmes d'accessibilité constatés.

**Critère d'acceptation :** une personne qui ne développe pas peut suivre le guide pour installer l'environnement de démonstration ou identifier clairement les prérequis et les limites ; les constats d'accessibilité sont documentés sous forme de points d'amélioration.

## 15.5. Compétences recherchées

- Python et développement Odoo ;
- connaissance de l'écosystème OCA ;
- PostgreSQL ;
- Docker ou environnement équivalent ;
- Git et GitHub ;
- GitHub Actions ou intégration continue ;
- tests fonctionnels et tests automatisés ;
- rédaction technique ;
- contrôle d'accessibilité et bonnes pratiques WCAG.

La maîtrise du français est utile pour comprendre les parcours associatifs et rédiger la documentation initiale. L'anglais technique est bienvenu pour communiquer avec les projets amont et les contributeurs internationaux.

## 15.6. Rôle du référent LFM

La demande ne devra être soumise que si un référent est effectivement disponible pour :

- expliquer le contexte fonctionnel ;
- répondre aux questions des bénévoles ;
- clarifier les priorités ;
- relire les résultats et les demandes de fusion ;
- faire les arbitrages nécessaires ;
- signaler rapidement les éventuels changements de périmètre.

Le champ GitHub indiquant qu'un interlocuteur est disponible (« Yes ») ne doit être sélectionné que si cette disponibilité est réellement assurée.

## 15.7. Textes de référence pour le formulaire GitHub

Les champs ci-dessous sont rédigés en anglais pour correspondre à la langue du formulaire. Ils sont inclus dans ce document français afin de constituer une base directement réutilisable. Les limites de caractères données dans le formulaire devront être vérifiées dans l'interface au moment de la soumission.

### About Your Nonprofit

**Proposition de texte :**

```text
La Famille Maghen (LFM) is a French nonprofit association (loi 1901), active in the Social and Solidarity Economy and a signatory of the Diversity Charter. Through its Innovation Lab, LFM develops digital solutions that support social inclusion and help reduce the digital divide. Its projects include e-PhotoID Express, Lien Social, Afrik Digital and OCNP. OCNP (Odoo Community For Non Profit) is an open-source project aiming to provide associations with an integrated management environment based on Odoo Community 19. It is designed to help volunteer-led organizations organize donations, memberships, grants, projects, volunteers and administrative activities with greater autonomy over their software and data.
```

### Project Request

**Proposition de texte (moins de 100 caractères) :**

```text
Help test and document an open-source Odoo 19 management solution for nonprofits
```

### Describe the development work needed

**Proposition de texte :**

```text
OCNP is an association-focused configuration and distribution project based on Odoo Community 19. Its first version is being tested internally by La Famille Maghen, and we are preparing a clean, documented public release. We are looking for a small volunteer team for an estimated 6-8 week engagement (about 3-5 hours per week per person; schedule to be agreed). Tasks: (1) verify OCA add-ons for Odoo 19.0 and document versions, licenses and dependencies; (2) add automated tests for a clean installation and key association workflows; (3) as a stretch goal, build a reproducible distribution from the repository using synthetic demo data and security scans; (4) improve installation and user documentation and review accessibility. No access to LFM's private instance, production data or secrets is required or provided. Deliverables, acceptance criteria and application instructions are in the linked GitHub issue. No promise of employment or paid work is made.
```

### Autres champs du formulaire

| Champ | Valeur proposée | À vérifier avant soumission |
|---|---|---|
| **Primary programming language/technology** | Python | Ajouter Odoo, PostgreSQL et GitHub Actions dans la description ou l'issue si le formulaire ne permet qu'un choix principal |
| **Number of volunteers needed** | 3 | Cohérent avec une petite équipe chargée des lots A, B et D ; le lot C est complémentaire |
| **Is a stakeholder available to work directly with volunteers?** | Yes, uniquement si un référent est confirmé | Ne pas sélectionner Yes sans engagement réel de réponse et de revue |
| **Organization website** | <https://maghen.eu> | Vérifier que le site et les mentions légales sont à jour |
| **GitHub issue or project link** | À compléter | Insérer l'URL de l'issue publique créée dans le dépôt OCNP |

## 15.8. Issue GitHub détaillée à créer

Le texte ci-dessous constitue un modèle d'issue d'équipe. Il ne doit être publié qu'après création du dépôt public, validation de la licence, clarification des droits sur le code initial et confirmation du responsable de mission.

**Titre proposé :**

`[Volunteer Project] Verify, test and document OCNP (Odoo Community 19 for nonprofits)`

**Libellés :** utiliser les libellés de statut actuellement demandés par GitHub pour un Project Pod, notamment `Project Open for Volunteers` au démarrage. Ajouter `help wanted` si ce libellé est utilisé dans le dépôt pour les contributions ouvertes. Mettre à jour le statut lorsque le projet est pris en charge ou terminé.

### About us

La Famille Maghen (LFM) is a French nonprofit association active in the Social and Solidarity Economy. OCNP (Odoo Community For Non Profit) is a project to prepare an open-source management environment for associations, based on Odoo Community 19. It aims to bring together workflows such as donations, memberships, grants, volunteer activities, projects and events. A first version is currently being tested internally. We are preparing a clean and documented public distribution.

### What we need

We are looking for a small team of up to 3 volunteers for an estimated 6-8 week engagement. The expected commitment is about 3-5 hours per week per volunteer, asynchronously, with no fixed working hours. The detailed start and end dates will be agreed before kickoff.

All work will use public repositories and test environments with synthetic data only. Volunteers will not receive access to LFM's internal Odoo instance, production databases, personal data or secrets.

### Task A — OCA compatibility matrix for Odoo 19.0

Check candidate OCA add-ons for the association workflows in scope: recurring donations or recurring payments, memberships and subscriptions, accounting reports, e-signature, events and projects.

- **Deliverable:** `docs/compat.md` listing the need, candidate module, repository, branch, version, license, dependencies, maintenance information, observed status and supporting evidence.
- **Done when:** each investigated need has a documented conclusion. Unknown or unavailable results must be reported as such, not guessed.

### Task B — Automated tests

Add or improve automated tests for a clean installation and the principal association scenarios: one-time donation, membership registration where supported, grant/project tracking, volunteer mission and event registration.

- **Deliverable:** tests that can be run locally and through GitHub Actions, plus README instructions.
- **Done when:** the suite runs from a clean checkout and reports its result in CI without requiring private data.

### Task C — Reproducible distribution build (stretch goal)

Prepare a script and CI job that assemble the distribution from the repository, initialize a fresh database and load synthetic demonstration data only. Add scans that detect test secrets and prohibited personal data in the files and build artefacts covered by the checks.

- **Deliverable:** a documented build procedure and CI job.
- **Done when:** a clean checkout produces the expected distribution and a deliberately inserted test secret makes the security check fail.

### Task D — Documentation and accessibility

Draft or improve installation and user guides for non-technical associations. Review the demonstration interface against relevant WCAG 2.1 AA criteria within the agreed scope.

- **Deliverable:** documentation in the repository and an accessibility findings report.
- **Done when:** the documented installation path is understandable to a non-developer, and accessibility findings are recorded as actionable issues.

### Rules

- Do not modify the Odoo Community core.
- Do not copy or use Odoo Enterprise code.
- Do not modify OCA modules directly; prefer clean extensions or upstream proposals.
- Use synthetic data only.
- Never add secrets, private documents or real personal data to issues, commits, tests or pull requests.
- Follow the repository's contribution, licensing and code-of-conduct instructions.

### Time commitment

About 3-5 hours per week per volunteer for an estimated 6-8 weeks, asynchronously and without fixed working hours. The start date, end date and review availability must be confirmed before the Project Pod begins.

### Skills

Python, Odoo, PostgreSQL, Docker, GitHub Actions, automated testing, technical writing and accessibility testing. French and English are both welcome.

### How to apply

Comment on this issue with:

- your GitHub handle;
- the task or tasks you would like to take on;
- a short description of relevant experience;
- your approximate weekly availability;
- whether you are applying individually or as part of a team;
- your time zone.

The project maintainer will confirm the next steps and the scope of the contribution.

### What we offer

Clear tasks, a defined scope, a contact person for project questions, code review, an optional public credit with the contributor's consent, and where appropriate an attestation describing actual contributions. We do not promise employment, paid work, an internship or any career outcome.

### License and contributions

The project license and contribution terms will be published in the repository before external contributions are accepted. Contributors must follow the applicable license and the repository's contribution procedure. A Developer Certificate of Origin (DCO), if adopted, confirms the contributor's right to submit the contribution; it does not replace a separate rights agreement where one is needed.

### Security and privacy

Do not post vulnerabilities, secrets or personal data in public issues. Follow the repository's security reporting instructions. Work on this volunteer request does not require access to LFM's internal systems or production data.

### Contact

contact@maghen.eu — https://maghen.eu

## 15.9. Prérequis avant d'envoyer la demande

| N° | Prérequis | Pourquoi c'est nécessaire |
|---|---|---|
| 1 | LFM dispose d'un compte/organisation GitHub et son statut GitHub for Nonprofits est vérifié ou l'éligibilité a été confirmée | Les Project Pods sont réservés aux organisations vérifiées dans le programme GitHub for Nonprofits |
| 2 | Le dépôt public OCNP est prêt ou son périmètre de publication est clairement préparé | Les bénévoles doivent disposer d'un espace où consulter les tâches et proposer leurs contributions |
| 3 | Le dépôt contient au minimum un README utile, un guide de contribution, un code de conduite, une politique de sécurité et les informations de licence appropriées | Les bénévoles doivent comprendre le projet, les règles de contribution et la manière de signaler un problème |
| 4 | Les droits sur le code initial ont été clarifiés | La version actuelle ayant été conçue par une seule personne, les droits de publication et les autorisations nécessaires doivent être confirmés avant l'ouverture du dépôt |
| 5 | La licence du projet et les licences des composants sont vérifiées | Les contributions et la redistribution doivent respecter les licences applicables à Odoo Community et aux modules complémentaires |
| 6 | Le dépôt ne contient aucun secret ni aucune donnée réelle de LFM | La demande publique doit pouvoir être traitée sans exposition des données internes |
| 7 | Un référent est réellement disponible | LFM doit pouvoir répondre aux questions, suivre l'équipe et relire les contributions |
| 8 | Le périmètre, les livrables, la durée et la charge de travail sont confirmés | GitHub attend une mission compréhensible, bornée et réalisable par une petite équipe |
| 9 | Les issues sont créées et portent les libellés correspondant au statut actuel demandé par GitHub | Les équipes doivent pouvoir identifier le projet ouvert, déjà pris en charge ou terminé |

**Ne pas soumettre la demande tant que les points relatifs aux droits, à la licence, à la sécurité et à la capacité de suivi ne sont pas satisfaits.** Une demande de bénévoles engage la réputation de LFM et la disponibilité de l'équipe qui accueillera les contributions.

---

# 16. Transparence : ce qu'OCNP ne promet pas

La transparence est une condition de confiance. À ce stade, OCNP ne promet pas :

- **une date de publication précise** : la première version est en test interne ; le calendrier dépend des validations ;
- **une disponibilité immédiate au téléchargement** : la distribution publique n'est pas encore annoncée ;
- **une compatibilité garantie avec les versions futures d'Odoo** : chaque montée de version nécessitera une étude et des tests ;
- **les fonctionnalités propres à Odoo Enterprise** : OCNP se fonde sur Odoo Community et des composants libres autorisés ;
- **un fonctionnement complet de toutes les fonctions envisagées** : certaines dépendances et exigences sont encore en cours de vérification ;
- **un support contractuel ou un délai garanti de correction** pour les installations auto-hébergées ;
- **un conseil juridique, fiscal, comptable ou social** ;
- **une conformité RGPD automatique** de chaque installation ;
- **une installation sans compétences techniques** : l'auto-hébergement nécessite une capacité d'installation, de sécurisation, de sauvegarde et de maintenance ;
- **un emploi, un stage, une mission rémunérée ou un résultat professionnel** aux personnes qui contribuent bénévolement.

Les fonctions de dons récurrents, cotisations, comptabilité associative et signature électronique dépendent de modules et d'exigences qui doivent être vérifiés et documentés avant d'être présentés comme disponibles.

---

# 17. Questions fréquentes

### OCNP est-il déjà disponible au téléchargement ?

Non. La première version est en test interne au sein de La Famille Maghen. La publication publique interviendra après les vérifications techniques, juridiques, de sécurité et de documentation.

### OCNP est-il gratuit ?

L'objectif est de publier le code et la documentation de base sous une licence libre, avec une utilisation en auto-hébergement sans redevance de licence OCNP. Les coûts d'hébergement, d'administration, de maintenance et les éventuels services de professionnels restent à la charge de l'association utilisatrice.

### Quelle est la différence entre OCNP et Odoo ?

OCNP est un projet qui s'appuie sur Odoo Community 19 et vise à fournir un paramétrage, une sélection de modules et une documentation orientés vers les besoins associatifs. Il ne s'agit pas d'une édition officielle d'Odoo et le cœur d'Odoo Community n'est pas modifié par le projet.

### OCNP est-il Odoo Enterprise en version gratuite ?

Non. OCNP repose sur Odoo Community. Il ne contient pas de code Enterprise et ne promet pas de reproduire les fonctions réservées à cette édition.

### Pourquoi avoir choisi Odoo Community ?

Odoo Community offre un socle libre et modulaire. LFM souhaite réutiliser au maximum les fonctions existantes, puis compléter uniquement lorsque le besoin le justifie. Ce choix permet de concentrer les efforts sur l'adaptation associative, la documentation et les tests plutôt que de développer un ERP complet depuis zéro.

### OCNP remplace-t-il mon expert-comptable ?

Non. Le logiciel peut aider à organiser les données, les écritures et les documents prévus dans son périmètre, mais il ne remplace pas l'analyse et les responsabilités des professionnels compétents. Les exigences comptables et fiscales devront être confirmées avant publication.

### OCNP garantit-il l'émission de reçus fiscaux conformes ?

Pas à ce stade. La possibilité de suivre un don et la possibilité d'émettre un reçu fiscal conforme sont deux sujets distincts. Les conditions d'éligibilité et les mentions nécessaires dépendent de la situation de l'association et doivent être vérifiées.

### Mes données seront-elles hébergées par LFM ?

Le modèle visé est l'auto-hébergement : les données sont stockées sur l'infrastructure choisie et administrée par l'association utilisatrice ou son prestataire. La qualité de la sécurité dépend aussi de cette infrastructure et de son administration.

### Puis-je utiliser OCNP si mon association n'a pas d'informaticien ?

L'installation et la maintenance nécessitent des compétences techniques. Le projet prévoit une documentation accessible, mais une association sans compétence interne devra identifier une personne ou un prestataire capable d'assurer l'installation et l'exploitation.

### OCNP fonctionne-t-il hors de France ?

La première version vise la France et le français, notamment parce que les besoins comptables, fiscaux et administratifs de départ sont ceux de LFM. Une adaptation à d'autres pays ou langues n'est pas annoncée pour cette première version.

### Puis-je contribuer sans savoir programmer ?

Oui. Les tests fonctionnels, la documentation, l'accessibilité, les retours d'usage, la validation de parcours associatifs et l'analyse des besoins sont des contributions importantes.

### Puis-je contribuer sans accéder aux données internes de LFM ?

Oui. Les contributions publiques seront organisées à partir de dépôts et d'environnements de test utilisant des données synthétiques. Aucun accès à l'instance interne ou aux données de production n'est nécessaire pour la demande de bénévoles décrite ici.

### Est-ce que contribuer à OCNP peut me garantir un emploi ?

Non. La contribution est bénévole et libre. Elle peut permettre de réaliser un travail concret et de documenter des expériences, mais LFM ne promet ni emploi, ni stage, ni mission rémunérée, ni résultat de carrière.

### Quelle licence sera utilisée ?

La licence exacte d'OCNP sera indiquée avant la première publication, après vérification des droits sur le code initial et des licences de tous les composants inclus ou distribués. Odoo Community 19 est publié sous LGPLv3 ; les modules complémentaires peuvent être soumis à d'autres licences.

### Quelle différence avec Dolibarr ?

Dolibarr et OCNP s'appuient sur des socles et des écosystèmes différents. Dolibarr est un logiciel libre de gestion qui propose notamment des fonctions pour les adhérents. OCNP vise à utiliser Odoo Community et ses modules pour réunir un ensemble de processus associatifs. Le choix doit dépendre des besoins, compétences, préférences et ressources de chaque association.

### Qu'est-ce que l'OCA ?

L'Odoo Community Association est une organisation à but non lucratif qui soutient le développement collaboratif de modules et fonctionnalités pour l'écosystème Odoo. La disponibilité, la licence et la qualité de chaque module doivent être vérifiées individuellement.

### Qui décide de la feuille de route ?

La feuille de route d'OCNP relève de La Famille Maghen, conformément à ses règles de gouvernance. Les contributeurs et utilisateurs peuvent proposer des évolutions, qui sont examinées et priorisées.

---

# 18. À propos de La Famille Maghen

La Famille Maghen est une association loi 1901 à but non lucratif, reconnue de l'Économie Sociale et Solidaire (ESS) et signataire de la Charte de la Diversité.

Son Laboratoire d'Innovation Familiale conçoit et développe des solutions solidaires d'inclusion sociale et de lutte contre la fracture numérique. LFM travaille avec des bénévoles aux profils pluridisciplinaires et développe des projets concrets dans lesquels les compétences techniques, administratives, juridiques, financières, humaines et relationnelles se complètent.

OCNP est l'un de ces projets. Il vise à mettre au service des associations une solution de gestion issue d'un besoin réel de LFM et dont l'ouverture doit permettre à d'autres structures de contribuer à son amélioration.

**La Charte de la Diversité** est un engagement volontaire en faveur de la prévention des discriminations, de l'égalité des chances et de la diversité dans les organisations. LFM indique en être signataire.

**Devise :** Solidarité — Travail — Développement  
**Slogan :** « Unir pour bâtir, ensemble pour toujours. »

**RNA :** W343027898  
**SIREN :** 883931222  
**Siège :** 3 B Rue Brueys, 34000 Montpellier  
**Gestion :** 01 Parc de l'Étoile, 67100 Strasbourg  
**Contact :** [contact@maghen.eu](mailto:contact@maghen.eu)  
**Mentions légales :** <https://maghen.eu/mentions-legales/>

---

# 19. Glossaire

- **AGPL :** licence libre de la famille GNU Affero GPL. Ses conditions diffèrent de celles de la LGPL ; chaque module doit être examiné selon sa licence exacte.
- **Auto-hébergement (self-host) :** installation et exploitation d'un logiciel sur un serveur choisi par l'utilisateur, directement ou auprès d'un hébergeur.
- **Base de démonstration :** base contenant des données fictives utilisées pour illustrer ou tester une application.
- **CI/CD :** automatisation de certaines étapes de construction, de test et de livraison d'un logiciel (intégration continue et livraison/déploiement continus).
- **Contribution :** travail proposé à un projet, par exemple code, tests, documentation, analyse, design ou retour fonctionnel.
- **DCO (Developer Certificate of Origin) :** déclaration par laquelle un contributeur atteste notamment avoir le droit de soumettre sa contribution sous les conditions applicables. Un DCO n'est ni une licence de logiciel ni, à lui seul, une cession générale de droits.
- **ERP :** logiciel de gestion intégré qui rassemble plusieurs processus d'une organisation dans un environnement commun.
- **GitHub Actions :** service d'automatisation associé à GitHub, utilisé notamment pour lancer des tests et des tâches de construction.
- **LGPL :** licence GNU Lesser General Public License. Odoo Community 19 est publié sous LGPLv3.
- **Module :** composant qui ajoute ou adapte une fonction dans Odoo.
- **OCA :** Odoo Community Association, organisation à but non lucratif qui soutient le développement collaboratif de modules pour Odoo.
- **Odoo Community :** édition libre et open source d'Odoo.
- **Odoo Enterprise :** édition soumise à une licence propriétaire distincte, avec des fonctions supplémentaires.
- **Open source / logiciel libre :** logiciel distribué sous une licence autorisant certains usages, études, modifications et redistributions, dans les conditions de cette licence.
- **PostgreSQL :** système de gestion de base de données utilisé par Odoo.
- **Paramétrage :** configuration des fonctions existantes d'un logiciel sans modifier son cœur.
- **Project Pod :** engagement de bénévolat structuré autour d'un projet open source de courte durée et d'une équipe de contributeurs, dans le programme GitHub for Nonprofits.
- **Pull request :** proposition de modification d'un dépôt de code, soumise à revue avant intégration.
- **WCAG :** recommandations internationales relatives à l'accessibilité des contenus web.

---

# 20. Ressources et sources

## 20.1. Ressources officielles et techniques

- **Odoo 19 — Licences :** <https://www.odoo.com/documentation/19.0/legal/licenses.html>
- **Odoo 19 — Administration et installation :** <https://www.odoo.com/documentation/19.0/administration.html>
- **Odoo Community Association :** <https://odoo-community.org/about>
- **OCA — OpenUpgrade :** <https://github.com/OCA/OpenUpgrade>
- **GitHub for Nonprofits — Project Pods :** <https://docs.github.com/en/nonprofit/project-pods/creating-a-volunteering-project>
- **GitHub for Nonprofits — Quickstart :** <https://docs.github.com/en/nonprofit/quickstart>
- **GitHub for Nonprofits — For Good First Issue :** <https://docs.github.com/en/nonprofit/contributing-to-open-source-for-good/contributing-to-an-open-source-for-good-project>
- **Formulaire de demande de bénévoles :** <https://nonprofits.github.com/volunteer-requests/new>
- **Dolibarr :** <https://github.com/Dolibarr/dolibarr>

## 20.2. Repères sur la vie associative et le numérique

- **Recherches & Solidarités — La France bénévole 2026**, étude sur l'engagement bénévole : <https://recherches-solidarites.org/> ; synthèse relayée par France générosités : <https://www.francegenerosites.org/ressources/la-france-benevole-2026-recherches-et-solidarites/>
- **La France associative en mouvement 2025**, chiffres sur les associations actives et les associations sans salarié : <https://www.francegenerosites.org/ressources/la-france-associative-en-mouvement-recherches-et-solidarites-2025/>
- **Solidatech et Recherches & Solidarités — La place du numérique dans le projet associatif en 2025 :** <https://www.solidatech.fr/ressources/etude-la-place-du-numerique-dans-le-projet-associatif-en-2025/>
- **Insee — Une personne sur trois manque de compétences numériques**, Insee Focus n° 376, février 2026 : <https://www.insee.fr/fr/statistiques/8739245>
- **Ministère de l'Économie — L'économie sociale et solidaire :** <https://www.economie.gouv.fr/leconomie-sociale-et-solidaire>
- **Charte de la Diversité :** <https://www.charte-diversite.com/>

## 20.3. Chiffres cités et précautions de lecture

Les principaux chiffres de contexte utilisés dans cette présentation sont les suivants :

| Repère | Année et portée | Source |
|---|---|---|
| Environ 1,6 million d'associations actives ; environ neuf sur dix sans salarié | Estimations relatives à la France associative en 2025 | Recherches & Solidarités, synthèse relayée par France générosités |
| 25 % des Français déclarent un engagement bénévole associatif ; estimation de 13 à 13,5 millions de bénévoles | Enquête IFOP / Recherches & Solidarités, janvier 2026, personnes de 15 ans et plus | *La France bénévole 2026* |
| 70 % des associations utilisent le numérique pour gérer plus efficacement leurs activités ; 26 % se considèrent expérimentées ; près de 70 % rencontrent encore des difficultés numériques | Enquête 2025 auprès de 2 285 responsables associatifs | Solidatech et Recherches & Solidarités |
| 34 % des 16-74 ans n'utilisent pas Internet ou n'ont pas les notions de base dans au moins un domaine essentiel ; parmi eux, 7 % en situation d'illectronisme et 27 % ayant des compétences faibles | France, données 2025 publiées par l'Insee en février 2026 | Insee Focus n° 376 |
| Odoo Community 19 est sous LGPLv3 | Licence de l'édition 19 Community | Documentation officielle Odoo |

Les statistiques sont des repères de contexte et non des prévisions de marché ou des estimations du nombre d'utilisateurs potentiels d'OCNP. Les enquêtes n'ont pas toutes le même périmètre ni la même méthodologie. Les chiffres devront être revérifiés lors de chaque mise à jour majeure de la page publique.

---

## Mentions relatives à Odoo et au nom OCNP

« Odoo » est une marque d'Odoo S.A. OCNP est un projet porté par La Famille Maghen. Il n'est ni édité, ni certifié, ni approuvé par Odoo S.A. Le nom « Odoo Community For Non Profit » est utilisé pour décrire le socle technique du projet ; son emploi dans les communications publiques et son éventuelle dénomination définitive devront respecter les droits de marque applicables.

**Dernière mise à jour éditoriale : 14 novembre 2026.**  
**Statut public à afficher : première version en test interne.**
