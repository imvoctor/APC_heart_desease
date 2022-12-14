# APC_heart_desease
Proyecto de APC UAB ingenieria informatica de prediccion de enfermedades cardiacas.

Nom: David Feliu de la peña Vilarroig
DATASET: League of Legends SOLO-Q Ranked Games
URL: [kaggle](https://www.kaggle.com/datasets/bobbyscience/league-of-legends-soloq-ranked-games)
## Objectius
El objetivo principal, és, predecir si una persona tendrá una enfermedad cardiaca o no mediante la base de datos de heart_desease. Para conseguir esto, hemos aplicado 4 diferentes modelos y los hemos comparado para saber qual es el que mejor predice nuestros casos.

## Resolución
Durante esta práctica emos aplicado diferentes modelos, en concreto 4 modelos diferentes y los emos comparado entre si para ver cual de los 4 nos predecia mejor. A la hora de aplicarlos, emos provado si era mejor normalizar los datos, que hiperparametros eran los que nos daban los mejores resultado y hemos validado cada uno de los modelos con ROC curves o Confussion matrix.

### Model
| Model | Parametros | Mètrica |
| -- | -- || -- |
| Random Forest | n_estimators = 500 | 80.33%|
| SVM | kernel = linear | 62.3% |
| SVM | kernel = rbf | 70.49% |
| Red Neuronal |activation = relu, loss  = binary_crossentropyk, metrics = accuracy, epochs = 500 | 83.61% |
| Decision Tree | - | 73.77% |
## Conclusions

## Idees per treballar en un futur

Links interes.
https://fhernanb.github.io/libro_mod_pred/rand-forests.html
https://rstudio-pubs-static.s3.amazonaws.com/24341_184a58191486470cab97acdbbfe78ed5.html
https://fhernanb.github.io/libro_mod_pred/rand-forests.html

Dataset
https://www.kaggle.com/datasets/zgeakyldz/heart-desease-data?resource=download
