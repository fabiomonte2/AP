# Anteprojeto de pesquisa



### Tema: 

Predição de itens em compras recorrentes

## Introdução
Com o advento da internet, vemos cada vez mais hábitos sendo mudados e migrando para o mundo da rede. As platarformas online de compra são um exemplo de como as pessoas estão substituindo a forma de adquirir produtos e para os comerciantes, a recompra de um cliente é fundamental Liu (2020). 
Ainda sobre Liu (2020), os aspectos estudados que influenciam na recompra podem ser: da confiança e do comprometimento como fator intermediário importante, a satisfação específica da transação, a falha do comerciante em atender o pedido conforme esperado, o que o cliente deseja em um ambiente de compra e o processo de entrega do produto adquirido. Entender esses e outros aspectos é fundamental para a escolha de um modelo de predição que irá recomendar uma lista de produtos que irão influenciar a recompra.
Segundo Pavlyshenko (2019) a previsão de vendas é uma parte importante para empresas atuais tornem seus negócios mais inteligentes. Nesse aspecto, as vendas podem ser consideradas como um tipo de série temporal que devem ser analisadas baseando-se em abordagens diferenciadas para prever cada tipo.



###  O problema

Alguns tipos de artigos, como por exemplo os hortifruti, possuem uma recorrência relativamente simples. Em geral, esse tipo de artigo é comprado semanalmente. Desta forma, uma aplicação que repete a lista comprada na semana anterior pode, muitas vezes, sugerir itens a serem comprados de forma satisfatória. Por outro lado, alguns itens não possuem uma recorrência tão óbvia, nem em relação a outros itens, nem em relação a outros usuários.

A empresa parceira desta pesquisa, a Homelist, atua de maneira manual em relação a predição de itens, que no caso do supermercado, exercem função de compras recorrentes. Com as platarformas disponíveis ao cliente é possível receber pedidos até um certo momento, e os funcionários é quem fazem as compras e entregas dos supermercados selecionados anteriormente.

Sendo assim, buscaremos respostas das seguintes perguntas nessa pesquisa: Como proporcionar aos usuários da plataforma web e aplicativo uma experiência diferenciada em relação a compras recorrentes? Quais algoritmos são candidatos para serem usados? uma vez que a forma com que esses algoritmos podem ser usados pode variar, assim como o resultado a ser obtido. Desta forma, apenas uma aplicação deve ser capaz de sugerir, de forma acurada, itens de recorrência mista na lista dos clientes.

### A proposta 

?????


### Objetivo Geral

O objetivo do projeto é facilitar e automatizar a rotina de compras recorrentes de itens de supermercados, através de uma plataforma de e-commerce que visa fornecer de forma inteligente, garantindo assim a reposição desses itens e abastecendo-o por um supermercado local que opera de forma otimizada sem grandes estoques e atuando numa região muito maior que a capacidade normal de uma loja física, trazendo diversos benefícios tanto para o consumidor quanto para o fornecedor.

### Objetivos Específicos:
- Criar um algoritmo capaz de encontrar padrões em dados coletados dos consumidores e propor uma métrica que usa a quantidade de acertos na sugestão do algoritmos em listas futuras.
- Reduzir o tempo gasto com realização de compras de itens recorrentes;
- Ampliar a região de abastecimento de supermercados e fornecedores locais.

### Organização do trabalho

Esse trabalho está organizado da seguinte maneira: (um parágrafo)

## Referencial teórico

O e-commerce, segundo Nakamura (2011) é toda atividade de compra e venda realizada com o apoio da tecnologia. Sendo assim, o tema da pesquisa está atrelado a um tipo de comércio eletrônico que procurará analisar fatores e características que nos oriente a predizer as compras recorrentes de clientes que buscam esse tipo de serviço.

A platarforma de e-commerce estudada já é desenvolvida pela empresa parceira, porém de forma manual no quisito de recomendação de ítens e possui o nome de Homelist. Disponível em versão de aplicativo mobile e também em uma plataforma web, como mostram as figuras 1 e 2,  a empresa trablha com venda de produtos de supermercado e busca junto ao programa de computação aplicada desenvolver um algoritmo que seja capaz de realizar uma predição nesses ítens que possuem características de compras recorrentes aos clientes.

<<<<<<< HEAD
Tendo em vista esses fatos, é imprescindível que a empresa Homelist, bem como empresas que buscam trabalhar com esse tipo de comércio, abordem estratégias que possam estar de acordo com a evolução tecnológica. Vale ressaltar que o comércio eletrónico, além de realizar compras e vendas de mercadorias, abrange também a entrega ou torca de informações, a prestração de serviçõs ao cliente antes e depois de uma venda, a colaboração comparceiros e negócios e o esforço para aumentar a produtividade dentro das organizações Napier (2006).
=======

Vale ressaltar que o comércio eletrónico, além de realizar compras e vendas de mercadorias, abrange também a entrega ou torca de informações, a prestração de serviçõs ao cliente antes e depois de uma venda, a colaboração comparceiros e negócios e o esforço para aumentar a produtividade dentro das organizações Napier (2006).
>>>>>>> 4243bc01e68591d8e4f8be9d646b4ccab52f0561

Para conluir os referencias sobre e-commerce, baseando-se nos pressupostos já citados, incluímos de maneira mais simples o que foi dito por Neto (2017), que se trata de um tipo de comércio virtual que premite uma interação entre as empresas e os consumidores, seja ela por meio da compra e venda ou até mesmo pela troca de produtos, serviços ou informações.

Nesse sentido, faz-se necessário a utilização de técnicas de aprendizado de máquinas, séries temporais e análise preditiva afim de melhorar as relações que compõe a compra e venda em platarformas digitais.



## Materiais e métodos


De posse de uma grande massa de dados, é possível utilizar algoritmos de predição para sugerir itens a
serem incluídos na lista dos clientes. Entretanto, existem inúmeros algoritmos candidatos para serem
usados. Além disso, a forma com que esses algoritmos podem ser usados pode variar, assim como o
resultado a ser obtido. A definição de algumas métricas para estimar o sucesso de cada algoritmo
combinado com a forma em que eles são usados é indispensável. Sendo assim, será definida uma métrica
que usa a quantidade de acertos na sugestão do algoritmos em listas futuras. Ainda assim, é necessário
diferenciar a qualidade dos acertos, podendo ter pesos diferentes para sugestões não aceitas pelos
usuários e itens inseridos pelos usuários mas não foram sugeridos pelo algoritmo. A partir dessas
métricas, será possível comparar os algoritmos e a forma como eles são usados, e assim utilizar o
algoritmo mais apropriado para o problema. Lembrando que o modelo de algoritmo a ser utilizado precisa
estar preparado para se adaptar a novas situações, como por exemplo o surgimento de novos produtos ou
uma mudança de comportamento do usuário. No primeiro exemplo, a mudança de comportamentos de
outros usuários pode alterar as sugestões para um determinado cliente, mesmo que tal produto nunca
tenha sido comprado por este usuário. No segundo exemplo, o algoritmo deverá ser capaz de identificar a
probabilidade de que a alteração ou uma baixa taxa de acerto em uma determinada lista de um cliente
seja uma mudança esporádica ou um novo padrão de compra.



##### Dicas da pesquisa:

- um paragrafo por imagem/figura citada.
