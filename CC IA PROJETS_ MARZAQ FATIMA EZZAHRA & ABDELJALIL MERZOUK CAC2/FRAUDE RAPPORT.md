# Rapport Académique — Contrôle Interne & Gouvernance

## Prédiction de la probabilité de fraude interne en entreprise à l'aide de l'Intelligence Artificielle

---

> **Module :** Contrôle Interne & Gouvernance  
> **Filière :** CAC — L3 S8  
> **Établissement :** École Nationale de Commerce et de Gestion de Settat  
> **Année Universitaire :** 2024–2025

---

## Sommaire

**1. Avant-propos**

**2. Introduction générale**

**3. Sommaire structuré**

**Chapitre 1 — Cadre conceptuel et théorique de la fraude interne**

- 1.1 Contexte du projet et évolution de la fraude à l'ère de l'intelligence artificielle
- 1.2 Définition juridique, normative et académique de la fraude interne
- 1.3 Le triangle de la fraude de Donald Cressey illustré aux données modernes
- 1.4 Profils à risque et identification des dysfonctionnements organisationnels
- 1.5 Rôle du contrôle interne et de la culture de l'éthique (Cadre COSO)

**Chapitre 2 — Intelligence artificielle et détection de fraude**

- 2.1 Les limites du paradigme classique face au Big Data et émergence de l'Audit Augmenté
- 2.2 Détection rétrospective vs. Prédiction probabiliste : le changement de paradigme
- 2.3 Avantages du Machine Learning et traitement algorithmique des comportements à risque
- 2.4 Typologie des principaux algorithmes de classification (de la Régression aux Réseaux de Neurones)

**Chapitre 3 — Méthodologie et modélisation prédictive**

- 3.1 Compréhension initiale des données (EDA — Exploratory Data Analysis)
- 3.2 Préparation méticuleuse (nettoyage, traitement des variables, gestion du déséquilibre)
- 3.3 Mise en place du protocole de modélisation prédictive de classification

**Chapitre 4 — Analyse des résultats et interprétation**

- 4.1 Choix et lecture des métriques d'évaluation algorithmiques (Accuracy, Recall, Precision, F1-Score)
- 4.2 Interprétation des attributs statistiques via le prisme du contrôle de la fraude pure
- 4.3 Appréciation par la gouvernance : traduire le mathématique en décisionnel

**Conclusion générale**

**Bibliographie (Factuelle et référentielle ACFE)**

---

## 1. Avant-propos

L'ère contemporaine, marquée par une transformation digitale sans précédent, redéfinit profondément les paradigmes fondamentaux de la gestion d'entreprise, de l'audit et du contrôle interne. Si la numérisation des processus offre des gains d'efficacité notables, elle s'accompagne corollairement d'une complexification systémique des risques. Parmi ces menaces intrinsèques, la fraude interne constitue l'une des manifestations les plus pernicieuses, sournoises et onéreuses d'une gouvernance défaillante.

L'objectif de ce projet est d'explorer et de démontrer comment les technologies avancées, spécifiquement l'intelligence artificielle (IA) et la Data Science, peuvent être intégrées aux dispositifs de gouvernance pour anticiper, détecter et prévenir les comportements frauduleux. La lutte contre la fraude interne n'est plus seulement une exigence réglementaire de conformité, mais un impératif stratégique pour pérenniser la viabilité financière, l'intégrité opérationnelle et la réputation des organisations modernes.

Ce rapport met en lumière le rôle croissant et indispensable de l'IA dans les métiers de l'audit et du contrôle de gestion. Il souligne une transition majeure : le passage d'un audit traditionnel, souvent rétrospectif et basé sur des échantillonnages statiques, à un **audit augmenté, continu et prédictif**. L'intérêt de ce projet est ainsi double :

- **Sur le plan pédagogique :** il illustre avec rigueur l'application des algorithmes de machine learning sur des données comportementales, organisationnelles et financières.
- **Sur le plan professionnel :** il propose un cadre méthodologique applicable par les comités de direction, les auditeurs et les contrôleurs internes pour repenser et doter d'une résilience technologique la gouvernance d'entreprise.

---

## 2. Introduction générale

