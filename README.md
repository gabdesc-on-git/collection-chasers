# ObjectDex - Collection d'Objets du Quotidien

ObjectDex est une application web gamifiée qui transforme la collection d'objets du quotidien en jeu captivant, similaire à un Pokédex. Photographiez des objets pour les ajouter à votre collection, découvrez leur valeur en euros, et partagez vos trouvailles avec vos amis.

## 🎮 Fonctionnalités

- **📸 Capture d'objets** : Utilisez votre caméra pour photographier et identifier des objets
- **💰 Valeurs en euros** : Chaque objet a une valeur correspondant à son prix réel
- **🌟 Système de rareté** : Objets communs, peu communs, rares et épiques
- **👥 Système d'amis** : Ajoutez des amis et suivez leur activité
- **🏆 Classements** : Comparez vos collections avec d'autres joueurs
- **🎯 Badges et objectifs** : Débloquez des achievements en collectionnant

## 🚀 Technologies

- **Frontend** : React 18 + TypeScript + Vite
- **Backend** : Node.js + Express + TypeScript
- **Styling** : Tailwind CSS + shadcn/ui
- **État** : TanStack Query
- **Routing** : Wouter
- **Base de données** : PostgreSQL (production) / Mémoire (développement)

## 📱 Installation

### Prérequis
- Node.js 18+
- npm ou yarn

### Développement local
```bash
# Cloner le projet
git clone https://github.com/votreusername/objectdex.git
cd objectdex

# Installer les dépendances
npm install

# Lancer en mode développement
npm run dev
```

L'application sera disponible sur `http://localhost:5000`

## 🌐 Déploiement

### Vercel (Recommandé)
1. Forkez ce repository
2. Connectez votre compte Vercel à GitHub
3. Importez le projet dans Vercel
4. Le déploiement se fera automatiquement

### Variables d'environnement
```env
NODE_ENV=production
DATABASE_URL=your_postgres_connection_string
```

## 📖 Structure du projet

```
├── client/              # Application React frontend
│   ├── src/
│   │   ├── components/  # Composants UI réutilisables
│   │   ├── pages/       # Pages de l'application
│   │   ├── hooks/       # Hooks React personnalisés
│   │   └── lib/         # Utilitaires et configuration
├── server/              # API Express backend
│   ├── index.ts         # Point d'entrée serveur
│   ├── routes.ts        # Routes API
│   └── storage.ts       # Gestion des données
├── shared/              # Types partagés
│   └── schema.ts        # Schémas de base de données
└── package.json
```

## 🎯 Utilisation

1. **Accueil** : Consultez votre collection et les objets disponibles
2. **Caméra** : Photographiez des objets pour les identifier et les ajouter
3. **Amis** : Connectez-vous avec d'autres collectionneurs
4. **Classement** : Voyez où vous vous situez par rapport aux autres
5. **Profil** : Consultez vos statistiques et achievements

## 🔧 Développement

### Scripts disponibles
- `npm run dev` : Lance le serveur de développement
- `npm run build` : Compile le projet pour la production
- `npm run start` : Lance le serveur de production

### Contribution
1. Forkez le projet
2. Créez une branche pour votre feature
3. Committez vos changements
4. Poussez vers la branche
5. Ouvrez une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 🤝 Support

Pour toute question ou suggestion, n'hésitez pas à ouvrir une issue sur GitHub.

---

Transformez votre quotidien en aventure de collection avec ObjectDex ! 🎮✨
