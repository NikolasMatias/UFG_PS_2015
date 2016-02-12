
Processo de software 2015, [Template]Plano de gerência de requisitos

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

Este documento tem como objetivo apresentar o escopo, Requisitos Funcionais, Não Funcionais, Regras de Negócio e Casos de Uso os usuários e tudo que envolva o processo de Engenharia de Requisitos para o programa Mr. Imune.

### 1.1 Objetivos

[_Definir os objetivos do documento._]	
_Exemplo:_
_Este documento tem os seguintes objetivos:_
•	[_Definir os interessados no sistema e as suas necessidades que devem ser satisfeitas pelo sistema a ser desenvolvido;_]
•	[_Derivar os casos de uso e requisitos do sistema de forma a orientar a equipe de que será responsável pelo seu desenvolvimento;_]	
•	[_Estabelecer um contrato para negociação e concordância entre todos os interessados;_]	
•	[_Reduzir retrabalho com projeto, codificação e teste através da especificação rigorosa e completa dos requisitos;_]	
•	[_Prover uma base para avaliação de prazos e custos de desenvolvimento;_]
•	[_Facilitar a transferência dos produtos do desenvolvimento para novos usuários, novos clientes, novos ambientes operacionais e novas equipes de desenvolvimento e manutenção;_]	
•	[_Prover uma base para a evolução futura do sistema a partir de uma versão aprovada (linha de base) deste documento._]	

### 1.2 Público Alvo

* Gerente de Requisitos: Para poder verificar o documento.
* Analista de Projeto Arquitetural: Para ter uma base para o processo arquitetural do software.
* Gerente de Qualidade: Para poder validar a qualidade do documento.
* Analista de Testes: Para poder já começar a criar os casos de teste.
* Gerente de Projeto: O gerente tem de estar informado sobre o andamento do  projeto.
### 1.3 Organização do documento

Aqui será descrito a organização do documento de requisitos:
* Capítulo 2 - Descrição do problema e do sistema: Nesta seção o sistema objeto da especificação de requisitos deve ser descrito. O domínio do problema que deverá ser resolvido pelo sistema deve ser explicado e também as características específicas do problema no contexto da empresa em que o sistema deverá ser utilizado. As subseções seguintes podem ser colocadas no documento EOR para separar cada conteúdo específico, mas também pode ser usado um estilo de texto sem separação de subseções desde que todo o conteúdo seja coberto.
* Capítulo 3 - Requisitos e restrições não funcionais: Elaborar uma lista de todos os requisitos não funcionais. A lista poderá ser dividida por tipo de requisito, mas é importante que os requisitos tenham uma identificação única para que possam ser referenciados sem ambiguidades no futuro.
* Capítulo 4 - Casos de Uso e Requisitos Funcionais: Nesse campo vai ser colocado os Casos de Uso e os Requisitos Funcionais
* Capítulo 5 - Requisitos Futuros (RFUT): Descrever os requisitos que poderão ser especificados em uma nova versão do produto.
* Capítulo 6 - Referências cruzadas complementares: Nesta seção são colocadas algumas referências cruzadas que podem ajudar o rastreamento futuro dos requisitos.
* Capítulo 7 - Aprovação Formal: O EOR deve ser datado e assinado de acordo com a definição contida no MPD. O documento aprovado se torna uma baseline do projeto que passa a ser controlada pela Gerência de Configuração de Software.
* Capítulo 8 - Bibliografia: Detalhar todas as fontes de informação citadas no documento ou usadas de alguma forma para sua elaboração, incluindo título, autor, data, fonte de obtenção, órgão responsável pela publicação e qualquer outra informação que possa facilitar a localização e obtenção dessas fontes pelo leitor. Nesta seção cada fonte citada deve ser associada a um número identificador. Junto de cada citação deve ser colocada também uma explicação sucinta de como a fonte foi usada na elaboração do documento.
* Capítulo 9 - Anexos: Anexar ao EOR documentos considerados importantes para sua compreensão. Por exemplo, documentos e leis usadas na especificação dos requisitos podem ser colocados nos anexos para facilitar o acesso do leitor às fontes dos requisitos do software. Cada anexo deverá receber uma folha de rosto indicando seu conteúdo.

### 1.4 Definição de Siglas e Nomenclaturas

Siglas, Acronimos, Nomeclaturas e Abreviações | Definições
-------------------------------------------- | ----------------
Letalidade  | O quão mortal é uma doença
Prevalência | O tanto que a doença está se espalhando em um determinado período de tempo.
RF | Requisito Funcional
RNF | Requisito Não Funcional
RN | Regra de Negócio
UC | User Case(Caso de Uso)


## 2. Descrição do problema e do sistema
-----------------------------------------

