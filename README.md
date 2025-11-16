# Previsão de Preço de Pizzas 🍕

Aplicação em Python que utiliza **regressão linear** para prever o preço de uma pizza a partir do seu diâmetro.  
A interface foi construída com **Streamlit**, permitindo inserir o tamanho da pizza e ver a previsão instantaneamente.

---

## 📌 Tecnologias utilizadas

- Python  
- Streamlit  
- Pandas  
- Scikit-learn  

---

## 📁 Estrutura do projeto

projeto-ml/
├── app.py
├── pizzas.csv
├── pyproject.toml
├── README.md
└── testes.ipynb

---

## ▶️ Executando o projeto

### 1. Instale as dependências (Poetry)
```bash
poetry install

### 2. Ative o ambiente virtual
poetry shell

### 3. Execute o Streamlit
streamlit run app.py

## 🧠 Descrição do modelo

O algoritmo utilizado é uma Regressão Linear, treinada com os dados do arquivo:

diametro — tamanho da pizza em cm
preco — preço correspondente

O modelo aprende a relação entre o diâmetro da pizza e o valor final.