La fraude en entreprise est un phénomène endémique qui transcende les secteurs d'activité, les cadres réglementaires, les zones géographiques et les tailles d'organisation. Selon les éditions successives du rapport mondial *Report to the Nations* publié par l'Association of Certified Fraud Examiners (ACFE), les organisations perdent chaque année une part structurelle de leurs revenus annuels — estimée en moyenne constante à **5 %** — en raison de fraudes internes ou occupationnelles. À l'échelle macroéconomique mondiale, l'ampleur de ce phénomène se chiffre en milliers de milliards de dollars, constituant une source silencieuse de destruction de valeur critique.

Historiquement, les départements d'audit et les fonctions de contrôle interne se sont appuyés sur des méthodes traditionnelles : audits périodiques basés sur le seul jugement professionnel, règles métier statiques (*red flags* figés), alertes manuelles et échantillonnage aléatoire. Or, confrontées à la volumétrie exponentielle des données numérisées (Big Data) et à la sophistication croissante des schémas de fraude, ces approches s'avèrent aujourd'hui obsolètes — trop lentes, davantage réactives que proactives, et génératrices d'un taux inexploitable de faux positifs.

C'est dans cette rupture que l'émergence de la Data Science et de l'IA offre un horizon salvateur. L'exploitation rigoureuse des modèles mathématiques et de l'apprentissage automatique (Machine Learning) permet l'analyse exhaustive des transactions et l'extraction de signaux faibles invisibles à l'analyse cognitive humaine.

### Problématique centrale

> **"Comment les techniques d'intelligence artificielle et de machine learning peuvent-elles améliorer la détection et la prédiction de la fraude interne dans les organisations, et quel est leur impact réel sur la solidité du contrôle interne ?"**

### Objectifs du projet

| # | Objectif |
|---|----------|
| 1 | Fournir un socle conceptuel profond analysant la fraude par le prisme théorique de la criminologie en entreprise (modèle de Donald Cressey) intégré au cadre de la gouvernance (COSO) |
| 2 | Concevoir une pipeline analytique complète pour appliquer les meilleurs modèles de Machine Learning à des jeux de données complexes et déséquilibrés |
| 3 | Extraire des conclusions interprétables reliant les variables statistiques découvertes par l'IA au comportement et au risque humain réel de fraude |

La démarche méthodologique adoptée suit une approche **hypothético-déductive**, s'appuyant sur les savoirs fondamentaux des fédérations d'audit (ACFE, normes internationales) projetés techniquement via une architecture de Machine Learning.

---

## Chapitre 1 — Cadre conceptuel et théorique de la fraude interne

### 1.1 Contexte du projet : la fraude interne à l'ère de l'IA

L'architecture structurelle de l'entreprise moderne est aujourd'hui indissociable de ses systèmes d'information. La digitalisation accélérée des processus métiers a drastiquement réduit les temps de friction opérationnels, mais un corollaire systémique ténébreux est apparu : une extension inédite des *surfaces d'attaque* comportementales aux mains mêmes des employés et dirigeants.

L'évolution de la fraude interne épouse la même course aux armements technologiques que sa contre-mesure. Dans un passé proche, le détournement d'actifs laissait des traces matérielles (signatures, doubles falsifiés, chèques caviardés). Avec la virtualisation des procédures, la malversation est devenue plus insidieuse, s'intégrant dans les recoins des ERP via l'utilisation abusive d'identifiants habilités ou l'ingénierie sociale intra-muros. Des employés malveillants contournent le cloisonnement informatique pour créer des circuits parallèles, fausser les bases de données fournisseurs, modifier temporairement des grilles RH dans un portail cloud, ou produire de faux justificatifs générés par les technologies IA. **Le fraudeur moderne ne s'identifie jamais physiquement ; il se fond dans les dizaines de milliers d'empreintes logicielles quotidiennes.**

L'impact financier, selon le *Report to the Nations* (ACFE, édition 2024), consolide que la fraude occupationnelle coûte environ **5 % du chiffre d'affaires mondial** d'une organisation. La *vélocité de la fraude* aggrave ce constat : il faut souvent entre **12 à 18 mois** pour qu'un acte frauduleux soit initialement détecté, une pénalité accumulée souvent fatale pour les PME et ETI visées.

### 1.2 Définition de la fraude interne

On entend par **Fraude Interne** (ou Fraude occupationnelle), comme l'indiquent conjointement l'ACFE, les normes internationales (ex : norme ISA 240) et le droit commercial :

