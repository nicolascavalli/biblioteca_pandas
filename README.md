# biblioteca_pandas

#O dataset de varejo que temos em mãos é composto por informações de vendas de uma loja virtual que atua em todo território nacional, vendendo produtos de diferentes departamentos. Além disso, a loja atua em diferentes canais de venda, como marketplace ,loja própria, entre outros.

Premissas de Negócio:
Ao analisar os dados, é importante ter em mente que existem algumas premissas de negócio que devem ser consideradas. A primeira delas é que, devido a um erro no sistema, algumas compras não possuem informações de UF(Unidade Federativa). Para solucionar esse problema, foi decidido que essas compras serão consideradas como pertencentes ao estado de Mato Grosso do Sul (MS). A segunda premissa é que o preço final de um produto não pode ser maior que o preço com frete.

Métricas:
Com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas:

1. Departamentos mais vendidos: Analisando os dados de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informação pode ser útil para entender quais são os produtos mais procurados pelos clientes e ajustar a estratégia de venda da loja em conformidade.
2. Média de Preço com Frete por Nome de Departamento: Para entender o comportamento do preço por departamento, podemos calcular a média de preço com frete por nome de departamento. Essa métrica pode ajudar a identificar quais são os departamentos mais rentáveis e ajustar a precificação de produtos de acordo com a margem de lucro desejada.
3. Quantidade de Vendas por Mês: Analisando a quantidade de vendas realizadas em cada mês, podemos identificar sazonalidades no comportamento de compra dos clientes, e assim planejar campanhas de marketing específicas para cada período.
4. Média de Renda por Canal de Venda: Identificar a média de renda dos clientes em diferentes canais de venda pode ajudar a loja a  ajustar a estratégia de marketing e vendas para cada público-alvo.
5. Média de Idade de Clientes por Bandeira: Saber a faixa etária dos clientes por bandeira pode ajudar a identificar perfis de consumidores e ajustar o marketing de venda para atender melhor cada público.
