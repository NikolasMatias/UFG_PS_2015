
Processo de software 2015, Plano de Projeto
=================================

Índice Analítico
----------------

* 1. [Escopo de Projeto](#1-escopo-de-projeto)
    * 1.1. [Objetivos](#11-objetivos)
    * 1.2. [Estratégia Organizacional](#12-estratégia-organizacional)
    * 1.3. [Artefatos Esperados](#13-artefatos-esperados)
    * 1.4. [Detalhamento dos Artefatos](#14-detalhamento-dos-artefatos)
    * 1.5. [Estudo de viabilidade](#15-estudo-de-viabilidade)
    * 1.6. [Detalhamento do Ciclo de Vida](#16-detalhamento-do-ciclo-de-vida)
    * 1.7. [Estimativa de esforço](#17-estimativa-de-esforço)
* 2. [Custo do Projeto](#2-custo-do-projeto)
    * 2.1. [Cronograma](#21-cronograma)
    * 2.2. [Recursos](#22-recursos)
    * 2.3. [Pontos de controle](#23-pontos-de-controle)
* 3. [Gerenciamento de Riscos](#3-gerenciamento-de-riscos)
    * 3.1. [Métricas de Risco](#31-métricas-de-risco)
    * 3.2. [Tipos de Riscos](#32-tipos-de-riscos)
* 4. [Recursos Humanos](#4-recursos-humanos)
    * 4.1. [Responsábilidades](#41-responsabilidades)
    * 4.2. [Riscos em RH](#42-riscos-em-rh)
* 5. [Detalhamento de Projeto](#5-detalhamento-de-projeto)
    * 5.1. [Estrutura de Projeto](#51-estrutura-de-projeto)
    * 5.2. [Armazenamento de Artefatos](#52-armazenamento-de-artefatos)
    * 5.3. [Metricas de Acessibilidade](#53-metricas-de-acessibilidade)
* 6. [Monitoramento de riscos](#6-monitoramento-de-riscos)
* 7. [Manutenção](#7-manutenção)
* 8. [Aprovação formal](#8-aprovação-formal)

1. Escopo de Projeto
---------------------

### 1.1 Objetivos
Este é um projeto com o propósito unicamente acadêmico, sua finalidade é disceminar o conhecimento nas áreas do MPS.BR, nos níveis G e F (apenas qualidade), entre os integrantes da equipe.

O software em que este projeto será aplicado é o **MR. Imune**, um programa multi-plataforma que apresenta o calendário de vacinas disponibilizadas pelo ministério da Saúde e o histórico das vacinas que o usuário já tomou.

O software possuirá as seguintes funcionalidades conforme o diagrama de caso de uso abaixo:

![Diagrama de caso de uso](https://raw.githubusercontent.com/PedroDrim/UFG_PS_2015/master/Anexos/Mr.%20Imune.v2.png)

### 1.2 Estratégia Organizacional
Este plano foi definido com o intuíto acadêmido de simular um projeto em uma empresa. O ciclo de vida utilizado como base para os futuros projetos que utilizarem deste plano é o __ciclo de vida em V__, devido a facilidade em encontrar erros durante as primeiras fases, evitando assim, maior custo no futuro conforme a representação abaixo.

![Ciclo de vida V](https://raw.githubusercontent.com/PedroDrim/UFG_PS_2015/master/Anexos/Ciclo%20de%20vida%20V.png)

Após cada etapa será realizado uma análise da qualidade dos produtos gerados de forma a encontrar não-conformidades á serem corrigidas.

### 1.3 Artefatos Esperados
No desenvolvimento de projetos pela organização deverá haver os artefatos a cada fase de desenvolvimento do produto. Seguindo o ciclo de vida do projeto, deverão ser apresentados ao longo do projeto documentos acerca do desenvolvimento de cada fase. Os resultados de cada fase deverão ser documentados para controle da organização, facilidade em manutenção posterior, organização no desenvolvimento, conforme o representado pela EAP abaixo.

![EAP](https://raw.githubusercontent.com/PedroDrim/UFG_PS_2015/master/Anexos/EAP.png)

### 1.4 Detalhamento dos Artefatos
O grau de importância de um artefato é dado pelo produto entre o __grau da atividade executada__ e __grau da fase do ciclo de vida__ em que é gerada.

* Tabela para classificação com base no grau da atividade executada:

 Grau da atividade | Nome | Valor 
------------------|------|------
Execução / Procedimentos | Baixo | 1
Planejamento | Alto | 2

* Tabela para classificação com base no grau da fase do ciclo de vida:

Etapa | Ciclo de vida | Nome | Valor
------|--------------|------|------
1     | Levantamento e detalhamento de requisitos | Alto | 4
2     | Definição de arquitetura | Medio | 3
3     | Detalhamento baixo nível | Medio | 3
4     | Construção | Baixo | 2

* Tabela para classificação de grau de importância (resultado):

 Métrica (produto entre as métricas anteriores) | Nome
------------------|------
Apenas __8__ | Alto
Entre __4 e 6__ | Médio
Entre __2 e 3__ | Baixo   

Os artefatos gerados em cada etapa do ciclo de vida são definidos abaixo:

Nome do artefato | Nome da atividade | Funcionalidade | Grau de importância
-----------------|-------------------|----------------|---------------------
**Plano de projeto** | planejamento da gerência de projeto | Este artefato é responsável por definir cronogramas e custos esperados durante o projeto, bem como definir o ciclo de vida utilizado e especificar quais artefatos serão esperados em cada etapa. | 8
**Relatórios de riscos** | procedimentos da gerência de projeto | responsável por armazenar quaisquér ocorrencia de riscos esperados, bem como as técnicas utilizadas para contornar a situação, quais as áreas afetadas por esse risco e quais os seus responsáveis. | 4
**Relatórios de manutenção** | procedimentos da gerência de projeto | responsável por armazenar quaisquér mudanças nos artefatos gerados (correções de não-conformidade, adequações de textos, correções de links), bem como as áreas afetadas por essa modificação e quais os seus responsáveis. | 4
**Processo de garantia de qualidade** | planejamento da garantia de qualidade | responsável por definir as métricas e métodos utilizados para avaliação da qualidade dos artefatos selecionados. | 8
**Checklist de garantia de qualidade** | procedimento da garantia de qualidade | responsável por verificar e validar os artefatos selecionados, assim como especificar quais não-conformidades foram encontradas. | 4
**Plano de gerência de configuração** | planejamento da gerencia de configuração | responsável por definir como será feita a nomenclatura e a organização dos objetos que compõem o projeto, bem como as formas de armazenamento e acessibilidade. | 8
**Notas de release** | execução da gerência de configuração | responsável por compilar as modificações ocorridas no software de um marco para outro de forma a explicar para o usuário, de forma simples, quais as modificações que ocorreram durante o antamento do projeto. | 4
**Código-fonte** | execução da construção | Este artefato deverá conter o código do produto, de forma que fique de acordo com o definido pela equipe de requisitos. | 2

### 1.5 Estudo de viabilidade
Antes da execução do projeto, deverá ser realizada um estudo de viabilidade de forma a verificar a aceitação do projeto no com base na necessidade e recursos da empresa.

Devido ao ambito acadêmico, este projeto foi considerado viável, entretanto não ocorrerão as etapas de levantamento arquitetural e codificação.

Um estudo de viabilidade também deverá ocorrer para a [manutenção](#7-manutenção) de artefatos gerados, conforme as métricas definidas para [esforço](#17-estimativa-de-esforco).

### 1.6 Detalhamento do Ciclo de Vida
O ciclo de vida definido para este plano é o __ciclo de vida em V__ a sua estruturação no projeto será realizada da seguinte maneira:

Etapa | Ciclo de vida
------|--------------
1     | Levantamento e detalhamento de requisitos
2     | Definição de arquitetura
3     | Detalhamento baixo nível
4     | Construção

* __Etapa 1:__ Será realizada o levantamento e análise dos requisitos do projeto bem como técnicas de verificação e validação destes requisitos.
   * __Artefatos gerados na Etapa 1:__ Documento de requisitos, além das notas de release do final da etapa 1.

* __Etapa 2:__ Será realizada a transição dos requisitos para a arquitetura bem como técnicas de verificação e validação para essa nova arquitetura.
   * __Artefatos gerados na Etapa 2:__ Artefatos gerados na etapa 1 além dos diagramas de componentes e classe (não necessário para este projeto) e das notas de release do final da etapa 2.

* __Etapa 3:__ Será realizada a construção do projeto bem como os testes que serão aplicados de forma a validar e verificar o produto.
   * __Artefatos gerados na Etapa 3:__ Artefatos gerados nas etapas 1 e 2 além dos diagramas de sequência e dos primeiros protótipos (não necessário para este projeto) e das notas de release do final da etapa 3.
   
* __Etapa 4:__ Por fim o produto-final será implementado.
   * __Artefatos gerados na Etapa 4:__ Artefatos gerados nas etapas 1,2 e 3 além do código-fonte completo do projeto (não necessário para este projeto) e das notas de release do final da etapa 4. 

* __Durante a execução:__ Esta etapa ocorrerá simultaneamente com as outras etapas.
   * __Artefatos gerados durante a execução:__ Checklist de garantia de qualidade, relatórios de riscos e relatórios de manutenção.

### 1.7 Estimativa de esforço
O esforço gasto em uma atividade é definida com base no __tempo__ gasto em média, o __custo__ gasto para equipamentos e preparo; e com o tamanho e tipo do __escopo__ da atividade a ser realizada. O calculo para definir o esforço é realizado conforme a tabela abaixo:

* Tabela para classificação com base no tempo:

 Métrica temporal | Nome | Valor 
------------------|------|------
Menor ou igual á __1 dia__ | Baixo | 3
Entre __2 e 4 dias__ | Médio | 2
Maior que __4 dias__ | Alto | 1

* Tabela para classificação com base no custo:

 Métrica monetária | Nome | Valor 
------------------|------|------
__Sem custo__ | Baixo | 1
Menor que __100 Reais__ | Médio | 2
Entre __100 e 1000 Reais__ | Alto | 3
Maior que __1000 Reais__ | Muito Alto | 4

* Tabela para classificação com base no escopo:

 Métrica dimensional | Nome | Valor 
------------------|------|------
__Manutenção de Artefato__ | Alto | 3
__Novo Artefato__ | Médio | 2
__Refatoração de Artefato__ | Baixo | 1

O __esforço__ é calculado pelo produto entre as métricas __tempo__,__custo__ e __escopo__, sendo classificada conforme a tabela abaixo:

* Tabela para classificação de esforço:

 Métrica (produto entre as métricas anteriores) | Nome
------------------|------
Entre __25 e 36__ | Alto
Entre __13 e 24__ | Médio
Entre __1 e 12__ | Baixo 

2. Custo do Projeto
--------------------

### 2.1 Cronograma
O cronograma será definido com base no ciclo de vida utilizado no projeto e possuirá um tempo total de 6 meses, as atividades serão divididas de forma a cumprir esse tempo estipulado conforme a tabela abaixo:

Etapa | Tempo estipulado
------|------------------
Levantamento / Detalhamento de requisitos | 1 Mês 
Definição / Detalhamento de arquitetura | 1 Mês
Construção | 4 Meses

### 2.2 Recursos
O Mr. Imune é um projeto acadêmico que não possuirá custos monetários, devido ao uso de ferramentas open source e por ser um projeto puramente de cunho acadêmico.

Neste software serão utilizadas as seguintes ferramentas:

Nome | Finalidade
-----|-----------
[Git](https://git-scm.com/downloads) | Controle de versão pelo desktop.
[Github](https://github.com/) | Controle de versão pelo navegador.
[Draw.io](https://www.draw.io/) | Desenho dos diagramas, Eap e macrofluxos.
[Visual Studio Code](https://code.visualstudio.com/) / [Atom](https://atom.io/) / [Sublime text](http://www.sublimetext.com/3) | Edição de códigos
[Skype](http://www.skype.com/pt-br/download-skype/skype-for-computer/) / [Hangout](https://plus.google.com/u/0/) | Reuniões.
[Android Studio](http://developer.android.com/intl/pt-br/sdk/index.html) / [Eclipse](https://eclipse.org/downloads/) | Ide's
[Trello](https://trello.com/) | Ferramenta para definição de atividades do projeto

Nesse software os computadores utilizados deverão possuir as sguintes configurações:

* Sistema operacional: Windows acima ou igual ao 7, Linux mint acima ou igual ao 15.
* Acesso a internet.
* Minimo 2gb RAM.

### 2.3 Pontos de controle

Levando em conta o ciclo de vida em uso, foram definidos como pontos de controle o período de transição entre as fases do ciclo de vida V.

Após cada etapa serão realizados os testes de verificação e validação nos artefatos gerados conforme o tópico de [Detalhamento do Ciclo de Vida](#15-detalhamento-do-Ciclo-de-Vida) e não-conformidades deverão ser identificadas e monitoradas até a sua conclusão.

Nessa fase também serão realizados reuniões de forma a verificar o andamento do projeto na opnião dos integrantes de forma a manter o compromisso entre a equipe.

Quaisquér não-conformidades encontradas durante os pontos de controle deverão ser documentadas e um relatório de estado para o marco será criado.

3. Gerenciamento de Riscos
--------------------------

### 3.1 Métricas de Risco

A prioridade de um risco é calculado pelo produto entre os __indivíduos afetados__ e seu __impacto__ no projeto.

* Tabela para classificação de afetibilidade:

 Métrica de afetibilidade | Nome | Valor 
------------------|------|------
O risco afeta apenas 1 (um) indivíduo da equipe | Baixo | 1
O risco afeta vários indivíduos | Alto | 2

* Tabela para classificação de impacto:

 Métrica de impacto | Nome | Valor 
------------------|------|------
Afeta todo o projeto | Alto | 3
Afeta várias área | Médio | 2
Afeta apenas 1 (um) área em específico | Baixo | 1

* Tabela para classificação de prioridade:

 Métrica (produto entre as métricas anteriores) | Nome
------------------|------
Entre __1 e 2__ | Baixo
Entre __3 e 4__ | Médio
Entre __5 e 6__ | Alto 

### 3.2 Tipos de Riscos

Os riscos serão classificados em __riscos de equipe__ e __riscos técnicos__.

Os riscos de equipe serão abordados em [Riscos em RH](#42-riscos-em-rh), enquanto que os riscos técnicos serão abordados neste tópico.

identificador | Nome | Prioridade | Forma de contingência  
--------------|------|------------|-----------------------
R1 | Equipamento defeituoso | Média/Alto | Deverá ser realizado uma realocação dos recursos
R2 | Falta de Energia | Média/Alto | Não há como proceder
R3 | Falta de Internet | Média/Alto | O projeto deverá continuar sendo feito em offline
R4 | Membro doente | Média/Alto | O escopo do projeto deverá ser refatorado
R5 | Auêencia de um membro | Média/Alto | O escopo do projeto deverá ser refatorado

4. Recursos Humanos
-------------------

### 4.1 Responsabilidades

           Nome             |            Papel           | Responsável por | Competências
-----------------------------|----------------------------|--------------|---------
Pedro Henrique Silva Farias    | Gerente de configuração / Gerente de projetos     | Estruturar a estrutura e definir métodos de acesso ao repositório | Aluno do 6* Periodo de Eng. de Software
Rony Nogueira  | Gerente de Projetos    | Verificar se o plano de projeto está sendo aplicado corretanmente     | Aluno do 4* Periodo de Eng. de Software
Milton Araújo   | Gerente de Requisitos          | Levantar e gerenciar os requisitos   | Aluno do 6* Periodo de Eng. de Software
Thallisson Lopes     | Analista de Requisitos | Levantar e anaisar os requisitos     | Aluno do 4* Periodo de Eng. de Software
Matheus Lima          | Gerente de qualidade          | Gerar e executar checklists para garantia de qualidade     | Aluno do 6* Periodo de Eng. de Software
Nikolas Mathias     | Gerente de qualidade | Gerar e executar checklists para garantia d qualidade     | Aluno do 6* Periodo de Eng. de Software

Caso algum membro não demonstre a devida competência em sua área, o membro deverá ser submetido por um treinamento durante a execução do projeto. O treinamento consistira em uma explicação breve sobre o sistema que será desenvolvido e a área definida além de ser ministrado por outro integrante do grupo da mesma área. 

### 4.2 Riscos em RH

Os riscos em RH são classificados conforme o que foi abordado em [Gerenciamento de Riscos](#3-gerenciamento-de-riscos).

Possiveis riscos de equipe:

identificador | Nome | Prioridade | Forma de contingência  
--------------|------|------------|-----------------------
R4 | Membro doente | Baixa | O escopo do projeto será remanejado
R5 | Membro inexperiente | Baixa | O membro deverá continuar estudando no mesmo tempo em que realiza o projeto
R6 | Remoção de um membro | Alta | O escopo do projeto será remanejado
R7 | Adição de um membro | Alta | O escopo do projeto será remanejado
R8 | Mudança no cliente | Alta | O escopo do projeto será remanejado

5. Detalhamento de Projeto
--------------------------

### 5.1 Estrutura de Projeto
Para o projeto a ser desenvolvido será necessário um ambiente de desenvolvimento que utilize ferramentas de código livre ou open source, para gerência e controle do projeto será necessário um repositório para controle de versões do produto em desenvolvimento. O repositório deverá ser privado para acesso externo aos membros da equipe de desenvolvimento.

### 5.2 Armazenamento de Artefatos
Os artefatos produzidos durante o desenvolvimento do produto deverão ser acessados apenas por membros da equipe de desenvolvimento e cliente envolvido. O cliente possuirá uma área de acesso para ver o andamento do projeto, nesse ambiente terá disponível os relatórios e documentos relativos ao desenvolvimento, não serão acessíveis aos clientes os códigos-fonte do projeto, conforme o [Plano de gerência de configuração](https://github.com/PedroDrim/UFG_PS_2015/blob/master/Documentos/Plano%20de%20Ger%C3%AAncia%20de%20configura%C3%A7%C3%B5es.md).

### 5.3 Metricas de Acessibilidade
Cada membro responsável por uma área deverá modificar apenas os artefatos referentes a tal área específica, conforme o [Plano de gerência de configuração](https://github.com/PedroDrim/UFG_PS_2015/blob/master/Documentos/Plano%20de%20Ger%C3%AAncia%20de%20configura%C3%A7%C3%B5es.md).

6. Monitoramento de riscos
----------------

Todos os artefatos do projeto deverão ser ter suas modificações monitoradas bem como os custos esperados e os recursos humanos e os interessados.

Os interessados também deverão ser informados das modificações. Para auxiliar o monitoramento, um relatório contendo a ocorrência dos riscos deverá existir sendo feito com base no [template de riscos](https://github.com/PedroDrim/UFG_PS_2015/blob/master/Templates/%5BTemplate%5D%20Relat%C3%B3rio%20de%20riscos.md)

[Relatório de riscos](https://github.com/PedroDrim/UFG_PS_2015/blob/master/Documentos/Relatorio%20de%20riscos.md)

7. Manutenção
-------------

Todos os problemas identificados durante o projeto deverão ser monitorados e acompanhados até a sua conclusão. Para auxiliar a manutenção, um relatório contendo a ocorrência dos erros deverá existir sendo feito com base no [template de manutenção](https://github.com/PedroDrim/UFG_PS_2015/blob/master/Templates/%5BTemplate%5D%20Relat%C3%B3rio%20de%20manuten%C3%A7%C3%A3o.md)

[Relatório de manutenção](https://github.com/PedroDrim/UFG_PS_2015/blob/master/Documentos/Relat%C3%B3rio%20de%20manuten%C3%A7%C3%A3o.md)

8. Aprovação formal
----------------------------
Aprovação do plano de projeto por todos os integrantes do grupo.

![Assinaturas](https://raw.githubusercontent.com/PedroDrim/UFG_PS_2015/master/Anexos/Assinaturas.jpg)


