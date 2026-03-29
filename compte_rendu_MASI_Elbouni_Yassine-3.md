<div align="center">

![Texte alternatif](https://github.com/elbouyassi-crypto/MARCH-S-FINANCIERS-MAROCAINS/blob/main/Image_180x210.png)

# COMPTE RENDU — ANALYSE DES MARCHÉS FINANCIERS MAROCAINS
## Dashboard MASI & Indicateurs Macroéconomiques

---

| **Champ**         | **Information**                                      |
|-------------------|------------------------------------------------------|
| **Réalisé**        | Elbouni Yassine                                      |
| **Date**          | 29 mars 2026                                         |
| **Institution**   | ENCG Settat — Université Hassan 1er                  |
| **Objet**         | Analyse du dashboard MASI et indicateurs financiers  |

  

---

## Table des Matières

1. [Introduction et Contexte](#1-introduction-et-contexte)
2. [Périmètre des Données Analysées](#2-périmètre-des-données-analysées)
3. [Analyse de l'Indice MASI](#3-analyse-de-lindice-masi)
4. [Indicateurs Macroéconomiques](#4-indicateurs-macroéconomiques)
5. [Performance des Indices Sectoriels](#5-performance-des-indices-sectoriels)
6. [Marché Monétaire — MONIA & TMP](#6-marché-monétaire--monia--tmp)
7. [Livrables Produits](#7-livrables-produits)
8. [Synthèse et Recommandations](#8-synthèse-et-recommandations)
9. [Conclusion](#9-conclusion)

---

## 1. Introduction et Contexte

Ce compte rendu présente les résultats de l'analyse du dataset **MASI_indice_Dataset**, réalisée dans le cadre d'un travail de visualisation et d'analyse des marchés financiers marocains. L'objectif principal était de transformer un jeu de données brutes issu de la **Bourse de Casablanca** et de **Bank Al-Maghrib** en deux livrables professionnels : un **dashboard HTML interactif** et un **fichier Excel structuré**.

L'ensemble du travail a été réalisé le **29 mars 2026**, par **Elbouni Yassine**, étudiant à l'ENCG Settat — Université Hassan 1er.

<div align="LEFT">


## 2. Périmètre des Données Analysées

Le dataset comprend **8 feuilles distinctes** couvrant plusieurs dimensions des marchés financiers marocains :



| # | Feuille Source                  | Description                              | Volume       |
|---|---------------------------------|------------------------------------------|--------------|
| 1 | **Indices Généraux**            | Cours journaliers MASI                   | 2 366 séances |
| 2 | **Avoirs officiels de réserve** | Réserves hebdomadaires BAM               | 207 semaines  |
| 3 | **CHANGE**                      | Taux de change USD/MAD                   | 1 000 entrées |
| 4 | **MONIA**                       | Indice interbancaire au jour le jour      | 985 séances   |
| 5 | **TMP**                         | Taux Moyen Pondéré                        | 963 séances   |
| 6 | **Inflation**                   | IPC général et sous-jacent               | 21 mois       |
| 7 | **Indices Taux**                | Courbe des taux nominaux (12 maturités)  | 738 séances   |
| 8 | **Indices Sectoriels**          | 24 secteurs cotés                         | 738 séances   |

> **Période couverte :** Décembre 2020 → Décembre 2023

---

## 3. Analyse de l'Indice MASI

### 3.1 Principaux Indicateurs

| Indicateur                  | Valeur        |
|-----------------------------|---------------|
| **Cours de clôture (dernière séance)** | **11 885,32 pts** |
| **Variation journalière**   | **+0,49 %**   |
| **Plus haut historique**    | 13 991,47 pts |
| **Plus bas historique**     | 8 796,65 pts  |
| **Nombre de séances**       | 2 366         |

### 3.2 Observations sur l'Évolution

L'indice **MASI** (Moroccan All Shares Index) affiche une trajectoire globalement **haussière** sur l'ensemble de la période analysée, avec plusieurs phases distinctes :

- **Phase de reprise (2021)** : rebond significatif après le choc de 2020, porté par la confiance des investisseurs et les mesures de soutien économique.
- **Phase de consolidation (2022)** : légère volatilité en lien avec la conjoncture internationale (inflation mondiale, resserrement monétaire).
- **Phase de stabilisation (2023)** : retour vers des niveaux stables autour de 11 500–12 000 pts, avec une tendance positive en fin d'année.

### 3.3 Volatilité et Variations Journalières

Les variations journalières se situent majoritairement dans la fourchette **[-0,5 % ; +0,5 %]**, témoignant d'un marché relativement stable avec des pics ponctuels de volatilité. La variation moyenne sur la période s'établit proche de **0,0 %**, confirmant une tendance directionnelle lente mais positive.

---

## 4. Indicateurs Macroéconomiques

### 4.1 Avoirs Officiels de Réserve

| Composante                  | Dernière valeur (Mds MAD) |
|-----------------------------|---------------------------|
| **Avoirs totaux**            | **353,43**                |
| **Or monétaire**             | 14,34                     |
| **Monnaies étrangères**      | 10,65                     |
| **Dépôts et titres**         | 306,76                    |
| **Avoirs en DTS**            | 19,69                     |
| **Réserves FMI**             | 1,98                      |

Les réserves officielles de **Bank Al-Maghrib** se maintiennent à un niveau robuste, dépassant **350 milliards de MAD**. La composante dominante reste les **dépôts et titres** (environ 87 % du total), reflétant une gestion prudente des avoirs de l'État.

### 4.2 Inflation — Évolution 2022–2023

L'inflation a connu une trajectoire préoccupante sur la période :

- **Pic historique atteint en janvier 2023 : 8,9 %** (inflation générale)
- **Pic de l'inflation sous-jacente : 6,1 %** (mai 2023)
- **Tendance baissière amorcée mi-2023** : retour à **4,9 %** en septembre 2023
- L'inflation sous-jacente, hors énergie et alimentation, suit une trajectoire similaire mais légèrement en dessous de l'inflation générale

> **Contexte :** Cette flambée inflationniste est principalement imputable à la hausse des prix des matières premières, de l'énergie et des produits alimentaires à l'échelle mondiale, accentuée par les effets post-COVID et le conflit russo-ukrainien.

---

## 5. Performance des Indices Sectoriels

### 5.1 Classement par Performance Totale (Déc. 2020 → Déc. 2023)

| Rang | Secteur                                         | Performance |
|------|-------------------------------------------------|-------------|
| 🥇 1 | Participation et Promotion Immobilières         | **+120,13 %** |
| 🥈 2 | Industrie Pharmaceutique                        | **+103,41 %** |
| 🥉 3 | Loisirs et Hôtels                               | **+84,21 %**  |
| 4    | Sylviculture & Papier                           | +52,51 %    |
| 5    | Ingénieries & Biens d'Équipement Industriels    | +31,67 %    |
| 6    | Services de Transport                           | +29,52 %    |
| 7    | Distributeurs                                   | +22,73 %    |
| 8    | Electricité                                     | +14,75 %    |
| 9    | Bâtiment & Matériaux de Construction            | +14,38 %    |
| 10   | Sociétés de Placement Immobilier                | +12,29 %    |

### 5.2 Secteurs en Difficulté

| Secteur                  | Performance |
|--------------------------|-------------|
| Télécommunications       | **-33,37 %** |
| Boissons                 | -2,51 %     |
| Matériels & Logiciels IT | -2,21 %     |
| Sté de Financement       | -1,95 %     |

### 5.3 Observations Sectorielles

- **18 secteurs sur 22** affichent une performance positive sur la période, témoignant d'une reprise économique globalement favorable.
- Le secteur **immobilier et hôtelier** bénéficie du rebond post-COVID du tourisme et de l'immobilier au Maroc.
- La contre-performance des **Télécommunications (-33,4 %)** reste notable et mérite une analyse approfondie (concurrence, pression tarifaire, dépenses d'investissement élevées).
- Le secteur **pharmaceutique** profite des investissements post-pandémie et de la montée en puissance de l'industrie locale.

---

## 6. Marché Monétaire — MONIA & TMP

### 6.1 Indice MONIA

| Indicateur             | Valeur         |
|------------------------|----------------|
| **Dernier taux MONIA** | **2,936 %**    |
| **Volume moyen JJ**    | ~8 900 M MAD   |
| **Tendance**           | Stable / légèrement haussier |

L'indice MONIA (Moroccan Overnight Index Average) reflète le coût de refinancement interbancaire au jour le jour. Il s'établit autour de **2,9–3,0 %** sur les dernières séances, en ligne avec le taux directeur de Bank Al-Maghrib.

### 6.2 Taux Moyen Pondéré (TMP)

| Indicateur                | Valeur    |
|---------------------------|-----------|
| **TMP — dernière séance** | **3,00 %** |
| **Encours moyen**         | ~8 000 M MAD |

Le TMP est resté **parfaitement stable à 3,00 %** sur les dernières séances analysées, confirmant le maintien du taux directeur par **Bank Al-Maghrib** dans un contexte de lutte contre l'inflation, tout en soutenant l'activité économique.

---

## 7. Livrables Produits

### 7.1 Dashboard HTML Interactif

Un dashboard HTML complet et autonome a été généré, structuré en **4 onglets thématiques** :

| Onglet | Contenu |
|--------|---------|
| 📈 MASI & Indices | Évolution 120 séances, variations, fourchette H/B, tableau paginé |
| 🏦 Indicateurs Macro | Réserves (24 semaines), inflation 2022–2023, donut de répartition |
| 🏭 Indices Sectoriels | Performance 22 secteurs, Top 10 classement |
| 💹 Taux & Monétaire | MONIA 90 jours, volumes interbancaires, TMP 60 séances |

**Caractéristiques techniques :**
- Fichier `.html` autonome (zéro dépendance locale)
- Graphiques dynamiques via **Chart.js 4.4**
- Branding ENCG Settat (vert `#006633` / or `#D4A017`)
- Design responsive (mobile et desktop)
- 8 KPI cards synthétiques en en-tête de chaque onglet

### 7.2 Fichier Excel Structuré

Un classeur Excel professionnel a été produit avec **6 feuilles** :

| Feuille | Description |
|---------|-------------|
| 📊 Dashboard KPI | Vue synthèse : 8 KPI cards + Top 10 secteurs |
| 📈 MASI — Indices Généraux | 2 366 séances + graphique linéaire embarqué |
| 🏦 Indicateurs Macro | Réserves + Inflation + 2 graphiques |
| 🏭 Indices Sectoriels | 22 secteurs triés + graphique barres |
| 💹 Taux & Marché Monétaire | MONIA + TMP + graphique linéaire |
| 📂 Sources & Données Brutes | Récapitulatif des sources de données |

**Caractéristiques techniques :**
- Formatage conditionnel (vert hausse / rouge baisse)
- Formules Excel dynamiques (`MAX`, `MIN`, `AVERAGE`, `SUM`)
- Lignes alternées pour lisibilité
- Couleurs ENCG appliquées à tous les en-têtes

---

## 8. Synthèse et Recommandations

### 8.1 Points Forts du Marché Marocain

- **Résilience du MASI** : malgré un contexte mondial difficile (inflation, hausse des taux), l'indice s'est maintenu à des niveaux élevés.
- **Réserves de change solides** : le coussin de réserves (~353 Mds MAD) offre une protection contre les chocs externes.
- **Reprise sectorielle large** : 18/22 secteurs en territoire positif sur la période.
- **Stabilité monétaire** : le TMP stable à 3 % témoigne d'une politique monétaire lisible et anticipée.

### 8.2 Points de Vigilance

- **Inflation structurelle** : bien qu'en baisse depuis le pic de janvier 2023, l'inflation reste au-dessus des niveaux historiques (~5 %).
- **Secteur Télécoms** : la contre-performance de -33 % mérite une attention particulière des investisseurs.
- **Volatilité des réserves** : légère tendance à la baisse des réserves en fin de période, à surveiller.
- **Concentration sectorielle** : les performances très élevées de l'immobilier (+120 %) pourraient masquer des risques de bulle localisée.

### 8.3 Recommandations

1. **Suivre l'évolution de l'inflation** sur les prochains mois pour anticiper un éventuel assouplissement monétaire par BAM.
2. **Approfondir l'analyse sectorielle** en intégrant les données de capitalisation boursière et de volume de transactions.
3. **Enrichir le dataset** avec les données de taux de change EUR/MAD et GBP/MAD pour une analyse du risque de change plus complète.
4. **Automatiser la mise à jour** des dashboards via une connexion API aux flux de données de la Bourse de Casablanca.

---

## 9. Conclusion

Ce travail d'analyse et de visualisation des marchés financiers marocains a permis de transformer un dataset brut complexe (8 feuilles, plusieurs milliers de lignes) en **deux livrables professionnels** — HTML et Excel — facilitant la lecture et l'interprétation des données pour tout utilisateur, qu'il soit analyste, décideur ou étudiant.

L'indice **MASI** clôture la période analysée à **11 885 points**, dans une tendance positive et avec des fondamentaux macroéconomiques globalement solides, malgré les défis inflationnistes de la période 2022–2023.

---

*Compte rendu rédigé par **Elbouni Yassine** — ENCG Settat, Université Hassan 1er*
*Date : **29 mars 2026***
*Source des données : Bourse de Casablanca & Bank Al-Maghrib*

---

> 📎 **Fichiers joints :**
> - `dashboard_MASI.html` — Dashboard interactif complet
> - `dashboard_MASI.xlsx` — Classeur Excel structuré (6 feuilles)
> - `MASI_indice_Dataset_____.xlsx` — Données source originales
