Processo de software 2015
==================================

Processo Garantia de Qualidade
================================

Índice Análitico
------------------
* 1. [Introdução](#1-introdução)
   * 1.1. [Objetivos](#11-objetivos)
   * 1.2. [Referências](#12-referências)
   * 1.3. [Escopo](#13-escopo)
   * 1.4 [Definições, Abreviações e Acronimos](#14-definições-abreviações-e-acronimos)
   * 1.5. [Politicas](#15-politicas)
* 2. [Papeis](#2-papeis)
* 3. [Métricas](#3-métricas)
* 4. [Resolução de Problemas e Ação Corretiva](#4-resolução-de-problemas-e-ação-corretiva)
   * 4.1 [Cronograma](#41-cronograma)
   * 4.2. [Ações corretivas para Porcentagem de Adequação da Execução](#42-ações-corretivas-para-porcentagem-de-adequação-da-execução)
   * 4.3. [Ações corretivas para Porcentagem de Adequação ao Template](#43-ações-corretivas-para-porcentagem-de-adequação-ao-template)
* 5. [Monitoramento de Resultados](#5-monitoramento-de-resultados)
* 6. [Validação dos Resultados](#6-validação-dos-resultados)



1. Introdução
--------------
Este Plano vai explicar como funciona o processo para se obter uma garantia da qualidade do processo de software.

### 1.1 Objetivos
O propósito do processo Garantia da Qualidade é assegurar que os produtos de trabalho e a execução dos processos estão em conformidade com os planos e recursos predefinidos.

### 1.2 Referências
MPS - BR: Melhoria de Processos do Software Brasileiro
CMMI: Capability Maturity Model - Integration ou Modelo de Maturidade em Capacitação - Integração

### 1.3 Escopo
O Mr Imune é programa multiplataforma(aplicação mobile e web) que apresenta um calendário de vacinas disponibilizados pelo Ministério da Saúde e histórico das vacinas que você de já tomou.

### 1.4 Definições, Abreviações e Acronimos

Definições, Abreviações e Acrônimos | Significado
----------------------------------- | -----------------
MPS-BR                             | Melhoria de Processo de Software Brasileiro
CMMI                               | Capability Maturity Model - Integration ou Modelo de Maturidade em Capacitação - Integração

### 1.5 Politicas

* Todos os processos atrelados aos projetos desenvolvidos pela organização devem estar em conformidade com os resultados esperados do nível G do MPS-BR.
* Deve haver um controle sistêmico de todos os artefatos de projeto.

2. Papeis
--------------------------

Papel              | Gerente de Qualidade(GQA)
------------------ | -----------------------------
Formação           | Essas ocupações são exercidas por pessoas com escolaridade de ensino superior na área de tecnologia da informação ou similares.
Conhecimentos      | Conceitos sobre garantia da qualidade, Processo de garantia da qualidade na empresa e Conhecimento básico nos modelos de maturidade de processo MPS-BR ou CMMI.
Responsabilidades  | Definir o plano de garantia da qualidade, Estabelecer os processos que serão geridos pela garantia da qualidade, Definir um cronograma para avaliação da conformidade da execução dos processos com o que foi planejado, Estabelecer métodos de avaliação de aderência de processo, Realizar auditorias.  Relatar todas as não conformidades, Planejar ações corretivas para as não conformidades identificadas.


3. Métricas
-------------
Indicador | Índice de cumprimento de cronograma
---------- | ------------------------------------------
Objetivo | O objetivo desse indicador é verificar o desempenho do processo de qualidade quanto ao cumprimento do cronograma.
Coleta | Os dados devem ser coletados através do cronograma do processo. As datas iniciais e finais planejadas serão analisadas com relação a execução.  Para medição utiliza-se a formula x= a - b.  x = Índice de cumprimento do cronograma. a = Atividades em dia. b = Atividades executadas ou entregues fora do prazo.
Análise | Quanto mais próximo de 0, x estiver, mais eficaz o processo no que diz respeito ao cumprimento do planejado.Caso X = 0-4 - BAIXO, X = 0-6 - MÉDIO, X >10 - ALTO.

Indicador | Resolução de Nâo confirmidade
----------- | -----------------------------
Objetivo | O objetivo desse indicador é medir o desempenho do processo de qualidade quanto a eficácia do mesmo na resolução das não conformidades ao longo do desenvolvimento.
Coleta | Os dados devem ser coletados através dos registros de não conformidades. Para medição utiliza-se a formula x= a - b. x = Resolução de não conformidades. a = Não conformidades relatadas. b = Não conformidades solucionadas.
Análise | Quanto mais próximo de 0, x estiver, mais eficaz o processo na resolução das não conformidades. Caso X = 0-4 - BAIXO, X = 0-6 - MÉDIO e X >10 - ALTO.

4. Comunicação
--------------------------------------------

Comunicação | Plano de Garantia de Qualidade
----------- | ------------------------------
Emissor | Gerente de Qualidade
Receptores | Todos os envolvidos no projeto
Mensagem | Determinar como Garantia da Qualidade auxiliará durante o projeto
Meio de Comunicação | Plano de Garantia de Qualidade
Quando | Planejamento e atualização do projeto

Comunicação | Registro de Não Conformidades
----------- | ------------------------------
Emissor | Gerente da Qualidade
Receptores | Responsável pela medição
Mensagem | Dados Referentes as Não Conformidades
Meio de Comunicação | Registro de Não Conformidades
Quando | Quando for ocorrer a medição do processo de qualidade

Comunicação | Comunicado de Não Conformidade
----------- | ------------------------------
Emissor | Gerente de Qualidade
Receptores | Todos os envolvidos
Mensagem | Relatar os envolvidos a existência de uma não conformidade
Meio de Comunicação | Forma de comunicação que permita o envio da mensagem para os membros relevantes e que mantenha o controle e integridade da mensagem. Podendo ser via e-mail, repositório, ou outros serviços de mensagens nos quais os envolvidos possuam familiaridade.
Quando | Quando houver necessidade de atentar os envolvidos

5. Macro Fluxo
--------------------
![Imagem do Macro Fluxo](https://i.imgsafe.org/c9c3b1c.png)

6. Atividades
---------------------------

Atividade | Definir os processos a serem geridos
--------- | -----------------------------------------
Responsabilidades | Realização: Identificar quais os processos em que será aplicada a garantia da qualidade.
Responsabilidades | Aprovação: Não se aplica.
Responsabilidades | Colaboração: Todos os envolvidos no projeto.
Responsabilidades | Informação: Gerente de projetos
Tarefas | 1. Identificação dos processos relacionados ao projeto. 2. Definições de quais processos devem ser gerenciados pela garantia da qualidade.
Pré-Condições | Nenhum critério especifico.
Entradas | Processos que compõe o projeto
Critérios de Saída | Escopo de garantia de Qualidade
Produtos | Seção 1.3 do Plano de Qualidade
Ferramentas | Microsoft Office.

Atividade | Verificar a Aderência dos Produtos de trabalho
--------- | -----------------------------------------
Responsabilidades | Realização: Verificar a aderência dos produtos de trabalho aos padrões, procedimentos e requisitos aplicáveis.
Responsabilidades | Aprovação: Não se aplica.
Responsabilidades | Colaboração: Todos os envolvidos.
Responsabilidades | Informação: Todos os envolvidos.
Tarefas | 1. Definir checklist. 2. Programar auditorias internas. 3. Realizar auditorias internas.
Pré-Condições | Nenhum critério específico.
Entradas | Produtos de trabalho, padrões, procedimentos e requisitos aplicáveis
Critérios de Saída | Nenhum criterio especifico.
Produtos | Checklist.
Ferramentas | Microsoft Office.

Atividade | Verificar a Aderencia do Processo
--------- | -----------------------------------------
Responsabilidades | Realização: Realizar Auditorias a fim de verificar a aderência dos processos executados às descrições de processo, padrões e procedimentos.
Responsabilidades | Aprovação: Não se aplica.
Responsabilidades | Colaboração: Todos os envolvidos.
Responsabilidades | Informação: Todos os envolvidos.
Tarefas | 1. Definir checklists. 2. Programar Auditorias Internas. 3. Realizar Auditorias Internas.
Pré-Condições | Nenhum critério especifico.
Entradas | Processo executados, descrições de processo, padrões e procedimentos.
Critérios de Saída | Nenhum critério especifico.
Produtos | Checklist
Ferramentas | Microsoft Office.

Atividade | Relatar as não conformidades
--------- | -----------------------------------------
Responsabilidades | Realização: Documentar todas as não conformidades auditadas.
Responsabilidades | Aprovação: Não se aplica.
Responsabilidades | Colaboração: Gerente de Projeto.
Responsabilidades | Informação: Todos os envolvidos.
Tarefas | 1. Documentar todas as não conformidades. 2. Classificar as não conformidades. 3. Comunicar as não conformidades.
Pré-Condições | Nenhum critério especifico.
Entradas | Checklist.
Critérios de Saída | Nenhum critério especifico.
Produtos | Relat´rio de não conformidades e Registro de não conformidades.
Ferramentas | Microsoft Office.

Atividade | Definir ações corretivas
--------- | -----------------------------------------
Responsabilidades | Realização: Planejar as açoes corretivas para as não conformidades relatadas.
Responsabilidades | Aprovação: Gerente de Projeto, Comitê de Controle de Mudanças.
Responsabilidades | Colaboração: Gerente de Projeto e o gerente responsável pelo processo que envolve a não conformidade junto ao Comitê de Controle de Mudanças.
Responsabilidades | Informação: Todos os envolvidos.
Tarefas | 1. Identificar a causa da não conformidade. 2. Avaliar a necessidade de ações para correção. 3. Determinar a implementação de ações necessárias. 4. Registrar os resultados da correção.
Pré-Condições | Para inicio da atividade é necessário que as não conformidades sejam identificadas e documentas.
Entradas | Relatório de não conformidades
Critérios de Saída | A solução deve ser implementada, registrada e aprovada pelo Gerente de Projeto
Produtos | Seção 4 Plano de Garantia Qualidade. Relatório de resolução de não conformidades. Registro de não conformidades.
Ferramentas | Microsoft Office.


5. Monitoramento de Resultados
-------------------------------
[_Aqui será descrito como será monitorado os resultados e produtos esperados do processo, e se tudo o que fora planejado foi cumprido._]


6. Validação dos Resultados
-------------------------------------
[_Aqui será validado os resultados do processo de Garantia da Qualidade. Juntamente com a gerência de alto nível do projeto._]

