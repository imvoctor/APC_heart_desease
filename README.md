# Pràctica Kaggle APC UAB 2022-23
### Nom: Arnau Ruzo ### DATASET: Heart_desease
### URL: [kaggle](https://www.kaggle.com/datasets/zgeakyldz/heart-desease-data?resource=download))
## Resum
El dataset utilitza dades de...
Tenim X dades amb N atributs. Un % d'ells és categoric / els altres són numérics i estàn normalitzats...
### Objectius del dataset
El objetivo principal, és, predecir si una persona tendrá una enfermedad cardiaca o no mediante la base de datos de heart_desease. Para conseguir esto, hemos aplicado 4 diferentes modelos y los hemos comparado para saber qual es el que mejor predice nuestros casos.
## Experiments
Durante esta práctica emos aplicado diferentes modelos, en concreto 4 modelos diferentes y los emos comparado entre si para ver cual de los 4 nos predecia mejor. A la hora de aplicarlos, emos provado si era mejor normalizar los datos, que hiperparametros eran los que nos daban los mejores resultado y hemos validado cada uno de los modelos con ROC curves o Confussion matrix.
### Preprocessat
Quines proves hem realitzat que tinguin a veure amb el pre-processat? com han afectat als resultats?
### Model
| Model | Hiperparametres | Mètrica | Temps |
| -- | -- | -- | -- |
| Random Forest | 500 Trees | 80.33% | 100ms |
| SVM | kernel: lineal  C:1 | 62.3% | 200ms |
| SVM | kernel: rbf  C:1 | 70.49% | 200ms |
| Red neuronal | activation: relu   epochs: 500   loss: binary crossentropy   metrics: accuracy | 83.6% | 1500ms |
| Decissin Tree | - | 73.77% | 200ms |

## Conclusions
El mejor modelo que se ha conseguido ha sido la red neuronal en cuanto a accuracy. Aun asi, yo me quedaria con el random forest ya que hemos podido comprobar que tiene una f1 score bastante alta.

## Idees per treballar en un futur
Crec que seria interesant indagar més en...


Links interes.
https://fhernanb.github.io/libro_mod_pred/rand-forests.html
https://rstudio-pubs-static.s3.amazonaws.com/24341_184a58191486470cab97acdbbfe78ed5.html
https://fhernanb.github.io/libro_mod_pred/rand-forests.html

