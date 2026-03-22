# Tech Challenge 3 - Pós Tech - 7MLET 

## Integrantes:
  
- GEREMIAS FRANCISCO DE OLIVEIRA SANTOS
  - geremias_cte@hotmail.com
  
- WAGNER ULISSES FONTALVA
  - wagner.ulisses@gmail.com

  # ✈️ Tech Challenge 3 - Machine Learning (FIAP)

Projeto desenvolvido como parte do Tech Challenge da pós-graduação da FIAP, com foco em **Machine Learning Supervisionado e Não Supervisionado**.

---

## 📌 Objetivo

Aplicar técnicas de Machine Learning para:

- 🔍 Prever atrasos de voos (classificação) - (Após a decolagem)
- 📈 Estimar valores contínuos (regressão) - (Após a decolagem)
- 📊 Identificar padrões ocultos nos dados (clusterização)

---

## 🧠 Modelos Desenvolvidos

### 🔹 Modelo de Classificação

**Objetivo:** prever se um voo irá atrasar ou não.

#### 📊 Métricas:

| Classe | Precision | Recall | F1-score | Support |
|--------|----------|--------|----------|--------|
| 0      | 0.88     | 0.92   | 0.90     | 746,437 |
| 1      | 0.85     | 0.78   | 0.82     | 417,379 |

- **Accuracy:** 0.87  
- **ROC AUC:** 0.93  

📌 **Insight:**  
O modelo apresenta alta precisão geral, com leve perda de recall na classe de atraso, indicando que alguns casos de atraso não são identificados.

---

### 🔹 Modelo de Regressão

**Objetivo:** prever variáveis contínuas relacionadas aos voos.

#### 📊 Métricas:

- **MAE:** 7.33  
- **RMSE:** 11.04  
- **R²:** 0.92  

📌 **Insight:**  
O modelo apresenta alta capacidade explicativa, com erros controlados e boa generalização.

---

### 🔹 Modelo de Clusterização (K-Means)

**Objetivo:** identificar padrões e segmentações nos dados de voos.

#### 📊 Métricas:

- **Silhouette Score:** 0.44  

📌 **Insight:**  
Os clusters identificados mostram separação consistente entre grupos, indicando padrões relevantes no comportamento dos dados.

---

## 📊 Etapas do Projeto

### 1️⃣ Análise Exploratória (EDA)
- Estatísticas descritivas
- Visualizações
- Tratamento de outliers e valores ausentes

---

### 2️⃣ Modelagem
- Classificação
- Regressão
- Clusterização (K-Means)

---

### 3️⃣ Avaliação
- Métricas quantitativas
- Análise de erros
- Ajuste de modelo

---

## 📦 Dataset

O dataset não está versionado devido ao tamanho (>100MB).

---

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🚀 Como executar

```bash
git clone https://github.com/Gere-santos/Tech-Challenge-3-FIAP-ML-Supervisionado-N-Supervisionado.git
cd Tech-Challenge-3-FIAP-ML-Supervisionado-N-Supervisionado
