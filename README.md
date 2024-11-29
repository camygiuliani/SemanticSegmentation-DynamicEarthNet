## Obiettivo del progetto
Semantic segmentation su immagini del dataset DynamicEarthNet (Daily Multi-Spectral Satellite Dataset for Semantic Change Segmentation)
scaricabile al link https://mediatum.ub.tum.de/1650201

Le immagini del dataset hanno 12 bande di cui se ne sono prese in esame 4.
Ho fatto un'importante modifica alle label: poichè la classe 6 e la classe 3 erano scarsamente presenti all'interno delle immagini contenute in questa porzione di dataset, ho modificato i valori di label con valore 6 e 3 in -1, mentre i valori 4 e 5 sono diventati rispettivamente 3 e 4 . In questo modo ho allineato le classi da predirre.Esse sono
**0 1 2 3 4** 

## Purpose of the project
Semantic segmentation on images from the DynamicEarthNet dataset (Daily Multi-Spectral Satellite Dataset for Semantic Change Segmentation) available for download at https://mediatum.ub.tum.de/1650201

The images in the dataset have 12 bands, four of which were examined. I made an important change to the labels: since class 6 and class 3 were scarcely present within the images contained in this portion of the dataset, I changed the label values 6 and 3 to -1, while values 4 and 5 became 3 and 4 respectively. In this way I aligned the classes to be predicted. 
They are **0 1 2 3 4**.



Bibliografia/References:
-https://github.com/aysim/dynnet
-https://arxiv.org/pdf/2203.12560
-https://arxiv.org/abs/2203.12560
-https://discovery.ucl.ac.uk/id/eprint/10125535/1/Accepted%20version-Convolutional%20Neural%20Networks%20for%20Water%20segmentation%20using%20Sentinel_Full.pdf
-https://www.youtube.com/watch?v=IHq1t7NxS8k&t=2106s

## Tesina LABIAGI --- IAGI lab work----
