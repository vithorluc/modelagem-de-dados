# Modelagem de dados - Níveis

## Classificamos o processo de modelagem em três níveis:


1. Modelo conceitual (alto nível) - MCD

1. Modelo Lógico - MLD

1. Modelo físico (nível baixo) - MFD


## Modelo conceitual


Esta é a primeira fase da modelagem, na qual representamos o mundo em relação ao poder por meio de uma visão simplificada dos dados e de seus relacionamentos. Dessa forma, podemos determinar quais informações serão armazenadas no banco de dados.

Nesse nível, o projeto é independente do DBMS.

Exemplo:
**Registre um produto em uma loja**
Dados necessários: Nome do produto, categoria do produto (limpeza, higiene etc.), código do fornecedor, tipo de embalagem, tamanho, quantidade.

Nesse nível, os detalhes da implementação não aparecem, no entanto, é detalhado o suficiente para poder descrever os tipos de dados necessários, seus relacionamentos entre si e regras de consistência.


## Modelo lógico


* Um modelo lógico possui conceitos que os usuários são capazes de entender, embora não estejam muito longe do modelo físico do banco de dados.

* Nesse nível, o projeto é independente do DBMS.

* Consiste na especificação lógica dos dados em um formato adequado ao DBMS escolhido. Os tipos de dados são completamente definidos.


## Modelo físico


* **De um modelo lógico** derivamos **do modelo físico**, que detalha os componentes da estrutura física do banco de dados, incluindo tabelas, campos, tipos de valores, etc.

* Ao criar o modelo físico, podemos começar a implementar o banco de dados usando o DBMS mais adequado.


## Arquitetura de três camadas


* Modelo em três camadas (3-Tier), derivado do modelo 'n' camadas, recebe esta denominação quando um sistema cliente-servidor é desenvolvido retirando-se a camada de negócio do lado do cliente. O desenvolvimento é mais demorado no início comparando-se ao modelo em duas camadas porque é necessário dar suporte a uma maior quantidade de plataformas e ambientes diferentes. Em contrapartida, o retorno vem em forma de respostas mais rápidas nas requisições, tanto em sistemas que rodam na Internet ou em intranet, e mais controle no crescimento do sistema.



## Esquema do banco de dados


* Um esquema e uma definição de banco de dados especificados durante o projeto, armazenados no **dicionário de dados**.

* Um esquema raramente muda durante a vida útil do DBMS.

* Trata-se de organizar os dados em um plano que mostra como o banco é construído.

* O esquema define tabelas, campos, relacionamentos, visualizações, funções e muitos outros elementos que compõem o banco de dados.


## Etapas do desenvolvimento do banco de dados


As principais etapas no desenvolvimento de um banco de dados são:

- Especificação e análise de requisitos.
  -Os requisitos estão documentados.

- Design conceptual
  -Com base nos requisitos

- Design lógico
  -Expressa em um modelo de dados, como o relacional.

- Projeto físico
  -Especificações para armazenar e acessar o banco de dados.
  -Implementação de banco de dados, inserção de dados reais e manutenção.


## Tarefas de modelagem


As tarefas de modelagem devem ser executadas para que seja possível executar a modelagem de dados e o design funcional do banco de dados:

* Identifique os tipos de entidades

* Identificar atributos

* Identificar relacionamentos

* Crie e associe chaves

* Normalize para reduzir a redundância

* Desnormalizar para aumentar o desempenho

## MER


Após o levantamento dos requisitos, eles são transformados em um **Modelo de Entidade-Relacionamento** (MER), que consiste nos seguintes elementos:

* Entidades
* Relacionamentos
* Atributos

O modelo é refinado ainda mais usando técnicas específicas e finalmente implementado em um banco de dados físico.
