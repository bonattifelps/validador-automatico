# 🚀 Validador Automático de Dados

[![GitHub last commit](https://img.shields.io/github/last-commit/felipesbonatti/validador-automatico?style=flat-square)](https://github.com/felipesbonatti/validador-automatico)
[![GitHub repo size](https://img.shields.io/github/repo-size/felipesbonatti/validador-automatico?style=flat-square)](https://github.com/felipesbonatti/validador-automatico)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo GitHub" width="100">
</p>

---

## 📌 Sobre o Projeto

Este repositório apresenta um **validador automático de dados** desenvolvido para ser utilizado durante os processos de atualização de dashboards. O objetivo principal é **detectar variações anômalas (outliers)** e **reportá-las via Microsoft Teams** antes da finalização do processo, evitando retrabalho e inconsistências nos relatórios.

O validador foi projetado para **automatizar a validação de dados**, garantindo maior confiabilidade e eficiência nos processos de atualização de dashboards.

<p style="color: red; font-size: 14px;">
  <strong>Observação:</strong> Por questões de conformidade com a <strong>Lei Geral de Proteção de Dados (LGPD)</strong>, os nomes dos campos e informações sensíveis foram omitidos ou anonimizados neste repositório.
</p>

---

## 🎯 Objetivo

O principal objetivo deste projeto é:

- **Validar os dados** antes da atualização dos dashboards.
- **Detectar outliers** na contagem de clientes e rentabilidade.
- **Alertar a equipe** via Microsoft Teams em caso de inconsistências.
- **Reduzir retrabalho** e garantir maior confiabilidade nos dashboards.

---

## ⚙️ Funcionamento

O validador funciona em quatro etapas principais:

1. **Consulta dos Dados:**
   - Consulta os dados no ambiente **PySpark SQL** com filtros específicos.

2. **Verificação de Anomalias:**
   - Verifica a contagem de registros e identifica possíveis anomalias.

3. **Geração de Mensagens:**
   - Gera uma mensagem de monitoramento, diferenciando casos normais e críticos.

4. **Envio de Alertas:**
   - Envia um alerta para o **Microsoft Teams**, permitindo a intervenção antes da conclusão da atualização.

---

## 🛠️ Tecnologias Utilizadas

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white" alt="PySpark">
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks">
  <img src="https://img.shields.io/badge/Microsoft_Teams-6264A7?style=for-the-badge&logo=microsoft-teams&logoColor=white" alt="Microsoft Teams">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
</div>

- **Linguagens:** Python, SQL
- **Big Data:** PySpark, Databricks, SparkSQL
- **Notificação:** pymsteams (Microsoft Teams Webhook)
- **Manipulação de Dados:** Pandas, PySpark DataFrames

---

## 📌 Benefícios do Validador

- **Automação do Processo:** Elimina a necessidade de validação manual, reduzindo erros.
- **Detecção de Outliers em Tempo Real:** Identifica anomalias antes que afetem os dashboards.
- **Integração com Microsoft Teams:** Facilita a comunicação e a tomada de ações corretivas.
- **Flexibilidade e Escalabilidade:** Pode ser adaptado para outros cenários e bases de dados.

 ### 🌟 Destaques do Projeto

- **Automação Inteligente:** Validação automática de dados, reduzindo erros manuais.
- **Integração com Microsoft Teams:** Alertas em tempo real para a equipe.
- **Conformidade com LGPD:** Respeito às normas de proteção de dados, garantindo segurança e privacidade.
- **Escalável e Adaptável:** Pode ser utilizado em diversos cenários e bases de dados.

---

## 🚀 Como Usar

1. **Configure o Webhook do Microsoft Teams:**
   - Crie um webhook no Microsoft Teams para receber as notificações.

2. **Adapte a Consulta SQL:**
   - Ajuste a consulta SQL no código conforme a base de dados utilizada.

3. **Execute o Código:**
   - Execute o código no **Databricks** ou outro ambiente compatível com PySpark.

