BASE DE DATOS 1: 
Parkinson data.csv

TAMAÑO: 
Filas (Registros): 195
Columnas (Variables): 23
195 filas x 24 columnas


DESCRIPCIÓN:
La base de datos es un conjunto de registros de voz utilizados para la detección de la enfermedad de Parkinson. Los datos se obtuvieron a partir de la fonación sostenida del sonido producida por pacientes diagnosticados con Parkinson y personas sanas. A partir de estas grabaciones se extrajeron parámetros acústicos relacionados con frecuencia, variabilidad, perturbación de la señal, ruido y complejidad de la voz.
Se borró una columna.

DESCRIPCIÓN COLUMNAS:
status: Variable objetivo: indica si la persona tiene Parkinson (1) o no (0). 
MDVP: Fo (Hz): Frecuencia fundamental promedio de la voz (en Hz).
MDVP: Fhi (Hz): Frecuencia fundamental máxima registrada (en Hz).
MDVP: Flo (Hz): Frecuencia fundamental mínima registrada (en Hz).                                                
MDVP: Jitter (%): Variación porcentual en la frecuencia de vibración de las cuerdas vocales (inestabilidad tonal).
MDVP: Jitter (Abs): Variación absoluta de la frecuencia fundamental.                                                 
MDVP: RAP: Promedio relativo de perturbación de la frecuencia.                                              
MDVP: PPQ: Cociente de perturbación por períodos sucesivos.                                                 
Jitter: DDP: Diferencias absolutas de los valores RAP.                                                        
MDVP: Shimmer: Variación en la amplitud de la voz (inestabilidad en volumen).                                   
MDVP: Shimmer (dB): Variación de amplitud en decibeles.                                                              
Shimmer: APQ3: Cociente de perturbación de amplitud en 3 períodos.                                              
Shimmer: APQ5: Cociente de perturbación de amplitud en 5 períodos.                                              
MDVP: APQ: Cociente medio de perturbación de amplitud.                                                      
Shimmer: DDA: Diferencias dobles en los valores APQ3.                                                          
NHR: Relación entre ruido y armonía (ruido más alto sugiere deterioro vocal).                         
HNR: Relación armonía-ruido (valores altos implican mejor calidad vocal).                             
RPDE: Entropía no lineal: mide complejidad en la señal de voz.                                         
DFA: Análisis de fluctuación detrended: cuantifica autocorrelación a largo plazo.                     
spread1: Medida estadística de la energía espectral.                                                      
spread2: Segunda medida relacionada con la distribución espectral.                                        
D2: Dimensión correlacional: patrón de repetición en la señal.


BASE DE DATOS 2: 
Preterm.csv

TAMAÑO: 
Filas (Registros): 58
Columnas (Variables): 6
58 filas x 6 columnas


DESCRIPCIÓN:
La base de datos contiene información relacionada con contracciones uterinas registradas en mujeres embarazadas, con el objetivo de analizar patrones que permitan diferenciar entre embarazos con parto pretérmino y parto a término. Cada fila corresponde al registro de una serie de contracciones y contiene medidas cuantitativas obtenidas de señales uterinas.

DESCRIPCIÓN COLUMNAS:
count_contraction: Número total de contracciones detectadas durante la medición.
length_of_contraction: Duración total de las contracciones (en unidades de tiempo definidas por el estudio).
Std: Desviación estándar de la señal uterina asociada a las contracciones, representa variabilidad.
Entropy: Medida de complejidad o irregularidad de la señal de contracción. Mayor valor indica contracciones más impredecibles.
contraction_times: Frecuencia o cantidad de episodios de contracción durante el periodo medido.
Preterm: Variable objetivo: indica si el caso corresponde a parto pre-término (1) o parto a término (0).