### 2.1 Identificação e missão do Sistema

O sistema é o Mr. Imune que tem como objetivo transformar o histórico de vacinas da população de um meio fisico para digital.

### 2.2 Domínio do problema e contexto de sua aplicação

Atualmente a população anda utilizando de um meio fisico, que no caso seria o papel, para organizar as vacinas que tomou. O problema é que a pessoa pode acabar perdendo o documento e as pessoas responsáveis pelo campo da saúde não tem controle do que a pessoa tomou nesses casos. O Sistema ajudará nesse ponto, deixando as informações da população segura, de modo que não se perca caso ocorra algo.

### 2.3 Descrição dos interessados do sistema

_Descrever os perfis de cada interessado envolvido com o sistema._

| Interessado(s) 	| Descrição 	|
|:----------------:	|---------	|
| Registrador | Pessoa que faz registro inicial, no momento da emissão da certidão de nascimento, ou nos postos serviço de atendimento ao usuário |

| Interessado(s) 	| Descrição 	|
|:----------------:	|---------	|
| Paciente | pessoa que pode acessar a qualquer momento o seu histórico de vacinas na internet |

| Interessado(s) 	| Descrição 	|
|:----------------:	|---------	|
| Agente de saúde | pessoa que pode acessar e registrar as vacinas assim que o paciente é imunizado. |

| Interessado(s) 	| Descrição 	|
|:----------------:	|---------	|
| Administrador de secretaria | Profissional da Secretaria de Saúde Estadual responsável pelo calendário anual de vacinas. |

| Interessado(s) 	| Descrição 	|
|:----------------:	|---------	|
|Administrador Geral |A pessoa escolhida pelo Ministério da saúde para poder servir como a autoridade suprema ao que se refere ao sistema. |

## 3. Requisitos e restrições não funcionais 
--------------------------------------------

[_Elaborar uma lista de todos os requisitos não funcionais. A lista poderá ser dividida por tipo de requisito, mas é importante que os requisitos tenham uma identificação única para que possam ser referenciados sem ambiguidades no futuro._]

### 3.1 Requisitos e Restrições de Usabilidade (RUS)

_Elaborar uma lista de todas as necessidades de informação que o software não pode deixar de atender. Esta lista deverá ser classificada em informações cadastrais e informações gerenciais. Por exemplo, para um software de vendas existem, entre outras, as seguintes necessidades de informação:_
_Exemplo:_

| Ref. 	|              Descrição                                               	| Caso de Uso     	|
|------	|-------------------------------------------------------------------	|-----------------	|
| [_RUSx_] | [_Descrição do requisito RINFx_]  | [_CSUy, CSUm ..._]  |

_Estes requisitos de informação são importantes para verificar a qualidade da modelagem de dados que for feita._       

### 3.2	Requisitos e Restrições de Interface Homem-Computador (RIHC)

_Definir os aspectos de Interface Homem Computador (IHC) como: conteúdo de informações, fatores ergonômicos, dispositivos de interação, formato de apresentação, tipo de diálogo, e mecanismos de ajuda alocados a cada perfil/grupo/tarefa de usuário. Descrever, em particular, os requisitos de usabilidade para cada perfil/grupo/tarefa de usuário. Por exemplo, pode-se definir como requisito que as opções de menu do sistema tenham teclas de atalho associadas._ 
_Exemplo:_

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| [_RIHCx_] 	| [_Descrição do requisito RIHCx_] | [_CSUy, CSUm ..._] |

### 3.3 Requisitos e Restrições de Interface Externa (RIEX)

_Identificar e descrever as interfaces com outros softwares/sistemas que o software deverá prover. Por exemplo, um software comercial deve gerar informações para o Sistema de Arrecadação da Secretaria da Fazenda Estadual. O formato dessas informações e o protocolo de envio são definidos pela própria secretaria, e atender essas definições é um requisito do software._
_Exemplo:_

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| [_RIEXx_] 	| [_Descrição do requisito RIEXx_] | [_CSUy, CSUm ..._]	|

### 3.4 Requisitos e Restrições de Plataforma de Hardware (RPHW)

_Identificar e descrever requisitos e restrições relacionadas com a plataforma de hardware que será utilizada pelo software:_
_Exemplo:_

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| [_RPHWx_]	| [_Descrição do requisito RPHWx_] | [_CSUy, CSUm ..._] |


### 3.5 Requisitos e Restrições de Plataforma de Software (RPSW)

