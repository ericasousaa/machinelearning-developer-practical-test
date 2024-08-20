------

### Análise Exploratória de Dados e Modelagem de Regressão Linear para Previsão de Preços de Voos - Case Vidya


------
Realizei a carga e a visualização do dataset com o objetivo de compreender sua estrutura e analisar as primeiras entradas. Posteriormente, examinei a presença de valores nulos para assegurar a integridade dos dados.

Na fase de análise exploratória, utilizei as seguintes técnicas e ferramentas:

- Elaborei um histograma para observar a distribuição dos preços dos voos, identificando que a maioria dos preços se concentra em uma faixa específica, com a presença de alguns outliers.
- Gerei uma matriz de correlação para avaliar as relações entre as variáveis numéricas, notando, por exemplo, que a duração do voo apresenta uma correlação positiva com o preço, embora essa relação não seja perfeitamente linear.
- Criei um scatter plot para analisar a correlação entre a duração do voo e o preço, observando que voos mais longos tendem a ter preços mais elevados.

Para a etapa de modelagem, utilizei os seguintes métodos e ferramentas:

- Codificação das variáveis categóricas por meio de one-hot encoding.
- Separação dos dados em variáveis independentes (X) e a variável dependente (y), que, neste caso, corresponde ao preço.
- Divisão do conjunto de dados em conjuntos de treino e teste para avaliar o desempenho do modelo.
- Normalização das features utilizando StandardScaler.
- Treinamento de um modelo de regressão linear.
- Comparação das previsões com os preços reais, seguida pela análise dos resíduos para avaliar a precisão do modelo.
- Elaboração de um gráfico comparando os preços reais com os preços previstos, o que possibilitou visualizar o desempenho do modelo de regressão.

Com base nas análises conduzidas, tomei decisões informadas ao longo do processo, garantindo que o modelo estivesse adequadamente ajustado aos dados, com vistas a proporcionar previsões precisas.
