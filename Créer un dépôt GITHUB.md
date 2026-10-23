# Créer un dépôt GitHub

## 1. Prérequis

- Avoir un compte [GitHub](https://github.com/).
- Avoir installé Git sur son ordinateur.
- Avoir installé Obsidian si le dépôt sert à sauvegarder ses notes.

Vérifier l'installation de Git dans le terminal :

```bash
git --version
```

## 2. Créer un dépôt sur GitHub

1. Se connecter à [GitHub](https://github.com/).
2. Cliquer sur le bouton **New repository**.
3. Saisir le nom du dépôt, par exemple `mes-notes`.
4. Ajouter une description si nécessaire.
5. Choisir la visibilité :
   - **Public** : accessible à tous.
   - **Private** : accessible uniquement aux personnes autorisées.
6. Cliquer sur **Create repository**.

## 3. Préparer le dossier local

1. Ouvrir le terminal.
2. Se déplacer dans le dossier du projet :

```bash
cd chemin/vers/mon-projet
```

3. Initialiser Git :

```bash
git init
```

4. Ajouter les fichiers au suivi :

```bash
git add .
```

5. Créer le premier commit :

```bash
git commit -m "Initial commit"
```

## 4. Relier le dossier à GitHub

1. Copier l'URL HTTPS du dépôt créé sur GitHub.
2. Déclarer la branche principale :

```bash
git branch -M main
```

3. Ajouter le dépôt distant :

```bash
git remote add origin https://github.com/UTILISATEUR/mes-notes.git
```