# Rapport de Bug – BUG-TC023

## 🐞 Identifiant du bug
**BUG-TC023**

## 🧪 Titre du bug
Le formulaire "Contact Us" accepte l'envoi avec des champs vides (sauf l’email)

## 📌 Module concerné
Formulaire de contact – Page “Contact Us”

## ▶️ Étapes pour reproduire
1. Aller sur [https://automationexercise.com](https://automationexercise.com)  
2. Cliquer sur **Contact Us**  
3. Laisser les champs **Nom**, **Sujet** et **Message** vides  
4. Saisir uniquement un email valide  
5. Cliquer sur **Submit**

## 🔍 Résultat observé
- Le formulaire est soumis avec succès, sans aucun avertissement
- Message affiché : *“Success! Your details have been submitted successfully.”*

## ✅ Résultat attendu
- Le système devrait empêcher la soumission si **l’un des champs suivants est vide** :  
  - Nom  
  - Sujet  
  - Message  
- Un message de validation ou une alerte devrait s’afficher

## 📎 Gravité
Moyenne

## ⚙️ Statut du bug
Ouvert

## 🖥️ Environnement de test
- Navigateur : Chrome (ou autre si tu veux préciser)
- Système : Windows / macOS / Linux / Android

## 📸 Capture d’écran
_Non fournie pour le moment_ (à ajouter dans `/screenshots` si besoin)
