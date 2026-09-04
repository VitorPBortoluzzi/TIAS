Papel de/Importância/Uso de/Significado de: p/ Validação do modelo treinado / Impacto no modelo treinado

Acuracy/F1 Score/ Recall/ Precision/ Matriz Confusão



# Matriz de Confusão:
    Mapear as previsões do modelo contra os casos reais.
    Permite identificar se o modelo favorece uma classe em detrimento de outra.


# Acurácia(ACCuracy):
    Proporção de todas as previsões corretas sobre o total de casos;

    {Acurácia} = {VP + VN}/{VP + VN + FP + FN}

    Util como um dado geral, quando as classes estão balanceadas

# Precisão:
    Taxa de acerto entre todas as vezes em que o modelo previu a classe Positiva.

    {Precisão} = {VP}/{VP + FP}

    Mede a confiabilidade dos alarmes emitidos pelo modelo. Deve ser priorizada quando o custo do Falso Positivo é alto.

# Recall:
    Proporção de casos positivos reais que o modelo conseguiu capturar com sucesso.

    {Recall} = {VP}/{VP + FN}

    Mede a capacidade do modelo de não deixar passar instâncias relevantes. Deve ser priorizada quando o custo do Falso Negativo é crítico.

# F1 Score:
    Média harmônica entre Precisão e Recall.

    F1 Score = 2 x {(Precisão x Recall)/(Precisao + Recall)}

    Métrica única para avaliar o equilíbrio do modelo em cenários com dados desbalanceados ou quando FP e FN possuem custos relevantes.