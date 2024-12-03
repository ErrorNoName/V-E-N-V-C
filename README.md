# Venv Manager - Gestionnaire d'Environnements Virtuels Python 🐍

![Logo](https://via.placeholder.com/728x90.png?text=Venv+Manager) <!-- Ajoutez un logo ici si souhaité -->

**Venv Manager** est un outil puissant et interactif pour créer et gérer des environnements virtuels Python rapidement et efficacement. Doté d'une interface conviviale, de messages interactifs, et d'un système avancé de gestion des dépendances, ce script Bash facilite le développement Python.

---

## 📋 Fonctionnalités

- **Création rapide d'environnements virtuels Python** via `venv`.
- **Vérification et installation automatique des dépendances nécessaires** (`python3`, `figlet`, `pv`, etc.).
- **Interface interactive** avec `dialog` pour une expérience utilisateur intuitive.
- **Gestion des dépendances :**
  - Installation depuis un fichier `requirements.txt`.
  - Installation manuelle de packages supplémentaires.
- **Système de logs et feedback utilisateur** avec animations et barres de progression.
- **Compatible avec la majorité des distributions Linux.**

---

## 🚀 Installation

### Prérequis
- Système d'exploitation : **Linux**.
- Logiciels requis : 
  - `python3` (version 3.6 ou plus)
  - `dialog`
  - `figlet`
  - `pv`
- Gestionnaire de paquets : `pip`.

Pour installer ces outils (si nécessaire), exécutez :
```bash
sudo apt update && sudo apt install python3 python3-pip dialog figlet pv -y
```

### Installation du script
Clonez le dépôt Git :
```bash
git clone https://github.com/ErrorNoName/V-E-N-V-C.git
cd V-E-N-V-C
```

Rendez le script exécutable :
```bash
chmod +x create_venv.sh
```

---

## 🛠️ Utilisation

Exécutez le script pour démarrer :
```bash
./create_venv.sh
```

### Étapes interactives
1. **Vérification des dépendances :** Le script vérifiera et installera automatiquement les outils nécessaires.
2. **Création de l'environnement virtuel :** Si un environnement existe déjà, le script vous le notifiera.
3. **Gestion des dépendances :** Choisissez parmi les options suivantes :
   - **Installer depuis `requirements.txt`** si le fichier existe.
   - **Installer manuellement des packages.**
   - Ignorer l'installation des dépendances.
4. **Activation automatique de l'environnement virtuel.**

Une fois terminé, l'environnement virtuel est prêt à être utilisé. Vous pouvez commencer à travailler immédiatement !

---

## 🌟 Fonctionnalités avancées

### Système de logs
- **Logs informatifs** affichés en couleur verte.
- **Messages d'erreur** en rouge en cas de problème.
- Suivi en temps réel des actions (barres de progression, animation).

### Fichier `requirements.txt`
- Si le fichier n'existe pas, il sera créé automatiquement.
- Après l'installation des packages, le fichier sera mis à jour avec les dépendances installées.

### Animation
- Animation de chargement (spinner) pour une expérience utilisateur améliorée.

---

## 📂 Structure des fichiers

```
V-E-N-V-C/
├── create_venv.sh       # Script principal
├── requirements.txt     # Fichier pour les dépendances (généré automatiquement)
└── README.md            # Documentation
```

---

## 🔧 Personnalisation

- **Changer le nom du script :** Modifiez la variable `SCRIPT_NAME` pour personnaliser le titre affiché.
- **Modifier le répertoire de l'environnement virtuel :** Changez la variable `VENV_DIR` selon vos préférences.

---

## 💻 Contribution

Les contributions sont les bienvenues ! Si vous avez des idées pour améliorer le script :
1. Forkez le dépôt.
2. Créez une branche : `git checkout -b feature/nom-feature`.
3. Effectuez vos modifications.
4. Soumettez une Pull Request.

---

## 📜 Licence

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](./LICENSE) pour plus d'informations.

---

### 🚧 Notes importantes
- Ce script est principalement conçu pour les systèmes Linux. Une compatibilité Windows nécessitera des modifications.
- Assurez-vous d'avoir les permissions suffisantes pour installer les dépendances nécessaires.

**Auteur :** Ezio/ErrorNoName  
**Dépôt :** [V-E-N-V-C](https://github.com/ErrorNoName/V-E-N-V-C)
```
