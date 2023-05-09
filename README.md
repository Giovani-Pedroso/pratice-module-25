# Objetivo do Projeto

Esse projeto foi minha entrada na competicao Sobrevivintes do Titanic, realizada pela plataforma Kaggle, essa competicao tem como o objetivo auxiliar os programadores a entrarem na area de ciencia de dados. 

A competicao tem como objetivo fazer os programadores treinarem uma inteligencia artificial capaz de prever os sobrevivintes do naufragio tendo como base os dados dos tripulantes (genero, idade, local de embraque etc...)

No arquino titanic.ipynb voce encontrara o desemvolvimento do projeto, o programador resolveu testar 4 tipos de algoritimos para alcansar a solucao desejada

# Coleta de dados

Os dados foram coletados na plataforma Kaggle

# Modelagem 

Os dados de treino estao disponiveis no arquivo train.csv, essa base de dados e constituida pelas colunas:

- survival
- pclass
- sex
- Age
- sibsp
- parch
- ticket
- fare
- cabin
- embarked

Para o treino desse modelo foram usadas as colunas:

- pclass
- sex
- Age

# Conclusões

Para esse projeto foram usados 4 tipos de algoritimos de inteligencia artificial: k-nearest neighbors algorithm, Naive Bayes, Log regression, Random Forest.

Apos feito o treino desses modelos o programador pode avaliar a acuracia dos mesmos aqui esta o rank do melhor ao pior:

1. Naive Bayes ac: 81%
2. Random Forest ac: 80%
3. Log regression ac: 78%
4. KNN ac: 76%

Apos feita a submicao dos resultados o projeto recebeu um Score de 0.76555
