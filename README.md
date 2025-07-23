# 🛍️ Analyse des Ventes & Recommandations Business (2024)

Ce projet présente une pipeline d’analyse de données appliquée à un jeu de données e-commerce issu du dépôt UCI. Il couvre toutes les étapes : du nettoyage des données à la formulation de recommandations stratégiques, en passant par la création d’un tableau de bord interactif sous Power BI.

---

## 🔍 Objectif du Projet

Analyser les ventes en ligne pour :
- Identifier les pays et segments clients les plus rentables
- Évaluer la répartition des revenus
- Proposer des actions concrètes pour optimiser la performance commerciale

---

## 🧰 Technologies Utilisées

- **Python** : nettoyage et préparation des données (Pandas, NumPy)
- **Power BI** : visualisations interactives et indicateurs clés
- **Jeu de données UCI Online Retail** : données brutes d’achat

---

## 📊 Étapes Réalisées

### 1. Nettoyage des Données (Python)
- Suppression des valeurs manquantes et doublons
- Filtrage des transactions annulées
- Création de nouvelles variables :
  - `Revenue` = `Quantity * UnitPrice`
  - `Segment Client` basé sur les revenus générés

### 2. Construction des KPIs
- Revenu total par pays et continent
- Valeur moyenne du panier
- Segmentation clients (Petit / Moyen / Gros / Top acheteurs)

### 3. Création du Dashboard Power BI
- Cartes, graphiques et KPIs dynamiques
- Comparaison des pays/segments par rapport à la moyenne
- Interface filtrable (pays, segment, période)

### 4. Recommandations Business
- Cibler les régions les plus performantes pour l’expansion
- Fidéliser les acheteurs moyens et les faire monter en gamme
- Proposer des actions correctives pour les zones en retrait

---

## 📈 Aperçu

> 🔗 *Lien public Power BI à venir*  
> 🖼️ Export PDF ou PowerPoint disponible dans le dossier `dashboard/`

---

## 🗂️ Structure du Répertoire

| Fichier / Dossier | Description |
|-------------------|-------------|
| `data_cleaned_uncleaned/online_retail_clean.csv` | Données nettoyées et non nttoyées |
| `notebook/ecommerce_notebook.ipynb` | Code Python de traitement des données |
| `dashboard/online_retail.pbix` | Fichier Power BI interactif |
| `README.md` | Description complète du projet |

---

## 🔮 Prochaines Étapes

- [x] Nettoyage et enrichissement des données
- [x] Visualisation Power BI
- [x] Publication du dashboard en ligne
- [ ] Intégration future dans une interface utilisateur (type PowerApps)

---

## 🤝 Contact

N’hésitez pas à cloner ce projet, proposer des améliorations ou me contacter :

- 📩 [LinkedIn: Louise Charline NDONGUEP TCHOUANKAM]
- 🌐 [Bientôt....]
