# Modelo de predição de limite de crédito

Olá! Seja muito bem-vindo a este projeto de predição do limite de crédito para clientes bancários. 

Este projeto foi desenvolvido como parte do curso de formação do curso Data Expert, da escola Dinâmica Group (DNC). 

O dataset utilizado é público, disponível no Kaggle através do seguinte endereço: https://www.kaggle.com/arjunbhasin2013/ccdata



## Introdução

Foi realizado um processo de entendimento dos dados, tratamento de outliers, tratamento de dados nulos e a criação de gráficos para um melhor entendimento das features. 

De forma a agregar informações, foi realizada classificações dos clientes, utilizando modelos não-supervisionados, por KMeans e Gaussian Mixture. O melhor modelo foi o de Gaussian Mixture.



## Modelo de regressão

Para a determinação do limite de crédito dos clientes, foi buscado um modelo de regressão que pudesse estimar este limite. Foram testados diferentes modelos, sendo realizado o tuning de hiperparâmetros para dois modelos, Gradiente Boosting e Random Forest. Com os modelos tunados, foram comparados com modelos de redes neurais, com diferentes camadas e neurônios.



## Conclusão

Nenhum modelo performou bem, atingindo no máximo um R² = 0.35, com um erro médio relativamente elevado. Uma das possíveis soluções seria a retirada de features não significativas, a criação de outras melhores e, principalmente, um tratamento mais aprimorado dos outliers, que influenciam negativamente na construção do modelo.

