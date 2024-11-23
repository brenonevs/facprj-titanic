
# Titanic Survival Prediction - Kaggle Competition

Este repositório contém o código e os recursos utilizados para participar da competição do **Titanic - Machine Learning from Disaster** no Kaggle. O objetivo é prever a sobrevivência de passageiros do Titanic com base em informações como idade, gênero, classe social, entre outras. A solução utiliza técnicas de aprendizado de máquina para treinar e avaliar modelos preditivos.

---

## 📋 Estrutura do Projeto

- **`data/`**: Contém os arquivos CSV de treino e teste fornecidos pelo Kaggle.
- **`src/`**: Código fonte com as funções utilizadas no projeto, como pré-processamento e avaliação.
- **`requirements.txt`**: Arquivo para instalação de dependências do projeto.
- **`README.md`**: Documentação do repositório (este arquivo).

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone git@github.com:brenonevs/facprj-titanic.git
   cd titanic-competition
   ```

2. **Crie um ambiente virtual (opcional, mas recomendado)**:
   ```bash
   python -m venv venv
   source venv/bin/activate    # Linux/Mac
   venv\Scripts\activate       # Windows
   ```

3. **Instale as dependências**:
   Todas as bibliotecas necessárias estão listadas no arquivo `requirements.txt`. Para instalá-las, execute:
   ```bash
   pip install -r requirements.txt
   ```
---

## 📈 Modelo Preditivo

O modelo baseia-se em algoritmos como:
- KNN
- Random Forest
- XGBoost

Todos os hiperparâmetros são ajustados para obter o melhor desempenho possível nos dados de validação.

---
