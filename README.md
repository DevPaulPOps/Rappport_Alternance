# 📚 Rapport d'Alternance 2023-2024

Rapport d'alternance rédigé en LaTeX détaillant mon expérience professionnelle et les projets réalisés.

## 📖 Structure du Document

```sh
src/
├── main.tex              # Document principal
├── introduction/         # Introduction du rapport
├── entreprise/          # Présentation de l'entreprise
├── projetFYT/          # Détails du projet FYT
├── projetSandBox/      # Détails du projet SandBox
├── conclusion/         # Conclusion du rapport
├── bibliographie/      # Références bibliographiques
├── glossaire/          # Définitions des termes techniques
└── image/             # Ressources visuelles
```

## 📋 Contenu Principal

Le rapport couvre les aspects suivants :

- **Introduction**: Contexte de l'alternance et objectifs
- **L'Entreprise**: Présentation et organisation
- **Projet FYT**: Réseau social pour les sportifs
- **Projet SandBox**: Projet découverte du devops
- **Conclusion**: Bilan et perspectives

## 🛠️ Technologies Utilisées

- **LaTeX**: Système de composition de documents
- **Git**: Gestion de versions
- **VS Code**: Éditeur de texte avec extensions LaTeX

## 📥 Installation

1. **Prérequis**

   - Distribution TeX (TeX Live, MiKTeX)
   - Éditeur LaTeX (VS Code + extensions recommandées)

2. **Cloner le projet**

   ```bash
   git clone git@github.com:DevPaulPOps/Rapport_Alternance.git
   cd Rapport_Alternance
   ```

## 📝 Compilation

Pour compiler le document :

```bash
# Avec latexmk
latexmk -pdf main.tex

# Compilation manuelle
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Le PDF généré se trouve dans le dossier `out/`.

## 📊 Illustrations

Le rapport contient plusieurs illustrations :

- Captures d'écran des applications développées
- Diagrammes organisationnels
- Schémas techniques
- Interfaces utilisateur

## 🔍 Note

Ce rapport est un document académique réalisé dans le cadre d'une formation en alternance. Le PDF final est disponible dans le dossier `out/`.

---

_Réalisé par Paul Perigault dans le cadre d'une formation en alternance._
