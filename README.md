# Statistique-pour-les-big-data

Package R nécessaires : car, mctest, MASS, plsdepot (à installer depuis une archive), pls, lars, misaem, missMDA, FactoMineR, mice, glmnet, neuralnet, nnet, e1071, kernlab, doMC, VGAM, adabag, randomForest, rpart, rpart.plot, class, mixOmics.

## Introduction aux big data

- Slides sur la <a href="Big-Data.pdf" target="new">Big Data</a>

## Régression en grande dimension

- Slides sur la <a href="Regression-HD.pdf" target="new">Régression HD</a>
- Jeux de données : <a href="vehicules.txt" target="new">vehicules.txt</a>, <a href="vehicles.txt" target="new">vehicles.txt</a></p>
- Correction des exercices : <a href="Regression-gasoline.pdf" target="new">données gasoline</a> et <a href="Exercices-Prostate.pdf" target="new">données prostate</a>

- Notes manuscrites : <a href="FormationBigData-20092022.pdf" target="new">19/09/2022</a> 
- Slides annotés : <a href="Regression-HD-19092022.pdf" target="new">19/09/2022</a> 

## Classification en grande dimension

- Slides sur d'<a href="Classification-intro.pdf" target="new">Introduction</a>
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
      
     - sur les données breast.tumors du package mixOmics, chercher à prédire si les échantillons ont été analysé avant (BE) ou après (AF) le traitement


## Prise en compte des données manquantes

- Slides sur la <a href="Donnees-Manquantes.pdf" target="new">Données Manquantes</a>

## Apprentissage sur données de nature hétérogènes

- Application : sur les données <a href="VisaPremier.txt" target="new">Visa Premier</a> (<a href="VisaPremier.pdf" target="new">descriptif des variables</a>), vous chercherez à construire un modèle pour prédire l'appétence à la carte Visa Premier : 
 
   - comparer différentes méthodes
   - interpréter l'impact des variables dans le modèle




