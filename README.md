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

| Modelo                          | Técnica de normalización | Accuracy promedio | Desviación estándar |
|---------------------------------|--------------------------|-------------------|---------------------|
| *Regresión Logística*         | MaxAbsScaler             | 0.7811            | 0.0058              |
|                                 | MinMaxScaler             | 0.7813            | 0.0065              |
|                                 | Normalizer               | 0.7649            | 0.0049              |
|                                 | PowerTransformer         | 0.7872            | 0.0073              |
|                                 | RobustScaler             | 0.7841            | 0.0062              |
|                                 | StandardScaler           | 0.7841            | 0.0062              |
|                                 | minmax_scale             | 0.7813            | 0.0065              |
|                                 | QuantileTransformer      | 0.8001            | 0.0070              |
| *RandomForestClassifier*      | MaxAbsScaler             | 0.8217            | 0.0024              |
|                                 | MinMaxScaler             | 0.8217            | 0.0024              |
|                                 | Normalizer               | 0.8181            | 0.0051              |
|                                 | PowerTransformer         | 0.8231            | 0.0051              |
|                                 | RobustScaler             | 0.8231            | 0.0056              |
|                                 | StandardScaler           | 0.8228            | 0.0038              |
|                                 | minmax_scale             | 0.8217            | 0.0024              |
|                                 | QuantileTransformer      | 0.8233            | 0.0046              |
| *SVM*                         | MaxAbsScaler             | 0.7979            | 0.0077              |
|                                 | MinMaxScaler             | 0.7906            | 0.0075              |
|                                 | Normalizer               | 0.7770            | 0.0058              |
|                                 | PowerTransformer         | 0.8262            | 0.0100              |
|                                 | RobustScaler             | 0.7629            | 0.0055              |
|                                 | StandardScaler           | 0.8110            | 0.0110              |
|                                 | minmax_scale             | 0.7906            | 0.0075              |
|                                 | QuantileTransformer      | 0.8314            | 0.0079              |
| *GradientBoostingClassifier*  | MaxAbsScaler             | 0.8147            | 0.0108              |
|                                 | MinMaxScaler             | 0.8146            | 0.0093              |
|                                 | Normalizer               | 0.8137            | 0.0108              |
|                                 | PowerTransformer         | 0.8158            | 0.0089              |
|                                 | RobustScaler             | 0.8136            | 0.0087              |
|                                 | StandardScaler           | 0.8142            | 0.0105              |
|                                 | minmax_scale             | 0.8146            | 0.0093              |
|                                 | QuantileTransformer      | 0.8153            | 0.0091              |
| *KNN*                         | MaxAbsScaler             | 0.8016            | 0.0069              |
|                                 | MinMaxScaler             | 0.8010            | 0.0053              |
|                                 | Normalizer               | 0.7887            | 0.0051              |
|                                 | PowerTransformer         | 0.8031            | 0.0065              |
|                                 | RobustScaler             | 0.7844            | 0.0094              |
|                                 | StandardScaler           | 0.8012            | 0.0070              |
|                                 | minmax_scale             | 0.8010            | 0.0053              |
|                                 | QuantileTransformer      | 0.8009            | 0.0077              |
