# 🩺 Prédiction du Diabète (Pima Indians)

## 📋 Contexte du projet
Le diabète est une maladie chronique majeure. L'objectif de ce projet est de développer un outil de **Machine Learning** capable de prédire la probabilité de diabète chez une patiente en fonction de mesures cliniques simples.

**Dataset :** Pima Indians Diabetes Database (768 patientes).

## 🛠️ Méthodologie
1.  **Exploration des données (EDA) :** Analyse des corrélations et nettoyage (traitement des valeurs manquantes).
2.  **Modélisation :** Comparaison de 3 approches :
    * Régression Logistique (Baseline : 78%)
    * Arbre de Décision (Overfitting détecté)
    * **Random Forest (Modèle retenu : ~81%)**
3.  **Application :** Création d'un simulateur interactif pour tester de nouveaux profils.

## 📊 Résultats Clés
Les facteurs déterminants identifiés par le modèle sont :
1.  Le taux de Glucose.
2.  L'Indice de Masse Corporelle (IMC/BMI).
3.  L'Âge.

Le modèle final atteint une précision de **81%** sur le jeu de test.

## 🚀 Comment utiliser ce projet
1.  Cloner le dépôt.
2.  Lancer le notebook `Pima_Indians_Project_Final.ipynb`.
3.  Utiliser le simulateur à la fin du notebook pour tester vos propres valeurs.

---
*Projet réalisé par [Ton Prénom] - [Date]*
