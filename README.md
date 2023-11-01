# Dashboard_Phyton

## Descrição do projeto
Esse é um projeto realizado através da escola DNC que tem como objetivo realizar a limpeza, avaliação e analisar os dados de uma organização fícticia de E-commerce. 

## Importação dos dados

Para que se possa entender os dados de forma clara e precisa, foi realizado a importação do dataset através da biblioteca Pandas. 
![image](https://github.com/Yagomendonca/Dashboard_Phyton/assets/143752309/7222338f-7627-42ee-926d-6741cfb6b6dd)

## Limpeza dos dados

Após a importação dos dados, foi verificado que os dados continham valores duplicados e nulos que de acordo com a análise do negócio não tinham relevância para o objetivo da análise. 

A partir da análise do dataset foi analisado que haviam outliers no projeto que impactariam na análise final, pois poderiam aumentar o diminuir a variabliadade das variáveis impactando na média dos resultados esperados. Logo, os outliers referentes a quantidade de produtos vendidos e preço unitário dos produtos foram removidos. Importante salientar que o setor responsável pelos dados, definiu como sendo outlier os preços unitários maiores ou iguais a R$ 5.000,00 e as quantidades maiores e iguais a R$ 10.000,00.

## Insights dos dados tratados.

Com os dados já tratados foram retiradas informações sobre os países com maior volume em vendas; os produtos mais vendidos; as vendas totais por mês e a venda total por país em cada mês, criando assim um painel de visualização desses resultados, conforme abaixo:
![image](https://github.com/Yagomendonca/Dashboard_Phyton/assets/143752309/2d1b236e-b0da-4137-9eaf-22405c21c99f)
![image](https://github.com/Yagomendonca/Dashboard_Phyton/assets/143752309/d03489c2-f967-4bf6-b062-6e388ab2cc44)

## Cálculo do RFM
Por fim, foram calculadas as taxas de Recência, Frequência e o Ticket médio da instuição estudada.


