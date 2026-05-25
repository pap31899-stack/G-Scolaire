# G-Scolaire - Système de Gestion Scolaire 🎓

Application web moderne pour gérer une école complète : élèves, classes, enseignants, notes, paiements.

## 🛠 Technologies

- **Backend** : Node.js + Express
- **Frontend** : React + Tailwind CSS
- **Base de données** : PostgreSQL
- **API** : REST API
- **Authentication** : JWT

## 🚀 Installation rapide

### 1. Base de données
```bash
createdb gscolaire
psql -U postgres -d gscolaire -f database/G-Scolaire.sql
```

### 2. Backend
```bash
cd backend
cp .env.example .env
npm install
npm start
```

### 3. Frontend (bientôt)
```bash
cd frontend
npm install
npm start
```

## 📱 Accès
- **Frontend** : http://localhost:3000
- **API** : http://localhost:5000
- **Preview** : Ouvrez `preview.html` dans le navigateur

## ✨ Fonctionnalités
- ✅ Gestion des élèves
- ✅ Gestion des classes
- ✅ Gestion des notes
- ✅ Gestion des paiements
- ✅ Authentification JWT
- ✅ Dashboard analytics

## 📝 Documentation
Voir les fichiers dans `backend/routes/` pour les endpoints API détaillés.
