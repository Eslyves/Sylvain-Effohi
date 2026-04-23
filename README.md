# Projets Java orientés Science et Analyse de Données
## Projet 3: Analyse d’un fichier CSV
Ce projet consiste à développer une application Java permettant l'analyse de fichiers CSV
contenant des données numériques. L'objectif est de calculer automatiquement des statistiques
descriptives tout en respectant les principes SOLID.

# Taches realisées
## Creation de :
- ILecteur : Interface abstraite pour la lecture de données.
- LecteurCSV : Implémente l'interface ILecteur
  Seule responsabilité : lire un fichier CSV et retourner les données.
- IAfficheur : Interface séparée uniquement pour l'affichage console.
  Affiche les statistiques dans la console.
- AfficheurConsole : implements IAfficheur.
  Seule responsabilité : afficher les statistiques dans la console.
- Statistiques : Classe avec une seule responsabilité : stocker les statistiques d'une colonne
  numérique (moyenne, min, max).  
