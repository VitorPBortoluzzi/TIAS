# Avaliação dos Modelos:

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

Modelo com Underfitting;
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
Modelo com Underfitting;
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
Modelo com Underfitting;
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
Modelo com Underfitting;
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
Modelo com Underfitting;
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
Modelo com Underfitting;
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
