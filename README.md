# TKS Build Project

[🇫🇷 Français](README.md) | [🇬🇧 English](README.en.md)

## Étude technique préliminaire — pompage d'eau à l'énergie solaire au Sénégal

### 1. Objectif du projet
Ce projet examine le fonctionnement général et les besoins énergétiques préliminaires d'une installation de pompage d'eau à l'énergie solaire signalée à Notto, au Sénégal. L'objectif est d'organiser les informations disponibles, de réaliser une première estimation transparente et d'identifier les données techniques nécessaires avant de conclure sur les performances.

### 2. Informations actuellement disponibles

| Élément | Valeur annoncée | Statut |
|---|---:|---|
| Localisation | Notto, Sénégal | À confirmer précisément |
| Puissance du champ photovoltaïque | 15 kWc | Annoncée ; documentation technique non obtenue |
| Volume d'eau produit | 50 m³/jour | Annoncé ; relevés de mesure non obtenus |
| Type et modèle de pompe | Inconnus | À demander |
| Hauteur manométrique totale (HMT) | Inconnue | À mesurer/calculer |

Ces données sont des éléments préliminaires et ne constituent pas des mesures vérifiées indépendamment.

### 3. Fonctionnement général du système
Les panneaux solaires produisent de l'électricité en courant continu. Un contrôleur adapté ou un variateur de vitesse gère l'alimentation électrique de la pompe. Celle-ci achemine l'eau par les conduites vers un réservoir de stockage, avant sa distribution. La configuration électrique exacte et la présence éventuelle d'un stockage ou d'une alimentation de secours restent à confirmer.

Voir le [schéma de fonctionnement](diagrams/system-flow.md).

### 4. Estimation hydraulique et énergétique préliminaire
Une estimation simplifiée est présentée à partir des hypothèses explicitement théoriques suivantes :
- Volume journalier : 50 m³/jour
- Hauteur manométrique totale : 30 m
- Rendement global du système de pompage : 60 %
- Durée de pompage : 6 heures/jour

Avec ces hypothèses :
- Débit moyen requis pendant le pompage : environ 8,33 m³/h
- Énergie estimée : environ 6,81 kWh/jour
- Puissance électrique moyenne pendant les 6 heures de pompage : environ 1,14 kW

**Il s'agit d'une estimation illustrative, et non d'une validation de l'installation ni d'un dimensionnement final.** Le besoin réel dépend notamment des niveaux d'eau mesurés, de la HMT, des pertes de charge, des performances de la pompe et des conditions d'exploitation. Voir le [détail du calcul](calculations/energy-calculation.md).

### 5. Informations techniques encore nécessaires
Les principales données manquantes sont :
- Profondeur du forage et niveaux d'eau statique et dynamique
- HMT, y compris le dénivelé et les pertes de charge
- Fabricant, modèle, puissance nominale et courbe de la pompe
- Modèle et configuration du contrôleur ou variateur
- Débit réel et durée quotidienne de fonctionnement
- Capacité du réservoir
- Volumes journaliers réellement mesurés et variations saisonnières
- Configuration du champ photovoltaïque et profil de production mesuré

Voir la [liste des données à obtenir](research/missing-data.md).

### 6. Conclusion provisoire
Les valeurs annoncées (15 kWc de puissance photovoltaïque et 50 m³/jour de production d'eau) ne suffisent pas à déterminer si l'installation est correctement dimensionnée ni à évaluer son rendement. Une analyse fiable nécessite le point de fonctionnement hydraulique, la courbe de la pompe, les caractéristiques du contrôleur et des données réelles de production. L'estimation présentée ici constitue uniquement un point de départ transparent.

### 7. État du projet
**Version :** V1 — analyse préliminaire  
**Prochaine étape :** obtenir les spécifications techniques et les mesures d'exploitation auprès de l'opérateur, puis mettre à jour les calculs avec des données confirmées.

---
*Ce document constitue une étude préliminaire indépendante. Les données annoncées concernant l'installation doivent être confirmées par l'opérateur avant d'être considérées comme vérifiées.*
