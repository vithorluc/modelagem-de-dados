# Modelo relacional e sua composição

1. **Modelos:** É uma estrutura que ajuda a comunicar os conceitos que estão na mente do designer. Podemos usá-lo para tarefas como descrever, analisar, especificar e comunicar idéias.
Nota: O modelo deve ter detalhes suficientes para que um desenvolvedor possa construir o banco de dados de acordo com as necessidades do projeto.


1. **Modelagem de dados:** Modelagem física consiste em escolher um DBMS e criar o projeto (Modelagem lógica) neste sistema. O Modelo de Entidades e Relações é um modelo abstrato cujo objetivo é descrever, de maneira conceitual, os dados a serem utilizados em um Sistema de Informação ou pertencentes a um domínio.


* Modelos de dados;
* Hierárquico;
* Rede;
* Relacional;
* Orientado a Objeto;
* Não relacional.


1. **Modelo relacional:** No modelo relacional, os dados são armazenados em coleções de tabelas bidimensionais, essas tabelas também são chamadas de "relações", relações são uma maneira de organizar dados na forma de linhas e colunas, com base em lógica e teoria dos conjuntos.


## Composição do modelo relacional:


Coleção de objetos ou relacionamentos que armazenam dados;
Um conjunto de operadores que atuam em relacionamentos;
Integridade dos dados, para precisão e consistência.


## Componentes de um banco de dados relacional:


1. **Tabela:** Componente básico de um sistema RDBMS. Armazena dados necessários sobre algo no mundo real, como clientes, pedidos ou produtos. também chamado de relacionamento. Um banco de dados relacional pode ter uma ou mais tabelas.


1. **Tupla:** Ou linha / registro, representa os dados necessários para uma ocorrência específica de uma entidade específica. Por exemplo, os dados para um cliente específico. Cada linha em uma tabela deve ser identificada por uma chave primária, para que não haja duplicação de registros.


1. **Coluna:** Unidade que armazena um tipo específico de dados (valor) - ou não armazena nada, com um valor nulo. Esta é uma coluna não chave, o que significa que seu valor pode ser repetido em outras linhas da tabela.


1. **Relacionamento:** Associação entre entidades (tabelas), conectadas por chaves primárias e chaves estrangeiras.
Outros: Índices, SP, Triggers, etc.


1. **Chave Primária:** coluna (atributo) que identifica exclusivamente um registro na tabela. Por exemplo, o CPF de um cliente, contendo um valor que não é repetido na lista.


1. **Chave Secundária:** coluna que define como as tabelas se relacionam. Um FK refere-se a um PK ou uma chave exclusiva em outra tabela (ou na mesma tabela!). Por exemplo, na tabela de pedidos, podemos ter uma chave estrangeira estabelecendo o relacionamento com a chave primária na tabela de clientes.


## Modelo de Entidade-Relacionamento


* MER, cria um diagrama de entidade-relacionamento a partir das especificações comerciais ou narrativas do usuário. Permite ilustrar as entidades em um negócio e também os relacionamentos entre elas. Construímos o MER durante a fase de análise no ciclo de vida de desenvolvimento do sistema.

* Um MER separa as informações necessárias para o negócio das atividades que são realizadas para o negócio.


## componentes MER

1. **Entidade:** Algo significativo, sobre o qual devemos ter informações. Como exemplos, temos clientes, funcionários, pedidos e produtos.

1. **Atributos:** Algo que descreve ou qualifica uma entidade. Por exemplo, a entidade *cliente* possui atributos que descrevem seu nome, endereço, telefone, número de identificação, entre outros.

1. **Relacionamento:** Esta é uma associação nomeada entre entidades, com um grau de associação. Por exemplo, os clientes podem ser associados a pedidos.

## Convenções para modelar entidades, relacionamentos, atributos e cardinalidade

1. **Entidades:** Nome único e singular; Caps Lock;

1. **Atributos:** Nome no singular; minúsculas; atributos obrigatórios marcados com '*'; identificador exclusivo marcado com '#'.

1. **Relacionamento:** Nome do identificador (verbo); opcionalidade ("deve ser" ou "pode ​​ser"); grau ou cardinalidade ('um e apenas um' ou 'um ou mais').

1. **Cardinalidade:** Define o grau de relacionamento entre duas entidades ou tabelas. No modelo relacional, podemos ter os seguintes níveis de relacionamento: 1: N, N: N, 1: 1.

[Curso de modelagem de dados] (https://www.youtube.com/watch?v=hGstS10kCPM&list=PLucm8g_ezqNoNHU8tjVeHmRGBFnjDIlxD&index=2)