_Se o software tiver que ser executado em plataformas de software específicas, essas plataformas de software deverão ser definidas:_
_1. Sistema Operacional: identificar e descrever o sistema operacional em que o software deverá ser executado;_
_2. Softwares Básicos: identificar SGBD, linguagem de programação, ferramentas CASE e outros._
_Se houver mais de uma plataforma de software, deve-se especificar qual a plataforma principal e em que situações as outras plataformas podem ser utilizadas._
_Exemplo:_

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| [_RPSWx_] | [_Descrição do requisito RSPWx_] | [_CSUy, CSUm ..._] |

### 3.6 Requisitos e Restrições de Desempenho (RDES)

_Identificar e descrever os requisitos e restrições de desempenho do software._
_Exemplo:_

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| [_RDESx_] | [_Descrição do requisito RDESx_] | [_CSUy, CSUm ..._] |

### 3.7 Requisitos e restrições de disponibilidade (RDIS).

_Especificar os requisitos de disponibilidade necessários para o software de uma forma global:_
_1. Período de disponibilidade: horário comercial, 24 horas por dia, etc._
_2. Período máximo para recuperação do software em caso de falha._
_Devem ser definidos os tipos de falha e a tolerância aceitável para cada tipo de falha. Os tipos de falha podem ser definidos em função dos requisitos funcionais e de dados, mas não se restringem a estes. Por exemplo: a função “Registrar Venda” deve ter um tempo para recuperação de falha de no máximo uma hora (o que significa que esta função não poderá ficar mais do que uma hora indisponível para o usuário em nenhuma circunstância)._ 
_Exemplo:_

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| [_RDISx_]	| [_Descrição do requisito RDISx_] | [_CSUy, CSUm ..._] |

### 3.8 Requisitos e Restrições de Segurança (RSEG)

_Especificar os requisitos de segurança necessários para controle de acesso ao software. Definir a necessidade, por exemplo, de:_
_1. Verificação de senha;_
_2. Criptografia de dados;_
_3. Registro das operações efetuadas;_
_4. Habilitação de funções por perfil de usuário;_
_5. Acesso seletivo aos dados e funções._
_Exemplo:_

| Ref.  	|              Descrição                      	| Caso de Uso 	|
|-------	|------------------------------------------	|-------------	|
| [_RSEGx_] | [_Descrição do requisito RSEGx_] | [_CSUy, CSUm ..._] |

### 3.9 Requisitos e Restrições de Manutenibilidade (RMAN)

_Especificar os requisitos que visam facilitar a manutenção posterior do software, tais como:_
_1. Requisitos de reutilização (exemplo: uso de implementação orientada a objetos; bibliotecas de classes e padrões de projeto);_
_2. Requisitos de modularização (exemplo: valores para métricas de acoplamento entre módulos; máximo de pontos de função por módulo);_
_3. Requisitos de configuração (exemplo: regras para controle de versões);_
_4. Requisitos de documentação (exemplo: documentação de programa)_
_Exemplo:_

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| [_RMANx_]	| [_Descrição do requisito RMANx_] | [_CSUy, CSUm ..._] |

### 3.10 Requisitos e Restrições de Documentação (RDOC)

_Especificar os requisitos de documentação do produto de software que será desenvolvido._
_Exemplo:_

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| [_RDOCx_] | [_Descrição do requisito RDOCx_] | [_CSUy, CSUm ..._] |

## 4. Casos de Uso e Requisitos Funcionais
---------------------------------

### 4.1 Diagramas de Caso de Uso

[_Este espaço deverá mostrar os casos de uso do sistema através de diagrama de caso de uso. Podem ser usados mais de um diagrama para facilitar a visualização e compreensão do leitor caso o número de casos de uso seja considerado grande._]

### 4.2 Descrição de Casos de Uso

_Cada caso de uso deve receber um identificador único, ser categorizado em primário, obrigatório ou opcional e ser descrito em um formato essencial resumido conforme explicado no capítulo 6 da terceira edição do livro “Utilizando UML e Padrões” de Craig Larman._ _Veja o exemplo a seguir:_

[_CSU1- Processar Venda_]
[_Atores: Vendedor e Cliente_]
[_Categoria: Primário_]
[_Descrição:_] 
[_Este caso de uso acontece quando um cliente chega a um ponto de venda com itens de produtos que deseja adquirir. O caixa usa o sistema para registrar cada item comprado. O sistema vai apresentando um total parcial e uma linha de detalhes à medida que registra cada item. O cliente fornece ao caixa os dados sobre o pagamento que são então validados e registrados pelo sistema. O sistema atualiza o estoque e emite um recibo que é entregue pelo caixa ao cliente. O cliente sai com os itens comprados._]

