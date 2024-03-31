# Aula Processamento de Linguagem Natural

Aula de PLN da Descomplica. Implementando modelo de `Classificação de Texto`.<br />
Comandos:
```
pip install nltk
```

## Tecnologias

Python3<br />
Anaconda

## Dataset

Twitter Sentiment Analysis - `https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis`

### Trechos de código importantes

```
# Filtre as linhas com os valores <value>
filtro = df['coluna'].isin(['value', 'value'])
df = df[filtro]
```

<hr />

```
# Redefina os índices (opcional, mas recomendado para manter a ordem crescente)
df.reset_index(drop=True, inplace=True)
```

<hr />

