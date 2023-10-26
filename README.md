# modelo_regressor_salarial

## Objetivo
Este projeto tem por objetivo tentar encontrar as atribuições individuais que influenciam no valor salarial e encontrar um modelo de machine learning capaz de predizer esse valor.

Dataset: Salary_Data_Based_country_and_race.csv

As colunas tem os nomes autoexplicativos e cada linha corresponde a um indivíduo
Age, Gender, Education_Level, Job_Title, Years_of_Experience, Country, Race e Salary

O projeto seguira os seguintes passos:

1. Analise exploratória.
2. Preparação da dataset para o modelo de machine learning.
3. Desenvolvimento do modelo.
4. Análise das métricas de performance.

Arquivos: 
```
.
├── data_preprocess
│   ├── Country.json
│   ├── Education_Level.json
│   ├── Gender.json
│   ├── Job_Title.json
│   ├── Job_Title_words.json
│   ├── Race.json
│   ├── salary_preprocess_1.csv
│   └── salary_preprocess_2.csv
├── data_explore.ipynb
├── data_prepare.ipynb
├── model.ipynb
├── README.md
├── requirements.txt
└── Salary_Data_Based_country_and_race.csv
```

| arquivo  | descrição  |
|--------------|--------------|
| data_explore.ipynb  | Arquivo para analise exploratória dos dados  |
| data_prepare.ipynb  | Arquivo para preparação das bases do modelo a partir da analise exploratória |
| model.ipynb         | Modelo e resultados  |
| data_preprocess/*.json   | dicionário de vetoriazação para as colunas categóricas  |
