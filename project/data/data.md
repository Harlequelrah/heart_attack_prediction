Explication des colonnes (GPT)

- 🔹 1. age

➡️ Âge du patient (en années)
C’est une variable quantitative simple. Plus l’âge augmente, plus le risque cardiovasculaire est généralement élevé.

- 🔹 2. sex

➡️ Sexe du patient

1 = Homme
0 = Femme
👉 Facteur important car les maladies cardiaques ont des distributions différentes selon le sexe.


- 🔹 3. cp (chest pain)

➡️ Type de douleur thoracique

1 : Angine typique (douleur classique liée au cœur)
2 : Angine atypique (douleur inhabituelle mais possiblement cardiaque)
3 : Douleur non angineuse (probablement pas liée au cœur)
4 : Asymptomatique (aucune douleur)

👉 Variable clé : elle donne un indice direct sur la nature des symptômes.

- 🔹 4. trestbps (resting blood pressure)

➡️ Pression artérielle au repos (en mmHg)
Mesurée à l’admission à l’hôpital.
👉 Une pression élevée est un facteur de risque majeur.

- 🔹 5. chol

➡️ Taux de cholestérol sérique (mg/dl)
👉 Un taux élevé favorise l’accumulation de plaques dans les artères.

- 🔹 6. fbs (fasting blood sugar)

➡️ Glycémie à jeun > 120 mg/dl

1 = Oui (hyperglycémie)
0 = Non

👉 Indique un possible diabète, facteur de risque cardiovasculaire.

- 🔹 7. restecg (resting electrocardiographic results)

➡️ Résultats de l’électrocardiogramme au repos

0 : Normal
1 : Anomalie des ondes ST-T (peut indiquer un problème cardiaque)

👉 Permet de détecter des anomalies électriques du cœur.

- 🔹 8. thalach

➡️ Fréquence cardiaque maximale atteinte
👉 Indique la capacité du cœur à répondre à un effort.

- 🔹 9. exang (exercise induced angina)

➡️ Angine induite par l’exercice

1 = Oui
0 = Non

👉 Si une douleur apparaît à l’effort, c’est un signe fort de problème cardiaque.

- 🔹 10. oldpeak

➡️ Dépression du segment ST induite par l’exercice
👉 Mesure ECG indiquant un stress cardiaque.
Plus la valeur est élevée, plus le risque est important.

- 🔹 11. slope

➡️ Pente du segment ST au pic d’exercice

1 : Montante (moins inquiétant)
2 : Plate
3 : Descendante (plus inquiétant)

👉 Utilisée pour affiner le diagnostic.

- 🔹 12. ca

➡️ Nombre de vaisseaux principaux obstrués (0 à 3)
Détecté par fluoroscopie (imagerie médicale).
👉 Plus ce nombre est élevé, plus la maladie est avancée.

- 🔹 13. thal

➡️ Résultat du test de thallium (imagerie cardiaque)

3 : Normal
6 : Défaut fixe (dommage permanent)
7 : Défaut réversible (problème temporaire)

👉 Très important pour évaluer la perfusion du cœur.

- 🔹 14. num (target)

➡️ Diagnostic de maladie cardiaque

0 : Pas de maladie (< 50% de rétrécissement)
1 : Maladie présente (> 50% de rétrécissement)

👉 🎯 C’est la variable cible (celle que ton modèle devra prédire).
