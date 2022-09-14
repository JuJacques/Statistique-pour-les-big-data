# Statistique-pour-les-big-data

## Introduction aux big data

## Régression en grande dimension

- Slides sur la <a href="Regression-HD.pdf" target="new">Régression HD</a>
- Jeux de données : <a href="vehicules.txt" target="new">vehicules.txt</a>, <a href="vehicles.txt" target="new">vehicles.txt</a></p>

## Classification en grande dimension

- Slides sur d'<a href="Classification-intro.pdf" target="new">Introduction</a>
- Slides sur la <a href="Classification-plsDA.pdf" target="new">plsDA</a>
- Slides sur les <a href="Classification-randomForest.pdf" target="new">Random Forest</a>
- Slides sur la <a href="Classification-RegressionLogistique.pdf" target="new">Regression Logistique</a>
- Slides sur les <a href="Classification-SVM.pdf" target="new">SVM</a>
- Slides sur les <a href="ReseauxDeNeurones.pdf" target="new">Réseaux de Neurones</a>

- Jeux de données : <a href="MNIST.Rdata" target="new">MNIST.Rdata</a>, avec la fonction suivante qui sera bien utile pour visualiser ces données :<br>
      show_digit <- function(x, col=gray(12:1/12), title='image') {<br>
        image(matrix(x, nrow=28)[,28:1], col=col, main=title)<br>
      }

## Prise en compte des données manquantes

## Apprentissage sur données de nature hétérogènes

- Application sur les données <a href="VisaPremier.txt" target="new">Visa Premier</a> (<a href="VisaPremier.pdf" target="new">descriptif des variables</a>). Objectif : 
      - comparer différentes méthodes pour prédire l'appétence à la carte Visa Premier
      - interpréter l'impact des variables dans le modèle




