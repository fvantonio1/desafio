# Desafio

O desafio consistia em resolver um problema de negócio, o qual buscava diminuir gastos com disparos de whatsapp não efetivos. Para resolver esse problema em machine learning, utilizei a técnica de classificação para decidir se um formulário resultará em compra ou não.

Algumas dificuldades, foram encontradas: 
* Classes muito desbalanceadas.
* Necessidade grande de precisão da classe com menos registros.
* Features com pouca relação aparente.

Como forma de avaliação dos algoritmos observei principalmente o recall e uma métrica criada, a qual é a proporção de True Negatives para False Negatives, ou seja, a proporção de disparos economizados para compras perdidas. A precisão não se mostrou interessante pelo desbalanceamento dos dados.

No final, o melhor modelo que encontrei foi a regressão logística utilizando um threshold de 0.4.