> L'action intentionnelle, l'omission ou la ruse de dissimulation menée par un salarié pour obtenir un *enrichissement illégitime d'un point de vue personnel*, aboutissant à la soustraction d'un actif tangible (fonds, équipement) ou incorporel (informations, trafic d'influence, base client) de son employeur.

Elle est **opposable** et ne recoupe pas la simple erreur matérielle d'appréciation fortuite, qui relève du dysfonctionnement incompétent.

### 1.3 Le triangle de la fraude (Donald Cressey)

Le modèle central du **Triangle de la Fraude** de Donald Cressey postule que la conjonction de trois éléments interdépendants est nécessaire pour que l'individu cède au passage à l'acte :

| Élément | Description |
|---------|-------------|
| **La Pression / Motivation** | Urgence inextricable et secrète : financière (dettes), sociale, ou culture toxique de pression sur les objectifs |
| **L'Opportunité** | Faille dans les dispositifs de contrôle permettant que le forfait soit réalisé ET dissimulé, sans validation hiérarchique croisée (ségrégation des tâches inexistante) |
| **La Rationalisation** | Ciment moral : l'individu se justifie ("Je vais le rendre !", "J'y ai droit, l'entreprise me paie horriblement mal !") pour compenser l'entrave pénale |

### 1.4 Profils à risque

Transposer ce Triangle au Machine Learning exige de cartographier la data vers des *Profils à Risque* matérialisés sous forme de variables d'entrée quantificatives :

- **Comportements suspects :** Monopolisation anormale des tâches, refus systématique de congés (pour éviter qu'un remplaçant découvre l'anomalie couverte)
- **Anomalies organisationnelles :** Nombre régulier d'annulations et de reprises de commandes, connexions nocturnes répétées d'un directeur
- **Variables RH :** Querelles exponentielles, dégradation faramineuse des évaluations annuelles, litiges répétés traduisant la frustration liée à la *Rationalisation*
- **Variables financières :** Demandes d'achat à 5 999,98 € récurrentes — juste sous le seuil de contrôle hiérarchique obligatoire à 6 000,00 €

### 1.5 Gouvernance et contrôle interne (Cadre COSO)

La solidité du contrôle pour résister au triangle n'est pas l'affaire exclusive du contrôleur des dépenses. Un solide dispositif **COSO** repose notamment sur un *environnement de contrôle* d'une éthique parfaite : *culture de l'anti-fraude*, charte de valeurs, et *Tone at the Top* imposé par le Conseil d'administration. L'intégration des solutions algorithmiques est rendue possible et légitime par ces plus hauts piliers de la gouvernance.

---

## Chapitre 2 — Intelligence artificielle et détection de fraude

### 2.1 Limites du paradigme classique et émergence de l'Audit Augmenté

Les systèmes de contrôle traditionnels basés sur des règles heuristiques (*"Si X dépasse tant, alors alerter"*) souffrent structurellement de la même paralysie que la Ligne Maginot : ils sont efficaces face à de vieux scénarios basiques, mais instantanément contournés dès que le fraudeur comprend le seuil programmé — technique du *Salami Slicing* ou éclatement de la fraude au centime près sous le seuil d'alerte.

Le Machine Learning intervient comme une **asymétrie tactique** en faveur du gestionnaire des risques. L'IA détecte des corrélations illogiques ou improbables, même sur des comportements nouveaux et complexes, chose infaisable par la définition stricte des règles classiques.

### 2.2 Détection rétrospective vs. Prédiction probabiliste

Il est crucial d'acter la profonde distinction entre ces deux approches :

| Approche | Définition | Limites |
|----------|-----------|---------|
| **Détection pure** | Débusque un problème s'opérant dans le temps *t* ou survenu récemment | Réactive, souvent trop tardive |
| **Prédiction probabiliste** | Attribue un *score de probabilité* de fraude à chaque collaborateur ou équipe | Proactive, préventive, nécessite des données historiques qualitatives |

### 2.3 Avantages du Machine Learning

- **Analyse exhaustive des Big Data :** Croisement des bases d'accès physiques, des e-mails de support et du grand livre comptable
- **Détection d'anomalies (Outlier Detection) :** Via apprentissage non supervisé, l'IA fait surgir une ligne de données isolée parmi des millions de lignes RH ou logistiques
- **Identification constante de schémas inédits :** Détecter une association de facteurs qu'aucun humain n'aurait eu l'intuition de relier a priori (ex : une note de frais légalement validée, mais par une équipe n'ayant jamais aucune raison d'opérer avec ce sous-traitant à cette date précise)

### 2.4 Typologie des algorithmes de classification

| Algorithme | Caractéristiques | Usage en détection de fraude |
|-----------|-----------------|------------------------------|
| **Logistic Regression** | Socle statistique lisible, hautement interprétable | Pondération et isolation des variables claires |
| **Decision Tree** | Boîte blanche, scissions logiques explicables | Visualisation des bifurcations comportementales |
| **Random Forest** | Compilation de centaines d'arbres dé-corrélés | Prédiction stable, sans sur-apprentissage |
| **Gradient Boosting** *(XGBoost, LightGBM)* | Minimise itérativement la classification des probabilités rares | Excellent sur les classes rarissimes comme la fraude |
| **Neural Networks** | Traitement de données hautement non structurées | Puissant mais peu explicable aux organes de gouvernance |

---

## Chapitre 3 — Méthodologie et modélisation prédictive

### 3.1 Compréhension des données (EDA)

La fondation est l'**Exploratory Data Analysis**. Le dataset synthétique comprend des dizaines de milliers d'enregistrements portés par plusieurs dizaines de variables clés :

- **Métriques quantitatives :** Salaires, Montant dévié, Ancienneté, Heures travaillées
- **Variables qualitatives :** Département, Poste, Niveau hiérarchique

L'analyse statistique quantifie d'emblée la difficulté centrale du domaine : le **ratio catastrophique de déséquilibre des classes (Class Imbalance)**. Un dataset sain regroupera peut-être 98,5 % de transactions non-frauduleuses face à 1,5 % de probabilité maligne. Un modèle naïf qui prédirait systématiquement l'honnêteté obtiendrait paradoxalement un score de 98,5 % — malgré le désastre stratégique que cela représente.

**Variable Cible (Target Variable) = `Fraude_Interne` : Oui (1) / Non (0)**

### 3.2 Préparation des données

Les algorithmes d'IA ne sont performants qu'au regard de la qualité de ce qu'ils ingèrent :

| Étape | Description |
|-------|-------------|
| **Nettoyage & Imputation** | Un trou dans les données comptables correspond souvent à la fraude elle-même. Les valeurs anormales sont normalisées à la médiane du poste concerné |
| **Encodage / Data-Transformation** | Les variables qualitatives (*"Chef de secteur"*) font l'objet de codages One-Hot (tableau de vérité binaire) ou de regroupements |
| **Normalisation** | Toutes les données sont alignées sur une même échelle mathématique (Standard-Scaler) pour empêcher la forte pondération trompeuse par volume numérique |

### 3.3 Protocole de modélisation prédictive

L'architecture de prédiction est lancée via divers modèles éprouvés par **validation croisée (Cross-Validation)** pour ne jamais apprendre les variables par cœur, mais généraliser à des comportements de fraude non vus :

1. **Logistic Regression** — modèle de lancement offrant l'assise mathématique et la distribution brute des opportunités d'amélioration
2. **Decision Tree** — garantit visuellement et concrètement (Boîte blanche) les bifurcations expliquant le dysfonctionnement comportemental
3. **Random Forest** et **Gradient Boosting Machines** — procurent des niveaux de précision incommensurables face aux nuances liées à la rare présence de "1" dans la variable cible

---

## Chapitre 4 — Analyse des résultats et interprétation

### 4.1 Choix et lecture des métriques d'évaluation

Dans le contexte de lutte anti-fraude, les métriques doivent isoler le risque systémique :

| Métrique | Rôle | Importance |
|----------|------|-----------|
| **Accuracy** | Taux de vérité global | ⚠️ Faussée par l'écrasante présence des classes saines — à ne jamais utiliser seule |
| **Matrice de Confusion** | Visualise les Faux Négatifs (instances frauduleuses classifiées comme saines) | ✅ Essentielle — les Faux Négatifs sont l'erreur vitale de gouvernance |
| **Recall (Sensibilité)** | Ratio global de découverte des fraudes réelles | ✅✅ Métrique reine — la gouvernance préférera un Recall à 98 % même au prix de quelques fausses alertes |
| **Precision** | Proportion de vraies fraudes parmi les alertes émises | ✅ Complémentaire du Recall |
| **F1-Score** | Balance équilibrée Recall/Precision | ✅ Baromètre statistique neutre du comportement de généralisation du modèle |

### 4.2 Interprétation des résultats

Un algorithme complexe doit être **explicatif** pour générer la confiance d'un auditeur. Via les méthodes d'interprétabilité (*SHAP Values* pour un Gradient Boosting ou la visualisation des règles sur l'Arbre de Décision), l'IA attribue l'importance de chaque variable au passage à l'acte.

Cette lecture remonte précisément pour valider les éléments fondateurs du Triangle de Cressey. Par exemple :

> *La fréquence très forte d'usurpations de niveau d'accès, croisée avec une note manager catastrophique et des augmentations de salaire inexistantes*, déterminée statistiquement par l'algorithme, traduit empiriquement la **Pression** et l'**Opportunité** du triangle — donnant un *Red Flag* proactif d'un comportement quasi déviant, à encadrer préventivement, sans pour autant condamner encore le collaborateur.

### 4.3 Appréciation par la gouvernance

Les équipes du contrôle interne ne procèdent plus à une modélisation mathématique du hasard ; elles documentent un effondrement psychologique d'équipes. Les bénéfices générés sont absolus : là où des heures d'enquêtes aveugles faisaient le désarroi des auditeurs, l'algorithme met à mal le bruit statistique sans augmenter les ressources budgétaires, tout en donnant une prévision sécuritaire continue de chaque maillon de l'écosystème commercial.

---

## Conclusion générale

En définitive, l'irruption de l'Intelligence Artificielle et de la Data Science propose des avancées techniquement et stratégiquement inestimables dans les fonctions inhérentes à la conformité d'audit, à la consolidation comptable et au contrôle d'entreprise. La gouvernance des comités n'a guère d'autre issue que d'embrasser activement ces évolutions.

Les sciences de la donnée ne se contentent plus de relater avec inertie les *"cadavres"* d'anomalies anciennes non résolues. Elles proposent au contraire d'endiguer proactivement le phénomène via la détection structurée et probabiliste. L'application des algorithmes de Data Science, de la Logistic Regression aux algorithmes de Gradient Boosting, confirme les préceptes théoriques majeurs du triangle de Cressey.

Si l'implémentation sur le terrain requiert inévitablement de relever des enjeux immenses — qualité de la data, gestion du déséquilibre systémique des classes, enjeux éthiques de la *Boîte Noire* — la gouvernance de la modernité ne substituera jamais la machine à la conscience analytique du métier d'auditeur. Bien au contraire, **la prédiction pure est une arme libérant la conscience de l'auditeur de ses tâches mécanistes**, lui permettant de se concentrer sur son vrai métier originel : enquêter sur l'anomalie signalée, réactiver le contact humain avec l'audité, et garantir au Directoire une immunité maximale.

Ce modèle ouvre ainsi des perspectives enivrantes pour les écoles de Gestion : une *IA de confiance et explicable*, où le contrôle interne retrouve ses armes pour asseoir une pleine résilience face à l'évolution cybernétique grandissante des menaces, garantissant une valorisation intacte des intérêts, des résultats et de l'intégrité morale et financière de toute la matrice organisationnelle.

---

## Bibliographie

| Source | Référence |
|--------|-----------|
| **ACFE** | *Report to the Nations on Occupational Fraud and Abuse*, édition 2024 |
| **Donald Cressey** | *Other People's Money: A Study in the Social Psychology of Embezzlement*, 1953 |
| **COSO** | *Internal Control — Integrated Framework*, Committee of Sponsoring Organizations, 2013 |
| **IFAC / IAASB** | Norme internationale d'audit ISA 240 — *Les responsabilités de l'auditeur concernant les fraudes lors d'un audit d'états financiers* |
| **Scikit-learn** | Documentation officielle des algorithmes de classification et de validation croisée |
| **SHAP** | Lundberg & Lee, *A Unified Approach to Interpreting Model Predictions*, NeurIPS 2017 |

---

*Document rédigé dans le cadre du module Contrôle Interne & Gouvernance — ENCG Settat, L3 S8, Année Universitaire 2024–2025.*
