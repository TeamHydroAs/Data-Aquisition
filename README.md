# Data-Aquisition

## Objectif : Définir et localiser les ensembles de données variés et pertinentes nécessaires pour la modélisation des inondations dans la région du bassin de l'Ouémé à Bonou.

### 1. Données Météorologiques

#### Sources
- **Agence Nationale de la Météorologie (Météo Bénin)**
- **Base de Données ERA de European Centre for Medium-Range Weather Forecasts (ECMWF)**

#### Types de Données
- Précipitations
- Température
- Évapotranspiration
- Pression

#### Procédure de Collecte
- Contacte avec les agences y afférents
- Téléchargement des ensembles disponibles en ligne
- Documentation de toutes les informations associées à chaque ensemble de données

### 2. Données Hydrométriques

#### Sources
- **Direction Générale de l'eau (DGeau) Bénin**
- **Personnes ressources**

#### Types de Données
- Débit et hauteur d'eau

#### Procédure de collecte
- Contacte avec les agences y afférents et des personnes reconnues ressources.

### 3. Données Géographiques 

#### Sources
- **Institut Géographique National du Bénin (IGN)**
- **Source en ligne (USGS Earth Explorer, Google Earth)**
- **Cartes topographiques et hydrographiques**
- **Projets de recherche et publications scientifiques antérieures**

#### Types de Données
- Topographie et élévation (Modèle numérique de Terrain (MNT)
- Cartes satellitaires
- Occupation des sols et couverture végétale

#### Procédure de Collecte
- Téléchargement sur les sites associés
- Recherches des documents pertinents

### 4. Evaluation de la qualité des données
L'évaluation de la qualité des données est est la première étape pour garantir la fiabilité des modèles prédictifs.
Voici les étapes clés utilisées dans cette étude pour effectuer une analyse de la qualité des données :

- **Vérification de l'Exhaustivité** : Cela passe par le comptage des valeurs manquantes (Connaître le pourcentage de valeurs manquantes pour jugez s'il faut combler ou ne pas utiliser cet ensemble de données) et l'analyse de leurs comportements (Aléatoire ou systématique);

- **Contrôle de la Cohérence** : Ici, nous vérifierons les plages des données pour identifier les valeurs abérantes (par Boxplot) ;

- **Évaluation de la Pertinence** : Nous examinerons les relations entre les données (Corrélation) et effectuerons des tests statistiques pour comprendre les données ;

- **Résolution** : Nous vérifierons la résolution des données pour s'assurer de leurs pertinences pour l'étude (Sinon, effectuer un rééchantillonnage) ;
  
- **Rectification des Erreurs** : Corriger les erreurs de saisie et incohérences.

### 5. Outils
- Logiciels statistiques : R et python (Avec les librairies nécessaires)
- Logiciels de la cartographie (Qgis)
- Logiciels hydrologique 
