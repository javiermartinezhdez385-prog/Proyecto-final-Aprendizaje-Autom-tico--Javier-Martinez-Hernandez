# Proyecto-final Aprendizaje Automatico Javier Martinez Hernandez
Clasificación de segmentos de clientes con SVM, Random Forest y Regresión Logística
# Segmentación de Clientes — Clasificación con ML

## Descripción
Proyecto de clasificación de clientes en 4 segmentos (High_Value, Loyal, 
Occasional, Regular) usando técnicas de Machine Learning.

## Contenido
- Análisis exploratorio de datos (EDA)
- Preprocesamiento (imputación, codificación, SMOTE)
- Modelos: Regresión Logística, Random Forest, SVM (RBF)

## Resultados
| Modelo | F1-macro | AUC-ROC |
|---|---|---|
| Reg. Logística | 0.64 | 0.86 |
| Random Forest | 0.76 | 0.91 |
| SVM (RBF) | 0.72 | 0.89 |

## Conclusiones principales
- Random Forest tuvo el mejor desempeño general.
- Las clases Regular y Occasional muestran solapamiento significativo 
  en sus variables (ej. months_active: 0.895 de coeficiente de solapamiento), 
  lo que limita estructuralmente la capacidad de cualquier modelo de 
  separarlas perfectamente.

## Autor
[Tu nombre]
