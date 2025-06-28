# 📊 Linear Regression with a Dummy Variable: Predicting Student Performance

This project explores the use of linear regression to predict a student's final grade based on their SAT score (`SAT`). It demonstrates how adding a dummy variable (`Attendance`) improves the predictive power of the model.

## 🧠 Problem Overview

We want to understand how students' **SAT scores** and their **class attendance** affect their **final grades**.

Two models are built:

1. **Without attendance**  
   - Linear regression equation:  
     **ŷ = 0.0017 × SAT + 0.275**  
   - All students are treated the same, regardless of whether they attended class.

2. **With attendance (dummy variable)**
   - **ŷ = 0.6439 + 0.0014 × SAT + 0.2226 * Attendance**
   - The dummy variable `Attendance` = 1 if the student attended classes, 0 otherwise.
   - This allows the model to **differentiate predictions** based on attendance behavior.

## 🔍 Why the Dummy Variable Matters

By including `Attendance`, the model better captures behavioral patterns. Two students with the same SAT grade might end up with different final grades if one attended class and the other didn’t — and the model learns that.

This showcases how even a **simple categorical variable** can significantly improve regression modeling and prediction accuracy.

## 📁 Files

- `Making predictions with a linear regression.ipynb`: Jupyter notebook with code and explanations.

## 💡 Skills Highlighted

- Linear Regression
- Dummy Variable Encoding
- Interpretation of Regression Coefficients
- Predictive Modeling

---

# 📊 Regressão Linear com Variável Dummy: Predizendo o Desempenho de Alunos

Este projeto explora o uso da regressão linear para prever a nota final de um aluno com base em sua nota no exame (`SAT`). Ele mostra como adicionar uma variável dummy (`Attendance`) melhora o poder preditivo do modelo.

## 🧠 Visão Geral do Problema

Queremos entender como as **notas de SAT** e a **frequência às aulas** influenciam as **notas finais** dos alunos.

Foram construídos dois modelos:

1. **Sem frequência**  
   - Equação da regressão:  
     **ŷ = 0.0017 × SAT + 0.275**  
   - Todos os alunos são tratados da mesma forma, independentemente de terem frequentado as aulas ou não.

2. **Com frequência (variável dummy)**
   - **ŷ = 0.6439 + 0.0014 × SAT + 0.2226 * Attendance**
   - A variável dummy `Attendance` = 1 se o aluno frequentou as aulas, 0 caso contrário.
   - Isso permite ao modelo **diferenciar as previsões** com base no comportamento de frequência.

## 🔍 Por que a Variável Dummy é Importante?

Ao incluir `Attendance`, o modelo consegue capturar padrões comportamentais. Dois alunos com a mesma nota no SAT podem ter resultados finais diferentes dependendo da frequência — e o modelo aprende essa diferença.

Este é um excelente exemplo de como até mesmo uma **variável categórica simples** pode melhorar significativamente o modelo preditivo.

## 📁 Arquivos

- `Making predictions with a linear regression.ipynb`: Notebook com código e explicações.

## 💡 Habilidades Demonstradas

- Regressão Linear
- Codificação de Variáveis Dummy
- Interpretação de Coeficientes
- Modelagem Preditiva
