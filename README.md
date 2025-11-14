# Predicting Road Accident Risk

Este repositório contém os dados e o código usado para resolver o desafio do Kaggle.

Neste desafio, tinhamos como objetivo estimar as probabilidades de acidente em certos locais baseando-se nos dados.


## Solução

Para este problema, fizemos a análise dos dados usando o notebook aqui presente [code.ipynb](./code.ipynb). 

Após a análise, submetemos os dados para o treinamento de algoritmos os quais foram: `LinearRegression` e `DecisionTree`.

## Como executar

Para executar o código:

1. Instale as dependências:

```bash
# usando UV
uv install

# ou, usando pip
pip install -r requirements.txt
```

2. abra o arquivo `.ipynb`

```bash
# usando UV
uv run --with jupyter jupyter lab code.ipynb

# ou, default
jupyter lab code.ipynb
```

