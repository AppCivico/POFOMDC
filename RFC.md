# contratos.paraondefoiomeudinheiro.com.br/

## Introdução

### Status do documento

* Versão 0.1 - 17 de Setembro 2015. Versão Inicial. (Thiago Rondon)

### Abstração

Esta é a especificação para desenvolver o novo projeto do "Para onde foi o meu dinheiro ?". O principal objetivo deste novo projeto é o mapeamento de despesas do governo através de contratos e não pela execução orçamentária, e com isto gerar um testemunho social.

### Objetivo

O objetivo geral é poder tornar os contratos "mais públicos", para que:

* Eles sejam encontrados por buscadores na Internet. 
* Facilitar a visualização e exploração dos contratos para um público maior.
* Compartilhar opiniões sobre os contratos.
* Vincular notícias relacionado aos contratos.
* Gerar discussões sobre o andamento através dos envolvidos e testemunhos sociais.

### Terminologia

#### Contratos

São os documentos que descrevem o acordo realizado entre as duas partes, e especificação o que é oferecido e o que é pago.


## Arquitetura da plataforma

### Visão Geral

A plataforma é baseado em um banco de dados que seja capaz de armazenar os documentos, com meta-dados. Este banco é gerenciado por um backend (API) que tem como objetivo ser a comunicação para facilitar o desenvolvimento das interfaces.

### Estrutura do banco de dados

A estrutura do banco de dados deve contemplar para os contratos pelo menos estes campos:

* Nome do órgão 
* Data da assinatura
* Vigência
* Modalidade de contratação
* Identificação única do fornecedor (No Brasil, CNPJ)
* Número do processo administrativo
* Nome do Fornecedor
* Valor total do contrato
* Data da publicação do contrato para o público.
* Objetivo (objeto)

### SEO

Para que estes contratos sejam mais públicos e acessíveis, a ideia é desenvolver na interface maneiras de facilitar que eles sejam encontrados com técnicas 
para otimizar que eles sejam encontrados.

## Indicadores

A plataforma deve ser capaz de demonstrar indicadores, tais eles como o número total de contratos, valor total de contratos, série histórica por ano e etc.

O objetivo é que existe uma interface para geração destes indicadores de maneira assíncrona.

## Rank

A plataforma, também deve permitir que sejam listadas informaçòes como: Empresas com o maior número de contratos, Empresas com os maiores valores em contrato, Empresas com a maior soma em valores e quantidade de contratos, Contratos adicionados recentemente, Comentários realizados recentemente e etc.

## Compare empresas

Interface para adicionar duas ou mais empresas, e montar uma tabela com informações:

- Número de contratos
- Contratos vigentes
- Valores totais
- Comentários

## Comparação de contratos

Possibilitar o compartilhamento de uma URL que tenha o comparativo entre os dois contratos.

## Selo de dialogo aberto

Uma empresa, governo ou sociedade cívil podem divulgar um selo baseado no nível de participação na plataforma.

## Parceiros institucionais

(em desenvolvimento)

## Participação

O perfil terá a possibilidade de ser verificado ou não pela equipe da plataforma. Os atores são as empresas, governo, entidades da sociedade cívil e pessoas.


# Interface

/perfil
-> contratos associados
-> últimos comentários

/contrato
-> meta-dados
-> documento

# Desenvolvimento e validação inicial

* http://transparencia.prefeitura.sp.gov.br/contas/Paginas/Contratos-v2.aspx

