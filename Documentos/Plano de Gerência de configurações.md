
Processo de software 2015, Gerência de Configuração (GCO).
========================

Índice Analítico
------------------

* 1. [Introdução] (#1-introdução)
    * 1.1 [Finalidade] (#1.1-finalidade)
    * 1.2 [Escopo] (#1.2-escopo)
    * 1.3 [Artefatos Esperados] (#1.3-artefatos-esperados)
    * 1.4 [Detalhamento dos Artefatos] (#1.4-detalhamento-dos-artefatos)
    * 1.3 [Definição de Siglas e Nomenclaturas] (#1.3-definição-de-siglas-e-nomenclaturas)
* 2. [Gerenciamento de Configuração de Software] (#2-gerenciamento-de-configuração-de-software)
    * 2.1 [Organização e Responsabilidades] (#2.1-organização-e-responsabilidades)
    * 2.2 [Ferramentas, Ambiente e Infra estrutura] (#2.2-ferramentas-ambiente-e-infra-estrutura)
* 3. [Programa de Gerenciamento de Configuração] (#3-programa-de-gerenciamento-de-configuração)
    * 3.1 [Métodos de Identificação] (#3.1-métodos-de-identificação)
    * 3.2 [Processamento e Aprovação de Solicitações de Mudança] (#3.2-processamento-e-aprovação-de-solicitações-de-mudança)
    * 3.3 [Processo de Armazenamento] (#3.3-processo-de-armazenamento)
* 4. [Marcos e Baselines] (#4-marcos-e-baselines)

 
1. Introdução 
-----------------

## 1.1 Finalidade 
Este documento tem como finalidade demonstrar como será realizado o Gerenciamento das configurações para o devido software. 

## 1.2 Escopo 
Este documento vai abordar a Gerência de Configuração. Seu objetivo será explicar como será feita a nomenclatura e a organização dos objetos que compõem o projeto, bem como as formas de armazenamento e acessibilidade.

## 1.3 Artefatos Esperados
Durante a etapa de processo teremos o plano de gerencia de configuração, enquanto que durante a fase de projeto teremos uma nota de release para cada baseline.

## 1.4 Detalhamento dos Artefatos
[_Detalhar os artefatos definidos acima_]

## 1.5 Definição de Siglas e Nomenclaturas 
Siglas e Nomenclaturas | Definição
--------------- | --------------------
GCO | Gerencia de configuração
RF | Requisito funcional
RNF | Requisito não funcional
RN | Regra de negócio
CT | Casos de teste
SD | Software design

2. Gerenciamento de Configuração de Software
----------------------------------------

## 2.1 Organização e Responsabilidades 
A equipe de gerência de configuração será composta por:

Nome | Papel
--------------- | --------------------
[nome] | [papel definido]

## 2.2 Ferramentas, Ambiente e Infraestrutura 
Para um bom Gerenciamento das configurações é necessário utilizar ferramentas que ajudam em todos os seus passos. Sendo elas: 

**Github** – Para o controle de versões online. 
**Git** – Para o controle de versões offline.

Por ser um projeto com cunho educacional a infraestrutura será os próprios computadores pessoais dos integrantes do grupo, tendo acesso a internet e o git instalado, além dos computadores da universidade.
O diretório principal do projeto será composto da seguinte maneira:

Diretório | Finalidade
--------------- | --------------------
Anexos | Armazenar imagens, links, planilhas e slides para uso do projeto.
Documentos | Armazenar quaisquér documentos gerados conforme os planos definidos, incluindo os mesmos planos.
Templates | Armazenar os templates dos documentos esperados conforme os planos definidos.

3. Programa de Gerenciamento de configurações 
-----------------------------------------------

## 3.1 Métodos de Identificação 
Parte do projeto abordado | Método de Identificação
-------------------------- | ----------------------
Requisitos | Os Requisitos serão devidos da seguinte forma. Primeiramente por padrão será colocado as siglas RF, RFN e RN e na frente desses valores terá um número respectivos à ordenação dos requisitos. 
Software Design | O software design será abreviado para SD e suas alterações serão colocadas como números. 
Código  |Quando o código sofrer uma grande alteração que comprometa todo o sistema será colocada no primeiro espaço a esqueda. Ex: Y.0  Quando algum subsistema precisar ser alterado o software colocara no segundo número. Ex: 1.X  Caso seja alguma alteração ou melhoria será colocado no terceiro. Ex: 1.1.Z. Bugs serão resolvidos na quarta linha. Ex.: 1.1.1.W  Sendo a ordenação final a seguinte Y.X.Z.W.
Testes |  Os casos de testes será usado em sigla CT seguido de algum número que represente a sua posição.

## 3.2 Processamento e Aprovação da solicitação de mudanças 
Quando for necessário uma mudança tanto o responsável pelas mudanças quanto o Gerente terão de ser avisados do caso e terão de aprovar a mudança. 

## 3.3 Processamento do Armazenamento 
O armazenamento será realizado todo no Github para que possa ter uma avaliação online. 

## 4. Marcos e Baselines
As Baselines serão as interações do ciclo de vida em V conforme definidos no plano de projeto.
Em cada baseline, deverá ser gerada uma nota de release das mudanças realizadas nos artefatos com base no seguinte template [template].
