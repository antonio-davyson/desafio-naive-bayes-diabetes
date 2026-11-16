# Naive Bayes: previsão de diabetes

Desafio da Rocketseat (Naive Bayes). Construo um modelo de classificação com Naive Bayes Gaussiano para prever se um paciente tem diabetes a partir de glicemia e pressão arterial.

## O que o projeto faz
- Carrega e explora o dataset (995 pacientes, 3 colunas)
- Decide o pré-processamento (duplicatas mantidas, sem necessidade de escalonamento)
- Explica e implementa o Naive Bayes Gaussiano e mostra o que o modelo aprendeu
- Treina com 80% dos dados e avalia nos 20% restantes
- Métricas: acurácia, precisão, recall, F1, ROC AUC, matriz de confusão, curva ROC e validação cruzada
- Compara o uso de cada variável e mostra as regiões de decisão do modelo

## Resultado
No teste: acurácia de 91% e ROC AUC de 0,976 (93% de acurácia na validação cruzada, contra 50% de um chute pela classe mais comum). A pressão arterial é a variável mais informativa.

Projeto de estudo com dados fornecidos pelo curso; não serve para diagnóstico.

## Tecnologias
Python, Pandas, scikit-learn, Matplotlib e Seaborn

## Como executar
1. Abra o `naive_bayes_diabetes.ipynb` no Google Colab ou no Jupyter
2. Envie o `diabetes.csv` quando a primeira célula pedir
3. Execute as células em ordem
