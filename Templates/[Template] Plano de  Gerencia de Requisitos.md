Índice Analítico
-----------------

* 1. [Introdução](#1-introdução)	
    * 1.1 [Objetivos](#11-objetivos)	
    * 1.2 [Público Alvo](#12-público-alvo)	
    * 1.3 [Organização do documento](#13-organização-do-documento)	
    * 1.4 [Definição de Siglas e Nomenclaturas](#14-definição-de-siglas-e-nomenclaturas)	
* 2. [Descrição do problema e do sistema](#2-descrição-do-problema-e-do-sistema)
    * 2.1 [Identificação e missão do Sistema](#21-identificação-e-missão-do-sistema)	
    * 2.2 [Domínio do problema e contexto de sua aplicação](#22-domínio-do-problema-e-contexto-de-sua-aplicação)	
    * 2.3 [Descrição dos interessados do sistema](#23-descrição-dos-interessados-do-sistema)	
* 3. [Requisitos e restrições não funcionais](#3-requisitos-e-restrições-não-funcionais)
    * 3.1 [Requisitos e Restrições de Usabilidade (RUS)](#31-requisitos-e-restrições-de-usabilidade-rus)	
    * 3.2 [Requisitos e Restrições de Interface Homem-Computador (RIHC)](#32-requisitos-e-restrições-de-interface-homem-computador-rihc)	
    * 3.3 [Requisitos e Restrições de Interface Externa (RIEX)](#33-requisitos-e-restrições-de-interface-externa-riex)	
    * 3.4 [Requisitos e Restrições de Plataforma de Hardware (RPHW)](#34-requisitos-e-restrições-de-plataforma-de-hardware-rphw)	
    * 3.5 [Requisitos e Restrições de Plataforma de Software (RPSW)](#35-requisitos-e-restrições-de-plataforma-de-software-rpsw)	
    * 3.6 [Requisitos e Restrições de Desempenho (RDES)](#36-requisitos-e-restrições-de-desempenho-rdes)	
    * 3.7 [Requisitos e restrições de disponibilidade (RDIS)](#37-requisitos-e-restrições-de-disponibilidade-rdis)	
    * 3.8 [Requisitos e Restrições de Segurança (RSEG)](#38-requisitos-e-restrições-de-segurança-rseg)	
    * 3.9 [Requisitos e Restrições de Manutenibilidade (RMAN)](#39-requisitos-e-restrições-de-manutenibilidade-rman)	
    * 3.10 [Requisitos e Restrições de Documentação (RDOC)](#310-requisitos-e-restrições-de-documentação-rdoc)
* 4. [Casos de Uso e Requisitos Funcionais](#4-casos-de-uso-e-requisitos-funcionais)	
    * 4.1 [Diagramas de Caso de Uso](#41-diagramas-de-caso-de-uso)	
    * 4.2 [Descrição de Casos de Uso](#42-descrição-de-casos-de-uso)	
* 5. [Requisitos Futuros (RFUT)](#5-requisitos-futuros-rfut)	
* 6. [Referências cruzadas complementares](#6-referências-cruzadas-complementares)	
* 7. [Aprovação Formal](#7-aprovação-formal)	
* 8. [Bibliografia](#8-bibliografia)	
* 9. [Anexos](#9-anexos)	


## 1. Introdução

Esta seção deverá apresentar o documento ao leitor. O objetivo principal da introdução é descrever o documento e não o sistema, embora deva ser mencionado qual é o sistema e para qual empresa ou mercado ele será construído. O conteúdo a ser coberto na introdução está descrito nas subseções seguintes.	

### 1.1 Objetivos

Definir os objetivos do documento.	
Exemplo:	
Este documento tem os seguintes objetivos:	
•	Definir os interessados no sistema e as suas necessidades que devem ser satisfeitas pelo sistema a ser desenvolvido;	
•	Derivar os casos de uso e requisitos do sistema de forma a orientar a equipe de que será responsável pelo seu desenvolvimento;	
•	Estabelecer um contrato para negociação e concordância entre todos os interessados;	
•	Reduzir retrabalho com projeto, codificação e teste através da especificação rigorosa e completa dos requisitos;	
•	Prover uma base para avaliação de prazos e custos de desenvolvimento;	
•	Facilitar a transferência dos produtos do desenvolvimento para novos usuários, novos clientes, novos ambientes operacionais e novas equipes de desenvolvimento e manutenção;	
•	Prover uma base para a evolução futura do sistema a partir de uma versão aprovada (linha de base) deste documento.	

### 1.2 Público Alvo

Identificar o público alvo do documento, isto é, todos os perfis de pessoas que terão interesse na sua leitura. Os interesses de cada perfil na leitura do documento também devem ser descritos.

### 1.3 Organização do documento

Descrever suscintamente a organização do documento em seções e o conteúdo de cada seção. Não há necessidade de descer ao nível de subseções.

### 1.4 Definição de Siglas e Nomenclaturas

Definir e explicar sucintamente siglas e nomencalturas utilizadas neste documento.

## 2. Descrição do problema e do sistema
-----------------------------------------

Nesta seção o sistema objeto da especificação de requisitos deve ser descrito. O domínio do problema que deverá ser resolvido pelo sistema deve ser explicado e também as características específicas do problema no contexto da empresa em que o sistema deverá ser utilizado. As subseções seguintes podem ser colocadas no documento EOR para separar cada conteúdo específico, mas também pode ser usado um estilo de texto sem separação de subseções desde que todo o conteúdo seja coberto.

### 2.1 Identificação e missão do Sistema

Identificar o sistema objeto da especificação de requisitos e definir em poucas palavras qual é a missão do sistema que está sendo considerado neste documento.

### 2.2 Domínio do problema e contexto de sua aplicação

A descrição do domínio do problema deve complementar e detalhar a visão geral do domínio do problema identificando o contexto deste problema no ambiente alvo (ambiente do cliente alvo).
Exemplo:
Suponha que o domínio do problema seja a venda de produtos em um comércio varejista. Esta seção deverá explicar em que consiste o problema de vender produtos em uma empresa que atua no comércio varejista, ou seja, descrever genericamente quais são os processos de negócio envolvidos e seus objetivos. Além disso, o problema deve ser contextualizado mostrando as características específicas do problema na empresa alvo.

### 2.3 Descrição dos interessados do sistema

Descrever os perfis de cada interessado envolvido com o sistema.

| Interessado(s) 	| Descrição 	|
|:----------------:	|---------	|
| Nome do perfil do interessado. Por exemplo: (cliente, atendente, vendedor, gerente comercial, etc.) | Descrever o perfil do interessado e como se espera que seja sua interação com o sistema direta ou indiretamente. Por exemplo, o vendedor da loja é a pessoa que atende os clientes e registra as vendas que são feitas. |

## 3. Requisitos e restrições não funcionais 
--------------------------------------------

Elaborar uma lista de todos os requisitos não funcionais. A lista poderá ser dividida por tipo de requisito, mas é importante que os requisitos tenham uma identificação única para que possam ser referenciados sem ambiguidades no futuro.

### 3.1 Requisitos e Restrições de Usabilidade (RUS)

Elaborar uma lista de todas as necessidades de informação que o software não pode deixar de atender. Esta lista deverá ser classificada em informações cadastrais e informações gerenciais. Por exemplo, para um software de vendas existem, entre outras, as seguintes necessidades de informação:
Exemplo:

| Ref. 	|              Descrição                                               	| Caso de Uso     	|
|------	|-------------------------------------------------------------------	|-----------------	|
| RUSx | Descrição do requisito RINFx  | CSUy, CSUm ...  |

Estes requisitos de informação são importantes para verificar a qualidade da modelagem de dados que for feita.       

### 3.2	Requisitos e Restrições de Interface Homem-Computador (RIHC)

Definir os aspectos de Interface Homem Computador (IHC) como: conteúdo de informações, fatores ergonômicos, dispositivos de interação, formato de apresentação, tipo de diálogo, e mecanismos de ajuda alocados a cada perfil/grupo/tarefa de usuário. Descrever, em particular, os requisitos de usabilidade para cada perfil/grupo/tarefa de usuário. Por exemplo, pode-se definir como requisito que as opções de menu do sistema tenham teclas de atalho associadas. 
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RIHCx 	| Descrição do requisito RIHCx | CSUy, CSUm ... |

### 3.3 Requisitos e Restrições de Interface Externa (RIEX)

Identificar e descrever as interfaces com outros softwares/sistemas que o software deverá prover. Por exemplo, um software comercial deve gerar informações para o Sistema de Arrecadação da Secretaria da Fazenda Estadual. O formato dessas informações e o protocolo de envio são definidos pela própria secretaria, e atender essas definições é um requisito do software.
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RIEXx 	| Descrição do requisito RIEXx | CSUy, CSUm ...	|

### 3.4 Requisitos e Restrições de Plataforma de Hardware (RPHW)

Identificar e descrever requisitos e restrições relacionadas com a plataforma de hardware que será utilizada pelo software:
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RPHWx	| Descrição do requisito RPHWx | CSUy, CSUm ... |


### 3.5 Requisitos e Restrições de Plataforma de Software (RPSW)

Se o software tiver que ser executado em plataformas de software específicas, essas plataformas de software deverão ser definidas:
1. Sistema Operacional: identificar e descrever o sistema operacional em que o software deverá ser executado;
2. Softwares Básicos: identificar SGBD, linguagem de programação, ferramentas CASE e outros.
Se houver mais de uma plataforma de software, deve-se especificar qual a plataforma principal e em que situações as outras plataformas podem ser utilizadas.
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RPSWx | Descrição do requisito RSPWx | CSUy, CSUm ... |

### 3.6 Requisitos e Restrições de Desempenho (RDES)

Identificar e descrever os requisitos e restrições de desempenho do software.
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDESx | Descrição do requisito RDESx | CSUy, CSUm ... |

### 3.7 Requisitos e restrições de disponibilidade (RDIS).

Especificar os requisitos de disponibilidade necessários para o software de uma forma global:
1. Período de disponibilidade: horário comercial, 24 horas por dia, etc.
2. Período máximo para recuperação do software em caso de falha.
Devem ser definidos os tipos de falha e a tolerância aceitável para cada tipo de falha. Os tipos de falha podem ser definidos em função dos requisitos funcionais e de dados, mas não se restringem a estes. Por exemplo: a função “Registrar Venda” deve ter um tempo para recuperação de falha de no máximo uma hora (o que significa que esta função não poderá ficar mais do que uma hora indisponível para o usuário em nenhuma circunstância). 
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDISx	| Descrição do requisito RDISx | CSUy, CSUm ... |

### 3.8 Requisitos e Restrições de Segurança (RSEG)

Especificar os requisitos de segurança necessários para controle de acesso ao software. Definir a necessidade, por exemplo, de:
1. Verificação de senha;
2. Criptografia de dados;
3. Registro das operações efetuadas;
4. Habilitação de funções por perfil de usuário;
5. Acesso seletivo aos dados e funções.
Exemplo:

| Ref.  	|              Descrição                      	| Caso de Uso 	|
|-------	|------------------------------------------	|-------------	|
| RSEGx | Descrição do requisito RSEGx | CSUy, CSUm ... |

### 3.9 Requisitos e Restrições de Manutenibilidade (RMAN)

Especificar os requisitos que visam facilitar a manutenção posterior do software, tais como:
1. Requisitos de reutilização (exemplo: uso de implementação orientada a objetos; bibliotecas de classes e padrões de projeto);
2. Requisitos de modularização (exemplo: valores para métricas de acoplamento entre módulos; máximo de pontos de função por módulo);
3. Requisitos de configuração (exemplo: regras para controle de versões);
4. Requisitos de documentação (exemplo: documentação de programa)
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RMANx	| Descrição do requisito RMANx | CSUy, CSUm ... |

### 3.10 Requisitos e Restrições de Documentação (RDOC)

Especificar os requisitos de documentação do produto de software que será desenvolvido. 
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDOCx | Descrição do requisito RDOCx | CSUy, CSUm ... |

## 4. Casos de Uso e Requisitos Funcionais
---------------------------------

### 4.1 Diagramas de Caso de Uso

Este espaço deverá mostrar os casos de uso do sistema através de diagrama de caso de uso. Podem ser usados mais de um diagrama para facilitar a visualização e compreensão do leitor caso o número de casos de uso seja considerado grande.

### 4.2 Descrição de Casos de Uso

Cada caso de uso deve receber um identificador único, ser categorizado em primário, obrigatório ou opcional e ser descrito em um formato essencial resumido conforme explicado no capítulo 6 da terceira edição do livro “Utilizando UML e Padrões” de Craig Larman. Veja o exemplo a seguir:

CSU1- Processar Venda
	Atores: Vendedor e Cliente
	Categoria: Primário
Descrição: 
Este caso de uso acontece quando um cliente chega a um ponto de venda com itens de produtos que deseja adquirir. O caixa usa o sistema para registrar cada item comprado. O sistema vai apresentando um total parcial e uma linha de detalhes à medida que registra cada item. O cliente fornece ao caixa os dados sobre o pagamento que são então validados e registrados pelo sistema. O sistema atualiza o estoque e emite um recibo que é entregue pelo caixa ao cliente. O cliente sai com os itens comprados.
	Requisitos Funcionais:


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| RFUN 1.1 | Obter e exibir a descrição e valor unitário de um produto a partir de seu código identificador | Evidente | Alta |
| RFUN 1.2 | Calcular e exibir o total parcial da venda a cada item informado | Evidente | Alta |
| RFUN 1.3 | Registrar o valor recebido para venda realizada | Evidente | Alta |
| RFUN 1.4 | Calcular e exibir o troco para o pagamento em dinheiro | Evidente | Alta |
| RFUN 1.5 | Emitir recibo de pagamento | Evidente | Alta |
| RFUN 1.6 | Atualizar o estoque do produto vendido | Evidente | Alta |
| RFUN 1.7 | Registrar dados da venda realizada (data, hora, PDV, produtos vendidos...) | Evidente | Alta |




## 5. Requisitos Futuros (RFUT)
---------------------------------

Descrever os requisitos que poderão ser especificados em uma nova versão do produto.

| Ref.|   Descrição | Caso de Uso |
|-------|------------|---------------|
| RFUT1 | Em um futuro próximo o software de atendimento de clientes deverá ser integrado com o software do sistema de faturamento para que o atendente possa identificar o perfil de negócios do cliente | CSUx |


## 6. Referências cruzadas complementares 
---------------------------------------------

Nesta seção são colocadas algumas referências cruzadas que podem ajudar o rastreamento futuro dos requisitos. Estes mapeamentos podem ser feitos em forma de matrizes de rastreabilidade como mostram os exemplos a seguir:

|Requisitos Funcionais | Requisitos Não-Funcionais|
|---------------------|--------------------------|
|Colocar identificação do requisito funcional|Colocar a identificação do requisito não funcional vinculado|

|Requisitos Funcionais | Origem do Requisito |
|---------------------|--------------------------|
| Colocar identificação dos requisitos funcionais | Colocar a origem do requisito. Pode ser uma entrevista, um questionário, ou outra técnica qualquer de elicitação de requisito aplicada. |

|Requisitos Não-Funcionais | Origem do Requisito |
|---------------------|--------------------------|
| Colocar identificação dos requisitos não-funcionais | Colocar a origem do requisito. Pode ser uma entrevista, um questionário, ou outra técnica qualquer de elicitação de requisito aplicada. |

| Casos de Uso | Origem do Caso de Uso |
|---------------------|--------------------------|
| Colocar a identificação do requisito funcional | 
Colocar a origem do caso de uso. Pode ser uma entrevista, um questionário, ou outra técnica  qualquer de elicitação de requisito aplicada. |

## 7. Aprovação Formal 
---------------------------------------------

O EOR deve ser datado e assinado de acordo com a definição contida no MPD. O documento aprovado se torna uma baseline do projeto que passa a ser controlada pela Gerência de Configuração de Software.

## 8. Bibliografia
---------------------------------------------

Detalhar todas as fontes de informação citadas no documento ou usadas de alguma forma para sua elaboração, incluindo título, autor, data, fonte de obtenção, órgão responsável pela publicação e qualquer outra informação que possa facilitar a localização e obtenção dessas fontes pelo leitor. Nesta seção cada fonte citada deve ser associada a um número identificador. Junto de cada citação deve ser colocada também uma explicação sucinta de como a fonte foi usada na elaboração do documento.
Referenciar todas as fontes de informações citadas no EOR, explicando o motivo de sua citação. Devem ser incluídos, por exemplo:

* Normas e Padrões utilizados;
* Livros e artigos (autores, título, editora, páginas, volume, data e local da publicação, ISBN/ISSN, etc);
* Manuais de outros Produtos.

Por exemplo, vamos supor que para elaborar o documento XXX-EOR-001 foram usadas as orientações contidas no Meta-Modelo de Especificação de Objetivos e Requisitos (EOR). Então, nesta seção deveria aparecer o seguinte texto:
[1] Ronaldo Lopes de Oliveira, EOR – Modelo de Documento de Especificação de Objetivos e Requisitos de Software, Versão 2.0, abril de 2014.
Meta-Modelo usado como guia para definição do formato e conteúdo deste documento.



## 9. Anexos 
---------------------------------------------
Anexar ao EOR documentos considerados importantes para sua compreensão. Por exemplo, documentos e leis usadas na especificação dos requisitos podem ser colocados nos anexos para facilitar o acesso do leitor às fontes dos requisitos do software. Cada anexo deverá receber uma folha de rosto indicando seu conteúdo.
