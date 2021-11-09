# Apresentação da jornada de integração

- (trecho do e-mail com o comando do trabalho) A apresentação deve ser bem simples: descrição do problema, objetivo e proposta de solução.

### Tema: 

Predição de itens em compras recorrentes.


###  Descrição do problema

Alguns tipos de artigos, como por exemplo os hortifruti, possuem uma recorrência relativamente simples. Em geral, esse tipo de artigo é comprado semanalmente. Desta forma, uma aplicação que repete a lista comprada na semana anterior pode, muitas vezes, sugerir itens a serem comprados de forma satisfatória. Por outro lado, alguns itens não possuem uma recorrência tão óbvia, nem em relação a outros itens, nem em relação a outros usuários.

Sendo assim, buscaremos respostas das seguintes perguntas nessa pesquisa: Como proporcionar a seus usuários uma experiência diferenciada em relação a compras recorrentes? Quais algoritmos são candidatos para serem usados? uma vez que a forma com que esses algoritmos podem ser usados pode variar, assim como o resultado a ser obtido. 

Desta forma, apenas uma aplicação deve ser capaz de sugerir, de forma acurada, itens de recorrência mista na lista dos clientes.


### Objetivo Geral

O objetivo do projeto é facilitar e automatizar a rotina de compras recorrentes de itens de supermercados, através de uma plataforma que visa fornecer de forma inteligente, garantindo assim a reposição desses itens e abastecendo-o por um supermercado local que opera de forma otimizada sem grandes estoques e atuando numa região muito maior que a capacidade normal de uma loja física, trazendo diversos benefícios tanto para o consumidor quanto para o fornecedor.
### Objetivos Específicos:
- Criar um algoritmo capaz de encontrar padrões em dados coletados dos consumidores e propor uma métrica que usa a quantidade de acertos na sugestão do algoritmos em listas futuras.
- Reduzir o tempo gasto com realização de compras de itens recorrentes;
- Ampliar a região de abastecimento de supermercados e fornecedores locais.

### Proposta de solução

Para que tenhamos a versão final da plataforma web e aplicativo capaz de fornecer produtos de supermercado de forma recorrente e inteligente, de acordo com o perfil do consumidor. Será necessário uma solução baseada em uma arquitetura distribuída, composta por um servidor de banco de dados (MySQL), servidores de aplicação (Angular, React) e aplicações clientes (Ionic), interligadas por APIs - Application Program Interface (Laravel/PHP). Essa estrutura fica hospedada em nuvem (AWS - Amazon Web Services) e as aplicações clientes podem ser acessadas via navegador web ou por dispositivos móveis (Android e iOS).
