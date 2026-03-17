<div align="center">

#  THEME : Contrôle interne & Gouvernance
### *Prédiction de la probabilité de fraude interne en entreprise à l'aide de l'intelligence artificielle*

[![Statut](https://img.shields.io/badge/Statut-Projet_Académique-blue?style=flat-square)](#)
[![Domaine](https://img.shields.io/badge/Domaine-Audit_&_Data_Science-success?style=flat-square)](#)

</div>

<br><br>

<table align="center">
  <tr>
    <td align="center">
      <img src="PHOTO PROFIL.jpg" alt="Photo MARZAQ Fatima-Ezzahra" width="130" height="130" style="border-radius:50%; object-fit: cover;"><br>
      <b>MARZAQ Fatima-Ezzahra</b><br>
      Code Apogée : 22007263
    </td>
    <td width="100"></td>
    <td align="center">
      <img src="abdeljalil.jpg" alt="Photo MERZOUK Abdeljalil" width="130" height="130" style="border-radius:50%; object-fit: cover;"><br>
      <b>MERZOUK Abdeljalil</b><br>
      Code Apogée : 24010401
    </td>
  </tr>
</table>

<br>

<div align="center">
<b>À l'attention du corps professoral</b><br>
<i>Année Universitaire : 2025 - 2026</i>
</div>

---

<details>
<summary><b>📑 Table des Matières (Cliquez pour dérouler)</b></summary>

1. [AVANT-PROPOS](#1-avant-propos)
2. [INTRODUCTION GÉNÉRALE](#2-introduction-générale)
3. [Chapitre 1 : Cadre conceptuel et théorique de la fraude interne](#chapitre-1--cadre-conceptuel-et-théorique-de-la-fraude-interne)
4. [Chapitre 2 : Intelligence artificielle et détection de fraude](#chapitre-2--intelligence-artificielle-et-détection-de-fraude)
5. [Chapitre 3 : Méthodologie et modélisation prédictive](#chapitre-3--méthodologie-et-modélisation-prédictive)
6. [Chapitre 4 : Analyse des résultats et interprétation](#chapitre-4--analyse-des-résultats-et-interprétation)
7. [CONCLUSION GÉNÉRALE](#conclusion-générale)
8. [BIBLIOGRAPHIE](#bibliographie)

</details>

---

## 1. AVANT-PROPOS

L'ère contemporaine, marquée par une transformation digitale sans précédent, redéfinit profondément les paradigmes fondamentaux de la gestion d'entreprise, de l'audit et du contrôle interne. Si la numérisation des processus offre des gains d'efficacité notables, elle s'accompagne corollairement d'une complexification systémique des risques. Parmi ces menaces intrinsèques, la fraude interne constitue l'une des manifestations les plus pernicieuses, sournoises et onéreuses d'une gouvernance défaillante.

L'objectif de ce projet est d'explorer et de démontrer comment les technologies avancées, spécifiquement l'intelligence artificielle (IA) et la Data Science, peuvent être intégrées aux dispositifs de gouvernance pour anticiper, détecter et prévenir les comportements frauduleux. La lutte contre la fraude interne n'est plus seulement une exigence réglementaire de conformité, mais un impératif stratégique pour pérenniser la viabilité financière, l’intégrité opérationnelle et la réputation des organisations modernes. 

Ce rapport met en lumière le rôle croissant et indispensable de l'IA dans les métiers de l'audit et du contrôle de gestion. Il souligne une transition majeure : le passage d'un audit traditionnel, souvent rétrospectif et basé sur des échantillonnages statiques, à un audit augmenté, continu et prédictif. L'intérêt de ce projet est ainsi double. Sur le plan pédagogique, il illustre avec rigueur l'application des algorithmes de machine learning sur des données comportementales, organisationnelles et financières. Sur le plan professionnel, il propose un cadre méthodologique applicable par les comités de direction, les auditeurs et les contrôleurs internes pour repenser et doter d'une résilience technologique la gouvernance d'entreprise.

---

## 2. INTRODUCTION GÉNÉRALE

La fraude en entreprise est un phénomène endémique qui transcende les secteurs d'activité, les cadres réglementaires, les zones géographiques et les tailles d'organisation. Selon les éditions successives du rapport mondial *Report to the Nations* publié par l'Association of Certified Fraud Examiners (ACFE), les organisations perdent chaque année une part structurelle de leurs revenus annuels — estimée en moyenne constante à 5 % — en raison de fraudes internes ou occupationnelles. À l'échelle macroéconomique mondiale, l'ampleur de ce phénomène se chiffre en milliers de milliards de dollars, constituant une source silencieuse de destruction de valeur critique.

Historiquement, face à ce risque, les départements d'audit et les fonctions de contrôle interne se sont appuyés sur des méthodes traditionnelles de remédiation et de détection : audits périodiques basés sur le seul jugement professionnel, règles métier statiques ("red flags" figés), alertes manuelles et, par l'impossibilité d'épuiser des populations de données volumineuses, l'échantillonnage aléatoire. Or, confrontées à la volumétrie exponentielle des données numérisées (Big Data) et à la sophistication croissante des schémas de fraude — impliquant souvent des dissimulations cybernétiques ou de complexes collusions internes — ces approches traditionnelles s'avèrent aujourd'hui obsolètes. Trop lentes dans leur exécution et davantage réactives que proactives, elles génèrent par surcroît un taux inexploitable de faux positifs, menant trop souvent à la saturation cognitive des équipes d'investigation.

C'est dans cette rupture que l'émergence exponentielle de la Data Science et de l'intelligence artificielle offre un horizon salvateur aux métiers de l'audit. L'exploitation rigoureuse des modèles mathématiques et de l'apprentissage automatique (Machine Learning) permet l'analyse de l'exhaustivité des transactions. Désormais, des relations non linéaires, des signaux faibles et des comportements anormaux — invisibles et inaccessibles à l'analyse cognitive humaine — peuvent être extraits et qualifiés sous la forme de profils de risques évolutifs.

> **💡 Problématique du projet :**
> *"Comment les techniques d'intelligence artificielle et de machine learning peuvent-elles améliorer la détection et la prédiction de la fraude interne dans les organisations, et quel est leur impact réel sur la solidité du contrôle interne ?"*

**Pour répondre à cette problématique, les objectifs du projet sont les suivants :**
* Fournir un socle conceptuel profond analysant la fraude par le prisme théorique de la criminologie en entreprise (modèle de Donald Cressey) intégré au cadre de la gouvernance (COSO).
* Concevoir une pipeline analytique complète pour appliquer les meilleurs modèles d'apprentissage automatique de Data Science à des jeux de données complexes et déséquilibrés.
* Extraire des conclusions interprétables reliant les variables statistiques découvertes par l'IA au comportement et au risque humain réel de fraude.

La démarche méthodologique adoptée suit une approche globale et hypothético-déductive. Elle s’appuie sur les savoirs fondamentaux établis par les fédérations d'audit (ACFE, normes internationales) tout en les projetant techniquement via une architecture de Machine Learning. 

---

## Chapitre 1 : Cadre conceptuel et théorique de la fraude interne

### 1.1 Contexte du projet et évolution de la fraude à l'ère de l'intelligence artificielle
L'architecture structurelle et organisationnelle de l’entreprise moderne est aujourd’hui indissociable de ses systèmes d'information globaux. La digitalisation accélérée des processus métiers de front, middle, et back-office, couplée à la dématérialisation incessante des flux logistiques et financiers, a drastiquement réduit les temps de friction opérationnels. Si cette mue digitale a optimisé la chaîne de valeur et stimulé la croissance concurrentielle, un corollaire systémique ténébreux est apparu : une extension et une fragmentation inédites des "surfaces d'attaque" comportementales aux mains mêmes des employés et dirigeants de l’entité. 

L’évolution de la fraude interne dans ces organisations est particulièrement révélatrice puisqu'elle épouse la même course aux armements technologiques que sa contre-mesure. Dans un passé proche, le détournement d’actifs ou la falsification de la comptabilité laissaient obligatoirement des traces matérielles. Avec la virtualisation des procédures, la malversation est devenue plus insidieuse, protéiforme, s’intégrant dans les recoins des pare-feux des ERP avec l’utilisation abusive d’identifiants habilités ou l’ingénierie sociale exploitée intra-muros.

Dans cette nouvelle ère de l’invisible, le rôle du contrôle interne revêt désormais une valeur indubitablement stratégique afin de prévenir l'effondrement éthique. La gouvernance exige l'anticipation perpétuelle des conflits d'intérêts et des zones de vulnérabilité. Elle place l'éthique au sommet de la responsabilité fiduciaire (le *Tone at the Top*). L'intégration des technologies avancées dans la détection de la fraude devient donc une composante intrinsèque de ce processus de revitalisation, pavant la voie à **"l'audit augmenté par l'Intelligence Artificielle"**.

### 1.2 Définition juridique, normative et académique de la fraude interne
On entend par Fraude Interne (ou Fraude occupationnelle), comme l'indiquent conjointement l'ACFE, les normes internationales de certification de l'information (ex: norme ISA 240) et le droit commercial, l’action intentionnelle, l'omission ou la ruse de dissimulation menée par un salarié membre du système, pour obtenir un "enrichissement illégitime d’un point de vue personnel", aboutissant indéniablement à la soustraction d’un actif tangible ou incorporel de son employeur. 

### 1.3 Le triangle de la fraude de Donald Cressey
C'est avec l'irruption de l'analyse comportementale de Donald Cressey que la compréhension moderne de la déviance est née. Le génie de cette structure est tout l’intérêt de la modélisation en IA :
* **La Pression / Motivation :** Le collaborateur fait face à une urgence financière (dettes), sociale, ou à une immense culture de la pression toxique.
* **L’Opportunité :** La faille des dispositifs logiques permettant que le forfait soit réalisé ET dissimulé, sans retour de validation hiérarchique croisée.
* **La Rationalisation :** Le ciment moral. Le voleur se convainc de la légitimité de son acte ("L'entreprise me paye horriblement mal !"). 

### 1.4 Profils à risque et identification des dysfonctionnements organisationnels
Transposer ce Triangle au Machine Learning exige de cartographier la data vers des "Profils à Risque" matérialisés sous forme de variables d'entrée quantificatives :
* **Comportements suspects :** Un individu qui monopolise soudainement ses tâches ou renonce à ses congés payés.
* **Anomalies organisationnelles :** Analyser le nombre régulier d’annulations et de reprises des commandes logicielles, ou l'intensité de connexions nocturnes inexpliquées.
* **Variables RH :** Suivi qualitatif du nombre de querelles ou d’une dégradation des évaluations annuelles.
* **Variables financières :** Apparition ininterrompue de demandes d'achat flirtant juste en dessous des seuils d'alerte stricts.

### 1.5 Rôle du contrôle interne et de la culture de l'éthique (Cadre COSO)
La solidité du contrôle pour résister au triangle n’est pas l’affaire exclusive du contrôleur. L’implémentation de solutions algorithmiques est rendue possible par les plus hauts piliers de la gouvernance, articulés autour du "Framework COSO", qui repose sur un "environnement de contrôle" d’une éthique parfaite à imposer.

---

## Chapitre 2 : Intelligence artificielle et détection de fraude

### 2.1 Les limites du paradigme classique face au Big Data et émergence de l'Audit Augmenté
Les systèmes de contrôle traditionnels basés sur des règles paramétrées heuristiques ("Si X dépasse tant, alors alerter") sont instantanément contournés dès l'instant où le fraudeur comprend le seuil des règles programmées pour passer systématiquement sous le radar (le *"Salami Slicing"*). Le Machine Learning intervient comme une asymétrie tactique en faveur du gestionnaire des risques, capable de détecter de la corrélation illogique ou improbable.

### 2.2 Détection rétrospective vs. Prédiction probabiliste
Il est crucial d'acter la profonde distinction entre **la détection pure et la prédiction de fraude**. La détection va débusquer un problème inexpliqué s'opérant dans le temps *t*. La prédiction, elle, cherche structurellement à comprendre et repérer l'étincelle comportementale globale en attribuant aux collaborateurs, équipes ou fournisseurs un "score de probabilité" de fraude interne.

### 2.3 Avantages du Machine Learning
* **L’analyse exhaustive des Big Data** : Croiser terminaux d'accès physiques, e-mails et journaux comptables.
* **La Détection d'anomalies (Outlier detection)** : Faire surgir une ligne de données isolée parmi une galaxie de millions de lignes.
* **L’Identification constante de schémas inédits** : Détecter une association ou combinaison de facteurs invisibles *a priori*.

### 2.4 Typologie des principaux algorithmes de classification
* **Logistic Regression (Régression Logistique) :** Modèle lisible et hautement interprétable pour déterminer une probabilité fiable. 
* **Decision Tree (Arbre de Décision) :** Construit autour de scissions logiques qui expliquent comment le modèle "réfléchit" étape par étape ("Boîte Blanche"). 
* **Random Forest (Forêts Aléatoires) :** Lisse les erreurs d'un arbre unique pour offrir une prédiction générale, stable et sans surapprentissage.
* **Gradient Boosting (ex. XGBoost, LightGBM) :** Minimise les erreurs de classification ; particulièrement efficace face aux classes rarissimes comme l’acte frauduleux.
* **Neural Networks (Réseaux de Neurones) :** Traitent des modèles d'association mathématiques complexes sur des données hautement non structurées.

---

## Chapitre 3 : Méthodologie et modélisation prédictive

### 3.1 Compréhension initiale des données (EDA - Exploratory Data Analysis)
La fondation est l'Exploratory Data Analysis. L’analyse statistique va d'abord cerner la difficulté majeure du domaine : **Le ratio catastrophique de déséquilibre des classes (Class Imbalance).** Un dataset sain regroupera souvent 98,5 % de transactions non-frauduleuses. Un modèle jeté sans comprendre ce déséquilibre sera structurellement biaisé, prédisant naïvement l'honnêteté systématique pour maximiser sa précision globale.

### 3.2 Préparation méticuleuse
* **Nettoyage et Imputation des valeurs manquantes :** Les valeurs anormales ou absentes doivent être normalisées à la médiane du poste concerné, et évaluées avec la plus grande défiance.
* **Encodage / Data-Transformation :** Codages One-Hot (Tableau de vérité Binaire) ou regroupement qualitatif pour les variables textuelles.
* **Normalisation :** Toutes les données numériques doivent être alignées sur une même échelle mathématique (ex: Standard-Scaler) afin d'empêcher une pondération trompeuse liée à l'amplitude des nombres.

### 3.3 Mise en place du protocole de modélisation prédictive
L'architecture de prédiction est lancée via divers modèles éprouvés par validation croisée (Cross Validation) pour généraliser à des comportements non vus de fraude : de la *Logistic Regression* pour la distribution brute, au *Decision Tree* pour l'explicabilité, jusqu'aux algorithmes puissants comme le *Random Forest* et le *Gradient Boosting*.

---

## Chapitre 4 : Analyse des résultats et interprétation

### 4.1 Choix et lecture des métriques d'évaluation algorithmiques
Dans le contexte de lutte anti-fraude d'entreprise, les métriques doivent isoler le risque systémique :
* Ignorer l'approximative **Accuracy** faussée par l’écrasante présence des classes saines.
* Observer la **Matrice de Confusion** pour traquer les "Faux Négatifs" (instances frauduleuses qualifiées de saines).
* **Recall (Sensibilité) :** Métrique reine dans la détection de fraude. La gouvernance préférera un Recall élevé, assumant quelques fausses alertes plutôt que de manquer une fraude réelle.
* **Precision et F1-Score :** Le F1-score offre un baromètre statistique neutre du comportement de généralisation du modèle.

### 4.2 Interprétation des attributs statistiques
Un algorithme complexe a besoin d'être explicatif s'il veut générer la confiance. Via les méthodes d'interprétabilité (*SHAP Values* ou visualisation des arbres), l'IA attribue l'importance d'une variable au passage à l'acte, remontant empiriquement pour valider les éléments du Triangle de Cressey (ex: usurpations d'accès croisées avec une notation RH catastrophique).

### 4.3 Appréciation par la gouvernance
Les équipes du contrôle interne ne modélisent plus le hasard : elles documentent un effondrement psychologique traduisant la "Pression" et l’"Opportunité", créant des "Red Flags" proactifs pour encadrer préventivement les risques.

---

## CONCLUSION GÉNÉRALE

En définitive, nous pouvons observer que l’irruption de l’Intelligence Artificielle et de la Data Science propose des avancées techniquement et stratégiquement inestimables dans les fonctions inhérentes propres de la conformité d'audit, de la consolidation comptable et du contrôle d'entreprise en général. La gouvernance des comités n'a guère d’autre issue que d'embrasser activement ces évolutions dans la modélisation à grande échelle ; en tirant profit de la digitalisation absolue, les sciences de la donnée ne se contentent plus de relater avec inertie à travers d'audits statistiques les "cadavres" d'anomalies anciennes non résolues. Elles proposent au contraire d'endiguer proactivement le phénomène via la détection structurée et probabiliste. L'application des multiples algorithmes et paradigmes liés à la Data Science confirme les préceptes théoriques majeurs développés par les sciences humaines de la fraude interne.

Si l'implémentation sur le terrain de tels outils requiert inévitablement l’absorption d'enjeux immenses sur la qualité réelle et intrinsèque de la data, sur le travail lié au "Déséquilibre systémique des classes" et par les doutes éthiques soulevés vis-à-vis d'une "Boîte Noire" obscure ; en rien, la gouvernance de la modernité ne substituera la machine à une conscience analytique du métier d'auditeur. Bien au contraire, la "prédiction pure" est une arme et un levier d'aide analytique surpuissant libérant la conscience au détriment des tâches mécanistes. Ce modèle ouvre ainsi des perspectives enivrantes pour les écoles scientifiques de Gestion : une "IA de confiance et explicable", garantissant une valorisation intacte des intérêts et de l’intégrité financière de toute la matrice organisationnelle.

---

## BIBLIOGRAPHIE

* **ACFE (Association of Certified Fraud Examiners).** *Report to the Nations on Occupational Fraud and Abuse.* Édition 2024.
* **Cressey, D. R.** (1953). *Other People's Money: A Study in the Social Psychology of Embezzlement*. Free Press.
* **Committee of Sponsoring Organizations of the Treadway Commission (COSO).** *Internal Control - Integrated Framework.*
