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

BASE DE DATOS 3: Alzheimers_disease_data.csv

Tamaño de la base de datos: 2149 filas x 35 columnas

Descripción sobre la base de datos: Esta base de datos contiene información sobre unos 2149 pacientes, contando con datos demográficos, historial médico, evaluaciones cognitivas así como de síntomas, mediciones clínicas, factores respecto al estilo de vida y finalmente, el diagnóstico de enfermedad del Alzheimer. 

Columnas:

Información demográfica:

- Identificador del paciente.
- Edad.
- Género.
- Etnia.
- Nivel de educación que se mide desde 0 hasta 3.

Factores respecto al estilo de vida:

- BMI: Indice de masa corporal que se mide desde 15 hasta 40
- Smooking: Si el paciente fuma o no, 1 indica Sí y 0 indica No.
- AlcoholConsumption: Consumo semanal de alcohol que se mide desde 0 hasta 20.
- PhysicalActivity: Actividad física semanal que se mide desde 0 hasta 10.
- DietQuality: Calidad de la dieta que se mide desde 0 hasta 10.
- SleepQuality: Calidad del sueño que se mide desde 4 hasta 10.

Historial médico:

- FamilyHistoryAlzheimers: Antecedentes familiares de Alzheimer, donde 1 indica Sí y 0 indica No.
- CardiovascularDisease: Presencia de una enfermedad cardiovascular, donde 1 indica Sí y 0 indica No.
- Diabetes: Presencia de diabetes, donde 1 indica Sí y 0 indica No.
- Depression: Presencia de depresión, donde 1 indica Sí y 0 indica No.
- HeadInjury: Antecedentes de traumatismo craneoencefálico, donde 1 indica Sí y 0 indica No.
- Hypertension: Presencia de hipertensión, donde 1 indica Sí y 0 indica No.


Mediciones clínicas:

- SystolicBP: Presión arterial sistólica que se mide entre 90 y 180 mmHg.
- DiastolicBP: Presión arterial diastólica que se mide entre 60 y 120 mmHg.
- CholesterolTotal: Niveles totales de colesterol que varian entre 150 y 300 mg/dL.
- Colesterol LDL: Niveles de colesterol de lipoproteínas de baja densidad que varian entre 50 y 200 mg/dL.
- Colesterol HDL: Niveles de colesterol de lipoproteínas de alta densidad que varian entre 20 y 100 mg/dL.
- CholesterolTriglycerides: Niveles de triglicéridos que varian entre 50 y 400 mg/dL.

Evaluaciones cognitivas y funcionales:

- MMSE: Puntuación en un mini-examen del estado mental que se mide desde 0 hasta 30.
- FunctionalAssessment: Puntuación de una evaluación funcional que se mide desde 0 hasta 10.
- MemoryComplaints: Presencia de quejas de memoria, donde 1 indica Sí y 0 indica No.
- BehavioralProblems: Presencia de problemas de comportamiento, donde 1 indica Sí y 0 indica No.
- ADL: Puntuación de actividades en la vida diaria que se mide desde 0 hasta 10.

Síntomas:

- Confusion: Presencia de confusión, donde 1 indica Sí y 0 indica No.
- Disorientation: Presencia de desorientación, donde 1 indica Sí y 0 indica No.
- PersonalityChanges: Presencia de cambios en la personalidad, donde 1 indica Sí y 0 indica No.
- DifficultyCompletingTasks: Presencia de dificultad para resolver tareas, donde 1 indica Sí y 0 indica No.
- Forgetfulness: Presencia de olvido, donde 1 indica Sí y 0 indica No.

Diagnóstico:

- Diagnosis: Estado del diagnóstico de la enfermedad de Alzheimer, donde 1 indica Sí y 0 indica No.

BASE DE DATOS 4: Diabetes.csv

Tamaño de la base de datos: 768 filas x 9 columnas

Descripción sobre la base de datos: Esta base de datos contiene información sobre 768 personas, contando con características como el grosor de la piel, insulina, presión arterial, glucosa, entre otras. Y con dicha información se busca analizar si el paciente tiene diabetes o no.

Columnas: 

Características y mediciones clínicas:

- Edad.
- Pregnancies: Número de embarazos.
- Glucose: Nivel de glucosa en la sangre.
- BloodPressure: Medición de la presión arterial.
- SkinThickness: Indica el grosor de la piel.
- Insulin: Nivel de insulina en la sangre.
- BMI: Indice de masa corporal.
- DiabetesPedigreeFunction: Porcentaje de diabetes de caracter hereditaria.
- Outcome: Estado del diagnóstico de diabetes, donde 1 indica Sí y 0 indica No.
