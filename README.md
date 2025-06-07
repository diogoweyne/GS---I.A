
# Projeto Global Solution - Classificação de Risco Psicológico

Este projeto simula um sistema de apoio psicológico remoto em contextos de calamidade, utilizando Machine Learning para classificar usuários com base em risco emocional (baixo, moderado ou alto).

---

## 🔍 Descrição do Problema

Em situações de calamidade (enchentes, pandemias, desastres naturais), o acesso a apoio psicológico é limitado. Este projeto propõe um modelo inteligente capaz de identificar, por meio de um app, o nível de risco emocional dos usuários com base em variáveis como estresse, ansiedade, tristeza, isolamento social e sono.

---

## 📊 Metodologia

1. Simulação de base de dados com 300 registros fictícios.
2. Pré-processamento: codificação de variáveis categóricas e normalização dos dados.
3. Divisão dos dados em treino/teste (70/30).
4. Treinamento do modelo com algoritmo Random Forest.
5. Avaliação com métricas de classificação e matriz de confusão.

---

## 🧠 Justificativa da Técnica e do Modelo de Machine Learning

Para este projeto, foi escolhido o modelo **Random Forest Classifier**, por apresentar as seguintes vantagens:

- Lida bem com variáveis numéricas e categóricas.
- Funciona eficientemente com datasets pequenos.
- É robusto contra overfitting por usar múltiplas árvores.
- Permite análise de importância de variáveis, o que é útil na área de saúde mental.

### Modelos não utilizados

- **Regressão Logística**: limitações para classificações multiclasse e baixa performance com variáveis não-lineares.
- **SVM**: maior complexidade de parametrização e custo computacional.
- **KNN**: ineficiente com grandes volumes e dados desbalanceados.

---

## ✅ Resultados

- Acurácia geral: aproximadamente 43%.
- O modelo obteve maior desempenho nas classes de risco emocional moderado e alto.
- Métricas utilizadas: matriz de confusão, precisão, recall e F1-score.

---

## 📌 Conclusões

O modelo demonstrou viabilidade para auxiliar na triagem remota de risco psicológico em populações afetadas por calamidades. Sua aplicação pode ser estendida a apps de atendimento psicológico automatizado para priorização de usuários em risco elevado.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas / NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

