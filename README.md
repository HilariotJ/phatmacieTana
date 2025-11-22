📱 Annuaire des Pharmacies - Antananarivo
Application Android d'annuaire des pharmacies de Antananarivo avec recherche en temps réel et fonctionnalités de contact.

🎯 Description
Une application mobile complète qui répertorie les pharmacies de Antananarivo avec leurs coordonnées, horaires d'ouverture et statut de garde. L'application permet aux utilisateurs de trouver rapidement une pharmacie proche et de la contacter directement.

✨ Fonctionnalités
🔍 Recherche en temps réel par nom ou adresse

📞 Appel direct vers les pharmacies

🗺️ Intégration Google Maps pour localisation

🚨 Identification des pharmacies de garde

📱 Interface moderne et intuitive

🌙 Affichage des horaires détaillés

🏗️ Structure du Projet
text
app/
├── src/main/java/com/pharmacietana/
│   └── MainActivity.java
├── res/
│   ├── layout/
│   │   └── activity_main.xml
│   └── values/
│       └── strings.xml, colors.xml, etc.
└── AndroidManifest.xml
📊 Données Incluses
L'application contient plus de 150 pharmacies réparties dans Antananarivo et ses environs, avec :

✅ Noms complets des pharmacies

✅ Adresses détaillées

✅ Numéros de téléphone

✅ Horaires d'ouverture

✅ Statut de garde (24h/24)

🚀 Installation
Prérequis
Android Studio Arctic Fox ou version ultérieure

SDK Android 21 (Android 5.0) minimum

Connexion Internet pour les fonctionnalités Maps

Étapes d'installation
Cloner le repository

bash
git clone https://github.com/votre-username/pharmacie-tana.git
Ouvrir le projet dans Android Studio

Synchroniser les dépendances Gradle

Exécuter sur un émulateur ou appareil physique

🛠️ Configuration
Permissions requises
xml
<uses-permission android:name="android.permission.CALL_PHONE" />
<uses-permission android:name="android.permission.INTERNET" />
Dépendances principales
gradle
implementation 'androidx.appcompat:appcompat:1.6.1'
implementation 'com.google.android.material:material:1.9.0'
📖 Utilisation
Recherche : Tapez le nom d'une pharmacie ou un quartier dans la barre de recherche

Localisation : Cliquez sur l'adresse pour ouvrir dans Google Maps

Appel : Cliquez sur le numéro pour composer directement

Filtrage : Identifiez les pharmacies de garde avec le badge rouge

🎨 Interface
Cartes modernes avec effet d'élévation

Couleurs sémantiques (bleu pour les liens, rouge pour les urgences)

Typographie claire et hiérarchie visuelle

Espacement optimisé pour une lecture facile

🔧 Développement
Architecture
Activité Unique : Pattern MainActivity avec gestion complète

Filtrage Dynamique : Recherche en temps réel sans base de données

Programmatique : Interface générée dynamiquement pour flexibilité

Classes Principales
MainActivity
Gestion de l'interface utilisateur

Implémentation de la recherche

Gestion des intents (appels, maps)

Pharmacie (classe interne)
java
static class Pharmacie {
    String nom;
    String adresse; 
    String telephone;
    String horaires;
    boolean isGarde;
}
Méthodes Clés
filtrerPharmacies() : Filtrage en temps réel

ajouterPharmacieALayout() : Génération d'interface dynamique

formatTitleCase() : Formatage des noms propres

📈 Améliorations Futures
Géolocalisation automatique

Base de données locale

Synchronisation cloud

Notifications push (pharmacies de garde)

Mode hors-ligne

Recherche par spécialité

Système de favoris

🤝 Contribution
Les contributions sont les bienvenues ! Pour contribuer :

Fork le projet

Créer une branche feature (git checkout -b feature/AmazingFeature)

Commit les changes (git commit -m 'Add some AmazingFeature')

Push sur la branche (git push origin feature/AmazingFeature)

Ouvrir une Pull Request

📄 Licence
Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.

👥 Auteurs
Votre Nom - Développement initial - VotreUsername

🙏 Remerciements
Données collectées auprès des services de santé locaux

Inspiration : Applications de santé publique

Communauté Open Source Android

⭐ N'oubliez pas de mettre une étoile si ce projet vous est utile !

📞 Support
Pour toute question ou problème, veuillez ouvrir une issue sur GitHub.

🏥 À Propos des Données
Les données des pharmacies sont régulièrement mises à jour pour assurer leur exactitude. Si vous constatez une erreur ou une omission, merci de nous en informer.

Dernière mise à jour : Décembre 2024

