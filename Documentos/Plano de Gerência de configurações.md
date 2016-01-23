Gerência de Configuração (GCO).
========================

Índice Analítico
------------------

* 1. [Introdução] (#1-introdução)
  * 1.1 [Finalidade] (#1.1-finalidade)
  * 1.2 [Escopo] (#1.2-escopo)
  * 1.3 [Definição de Siglas e Nomenclaturas] (#1.3-definição-de-siglas-e-nomenclaturas)
* 2. [Gerenciamento de Configuração de Software] (#2-gerenciamento-de-configuração-de-software)
  * 2.1 [Organização e Responsabilidades] (#2.1-organização-e-responsabilidades)
  * 2.2 [Ferramentas, Ambiente e Infra estrutura] (#2.2-ferramentas-ambiente-e-infra-estrutura)
* 3. [Programa de Gerenciamento de Configuração] (#3-programa-de-gerenciamento-de-configuração)
  * 3.1 [Métodos de Identificação] (#3.1-métodos-de-identificação)
  * 3.2 [Baselines do Projeto] (#3.2-baselines-do-projeto)
  * 3.3 [Processamento e Aprovação de Solicitações de Mudança] (#3.3-processamento-e-aprovação-de-solicitações-de-mudança)
  * 3.4 [Processo de Armazenamento] (#3.4-processo-de-armazenamento)
* 4. [Marcos] (#4-marcos)

 
1. Introdução 
-----------------
## 1.1 Finalidade 
Este documento tem como finalidade demonstrar como será realizado o Gerenciamento das configurações para o devido software. 
## 1.2 Escopo 
Este documento vai abordar a Gerência de Configuração. Seu objetivo será explicar como será feita a nomenclatura e a organização dos objetos que compõem o projeto. Envolvendo os requisitos, o software design, o código e os testes. 
## 1.3 Definição de Siglas e Nomenclaturas 
Siglas e Nomenclaturas | Definição
--------------- | --------------------
RF |  Requisito Funcional 
RFN | Requisito Não Funcional 
RN | Regra de Negócio 

2. Gerenciamento de Configuração de Software
----------------------------------------
## 2.1 Organização e Responsabilidades 
A organização do gerenciamento de configuração será atribuído ao Gerente de configuração e sua equipe. Onde uma pessoa ficará encarregada do controle das versões, outra com o gerenciamento das mudanças e uma para a integração contínua. Logo o Gerente terá o trabalho de monitorar e aprovar ou reprovar a ação de sua equipe. 
## 2.2 Ferramentas, Ambiente e Infraestrutura 
Para um bom Gerenciamento das configurações é necessário utilizar ferramentas que ajudam em todos os seus passos. Sendo elas: 

Git – Para o controle de versões. 

Redmine - Para o controle das mudanças. 

Ant – Para a integração contínua.

Além disso teremos de ter um ambiente para ser realizado este trabalho. Como a equipe é pequena e se trata de um trabalho para uma matéria do curso. Então o ambiente será a sala de aula, juntamente com a casa dos integrantes do grupo. O material para realizar o projeto será notebooks ou computadores pessoais, além das máquinas disponibilzadas durante a aula. 
3. Programa de Gerenciamento de configurações 
-----------------------------------------------
## 3.1 Métodos de Identificação 
Parte do projeto abordado | Método de Identificação
-------------------------- | ----------------------
Requisitos | Os Requisitos serão devidos da seguinte forma. Primeiramente por padrão será colocado as siglas RF, RFN e RN e na frente desses valores terá um número respectivos à ordenação dos requisitos. 
Software Design | O software design será abreviado para SD e suas alterações serão colocadas como números. 
Código  |Quando o código sofrer uma grande alteração que comprometa todo o sistema será colocada no primeiro espaço a esqueda. Ex: Y.0  Quando algum subsistema precisar ser alterado o software colocara no segundo número. Ex: 1.X  Caso seja alguma alteração ou melhoria será colocado no terceiro. Ex: 1.1.Z. Bugs serão resolvidos na quarta linha. Ex.: 1.1.1.W  Sendo a ordenação final a seguinte Y.X.Z.W.
Testes |  Os casos de testes será usado em sigla CT seguido de algum número que represente a sua posição.

## 3.2 Baselines do projeto 
As Baselines do projeto somente poderão ser alteradas com autorização do Gerente de Configurações. Nela é onde trará todo o projeto primordial que já foi aprovados. Ele ficará no Github como o resto do projeto. 
## 3.3 Processamento e Aprovação da solicitação de mudanças 
Quando for necessário uma mudança tanto o responsável pelas mudanças quanto o Gerente terão de ser avisados do caso e terão de aprovar a mudança. 
## 3.4 Processamento do Armazenamento 
O armazenamento será realizado todo no Github para que possa ter uma avaliação online. 
## 4. Marcos 
[...] 
