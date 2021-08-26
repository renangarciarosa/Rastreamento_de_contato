# Rastreamento_de_contato
Aplicação de técnicas de Machine Learning para o rastreamento de contato para ajudar a impedir a propagação de doenças infecciosas.

# Como funciona o rastreamento de contatos de pessoas?
Uma vez que uma pessoa é positiva para coronavírus, é muito importante identificar outras pessoas que possam ter sido infectadas pelos pacientes diagnosticados. Para identificar os infectados, as autoridades acompanham a atividade dos pacientes diagnosticados nos últimos 14 dias. Esse processo é chamado de rastreamento de contato. Dependendo do país e da autarquia local, a procura de contactos realiza-se quer por métodos manuais quer por métodos numéricos.

Neste projeto, irei propor um algoritmo de rastreamento de contato digital que se baseia em dados de GPS, que pode ser usado no rastreamento de contato com aprendizado de máquina.

DBSCAN é um algoritmo de agrupamento de dados baseado em densidade que agrupa pontos de dados em um determinado espaço. O algoritmo DBSCAN agrupa pontos de dados próximos uns dos outros e marca pontos de dados discrepantes como ruído. Vou usar o algoritmo DBSCAN para a tarefa de rastreamento de contatos com Machine Learning.

O conjunto de dados que usarei nesta tarefa são dados JSON. 

# Bibliotecas necessárias
1. Pandas
2. NumPy
3. Matplotlib
4. Pygal
5. Sklearn
6. IPython

