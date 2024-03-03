# Projet : Gestion du réseau de transport de la ville de Tokyo

## Mode d’emploi compilation

### 1. Description 
Ce programme est une application conçue pour gérer et optimiser le réseau de métro de Tokyo. Il implémente des structures de données avancées et l'algorithme de Dijkstra pour calculer le chemin le plus court entre deux stations. 

### 2. Prérequis 
- Compilateur GCC 
- Environnement Unix/Linux 

### Installation 
1. Clonez ou téléchargez le répertoire du projet sur votre machine. 
2. Assurez-vous que tous les fichiers source (.c et .h) ainsi que le makefile sont dans le même dossier. 

### Compilation 
Pour compiler le programme, ouvrez votre terminal, naviguez vers le dossier du projet et exécutez la commande suivante : 
```bash
make 
```
Cette commande va générer un exécutable nommé projet_metro. 

### Exécution 
Pour lancer le programme, exécutez la commande suivante dans le terminal : 
```bash
./projet_metro 
```

### Utilisation 
Une fois le programme lancé, suivez les instructions à l'écran pour interagir avec le système. Vous pourrez : 
- Trouver le chemin le plus court entre deux stations. 
- Afficher des informations sur les différentes lignes de métro. 
- Quitter le programme à tout moment. 

### Nettoyage 
Après avoir fini d'utiliser le programme, vous pouvez nettoyer les fichiers compilés en exécutant :	 
```bash
make clean
```
