# Rapport de Bug – BUG-TC029

## 🐞 Identifiant du bug
BUG-TC029

## 🧪 Titre
La combinaison recherche + filtre catégorie n’est pas prise en compte

## 📌 Module
Recherche de produit – Page “Products”

## ▶️ Étapes pour reproduire
1. Aller sur [https://automationexercise.com](https://automationexercise.com)  
2. Cliquer sur **Products**  
3. Dans la barre de recherche, saisir le mot-clé : `Blue`  
4. Cliquer sur **Search**  
5. Une fois les résultats affichés, cliquer sur **Women > Tops** dans le filtre de catégorie

## 🔍 Résultat observé
- Tous les produits de la catégorie “Women > Tops” sont affichés  
- Le mot-clé “Blue” est ignoré, même si les produits affichés ne contiennent pas ce mot

## ✅ Résultat attendu
- La catégorie devrait **affiner** les résultats de la recherche “Blue”  
- Le filtre ne devrait pas **écraser** le mot-clé déjà utilisé

## 📎 Gravité
Moyenne à Haute

## ⚙️ Statut
Ouvert

## 🖥️ Environnement
- Navigateur : Chrome  
- Système : Windows / macOS / autre (à adapter selon ton cas)

## 📸 Capture d’écran
Non fournie (à ajouter dans `/screenshots` si besoin)
