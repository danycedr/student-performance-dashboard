# 🎓 Student Performance Dashboard (MongoDB + DataViz)

📊 Analyse interactive des performances scolaires des élèves avec MongoDB, JavaScript, et Chart.js

---

## 🔍 Contexte du projet

Ce projet vise à analyser les **facteurs qui influencent la réussite scolaire** des élèves, à partir d’un dataset réel.  
L’objectif est de mettre en évidence :
- L’impact du **cours de préparation**
- Les inégalités selon le **genre**, le **niveau d’éducation des parents**, et le **groupe ethnique**
- Les **corrélations entre les différentes matières**

Les données sont stockées dans MongoDB, exploitées avec des agrégations, puis visualisées via un tableau de bord en HTML/JS/Chart.js.

---

## 🧠 Objectifs pédagogiques

- Maîtriser les **requêtes avancées MongoDB**
- Créer un **dashboard interactif** avec JavaScript + Chart.js
- Organiser un projet comme une **application pro** (backend + frontend)
- Présenter un projet clair et exploitable sur GitHub

---

## 📁 Dataset utilisé

🗂️ [Students Performance Dataset – Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---

## ⚙️ Fonctionnalités du dashboard

- ✅ Moyennes par matière
- ✅ Comparaison des scores par genre / origine
- ✅ Impact du cours de préparation
- ✅ Histogrammes, courbes, pie charts (Chart.js)
- ✅ Profil complet par élève (radar, barres)

---
## 📊 Exemples de questions traitées

## 🧠 Performance globale
- Quelle est la moyenne générale des élèves dans chaque matière ?
- Combien d’élèves ont une moyenne supérieure à 80 ?
- Quelle est la proportion d’élèves en échec (note < 50) ?
- Quels sont les élèves les plus performants (top 10%) ?
- Quels élèves ont les écarts les plus marqués entre les matières ?

## 👩‍🎓 Analyse par genre
- Les filles sont-elles globalement meilleures en lecture et écriture ?
- Les garçons ont-ils de meilleurs résultats en mathématiques ?
- Le genre influence-t-il la régularité des résultats entre les matières ?

## 👨‍👩‍🎓 Analyse par origine sociale / ethnique
- Y a-t-il des inégalités de performance selon le groupe ethnique ?
- Quel groupe a la moyenne la plus élevée en mathématiques ?
- Le type de repas (standard vs réduit) a-t-il un impact significatif sur les résultats ?
- L’éducation des parents améliore-t-elle les performances scolaires ?

## 📚 Impact pédagogique
- Le cours de préparation améliore-t-il vraiment les résultats ?
- Dans quelle matière l’impact du cours est-il le plus visible ?
- Le taux de réussite (note ≥ 60) est-il plus élevé pour ceux qui ont suivi le cours ?
- Est-ce que les élèves sans cours de préparation échouent plus souvent ?

## 📈 Corrélations & Comparaisons entre matières
- Les élèves bons en mathématiques le sont-ils aussi en écriture ?
- Quelle est la matière la plus "corrélée" aux autres ?
- Peut-on prédire le score de lecture à partir du score d’écriture ?
- Y a-t-il des profils "lecture forte / maths faible" et inversement ?

## 🔎 Segmentation des élèves
- Combien d’élèves sont "bons dans tout" (≥70 partout) ?
- Quels sont les profils d’élèves en difficulté ?
- Peut-on identifier des groupes d’élèves à accompagner en priorité ?
- Quels sont les 3 facteurs les plus liés à la réussite globale ?
---

## 🧪 Requêtes MongoDB utilisées

- `$match`, `$group`, `$sort`, `$project`, `$unwind`, `$lookup`, `$avg`, `$count`, `$bucket`
- `$expr`, `$cond`, `$dateFromString` pour les dates

## 🛠️ Technologies utilisées

| Outil        | Rôle                        |
|--------------|-----------------------------|
|**MongoDB**  | Base de données NoSQL       |
|**Chart.js** | Graphiques et visualisation |
|**HTML/CSS/JS** | Interface du dashboard   |
|**Node.js/Express** | API REST si back-end |

---
