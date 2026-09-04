# Avaliação dos Modelos:   1 Base de Dados

Modelo: Logistic Regression  
Acurácia: 0.6533  
F1-Score (Macro): 0.6100  
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.67      0.82      0.74        45
           1       0.60      0.40      0.48        30

    accuracy                           0.65        75  
   macro avg       0.64      0.61      0.61        75  
weighted avg       0.64      0.65      0.64        75  



Matriz de Confusão:  
0 [[37  8]     Acertou: 37    Errou: 8  
1  [18 12]]    Errou:18     Acertou: 12


```
------------------------------------------------------------
Modelo: Decision Tree
Acurácia: 0.6933
F1-Score (Macro): 0.6746
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.73      0.78      0.75        45
           1       0.63      0.57      0.60        30

    accuracy                           0.69        75
   macro avg       0.68      0.67      0.67        75
weighted avg       0.69      0.69      0.69        75

Matriz de Confusão:
[[35 10]           Acertou: 35    Errou:10
 [13 17]]          Errou: 13      Acertou 17;

Modelo com underfitting
 ```
------------------------------------------------------------
Modelo: Random Forest
Acurácia: 0.6533
F1-Score (Macro): 0.6173
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.68      0.80      0.73        45
           1       0.59      0.43      0.50        30

    accuracy                           0.65        75
   macro avg       0.64      0.62      0.62        75
weighted avg       0.64      0.65      0.64        75

Matriz de Confusão:
[[36  9]
 [17 13]]

```
------------------------------------------------------------
Modelo: KNN
Acurácia: 0.6533
F1-Score (Macro): 0.6238
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.69      0.78      0.73        45
           1       0.58      0.47      0.52        30

    accuracy                           0.65        75
   macro avg       0.63      0.62      0.62        75
weighted avg       0.65      0.65      0.64        75

Matriz de Confusão:
[[35 10]
 [16 14]]

```
------------------------------------------------------------
Modelo: Naive Bayes
Acurácia: 0.6533
F1-Score (Macro): 0.6100
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.67      0.82      0.74        45
           1       0.60      0.40      0.48        30

    accuracy                           0.65        75
   macro avg       0.64      0.61      0.61        75
weighted avg       0.64      0.65      0.64        75


Matriz de Confusão:
[[37  8]
 [18 12]]

```
------------------------------------------------------------
Modelo: SVM
Acurácia: 0.6800
F1-Score (Macro): 0.6237
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.68      0.89      0.77        45
           1       0.69      0.37      0.48        30

    accuracy                           0.68        75
   macro avg       0.68      0.63      0.62        75
weighted avg       0.68      0.68      0.65        75

Matriz de Confusão:
[[40  5]
 [19 11]]

```
------------------------------------------------------------
Modelo: Gradient Boosting
Acurácia: 0.6000
F1-Score (Macro): 0.5297
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.63      0.82      0.71        45
           1       0.50      0.27      0.35        30

    accuracy                           0.60        75
   macro avg       0.56      0.54      0.53        75
weighted avg       0.58      0.60      0.57        75

Matriz de Confusão:
[[37  8]
 [22  8]]

```
------------------------------------------------------------
```
Ranking Final dos Modelos:
Modelo                    Acurácia   F1-Score (Macro)
--------------------------------------------------
Decision Tree             0.6933     0.6746         
KNN                       0.6533     0.6238         
SVM                       0.6800     0.6237         
Random Forest             0.6533     0.6173         
Logistic Regression       0.6533     0.6100         
Naive Bayes               0.6533     0.6100         
Gradient Boosting         0.6000     0.5297         

Avaliação da Base de Dados:
  Devido ao baixo volume total da base de dados, a amostra de teste ficou reduzida (75 pessoas) e ligeiramente desequilibrada: 45 não compraram (Classe 0) e 30 compraram (Classe 1). 
  Há 50% mais registros no grupo de não compradores em relação ao de compradores.

Uma base de Dados fraca
```


# Avaliação dos Modelos:   2 Base de Dados

Modelo: Logistic Regression
Acurácia: 0.7600
F1-Score (Macro): 0.7600
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.78      0.74      0.76        38
           1       0.74      0.78      0.76        37

    accuracy                           0.76        75
   macro avg       0.76      0.76      0.76        75
weighted avg       0.76      0.76      0.76        75

Matriz de Confusão:
[[28 10]                
 [ 8 29]]
 ```
------------------------------------------------------------
Modelo: Decision Tree
Acurácia: 0.7467
F1-Score (Macro): 0.7450
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.81      0.66      0.72        38
           1       0.70      0.84      0.77        37

    accuracy                           0.75        75
   macro avg       0.76      0.75      0.75        75
weighted avg       0.76      0.75      0.74        75

Matriz de Confusão:
[[25 13]
 [ 6 31]]
```
------------------------------------------------------------
Modelo: Random Forest
Acurácia: 0.7467
F1-Score (Macro): 0.7459
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.73      0.79      0.76        38
           1       0.76      0.70      0.73        37

    accuracy                           0.75        75
   macro avg       0.75      0.75      0.75        75
weighted avg       0.75      0.75      0.75        75

Matriz de Confusão:
[[30  8]
 [11 26]]
 ```
------------------------------------------------------------
Modelo: KNN
Acurácia: 0.6933
F1-Score (Macro): 0.6925
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.73      0.63      0.68        38
           1       0.67      0.76      0.71        37

    accuracy                           0.69        75
   macro avg       0.70      0.69      0.69        75
weighted avg       0.70      0.69      0.69        75

Matriz de Confusão:
[[24 14]
 [ 9 28]]
 ```
------------------------------------------------------------
Modelo: Naive Bayes
Acurácia: 0.8133
F1-Score (Macro): 0.8125
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.79      0.87      0.82        38
           1       0.85      0.76      0.80        37

    accuracy                           0.81        75
   macro avg       0.82      0.81      0.81        75
weighted avg       0.82      0.81      0.81        75

Matriz de Confusão:
[[33  5]
 [ 9 28]]
```
------------------------------------------------------------
Modelo: SVM
Acurácia: 0.7467
F1-Score (Macro): 0.7467
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.76      0.74      0.75        38
           1       0.74      0.76      0.75        37

    accuracy                           0.75        75
   macro avg       0.75      0.75      0.75        75
weighted avg       0.75      0.75      0.75        75

Matriz de Confusão:
[[28 10]
 [ 9 28]]
 ```
------------------------------------------------------------
Modelo: Gradient Boosting
Acurácia: 0.7867
F1-Score (Macro): 0.7863
Relatório de Classificação:
```
              precision    recall  f1-score   support

           0       0.78      0.82      0.79        38
           1       0.80      0.76      0.78        37

    accuracy                           0.79        75
   macro avg       0.79      0.79      0.79        75
weighted avg       0.79      0.79      0.79        75

Matriz de Confusão:
[[31  7]
 [ 9 28]]
 ```
------------------------------------------------------------

Ranking Final dos Modelos:
Modelo                    Acurácia   F1-Score (Macro)
--------------------------------------------------
Naive Bayes               0.8133     0.8125         
Gradient Boosting         0.7867     0.7863         
Logistic Regression       0.7600     0.7600         
SVM                       0.7467     0.7467         
Random Forest             0.7467     0.7459         
Decision Tree             0.7467     0.7450         
KNN                       0.6933     0.6925         


Uma base de dados pequena para a amplitude da regra de negócio
Modelos com falta de treinamento;
