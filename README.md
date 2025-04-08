# 🏠 **Projeto de Machine Learning: Previsão de Preços na Califórnia**

## 📊 **Descrição do Projeto**  
Este projeto foi desenvolvido para consolidar os fundamentos de **Machine Learning**, aplicando técnicas de análise exploratória de dados (EDA), pré-processamento, modelagem e avaliação de modelos preditivos. Utilizamos o famoso **dataset California Housing**, que contém informações detalhadas sobre características de imóveis na Califórnia.

---

## 🛠️ **Tecnologias e Bibliotecas Utilizadas**  
- **Python** 🐍  
- **Pandas** 📑  
- **NumPy** 🔢  
- **Matplotlib** 📊  
- **Scikit-learn** 🤖  

---

## 🚀 **Principais Etapas do Projeto**  

### 1️⃣ **Aquisição e Preparação dos Dados**  
- Download do dataset diretamente de um repositório online.  
- Pré-processamento com **pipelines** e transformadores personalizados.  

### 2️⃣ **Análise Exploratória de Dados (EDA)**  
- Histogramas e gráficos de dispersão.  
- Mapas de correlação para identificar relações entre variáveis.  

### 3️⃣ **Modelagem**  
- Algoritmos aplicados: **Regressão Linear**, **Árvore de Decisão**, entre outros.  
- Ajuste de hiperparâmetros com **Grid Search** e **Random Search**.  
- Validação cruzada para garantir robustez nos resultados.  

### 4️⃣ **Avaliação**  
- Métricas utilizadas: **Mean Squared Error (MSE)**, **R²**.
- Uso de técnica de validação cruzada para evitar data-leakage
- Intervalos de confiança para analisar a variabilidade das previsões.  

---

## 📊 **Resultados**  
Os modelos foram avaliados com métricas robustas, e gráficos comparativos entre valores reais e previstos foram gerados para melhor visualização dos resultados.

---

## 🖼️ **Visualizações Principais**  
- Histogramas mostrando a distribuição das variáveis.  
- Gráficos de dispersão para identificar padrões.  
- Comparação visual entre previsões e valores reais.  

---

## 📚 **Como Executar o Projeto**  

1. Clone este repositório:  
```bash
git clone https://github.com/phaa/california-housing.git
```

2. Crie um ambiente Anaconda:
```bash
conda create -n housing-env python=3.9
```

3. Ative o ambiente
```bash
conda activate housing-env
```

4. Instale as dependências:
```bash
conda install --file requirements.txt
```

5. Execute o Jupyter Lab: 
```bash
jupyter lab
```

5. Abra o arquivo Housing.ipynb e execute as células.

