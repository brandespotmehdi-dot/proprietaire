# Courtage Immobilier CRM

Un système CRM complet pour agents immobiliers, développé en HTML, CSS et JavaScript.

## 🏢 Fonctionnalités

- **Tableau de bord** avec KPIs en temps réel
- **Gestion clients** complète (Acheteurs, Vendeurs, Investisseurs)
- **Catalogue de biens** immobiliers avec filtres avancés
- **Pipeline prospects** avec suivi de conversion
- **Calculateur de commissions** automatique
- **Rapports** et analyses de performance
- **Interface responsive** (mobile et desktop)

## 🚀 Installation

### Option 1: GitHub Pages (Recommandé)
1. Fork ce repository
2. Allez dans Settings > Pages
3. Sélectionnez "Deploy from a branch" > "main"
4. Votre application sera accessible à `https://votre-username.github.io/courtage-immobilier-crm`

### Option 2: Installation locale
```bash
git clone https://github.com/votre-username/courtage-immobilier-crm.git
cd courtage-immobilier-crm
# Ouvrir index.html dans votre navigateur
```

## 📱 Usage

### Démarrage rapide
1. Ouvrez `index.html` dans votre navigateur
2. Explorez les différentes sections depuis le menu de navigation
3. Ajoutez vos clients, biens et prospects
4. Utilisez le calculateur de commissions pour vos transactions
5. Consultez vos KPIs dans le tableau de bord

### Gestion des données
- Les données sont sauvegardées localement dans le navigateur
- Exportez régulièrement vos données via les fonctions d'export
- Importez des données existantes via les formulaires

## 🛠️ Structure du projet

```
courtage-immobilier-crm/
├── index.html          # Page principale
├── style.css           # Styles CSS
├── script.js           # Logique JavaScript
├── README.md           # Documentation
└── assets/             # Images et ressources (optionnel)
```

## 📊 Modules inclus

### 1. Tableau de bord
- Métriques mensuelles
- Graphiques de performance
- Objectifs vs réalisations

### 2. Gestion clients
- Base de données clients
- Segmentation par type (Acheteur/Vendeur/Investisseur)
- Historique des interactions
- Planification des rendez-vous

### 3. Catalogue biens
- Inventaire complet des mandats
- Filtres par prix, surface, localisation
- Suivi des visites et offres
- Calcul automatique prix/m²

### 4. Pipeline prospects
- Qualification des leads
- Suivi des sources d'acquisition
- Taux de conversion
- Actions de suivi programmées

### 5. Calculateur commissions
- Calcul automatique des commissions
- Gestion des frais et charges
- Partage entre agents
- Historique des transactions

## 🔧 Personnalisation

### Modification des données par défaut
Editez le fichier `script.js` et modifiez les arrays de données d'exemple :

```javascript
// Exemple de client
const defaultClients = [
    {
        id: 1,
        prenom: "Votre",
        nom: "Client",
        email: "client@example.com",
        // ... autres propriétés
    }
];
```

### Personnalisation du style
Modifiez `style.css` pour adapter les couleurs, polices et mise en page à votre identité visuelle.

### Ajout de fonctionnalités
Le code JavaScript est modulaire, vous pouvez facilement :
- Ajouter de nouveaux champs
- Créer de nouveaux rapports
- Intégrer des APIs externes
- Ajouter des notifications

## 🌐 Déploiement

### GitHub Pages (Gratuit)
1. Créez un repository public sur GitHub
2. Uploadez tous les fichiers
3. Activez GitHub Pages dans les settings
4. Votre app sera disponible en ligne !

### Autres options
- **Netlify** : Drag & drop des fichiers
- **Vercel** : Connexion directe avec GitHub
- **Firebase Hosting** : Pour des besoins avancés

## 📱 Compatibilité

- ✅ Chrome, Firefox, Safari, Edge (versions récentes)
- ✅ Responsive design (mobile, tablette, desktop)
- ✅ Données sauvegardées localement (localStorage)
- ✅ Fonctionne hors ligne une fois chargé

## 🔒 Sécurité et Données

- **Données locales** : Aucune donnée n'est envoyée sur internet
- **Pas de serveur** : Application 100% client-side
- **Vie privée** : Vos données restent sur votre appareil
- **Sauvegarde** : Exportez régulièrement vos données

## 🤝 Contribution

Les contributions sont les bienvenues ! 

1. Fork le projet
2. Créez votre branche (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Commitez vos changements (`git commit -m 'Ajout nouvelle fonctionnalité'`)
4. Push vers la branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Ouvrez une Pull Request

## 📞 Support

Pour toute question ou suggestion :
- Ouvrez une issue sur GitHub
- Documentation complète dans le wiki
- Exemples d'utilisation dans les issues

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 🙏 Remerciements

- Développé pour les professionnels de l'immobilier français
- Interface adaptée aux spécificités du marché français
- Terminologie et processus conformes aux pratiques du secteur

---

**Made with ❤️ for French Real Estate Professionals**