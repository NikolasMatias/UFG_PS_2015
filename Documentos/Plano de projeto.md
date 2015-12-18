
Processo de software 2015
=================================

Índice Analítico
----------------

* 1. [Escopo de Projeto](#1-escopo-de-projeto)
    * 1.1. [Objetivos](#11-objetivos)
    * 1.2. [Estratégia Organizacional](#12-estratégia-organizacional)
    * 1.3. [Artefatos Esperados](#13-artefatos-esperados)
    * 1.4. [Detalhamento dos Artefatos](#14-detalhamento-dos-artefatos)
    * 1.5. [Detalhamento do Ciclo de Vida](#15-detalhamento-do-Ciclo-de-Vida)
    * 1.6. [Estimativa de esforço](#16-estimativa-de-esforço)
* 2. [Custo do Projeto](#2-custo-do-projeto)
    * 2.1. [Cronograma](#21-cronograma)
    * 2.2. [Recursos](#22-recursos)
    * 2.3. [Pontos de controle](#23-pontos-de-controle)
* 3. [Gerenciamento de Riscos](#3-gerenciamento-de-riscos)
    * 3.1. [Métricas de Risco](#31-métricas-de-risco)
    * 3.2. [Tipos de Riscos](#32-tipos-de-riscos)
* 4. [Recursos Humanos](#4-recursos-humanos)
    * 4.1. [Responsábilidades](#41-responsábilidades)
    * 4.2. [Riscos em RH](#42-riscos-em-rh)
* 5. [Detalhamento de Projeto](#5-detalhamento-de-projeto)
    * 5.1. [Estrutura de Projeto](#51-estrutura-de-projeto)
    * 5.2. [Armazenamento de Artefatos](#52-armazenamento-de-artefatos)
    * 5.3. [Metricas de Acessibilidade](#53-metricas-de-acessibilidade)
* 6. [Monitoramento](#6-monitoramento)
* 7. [Manutenção](#7-manutenção)
* 8. [Aprovação formal](#6-aprovação-formal)

1. Escopo de Projeto
---------------------

### 1.1 Objetivos
Este é um projeto com o propósito unicamente acadêmico, sua finalidade é disceminar o conhecimento nas áreas do MPS.BR, nos níveis G e F, entre os integrantes da equipe.

### 1.2 Estratégia Organizacional
Este plano foi definido com o intuíto acadêmido de simular um projeto em uma empresa. O ciclo de vida utilizado como base para os futuros projetos que utilizarem deste plano é o __ciclo de vida em V__, devido a facilidade em encontrar erros durante as primeiras fases, evitando assim, maior custo no futuro.

### 1.3 Artefatos Esperados
 No desenvolvimento de projetos pela organização deverá haver os artefatos a cada fase de desenvolvimento do produto. Seguindo o ciclo de vida do projeto, deverão ser apresentados ao longo do projeto documentos acerca do desenvolvimento de cada fase. Os resultados de cada fase deverão ser documentados para controle da organização, facilidade em manutenção posterior, organização no desenvolvimento.
 
	Na etapa de especificação dos requisitos do software deverão ser gerados os artefatos relativos à: elicitação dos requisitos junto aos stakeholders; rastreabilidade dos requisitos deve ser realizada e documentada; deverá haver um relatório com as mudanças nos requisitos ao longo do desenvolvimento.
	
	Na etapa de projeto preliminar deverão ser gerados os artefatos relativos à: Gerência de projeto, tais como plano de projeto, cronogramas, marcos de projeto, análise de custo e viabilidade, gerenciamento e controle de riscos.
	
	Na etapa de projeto detalhado deverão ser gerados os artefatos relativos à: Gerência de áreas do projeto, tais como plano de gerência de requisitos, plano de qualidade e plano de gerência de configuração.
	
	Na etapa de codificação deverão ser gerados os artefatos relativos à: codificação; documentação dos códigos; testes locais realizados pelo programador.
	
	Nas etapas de testes deverão ser gerados relatórios relativos a realização dos testes em cada fase, os testes realizados na fase de especificação (teste de qualificação de requisitos) deve ser documentada e gerenciada, os testes realizados na fase de projeto (teste de integração e teste unitário) deverão gerar relatórios com os resultados obtidos nos testes realizados, deve ser documentado e gerenciado, os testes locais realizados por programadores e desenvolvedores deverão produzir documentação acerca do código, possuindo data de elaboração e versão do código e do produto.


### 1.4 Detalhamento dos Artefatos
[_Seguindo o GPR2 do MPS.BR, os artefatos estimados deverão ser divididos em artefatos menores tornando mais fácil o regenciamento. Nesta seção, todos os artefatos gerados na EAP serão detalhados e classificados quanto a sua importância no projeto._]

### 1.5 Detalhamento do Ciclo de Vida
O ciclo de vida definido para este plano é o __ciclo de vida em V__ a sua estruturação no projeto será realizada da seguinte maneira:

* __Etapa 1:__ Será realizada uma análise dos requisitos do projeto bem como técnicas de verificação e validação destes requisitos.
   * __Artefatos gerados na Etapa 1:__

* __Etapa 2:__ Será realizada a transição dos requisitos para a arquitetura bem como técnicas de verificação e validação para essa nova arquitetura.
   * __Artefatos gerados na Etapa 2:__

* __Etapa 3:__ Será realizada a construção do projeto bem como os testes que serão aplicados de forma a validar e verificar o produto.
   * __Artefatos gerados na Etapa 3:__
   
* __Etapa 4:__ Por fim o produto-final será implementado.
   * __Artefatos gerados na Etapa 4:__

### 1.6 Estimativa de esforço
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
[_Por definição, custo pode ser tanto "cronológico" quanto "monetário". Seguindo o GPR5 do MPS.BR, nesta seção deverá ser definido o custo do projeto bem como os marcos e pontos de controle_]

### 2.1 Cronograma
[_O cronograma poderá ser definido por meio da EAP, presente no tópico 1.3, em conjunto com o esforço estimado, presente no tópico 1.6. O cronograma deverá estimar quantas horas serão gastas em cada atividade do projeto._]

### 2.2 Recursos
[_Os recursos, assim como o cronograma, poderão ser definidos pela EAP, presente no tópico 1.3, em conjunto com o esforço estimado, presente no tópico 1.6. Os recursos gastos poderão ser detalhados._]

### 2.3 Pontos de controle

Levando em conta o ciclo de vida em uso, foram definidos como pontos de controle o período de transição entre as fases do ciclo de vida V.

Após cada etapa serão realizados os testes de verificação e validação nos artefatos gerados conforme o tópico de [Detalhamento do Ciclo de Vida](#15-detalhamento-do-Ciclo-de-Vida) e não conformidades deverão ser identificadas e monitoradas até a sua conclusão.

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

4. Recursos Humanos
-------------------

### 4.1 Responsábilidades

           Nome             |            Papel           | Responsável por | Competências
-----------------------------|----------------------------|--------------|---------
Pedro Henrique Silva Farias    | Gerente de Projetos     | Verificar se o plano de projeto está sendo aplicado corretanmente | [LinkedIn de Pedro]
Rony Nogueira  | Gerente de Projetos    | Verificar se o plano de projeto está sendo aplicado corretanmente     | [LinkedIn de Rony]
Milton Araújo   | Gerente de Requisitos          | Levantar e gerenciar os requisitos   | [LinkedIn de Milton]
Matheus Vani | Analista de Requisitos      | Levantar e anaisar os requisitos     | [LinkedIn de Matheus]
Thallisson Lopes     | Analista de Requisitos | Levantar e anaisar os requisitos     | [LinkedIn de Thallisson]
Matheus Lima          | Gerente de qualidade          | Gerar e executar checklists para garantia de qualidade     | [LinkedIn de Matheus Lima]
Nikolas Mathias     | Gerente de qualidade | Gerar e executar checklists para garantia d qualidade     | [LinkedIn de Nikolas]

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
[_Nesta seção serão definidos aspéctos específicos para a execução do projeto definido._]

### 5.1 Estrutura de Projeto
Para o projeto a ser desenvolvido será necessário um ambiente de desenvolvimento que utilize ferramentas de código livre ou open source, para gerência e controle do projeto será necessário um repositório para controle de versões do produto em desenvolvimento. O repositório deverá ser privado para acesso externo aos membros da equipe de desenvolvimento.
	A comunicação entre os participantes do projeto que será desenvolvido deverá ser realiza através de chats online ou pessoalmente, funcionando de acordo com a quantidade de pessoas envolvidas no projeto. 
	Para cada projeto deverá ter reuniões a cada semana, de aproximadamente 15 min para discutir com a equipe o andamento do projeto, ao final de cada reunião deverá ser realizado a elaboração de um relatório contendo os fatos discutidos.
	Para os clientes deverá ser disponibilizado uma área para acesso aos artefatos gerados durante o desenvolvimento, essa área deverá ser controlada.

### 5.2 Armazenamento de Artefatos
Os artefatos produzidos durante o desenvolvimento do produto deverão ser acessados apenas por membros da equipe de desenvolvimento e cliente envolvido. O cliente possuirá uma área de acesso para ver o andamento do projeto, nesse ambiente terá disponível os relatórios e documentos relativos ao desenvolvimento, não serão acessíveis aos clientes os códigos-fonte do projeto.
	Para os membros da equipe estará disponível o repositório do projeto, o qual terá o acesso privado, neste repositório do projeto terão os documentos de cada fase do projeto, projetos e códigos-fonte. Gerentes poderão ter acesso a qualquer projeto desenvolvido na empresa.

[_Linkar plano de gerência de configuração_]

### 5.3 Metricas de Acessibilidade
[_As métricas utilizadas para definir acessibilidade dos artefatos deverão ser definidos._]

[_Linkar plano de gerência de configuração_]

6. Monitoramento
----------------

Todos os artefatos do projeto deverão ser ter suas modificações monitoradas bem como os custos esperados e os recursos humanos e os interessados.

Os interessados também deverão ser informados das modificações. Para auxiliar o monitoramento, um relatório contendo a ocorrência dos riscos deverá existir sendo feito com base no [template de riscos](https://github.com/PedroDrim/UFG_PS_2015/blob/master/Templates/%5BTemplate%5D%20Relat%C3%B3rio%20de%20riscos.md)

[_Linkar os relatórios de monitoramento._]

7. Manutenção
-------------

Todos os problemas identificados durante o projeto deverão ser monitorados e acompanhados até a sua conclusão. Para auxiliar a manutenção, um relatório contendo a ocorrência dos erros deverá existir sendo feito com base no [template de manutenção](https://github.com/PedroDrim/UFG_PS_2015/blob/master/Templates/%5BTemplate%5D%20Relat%C3%B3rio%20de%20manuten%C3%A7%C3%A3o.md)

[_Linkar os relatórios de manutenção._]

8. Aprovação formal
----------------------------
A aprovação do plano de projeto deverá ser realizada junto aos clientes e/ou stakeholders envolvidos no projeto.


