# flood

Este projeto tem como objetivo prever o impacto das mudanças climáticas e o risco de enchentes utilizando técnicas de aprendizado de máquina. O dataset utilizado foi obtido a partir do Kaggle, contendo informações ambientais e socioeconômicas relevantes, como desmatamento, urbanização, drenagem, intensidade das monções, qualidade das barragens, entre outras. A variável alvo é ClimateChange, que representa o nível de impacto climático em determinada região.

O código realiza a leitura e análise dos dados, gera uma matriz de correlação para entender a relação entre as variáveis e aplica a transformação Box-Cox para normalizar a variável alvo. Em seguida, o conjunto de dados é dividido em treino e teste, sendo utilizado o modelo XGBoost Regressor para realizar as previsões. O desempenho do modelo é avaliado por métricas como R² e RMSE. Por fim, é gerado um gráfico com a importância das variáveis, permitindo identificar os principais fatores que contribuem para as enchentes.

Esse projeto mostra como a inteligência artificial pode ser uma aliada na prevenção de desastres naturais, auxiliando na tomada de decisões e na redução de impactos sociais e ambientais.
