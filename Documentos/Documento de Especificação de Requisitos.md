
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
    * 3.1 [Requisitos de Facilidade de Uso (RFDU)](#31-requisitos-de-facilidade-de-uso-rfdu)
    * 3.2 [Requisitos de Desempenho (RD)](#32-requisitos-de-desempenho-rd)
    * 3.3 [Requisitos de Eficiência (RE)](#33-requisitos-de-eficiência-re)
    * 3.4 [Requisitos de Confiabilidade (RC)](#34-requisitos-de-confiabilidade-rc)	
    * 3.5 [Requisitos de Portabilidade (RP)](#35-requisitos-de-portabilidade-rp)	
    * 3.6 [Requisitos de Entrega (RENT)](#36-requisitos-de-entrega-rent)	
    * 3.7 [Requisitos de Implementação (RI)](#37-requisitos-de-implementação-ri)	
    * 3.8 [Requisitos de Padrões (RPAD)](#38-requisitos-de-padrões-rpad)	
    * 3.9 [Requisitos de Interoperabilidade (RINT)](#39-requisitos-de-interoperabilidade-rint)	
    * 3.10 [Requisitos Éticos (RET)](#310-requisitos-éticos-ret)
    * 3.11 [Requisitos de Privacidade (RPRIV)](#311-requisitos-de-privacidade-rpriv)
    * 3.12 [Requisitos de Segurança (RSEG)](#312-requisitos-de-segurança-rseg)
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

### 3.1 Requisitos de Facilidade de Uso (RFDU)

[RNF001] A ajuda online deve estar acessível de qualquer página do sistema.    
[RNF003] Não deve ser preciso mais que 3 cliques para executar o requisito funcional [RF010].

### 3.2	Requisitos e Restrições de Desempenho (RD)

[RNF003] A consulta ao histórico de vacina não deve demorar mais que 20 segundos.

### 3.3 Requisitos de Eficiência (RE)

[RNF004] O tamanho do aplicativo não deve passar dos 20MB e não ocupar mais de 50MB quando estiver em execução.

### 3.4 Requisitos de Confiabilidade (RC)

[RNF005] Falhas nas consultas ao histórico não devem ocorrer mais de uma vez por dia.

### 3.5 Requisitos de Portabilidade (RP)

[RNF006] O sistema deve funcionar em dispositivos móveis como IOS e Android. 
[RNF007] O sistema deve funcionar em navegadores como Mozilla Firefox e Google Chrome.

### 3.6 Requisitos de Entrega (RENT)

[RNF008] O Sistema irá gerar um arquivo .pdf de todas as vacinas tomadas e irá o enviar para o e-mail do usuário. Logo após alguma campanha ser finalizada.

### 3.7 Requisitos de Implementação (RI).

[RNF009] A apresentação do histórico de vacinas deve ser mostrada em um arquivo no formato PDF.
[RNF010] A apresentação do histórico de vacinas deve ser mostrada em um arquivo no formato PDF.
[RNF011] Para o usuário que já fez o cadastro usando o RF-001.01 ou RF-001.02 não poderá fazer o Cadastro usando o RF-001-02.
[RNF012] Referente ao RF-010. Caso uma campanha tenha nível nacional apenas o Administrador Geral poderá ter o poder de criá-la.

### 3.8 Requisitos de Padrões (RPAD)

[RNF013] O sistema deve seguir o padrão do Calendário Nacional de Vacina que pode ser encontrado aqui: 
http://portalsaude.saude.gov.br/index.php/o-ministerio/principal/leia-mais-o-ministerio/197-secretaria-svs/13600-calendario-nacional-de-vacinacao

### 3.9 Requisitos de Interoperabilidade (RINT)

[RNF014] O sistema deve se comunicar com o site da Receita Federal para confirmação de CPF.

### 3.10 Requisitos Éticos (RET)

[RNF015] De acordo com o Ministério da Saúde nenhum dado do usuário poderá ser divulgado a terceiros, salvo perante requerimento da justiça.

### 3.11 Requisitos de Privacidade (RPRIV)

[RNF016] No histórico de vacina do paciente o sistema não deve revelar o nome do funcionário que aplicou a vacina em usuário

### 3.12 Requisitos de Segurança (RSEG)

[RNF017] O sistema deve criptografar todas as informações trocadas nos RFs: [RF001], [RF002], [RF003], [RF004], [RF005], [RF006], [RF007], [RF008], [RF009].

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

[RF001] Cadastro de Pacientes 
O sistema deve permitir que o registrador cadastre novos pacientes maiores de 18 anos e também deve permitir ao paciente se auto cadastrar.
Para o cadastro as seguintes informações são obrigatoriamente necessárias: Nome completo do paciente, data de nascimento e CPF.
Informações opcionais: Telefone(s) para contato, e-mail, código postal, endereço.
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF002] Cadastro de Dependentes 
O sistema deve permitir que o registrador e um paciente maior de 18 anos cadastrem pacientes menores de 18 anos como dependentes. 
Para o cadastro de dependentes as seguintes informações são obrigatoriamente necessárias: Nome completo do dependente, data de nascimento do dependente e CPF do responsável. No final do cadastro os dados do dependente são linkados ao do paciente responsável cadastrado [RF001]. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF003] Efetivação de cadastro de paciente 
O sistema deve gerar uma senha única para o paciente cadastrado [RF001]. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF004] Editar Cadastro de Paciente 
O sistema deve permitir ao paciente editar seus dados com exceção do CPF. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF005] Cadastro de Vacinas 
O sistema deve permitir que o administrador geral e o administrador de secretaria cadastrarem novas vacinas.
As seguintes informações são obrigatoriamente necessárias: Identificador único da vacina (fornecido pelo ministério da saúde), nome da vacina, grupo alvo e faixa etária da vacina (de acordo com o calendário nacional de vacinação).
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF006] Cadastro de Funcionários 
O sistema deve permitir o cadastro de administradores gerais, administradores de secretaria, registradores e agentes de saúde.
Para cadastrar funcionários as seguintes informações são obrigatoriamente necessárias: Nome Completo, CPF, Data de Nascimento.
Informações Opcionais: Telefone para contato, e-mail, código postal e endereço.
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF007] Efetivação de Cadastro de funcionário  
O sistema deve gerar uma senha única para o funcionário cadastrado [RF005]. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF008] Registrar Vacinação 
O sistema deve permitir ao agente de saúde registrar no sistema a vacina tomada pelo paciente. 
Para registrar a vacina tais informações são necessárias: CPF cadastrado do paciente [RF001], CPF cadastrado do agente de saúde, identificador da vacina cadastrada [RF004], senha do agente de saúde [RF006]. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF009] Cadastrar Campanha 
O sistema deve permitir que o Administrador Geral e o Agente de Saúde cadastrem uma campanha. 
Para o cadastro de campanha as seguintes informações são obrigatoriamente necessárias: Nome da campanha, Data de inicio e término da campanha, identificador único da vacina, nome da vacina [RF004], grupo alvo e faixa etária [RF004], região onde a campanha será realizada. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 
 
[RF010] Histórico de Vacinas 
O sistema de permitir a visualização do histórico de vacinas tomadas pelo paciente. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF011] Editar Campanha  
O sistema deve permitir que o administrador geral e o agente de saúde editem uma campanha. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF012] Deletar Campanha  
O sistema deve permitir que o administrador geral delete uma campanha. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF013] Deletar Vacina 
O sistema deve permitir que o administrador geral delete uma vacina. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 

[RF014] Alerta de Vacina 
O sistema deve emitir um alerta de vacina para o paciente. 
Prioridade: Alta 
Fonte Responsável: Desenvolvedor 



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
