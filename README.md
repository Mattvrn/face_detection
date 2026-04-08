# face_detection
Ce projet universitaire vise à créer une application qui servirait à reconnaître deux visages identiques.

## Afin d'exécuter le projet :

Il suffit simplement de lancer toutes les cellules du notebook Jupyter (run all). Un temps
d’attente est à prévoir pour l’entraînement des modèles.


Une fois que l’entraînement est terminé, l’application ipywidgets (qui se trouve tout en bas
du notebook) se lancera dans la continuité du run all.


## UTILISATION DE L’APPLICATION
L’application prend en charge tous types d’images classiques (jpeg, png etc.) et s'occupe aussi de la dimension. Il faut
uploader la première image (celle de référence) dans l’upload Image 1, et celle qu’on veut
comparer dans l’upload Image 2.


Une fois que c’est fait, cliquer sur le bouton comparer.
L’application affichera alors la prédiction du modèle FaceNet, et celle du modèle ResNet.


L’application rappelle aussi les scores auc respectifs des modèles, pour donner une
indication de leur fiabilité.
