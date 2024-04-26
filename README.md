# Análise da Vibração Musical: Descobrindo o Segredo das Músicas Populares no Spotify 🎵

Bem-vindo ao repositório do projeto que mergulha nas ondas sonoras do Spotify para desvendar o mistério por trás das faixas que conquistam nossos corações e playlists. Usando dados reais, exploramos o que faz uma música ser considerada popular e como diferentes atributos contribuem para isso.

## 🌟 Destaques do Projeto

Este projeto não é apenas sobre números e dados; é sobre música, cultura e as emoções que elas evocam. Aqui, você encontrará:

- **Visualizações Dinâmicas**: Gráficos interativos que mostram mais do que tendências; eles cantam histórias de dados.
- **Análises Profundas**: Mergulhamos profundamente nos dados para oferecer insights que vão além do óbvio.
- **Modelagem Preditiva**: Utilizamos algoritmos de machine learning para prever o que faz uma música brilhar.

## 🛠 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=Pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-FFFFFF?style=flat-square&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/-Seaborn-76B900?style=flat-square&logo=Seaborn&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/-Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Imbalanced Learn](https://img.shields.io/badge/-Imbalanced_Learn-FFFFFF?style=flat-square&logo=Imbalanced-Learn&logoColor=black)

## 🎼 Dados Utilizados

Os dados são provenientes de uma coleção pública do Spotify disponível no GitHub, contendo características detalhadas das músicas como danceabilidade, energia, chave musical e muito mais.

```python
dados_musicas = pd.read_csv('https://raw.githubusercontent.com/Quemoel/7DaysOfCode_Machine_Learning/main/17%20Coleta%20de%20dados%20e%20An%C3%A1lise%20Explorat%C3%B3ria/dataset.csv', index_col=0)