---
layout: page
title: Installation des Environnements de Développement
permalink: /envdev/
---

# Installation des Environnements de Développement

Cette page fournit un guide pour installer les principaux outils de développement : **Visual Studio Code (VS Code)**, **Git**, **Hugo**, et **Jekyll**. Les instructions sont spécifiques à **Windows**, avec des liens vers les guides officiels pour macOS et Linux.

---

## 1. Installation de Visual Studio Code (VS Code)

### Qu'est-ce que VS Code ?

Visual Studio Code (VS Code) est un éditeur de code source moderne et léger développé par Microsoft. Il prend en charge de nombreux langages et offre une large gamme d'extensions pour améliorer la productivité des développeurs.

### Sur Windows

1. **Téléchargez l’installateur** depuis le site officiel : [VS Code](https://code.visualstudio.com/download)
2. **Exécutez l’installateur** (`VSCodeSetup.exe`).
3. **Sélectionnez les options** recommandées :
   - Ajouter VS Code au `PATH`
   - Activer l’intégration avec Git
4. **Lancez VS Code** et vérifiez l’installation.

### Liens pour autres systèmes :

- **macOS** : [Installation sur macOS](https://code.visualstudio.com/docs/setup/mac)
- **Linux** : [Installation sur Linux](https://code.visualstudio.com/docs/setup/linux)

---

## 2. Installation de Git

### Qu'est-ce que Git ?

Git est un système de contrôle de version distribué utilisé pour suivre les modifications de code source et collaborer efficacement sur des projets logiciels. Il est essentiel pour le développement moderne et est utilisé avec des plateformes comme GitHub et GitLab.

### Sur Windows

1. **Téléchargez Git pour Windows** : [git-scm.com](https://git-scm.com/downloads)
2. **Exécutez l’installateur** (`Git-*.exe`).
3. **Options recommandées** :
   - Choisissez `Git Bash` comme terminal par défaut.
   - Activez `Git Credential Manager` pour la gestion des identifiants.
   - Sélectionnez `Use Windows default console`.
4. **Vérifiez l’installation** en ouvrant un terminal et exécutant :
   ```bash
   git --version
   ```

### Liens pour autres systèmes :

- **macOS** : [Installation sur macOS](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- **Linux** : [Installation sur Linux](https://git-scm.com/download/linux)

---

## 3. Installation de Hugo

### Qu'est-ce que Hugo ?

Hugo est un générateur de site statique extrêmement rapide et flexible, écrit en Go. Il est utilisé pour créer des blogs, des sites documentaires et des portfolios sans nécessiter de base de données.

### Sur Windows

1. **Téléchargez l’archive Hugo** depuis le site officiel : [Hugo Releases](https://github.com/gohugoio/hugo/releases)
2. **Extrayez les fichiers** et ajoutez `hugo.exe` au `PATH`.
   - Copiez `hugo.exe` dans `C:\Program Files\Hugo\`
   - Ajoutez `C:\Program Files\Hugo\` au `PATH` via les **Variables d’environnement**.
3. **Vérifiez l’installation** en exécutant :
   ```bash
   hugo version
   ```

### Liens pour autres systèmes :

- **macOS** : [Installation sur macOS](https://gohugo.io/installation/macos/)
- **Linux** : [Installation sur Linux](https://gohugo.io/installation/linux/)

---

## 4. Installation de Jekyll

### Qu'est-ce que Jekyll ?

Jekyll est un générateur de site statique écrit en Ruby. Il est principalement utilisé pour créer des blogs et des sites documentaires et est compatible avec GitHub Pages pour un déploiement simple.

### Sur Windows

Jekyll nécessite **Ruby** pour fonctionner.

1. **Installez Ruby avec RubyInstaller** :
   - Téléchargez **Ruby+Devkit** depuis [rubyinstaller.org](https://rubyinstaller.org/)
   - Exécutez l’installateur et cochez `Add Ruby to PATH`
   - Après l’installation, ouvrez **Git Bash** ou **PowerShell** et exécutez :
     ```bash
     ridk install
     ```
2. **Installez Jekyll et Bundler** :
   ```bash
   gem install jekyll bundler
   ```
3. **Vérifiez l’installation** :
   ```bash
   jekyll -v
   ```

### Liens pour autres systèmes :

- **macOS** : [Installation sur macOS](https://jekyllrb.com/docs/installation/macos/)
- **Linux** : [Installation sur Linux](https://jekyllrb.com/docs/installation/ubuntu/)

---

Ces instructions vous permettent de configurer un environnement de développement complet sur Windows. Si vous utilisez macOS ou Linux, consultez les liens fournis pour suivre les instructions adaptées à votre système.
