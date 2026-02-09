# 🧭 Step by Step – Project Zero Downtime

Este documento descreve o **processo técnico completo** utilizado no desenvolvimento do projeto de Manutenção Preditiva.

---

## 1️⃣ Entendimento do Problema
Análise do impacto do downtime na indústria automotiva e definição do objetivo de prever falhas antes da quebra.

---

## 2️⃣ Geração dos Dados
Uso de um Digital Twin para simular sensores industriais:
- Vibração
- Temperatura
- RPM

---

## 3️⃣ Análise Exploratória
- Visualização das séries temporais
- Identificação de padrões normais e anômalos

---

## 4️⃣ Tratamento de Ruído
- Aplicação de média móvel
- Criação de baseline dinâmica

---

## 5️⃣ Engenharia de Features
- Derivadas
- Crescimento percentual
- Correlação entre variáveis

---

## 6️⃣ Lógica de Detecção
Criação de regras para:
- Crescimento contínuo de vibração
- Aumento simultâneo de temperatura
- Geração de alertas preditivos

---

## 7️⃣ Insights de Negócio
- Redução de downtime
- Otimização da manutenção
- Base para escalabilidade do sistema
