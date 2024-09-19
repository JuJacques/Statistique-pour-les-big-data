# Méthodes Statistiques pour les données massives (big data)

Ayez une version à jour de R (moi j'ai la 4.4.0).

Package R nécessaires : car, mctest, MASS, plsdepot (à installer depuis une archive), pls, lars, misaem, missMDA, FactoMineR, mice, glmnet, neuralnet, nnet, e1071, kernlab, doMC, VGAM, adabag, randomForest, rpart, rpart.plot, class, mixOmics.

## Introduction aux big data

- Slides sur la <a href="Big-Data.pdf" target="new">Big Data</a>

## Régression en grande dimension

- Slides sur la <a href="Regression-HD.pdf" target="new">Régression HD</a>
- Jeux de données : <a href="vehicules.txt" target="new">vehicules.txt</a>, <a href="vehicles.txt" target="new">vehicles.txt</a>
- Exercice : <a href="Prostate.Rdata" target="new">Prostate.Rdata</a> (prédidre log(cancer volume))
- Correction des exercices : 

## Classification en grande dimension

- Slides d'<a href="Classification-intro.pdf" target="new">Introduction</a>
- Slides sur la <a href="Classification-plsDA.pdf" target="new">plsDA</a>
- Slides sur les <a href="Classification-randomForest.pdf" target="new">Random Forest</a>
- Slides sur la <a href="Classification-RegressionLogistique.pdf" target="new">Regression Logistique</a>
- Slides sur les <a href="Classification-SVM.pdf" target="new">SVM</a>
- Slides sur les <a href="ReseauxDeNeurones.pdf" target="new">Réseaux de Neurones</a>

- Application : 
     - sur les données <a href="MNIST.Rdata" target="new">MNIST.Rdata</a>, chercher le meilleur modèle pour prédire les chiffres manuscrits contenus dans les images. La fonction suivante sera bien utile pour visualiser ces images :

      show_digit <- function(x, col=gray(12:1/12), title='image') {
        image(matrix(x, nrow=28)[,28:1], col=col, main=title)
      }
      
     - sur les données <a href="breast.tumors.Rdata" target="new">breast.tumors.Rdata</a> du package mixOmics, chercher à prédire si les échantillons ont été analysé avant (BE) ou après (AF) le traitement

- Corrections des exercices :

## Clustering

- Slides sur le<a href="Clustering.pdf" target="new">clustering</a>

- Application : 
     - réaliser un clustering <a href="MNIST.Rdata" target="new">MNIST.Rdata</a> des données MNIST. Choisissez de façon adéquate le nombre de clusters et représenter vos résultats de façon la plus parlante possible

## Prise en compte des données manquantes

- Slides sur la <a href="Donnees-Manquantes.pdf" target="new">Données Manquantes</a>

## Apprentissage sur données de nature hétérogènes

- Application : sur les données <a href="VisaPremier.txt" target="new">Visa Premier</a> (<a href="VisaPremier.pdf" target="new">descriptif des variables</a>), vous chercherez à construire un modèle pour prédire l'appétence à la carte Visa Premier : 
 
   - comparer différentes méthodes
   - interpréter l'impact des variables dans le modèle

## Exercices



