# 🏭 Project Zero Downtime  
## Manutenção Preditiva Industrial com Análise de Dados  
**Relatório Técnico e de Negócio – MVP**  
Curso de Análise de Dados – Generation Brasil  
Bootcamp Indústria 4.0


### 1. Introdução

Este projeto foi desenvolvido no âmbito do bootcamp de **Análise de Dados da Generation Brasil**, simulando um cenário realista de **Indústria 4.0**.  
Utilizando **gêmeos digitais (Digital Twins)** para geração de dados realistas e representativos do comportamento físico de equipamentos industriais, o trabalho tem como foco central a **redução de downtime não planejado** por meio de um sistema de **manutenção preditiva** baseado na análise contínua de dados de sensores.

O principal entregável é um **MVP (Minimum Viable Product)** funcional que demonstra a viabilidade técnica e o retorno econômico da abordagem preditiva em um contexto de alta criticidade operacional.

### 2. Visão Geral do Problema

Na indústria automotiva, linhas de produção contam com braços robóticos KUKA que operam ininterruptamente em etapas críticas, como soldagem.  
Uma falha inesperada em um único equipamento pode interromper toda a linha, gerando custos expressivos.

**Principais impactos financeiros observados:**

- Valor unitário de cada robô: **R$ 250.000,00**  
- Custo médio de parada da linha: **R$ 50.000,00 por hora**

**Abordagens tradicionais apresentam limitações importantes:**

- **Manutenção corretiva** → elevadas perdas por paradas não planejadas  
- **Manutenção preventiva** → desperdício de peças e intervenções desnecessárias

**Objetivo estratégico:**  
Antecipar falhas com antecedência suficiente para realizar intervenções planejadas durante janelas de parada programada, eliminando ou reduzindo significativamente as paradas emergenciais.

 
*Adotamos a dinâmica de Role-Play (RPG) nesta apresentação*

### 3. Objetivos do Projeto

Desenvolver e validar um **MVP de manutenção preditiva** com as seguintes capacidades:

- Monitoramento contínuo de variáveis críticas (vibração, temperatura, RPM)  
- Detecção precoce de padrões de degradação do equipamento  
- Redução significativa de falsos positivos por meio de tratamento de ruído  
- Geração de alertas preditivos acionáveis  
- Cálculo preliminar de indicadores de retorno financeiro (**Payback** e **ROI**)  
- Arquitetura escalável como base para expansão a múltiplos equipamentos e linhas

### 4. Contexto de Negócio – Titan Motors

**Empresa fictícia:** Titan Motors  
**Segmento:** Indústria Automotiva  
**Equipamento crítico monitorado:** Braço robótico KUKA de soldagem

**Modelo de manutenção atual:**

- Corretiva → alto custo por hora parada  
- Preventiva → troca periódica de componentes (desperdício quando peças ainda estão em bom estado)

**Valor esperado da solução preditiva:**

- Redução drástica do tempo de inatividade não planejado  
- Aumento da vida útil efetiva dos componentes  
- Melhoria expressiva do **OEE** (Overall Equipment Effectiveness)

  
*Time de Dados contratado para o projeto*

### 5. Abordagem Técnica – MVP

**Fonte de dados:**  
Simulação realista por meio de **Digital Twin industrial** (gêmeo digital), gerando leituras a cada segundo com as seguintes variáveis principais:

- Vibração  
- Temperatura  
- RPM  
- Timestamp  
- Indicador composto de saúde do equipamento (health)

**Etapas executadas no MVP:**

1. Aquisição e união de dados simulados  
2. Análise exploratória detalhada  
3. Tratamento de ruído (média móvel rolante)  
4. Engenharia de *features* (tendências, variações percentuais, correlações multivariadas)  
5. Desenvolvimento de lógica de detecção de drift e geração de alertas preditivos  
6. Exploração conceitual de **RUL** (Remaining Useful Life)  
7. Modelagem preliminar de **Payback** e **ROI** com base no custo evitado de paradas

**Resultados financeiros estimados (MVP):**

- Cenário conservador: redução de **60–80%** das paradas não planejadas  
- **Payback** projetado: entre **6 e 12 meses** (dependendo do número de robôs monitorados)  
- **ROI** anual estimado: superior a **300–500%** após o primeiro ano

### 6. Documentação

📌 **Passo a passo técnico:**  
➡️ [STEP_BY_STEP_PASSO_A_PASSO.md](STEP_BY_STEP_PASSO_A_PASSO.md)

📊 **Slides da apresentação:**  
https://drive.google.com/drive/folders/10eJ1iVi4xAh6G02Evj40vIopw8VnmMsm

📋 **Quadro do projeto (Backlog) no Trello:**  
https://trello.com/b/65WfSG1j/ind%C3%BAstria-40

### 7. Equipe de Desenvolvimento

Projeto realizado em grupo no bootcamp **Generation Brasil – Análise de Dados**.

**Time de Dados:**

- Amanda dos Santos  
- Caroline Henrique  
- Edson Ricardo  
- **Everton Alexandre da Silva Santos**  
- Luana Andrade

---

**Projeto MVP concluído em 4 de fevereiro de 2026**  
Generation Brasil – Análise de Dados | Indústria 4.0

