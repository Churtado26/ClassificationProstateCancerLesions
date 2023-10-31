# Classification of clinically significant lesions of prostate cancer in MRI sequences.

# Autor 
_César Hurtado Rodríguez_

# Dataset
El conjunto de datos a utilizar es el dataset de **PI-CAI CHALLENGE**, el cual cuenta con 1500 estudios con estas características:
+ De los **1500** estudios, **425** son con lesión.
+ De los **425** con lesión, **220** son con marcación y grado **(ISUP)**.
+ Los **205** restantes se sabe que sienen lesión significativa pero no existe marcación ni grado.
+ Ahora de los **1500**, hay **1075** sin lesión significativa.
Así se conforman esos **1500 estudios** los cuales cada uno de ellos cuenta con 3 modalidades de **MRI** **T2WI, ADC Y B-VAL (DWI)**.

# __*Datos adicionales*__
+ Un paciente puede tener mas de un estudio de **MRI**.
+ Un estudio puede tener mas de una lesión **clinicamente significativa**.
+ Una lesión clínicamente significativa se define como **ISUP >= 2** la cual es la escala histopatológica de lesiones de cancer de próstata que dice que tan crítica o de que grado es la lesión en un estudio **HISTOPATOLÓGICO** que este es un estudio el cual se analizan la células y tejidos de interés mediante un microscopio los cuales han sido extraídos previamente mediante una biopsia.

[Click para ir al sitio oficial de PI-CAI CHALLENGE](https://pi-cai.grand-challenge.org/)

# Idea general del proyecto
El diagnóstico temprano para el cáncer de próstata a partir de una **imagen de resonancia magnética** es importante para poder determinar un tratamiento oportuno al paciente, el problema en esto es que este diágnostico muchas veces depende del experto y es subjetivo e incierto llegando a un desacuerdo entre radiologos, para esto se busca desarrollar un modelo de aprendizaje profundo para la clasificación de lesiones clínicamente significativas de próstata en secuencias MRI
