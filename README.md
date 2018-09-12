# Desenvolvimento de Aplicações Web

**Data de Apresentação: 10/12/2021**

**Valor: 35 pontos**

## Sistema Bibliotecário

A biblioteca do COLTEC decidiu atualizar o sistema de consulta às obras existentes em seu acervo, que atualmente está defasado. 
Para isso, a direção do colégio entrou em contato com o Setor de Informática no intuito de viabilizar a atualização do sistema.

Seu grupo deverá apresentar um primeiro protótipo do sistema, com as seguintes funcionalidades implementadas:

1. Cadastro de novas obras no acervo
1. Exibição das últimas obras cadastradas
1. Pesquisa às obras existentes

Você pode verificar em mais detalhes cada uma das funcionalidades abaixo:

### Cadastro de novas obras

O seu sistema deverá suportar o cadastro a novas obras. 
Para isso você deverá desenvolver uma interface que conterá um formulário de cadastro. 
Esse formulário deverá implementar mecanismos básicos de validação (tipo dos campos, formatação, etc.).

Ainda, para cada obra deverão se cadastrados os seguintes campos:

* Nome da obra
* Resumo da obra
* Nome do Autor
* Nome da Editora
* Nº de exemplares
* Data de cadastro da obra

### Exibição das últimas obras cadastradas

A página principal deverá listar as últimas obras cadastradas. 
A listagem poderá ser feita de duas formas: [grade](https://www.saraiva.com.br/universitarios/informatica) ou [lista](https://www.amazon.com.br/s?k=domain+driven+design&__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&ref=nb_sb_noss_2). 
Fica a critério do grupo definir como a listagem será feita.

Ainda, deverá haver uma barra de busca no topo da página, que será utilizada na funcionalidade a seguir.

### Pesquisa às obras existentes

A barra presente na página principal deverá permitir fazer a pesquisa das obras existentes na biblioteca. 
Essa pesquisa deverá abranger a busca pelo nome, autor ou editora. 
Os resultados da pesquisa deverão ser exibidos em uma nova página de listagem, que deverá mostrar a quantidade de registros pesquisados, seguidos da lista obtida a partir da busca.

## Entrega

A apresentação do trabalho ocorrerá no dia **10/12/2021**, por meio de um pull-request.
O aluno deverá também gravar um vídeo fazendo a demonstração das funcionalidades implementadas no projeto.

**OBS: O código quanto e apresentação serão levados em consideração no momento da avaliação!**

## Pilha de Tecnologias

Você estará livre para utilizar as bibliotecas e frameworks que considerar necessários. O uso de tais recursos inclusive é incentivado!!

Contudo, o desenvolvimento do trabalho **deve** englobar, de alguma forma, os seguintes conceitos:

* HTML
* PHP: Classes, funções, etc.
* PHP: Sessões e Cookies
* PHP: Arquivos