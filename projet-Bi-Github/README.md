# Retail Analytics Dashboard — Global Superstore

Dashboard Power BI construit sur le dataset public Global Superstore (Kaggle), couvrant 9 994 commandes entre 2014 et 2017 aux États-Unis. L'objectif est d'analyser les performances commerciales, la rentabilité, le comportement clients et la logistique à travers 4 pages interactives.

---

## Le projet en quelques mots

J'ai voulu construire un projet BI complet de A à Z — de l'audit des données brutes jusqu'aux insights finaux — en utilisant uniquement Power BI, DAX et Power Query. Pas de données fictives, pas de template tout fait : un vrai dataset, un vrai problème business, une vraie modélisation.

---

## Ce que le dashboard analyse

**Page 1 — Vue générale**
Chiffre d'affaires total, bénéfice, nombre de commandes et marge bénéficiaire. Évolution temporelle des ventes, répartition par segment et carte géographique par État.

**Page 2 — Analyse des ventes**
Comparaison des ventes année par année (2014–2017), décomposition du bénéfice par catégorie via un waterfall chart, et analyse de l'impact des remises sur la rentabilité via un scatter plot.

**Page 3 — Clients & RFM**
Segmentation de 793 clients en 4 groupes (Champions, Fidèles, Potentiels, À risque) selon leur fréquence d'achat et leur chiffre d'affaires. Top 10 clients avec alerte sur les profils à profit négatif.

**Page 4 — Logistique**
Délai moyen de livraison par mode d'expédition et par région. Analyse du taux de commandes non rentables selon le Ship Mode choisi.

---

## Quelques chiffres trouvés dans les données

- Une remise supérieure à 50% fait passer le profit moyen de +67$ à -105$
- Sean Miller est le client n°1 en chiffre d'affaires ($25K) mais génère un profit négatif (-$1 981)
- Standard Class représente 60% des commandes avec le délai le plus long (5 jours) et le taux de perte le plus élevé (19.7%)
- Home Office est le plus petit segment (18.7% du CA) mais affiche la meilleure marge (14%)

---

## Stack utilisée

Power BI · DAX · Power Query · Python (audit qualité) · Dataset Kaggle

---

## Auteure

**Nelly MALIEDJE** — Data Analyst Junior | Master 2 Data/IA & Management
[LinkedIn](https://linkedin.com/in/nelly-maliedje) · maliedjenelly@yahoo.com
