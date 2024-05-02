# Estatistica-ADA-Santander

- Projeto: EDA (Análise Exploratória de Dados)
- Curso: Data Science - Santander Coders 2023 | 2º Semestre
- Módulo: Machine Learning I
- Turma: 11160
- Professor: Thiago Tavares Magalhães


### Por: Tainah Guerra ID: 05, Matheus Mendonça - ID: 08 e Otávio Santos - ID: 14

### ``1.1 OBJETIVO``

Este projeto tem como principal objetivo aplicar os
conhecimentos adquiridos ao longo da disciplina de Machine Learning I, como Sckit-Learn, KNN's, Random Forests, Métricas de Avaliação de Modelos de Classificação e Otimização de Hiperparâmetros.

### ``1.2 OBJETIVO ESPECÍFICO``

Esse projeto visa comparar a performance de modelos de K-Nearest Neighbors (KNN) e Random Forest para prever o diagnóstico de doença cardíaca pacientes dado um conjunto de informações sobre sua saúde. Temos, então, um problema de aprendizado de máquina **supervisionado de clasificação**.

### ``2. METODOLOGIAS ÁGEIS``

Para este projeto, foi utilizada a ferramenta de gestão de projetos [Trello](https://trello.com/b/h9Q6qqib/projeto-estatistica-ada). Utilizado para manter o projeto organizado,
facilitar a colaboração entre os membros da equipe e garantir que o projeto seja concluído dentro do prazo estabelecido.

![image](https://github.com/tainahguerras/Estatistica-ADA-Santander/assets/142911747/b97bdec4-3ba1-4bb3-b93b-25b5013e0b10)



### ``3. BASE DE DADOS``

Os dados usados foram originados combinando 5 diferentes bancos de dados em saúde cardíaca: Cleveland, Hungarian, Switzerland, Long Beach VA e Stalog (Heart) Data Set. O dataset completo pode ser encontrado [aqui](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction).

| Atributo                    | Descrição                                      | 
|-----------------------------|------------------------------------------------|
| Age                         | Idade do paciente (anos) |
| Sex                         | Sexo do paciente (M: Masculino, F: Feminino)                               |
| ChestPainType               | Tipo de dor no peito (TA: Angina Típica, ATA: Angina Atípica, NAP: Dor Não-Anginosa, ASY: Assintomático) |
| RestingBP                   | Pressão arterial em repouso (mm Hg) | 
| Cholesterol                 | Colesterol sérico (mm/dl) | 
| FastingBS                   | Açúcar no sangue em jejum (1: se FastingBS > 120 mg/dl, 0: caso contrário) | 
| RestingECG                  | Resultados do eletrocardiograma em repouso (Normal: Normal, ST: anormalidade de onda ST-T, LVH: mostrando hipertrofia ventricular esquerda provável ou definitiva) |
| MaxHR                       | Frequência cardíaca máxima alcançada (60-202) | 
| ExerciseAngina              | Angina induzida por exercício (Y: Sim, N: Não) | 
| Oldpeak                     | Valor do Oldpeak = ST |                         
| ST_Slope                    | Inclinação do segmento ST no pico do exercício (Up: inclinação ascendente, Flat: plana, Down: inclinação descendente)| 
| HeartDisease                | Classe de saída (1: Doença Cardíaca, 0: Normal) | 


### ``4. FERRAMENTAS``

- Git
- Matplotlib
- Numpy
- Pandas
- Sckit-Learn
- Trello

### ``5. REFERÊNCIAS``

- https://neptune.ai/blog/using-exploratory-notebooks
- https://www.alura.com.br/artigos/get-dummies-vs-onehotencoder-qual-metodo-escolher
- https://scikit-learn.org/stable/
- https://matplotlib.org/stable/index.html
- https://numpy.org/doc/
- https://pandas.pydata.org/docs/
