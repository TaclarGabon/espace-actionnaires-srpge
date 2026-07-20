# SRPGE Firebase V1

## Avant le test

### 1. Activer Authentication
Dans Firebase :
- Sécurité > Authentication
- Commencer
- Mode de connexion
- Activer **Adresse e-mail/Mot de passe**

### 2. Créer Firestore
- Firestore
- Créer une base de données
- Choisir le mode Production
- Choisir une région proche des utilisateurs

### 3. Installer les règles
Dans Firestore > Règles, remplacer le contenu par celui de `firestore.rules`, puis publier.

### 4. GitHub
Téléverser `index.html` à la racine du dépôt de test.

## Fonctionnalités
- Création d’un compte test par courriel/mot de passe
- Connexion/déconnexion
- Réinitialisation du mot de passe
- Enregistrement du profil
- Sauvegarde et rechargement des souscriptions
- Prévisualisation du bulletin SRPGE
