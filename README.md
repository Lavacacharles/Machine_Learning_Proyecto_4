# Machine_Learning_Proyecto_4

## **Integrantes:**

1. Juan Leibniz Aquino Espinoza
2. Ximena Nicolle Lindo Peña
3. Margiory Alvarado Chávez
4. Ronaldo Dylan Flores Soto

## **Descripción General**

### **_Dataset:_** [Whale Calls to Prevent Collisions](https://www.kaggle.com/competitions/project-4-whale-calls-2024-2/overview "Project 4: Whale Calls 2024-2")

El problema es clasificar un caso como ballena franca o no basándose en una señal de audio.

Esos casos positivos contienen un conjunto de llamadas ascendentes de ballena franca.

Las llamadas ascendentes son la vocalización de ballena franca más comúnmente documentada con una firma acústica de aproximadamente 60 Hz a 250 Hz, que suele durar 1 segundo.

Cada serie está etiquetada como que contiene una ballena franca o no con el objetivo de identificar correctamente la serie que contiene llamadas ascendentes.

Las llamadas de ballena franca a menudo pueden ser difíciles de escuchar ya que la banda de baja frecuencia puede congestionarse con sonidos antropogénicos como el ruido de los barcos, las perforaciones, los pilotes o las operaciones navales.

_Cada caso es un segmento de audio de dos segundos muestreado a 2 kHz, lo que da una longitud de serie de 4000._

### **Instrucciones**

- Analice y extraiga las características del conjunto de datos pertinentes al problema que seleccionó en el paso anterior. Justifique sus decisiones.
- Elige al menos dos métodos (incluido al menos uno aprendido en clase) para resolver el desafío propuesto que seleccionaste. Justifica tus decisiones.
- Informar las métricas adecuadas. Analizar y discutir los resultados de cada método.

## **AGREGAR AL LATEX**

| Modelo / Técnica de normalización  | *Regresión Logística* | *RandomForestClassifier* | *SVM* | *GradientBoostingClassifier* | *KNN* |
|-----------------------------------|-------------------------|----------------------------|---------|-------------------------------|---------|
| *MaxAbsScaler*                 | 0.7811                  | 0.8217                     | 0.7979  | 0.8147                        | 0.8016  |
| *MinMaxScaler*                 | 0.7813                  | 0.8217                     | 0.7906  | 0.8146                        | 0.8010  |
| *Normalizer*                   | 0.7649                  | 0.8181                     | 0.7770  | 0.8137                        | 0.7887  |
| *PowerTransformer*             | 0.7872                  | 0.8231                     | 0.8262  | 0.8158                        | 0.8031  |
| *RobustScaler*                 | 0.7841                  | 0.8231                     | 0.7629  | 0.8136                        | 0.7844  |
| *StandardScaler*               | 0.7841                  | 0.8228                     | 0.8110  | 0.8142                        | 0.8012  |
| *minmax_scale*                 | 0.7813                  | 0.8217                     | 0.7906  | 0.8146                        | 0.8010  |
| *QuantileTransformer*          | 0.8001                  | 0.8233                     | 0.8314  | 0.8153                        | 0.8009  |
| *Accuracy promedio*            | 0.7811                  | 0.8217                     | 0.7979  | 0.8147                        | 0.8016  |
| *Desviación estándar*          | 0.0058                  | 0.0024                     | 0.0077  | 0.0108                        | 0.0069  |
