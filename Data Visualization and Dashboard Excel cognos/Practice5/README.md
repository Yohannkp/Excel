# 📊 Hands-on Lab – Visualisations avec IBM Cognos Analytics

Ce TP a été réalisé dans le cadre du **IBM Data Analyst Professional Certificate**.

🎯 Objectif : créer un tableau de bord interactif dans **Cognos Analytics**, permettant à un manager régional d’analyser les ventes et services de plusieurs concessions automobiles.

---

## 🛠️ Outils utilisés

- IBM Cognos Analytics (version d’essai gratuite)
- Données internes à Cognos : `Auto group data module`

---

## 📁 Jeu de données

Les données proviennent du **IBM Accelerator Catalog** (secteur automobile) et sont intégrées à Cognos via le module :  
**Auto group data module**  
🔗 [Conditions d'utilisation](https://developer.ibm.com/terms/ibm-developer-terms-of-use/)

---

## 🧪 Étapes réalisées

### 🔹 Accès aux données

1. Ouverture de Cognos Analytics
2. Accès :  
   `Team content` → `Samples` → `By industry` → `Automotive` → `Data`
3. Clic droit sur **Auto group data module** → **Create Dashboard**

---

## 🖥️ Création des tableaux de bord

### 🧾 **1. Sales Dashboard**

**Template utilisé :** tab avec **4 petits rectangles en haut** et **1 grand rectangle en bas**  
**Nom de l’onglet :** `Sales`

#### ▶️ Panels du haut :

| Panel | Indicateur                             | Type de visualisation         |
|-------|----------------------------------------|-------------------------------|
| 1     | Profit (en M USD, 1 décimale)          | KPI / Texte formaté           |
| 2     | Quantity sold                          | KPI                           |
| 3     | Quantity sold by model                 | Bar chart                     |
| 4     | Average quantity sold                  | KPI                           |

#### 📊 Panel du bas :

| Panel | Indicateur                             | Type de visualisation         | Spécificités               |
|-------|----------------------------------------|-------------------------------|----------------------------|
| 5     | Profit by Dealer ID                    | Column chart                  | Trié par ordre croissant  |

📷 ![alt text](<Capture d'écran 2025-05-01 165749.png>)

---

## 🧠 Réalisé par

**Assiawassa Yendi (Yohann)**  
🎓 Étudiant en Master Big Data & Intelligence Artificielle  
🔗 [Portfolio](https://yohannkp.github.io/portfolio) – [GitHub](https://github.com/Yohannkp) – [LinkedIn](https://linkedin.com/in/yendi-aharh)

---

## 👨‍🏫 Auteurs du Lab

> TP proposé par IBM dans le cadre du certificat professionnel  
> Auteur : *Steve Ryan*  
> Contributeur : *Sandip Saha Joy*

---

> _« Un bon tableau de bord n'est pas une vitrine de données, mais un guide pour l’action. »_
