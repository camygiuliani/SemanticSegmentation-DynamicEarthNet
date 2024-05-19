# Tesina LABIAGI
-- Lavoro per laboratorio IAGI----

## Obiettivo del progetto
Semantic segmentation su immagini del dataset DynamicEarthNet (Daily Multi-Spectral Satellite Dataset for Semantic Change Segmentation)
scaricabile al link https://mediatum.ub.tum.de/1650201

Le immagini del dataset hanno 12 bande di cui se ne sono prese in esame 4.
Ho fatto un'importante modifica alle label: poichè la classe 6 e la classe 3 erano scarsamente presenti all'interno delle immagini contenute in questa porzione di dataset, ho modificato i valori di label con valore 6 e 3 in -1, mentre i valori 4 e 5 sono diventati rispettivamente 3 e 4 . In questo modo ho allineato le classi da predirre
**0 1 2 3 4** 
