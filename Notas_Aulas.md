# Anotações Aulas:

## Aula_02: 
* Diferenças entre :
    * <b>"Sistema de Apoio à Decisão X Sistema de recomendação"</b>
    * Predição e Previsão;

```
Predição e Previsao:
    KDD(Descoberta de Conhecimento em Bancos de Dados - Knowledge Discovery in Databases)  
        --> Mineração de Dados   
                -->Algoritmos de Predição  
                -->Algoritmos de Previsão  
                    Redes Neuráis Artificiais (R.N.A)  
                    Estátisticas(Matemática)  

                    --> Reconhecimento de Padrões (Pattern Recognition)  

```

#### Predição

Categorizar/Classificar/Etiquetar/Rotular

* **Sentido geral:** é o termo mais amplo. Refere-se ao ato de **estimar um valor, classe ou comportamento futuro, presente ou até passado desconhecido**, com base em dados e modelos.
* **Âmbito:** pode envolver **classificação** (prever rótulos/categorias) ou **regressão** (prever valores numéricos).
* **Exemplos:**

  * Identificar se um cliente **vai** cancelar a assinatura (classificação).
  * Descobrir a idade de uma pessoa a partir de uma foto (a idade já ocorreu, mas não era conhecida — logo, é predição).
* **Importante:** a predição não precisa ser, necessariamente, sobre o futuro. Pode ser sobre o presente ou passado, desde que o dado real não seja conhecido no momento.

#### Previsão

Estimar/Prever/Linha Temporal|Série Temporal
Trabalha com Dados Futuros

* **Sentido mais específico:** normalmente associada a **séries temporais** e eventos futuros.
* **Âmbito:** quase sempre lida com estimativas de **valores futuros** baseadas em padrões históricos.
* **Exemplos:**

  * Estimar a temperatura de amanhã com base nos dados climáticos dos últimos 10 anos.
  * Projetar o faturamento do próximo trimestre.
* **Importante:** a previsão implica **tempo** — está sempre ligada ao que ainda vai acontecer.


# Métricas de Avaliação de Modelos de Machine Learning

---

## 1. Matriz de Confusão
> Mapeia as previsões do modelo contra os casos reais, permitindo identificar se o modelo favorece uma classe em detrimento de outra.

---

## 2. Acurácia (*Accuracy*)
Proporção de todas as previsões corretas sobre o total de casos.

$$ \text{Acurácia} = \frac{VP + VN}{VP + VN + FP + FN} $$

* **Uso ideal:** Útil como uma visão geral do desempenho quando as **classes estão balanceadas**.

---

## 3. Precisão
Taxa de acerto entre todas as vezes em que o modelo previu a classe Positiva.

$$ \text{Precisão} = \frac{VP}{VP + FP} $$

* **Uso ideal:** Mede a confiabilidade dos alarmes emitidos pelo modelo. Deve ser priorizada quando o **custo do Falso Positivo (FP) é alto**.

---

## 4. Recall (Sensibilidade)
Proporção de casos positivos reais que o modelo conseguiu capturar com sucesso.

$$ \text{Recall} = \frac{VP}{VP + FN} $$

* **Uso ideal:** Mede a capacidade do modelo de não deixar passar instâncias relevantes. Deve ser priorizada quando o **custo do Falso Negativo (FN) é crítico**.

---

## 5. F1-Score
Média harmônica entre a Precisão e o Recall.

$$ F1 = 2 \times \frac{\text{Precisão} \times \text{Recall}}{\text{Precisão} + \text{Recall}} $$

* **Uso ideal:** Métrica única para avaliar o equilíbrio do modelo em **cenários com dados desbalanceados** ou quando tanto FP quanto FN possuem custos relevantes.

---

### Legenda:
* **VP:** Verdadeiro Positivo
* **VN:** Verdadeiro Negativo
* **FP:** Falso Positivo
* **FN:** Falso Negativo