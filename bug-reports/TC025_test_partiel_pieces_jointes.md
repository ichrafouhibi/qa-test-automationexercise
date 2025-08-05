# Rapport de Test Partiel – TC025

## 🐞 Identifiant
TC025

## 🧪 Titre
Vérification de l’envoi de pièces jointes via le formulaire Contact Us (test partiel)

## 📌 Module
Formulaire de contact – Page “Contact Us”

## ▶️ Étapes pour reproduire
1. Aller sur https://automationexercise.com  
2. Cliquer sur **Contact Us**  
3. Remplir tous les champs obligatoires  
4. Joindre un fichier (image, PDF, etc.)  
5. Cliquer sur **Submit**

## 🔍 Résultat observé
- Le formulaire accepte la pièce jointe et ne génère pas d’erreur côté client  
- Le message de confirmation s’affiche : “Success! Your details have been submitted successfully.”  
- **Impossible de vérifier la réception de la pièce jointe côté serveur/utilisateur final**

## ✅ Résultat attendu
- Le formulaire accepte la pièce jointe  
- Le fichier est correctement transmis et reçu (non vérifiable dans ce test)

## ⚠️ Limite du test
- Absence d’accès à la réception côté backend ou utilisateur final pour vérifier la pièce jointe

## 📎 Gravité
Basse (test partiel)

## ⚙️ Statut
Test partiel effectué – à compléter si possible

## 🖥️ Environnement
- Navigateur : Chrome (ou autre)  
- Système : Windows / macOS / Linux / Android

## 📸 Capture d’écran
Non fournie
