# 🎵 Spotify Hit Predictor: Análise e Classificação

Este projeto utiliza técnicas de **Data Science** e **Machine Learning** para analisar e prever se uma música será um "Hit" (sucesso) ou não, com base em suas características de áudio extraídas da API do Spotify.

## 📌 Contexto do Problema
O que faz uma música estourar nas paradas de sucesso? Será a "dançabilidade"? A energia? Ou a falta de instrumentos acústicos? 
Este projeto investiga os atributos musicais de faixas das décadas de 90, 2000 e 2010 para identificar padrões que definem o sucesso comercial.

## 📊 O Dataset
Os dados foram consolidados a partir de três décadas distintas, totalizando mais de 17.000 faixas. As variáveis incluem:
* **Danceability, Energy, Valence**: Atributos psicológicos e rítmicos.
* **Loudness, Acousticness, Instrumentalness**: Atributos técnicos do áudio.
* **Target**: Variável alvo (1 para Hit, 0 para Não-Hit).

## 🛠️ Tecnologias Utilizadas
* **Python 3.x**
* **Pandas & Numpy**: Manipulação e limpeza de dados.
* **Matplotlib & Seaborn**: Visualização de dados e análise estatística.
* **Scikit-Learn**: Criação do modelo de Machine Learning (Random Forest).

## 📈 Insights da Análise Exploratória (EDA)
Durante a análise, observamos que:
1.  **Instrumentalness**: Músicas com alta probabilidade de serem hits tendem a ter valores muito baixos de instrumentalidade (músicas com vocais dominam o mainstream).
2.  **Danceability**: Existe uma correlação positiva clara entre a capacidade de dançar e o sucesso comercial.
3.  **Balanceamento**: O dataset está equilibrado, permitindo um treinamento de modelo sem viés de classe.

## 🤖 Modelo de Machine Learning
Foi utilizado o algoritmo **Random Forest Classifier**. O modelo foi capaz de prever com alta precisão os sucessos musicais.

### Performance Final:
* **Acurácia**: [INSIRA AQUI A % QUE APARECEU NO SEU NOTEBOOK, ex: 79%]
* **Principais Métricas**: O modelo apresentou um bom equilíbrio entre *Precision* e *Recall*, minimizando falsos positivos.

## 🚀 Como executar o projeto
1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt

3. Abra o notebook Análise_exploratória_Classificação_de_Dados_SpotiFy.ipynb no Jupyter ou Google Colab.

 .

Feito com ☕ por Raphael Sandes, como parte da disciplina Modelos de Classificação e Regressão da formação em Ciência de Dados, da Escola DNC. 