_Requisitos Funcionais:_

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| [_RFUN 1.1_] | [_Obter e exibir a descrição e valor unitário de um produto a partir de seu código identificador_] | [_Evidente_] | [_Alta_] |
| [_RFUN 1.2_] | [_Calcular e exibir o total parcial da venda a cada item informado_] | [_Evidente_] | [_Alta_] |
| [_RFUN 1.3_] | [_Registrar o valor recebido para venda realizada_] | [_Evidente_] | [_Alta_] |
| [_RFUN 1.4_] | [_Calcular e exibir o troco para o pagamento em dinheiro_] | [_Evidente_] | [_Alta_] |
| [_RFUN 1.5_] | [_Emitir recibo de pagamento_] | [_Evidente_] | [_Alta_] |
| [_RFUN 1.6_] | [_Atualizar o estoque do produto vendido_] | [_Evidente_] | [_Alta_] |
| [_RFUN 1.7_] | [_Registrar dados da venda realizada (data, hora, PDV, produtos vendidos...)_] | [_Evidente_] | [_Alta_]




## 5. Requisitos Futuros (RFUT)
---------------------------------

_Descrever os requisitos que poderão ser especificados em uma nova versão do produto._

| Ref.|   Descrição | Caso de Uso |
|-------|------------|---------------|
| [_RFUT1_] | [_Em um futuro próximo o software de atendimento de clientes deverá ser integrado com o software do sistema de faturamento para que o atendente possa identificar o perfil de negócios do cliente_] | [_CSUx_] |


## 6. Referências cruzadas complementares 
---------------------------------------------

_Nesta seção são colocadas algumas referências cruzadas que podem ajudar o rastreamento futuro dos requisitos. Estes mapeamentos podem ser feitos em forma de matrizes de rastreabilidade como mostram os exemplos a seguir:_

|Requisitos Funcionais | Requisitos Não-Funcionais|
|---------------------|--------------------------|
|[_Colocar identificação do requisito funcional_] | [_Colocar a identificação do requisito não funcional vinculado_] |

|Requisitos Funcionais | Origem do Requisito |
|---------------------|--------------------------|
| [_Colocar identificação dos requisitos funcionais_] | [_Colocar a origem do requisito. Pode ser uma entrevista, um questionário, ou outra técnica qualquer de elicitação de requisito aplicada._] |

|Requisitos Não-Funcionais | Origem do Requisito |
|---------------------|--------------------------|
| [_Colocar identificação dos requisitos não-funcionais_] | [_Colocar a origem do requisito. Pode ser uma entrevista, um questionário, ou outra técnica qualquer de elicitação de requisito aplicada._] |

| Casos de Uso | Origem do Caso de Uso |
|---------------------|--------------------------|
| [_Colocar a identificação do requisito funcional_] | 
[_Colocar a origem do caso de uso. Pode ser uma entrevista, um questionário, ou outra técnica  qualquer de elicitação de requisito aplicada._] |

## 7. Aprovação Formal 
---------------------------------------------

[_O EOR deve ser datado e assinado de acordo com a definição contida no MPD. O documento aprovado se torna uma baseline do projeto que passa a ser controlada pela Gerência de Configuração de Software._]

## 8. Bibliografia
---------------------------------------------

_Detalhar todas as fontes de informação citadas no documento ou usadas de alguma forma para sua elaboração, incluindo título, autor, data, fonte de obtenção, órgão responsável pela publicação e qualquer outra informação que possa facilitar a localização e obtenção dessas fontes pelo leitor. Nesta seção cada fonte citada deve ser associada a um número identificador. Junto de cada citação deve ser colocada também uma explicação sucinta de como a fonte foi usada na elaboração do documento._
_Referenciar todas as fontes de informações citadas no EOR, explicando o motivo de sua citação. Devem ser incluídos, por exemplo:_

* [_Normas e Padrões utilizados;_]
* [_Livros e artigos (autores, título, editora, páginas, volume, data e local da publicação, ISBN/ISSN, etc);_]
* [_Manuais de outros Produtos._]

_Por exemplo, vamos supor que para elaborar o documento XXX-EOR-001 foram usadas as orientações contidas no Meta-Modelo de Especificação de Objetivos e Requisitos (EOR). Então, nesta seção deveria aparecer o seguinte texto:_
[_[1] Ronaldo Lopes de Oliveira, EOR – Modelo de Documento de Especificação de Objetivos e Requisitos de Software, Versão 2.0, abril de 2014._]
[_Meta-Modelo usado como guia para definição do formato e conteúdo deste documento._]



## 9. Anexos 
---------------------------------------------
[_Anexar ao EOR documentos considerados importantes para sua compreensão. Por exemplo, documentos e leis usadas na especificação dos requisitos podem ser colocados nos anexos para facilitar o acesso do leitor às fontes dos requisitos do software. Cada anexo deverá receber uma folha de rosto indicando seu conteúdo._]
