# PROGRAMAS
## Instalación

Para este proyecto se utilizarán tres programas:
- CRISPRCasFinder
- CRISPRDetect
- CRISPRminer

### CRISPRCasFinder

Para descargar el programa, se debe ejecutar el siguiente comando:
```
 $ sudo apt-get install CRISPRCasFinder
```
Después de descargar el archivo correspondiente, es necesario descomprímirlo y e ir al repositorio del programa:
```
$ unzip CRISPRCasFinder.zip
$ cd CRISPRCasFinder
```

Para ejecutar la búsqueda de posibles secuencias repetidas y espaciadoras en cada uno de los genomas de estudio, se ejecuta el siguiente comando: 
```
$ CRISPRCasFinder.pl -in sequence.fasta -md 20 -t 33.3 -mr 11 -r 55 -ms 11 -xs 60 -pm 0.6 -p 2.5 -s 60
```

> - in: Archivo de entrada
> - -md: Porcentaje de mismatches entre secuencias repetidas (20)
> - -t: Porcentaje de mismatches entre secuencias repetidas truncadas (33.3)
> - -mr: Longitud mínima de la secuencia repetida (11)
> - -xr: Longitud maxima de la secuencia repetida (55)
> - -ms: Longitud mínima de la secuencia espaciadora (11)
> - -xs: Longitud máxima de la secuencia espaciadora (60)
> - -pm: Longitud mínima del espaciador en función de la longitud mínima de la secuencia repetida (0.6).
> - -s : Porcentaje máximo de similitud entre secuencias espaciadoras (60%). 

Los comandos utilizados para el análisis de las secuencias de los genomas, se realiza con base en la información disponible en el manual del programa: 

> Note: https://github.com/dcouvin/CRISPRCasFinder/blob/master/CRISPRCasFinder_Viewer_manual.pdf


### CRISPRDetect y CRISPRminer

Para ejecutar estos programas se utilizarán las versiones en línea, utilizando los siguientes parámetros: 

> - Longitud mínima de la secuencia repetida: 11 pb
> - Longitud máxima de la secuencia repetida: 50 pb
> - Tamaño mínimo de las secuencias espaciadores en función del tamaño de las secuencias repetidas: 0.6
> - Tamaño máximo de espaciadores en función del tamaño de repetición: 2.5
> - Porcentaje máximo de similitud entre los espaciadores: 60%






 
