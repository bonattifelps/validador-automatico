# *OBS: OS NOMES DOS CAMPOS FORAM OMITIDOS POR QUESTÕES DE LGPD*

# **🚀 Validador de Dados para Atualização de Dashboards**  

## 📌 **Sobre o Projeto**  
Este repositório apresenta um **validador automático** desenvolvido para ser utilizado durante os processos de **atualização de dashboards**. O objetivo é **detectar variações anômalas (outliers) e reportá-las via Microsoft Teams antes da finalização do processo**, evitando retrabalho e inconsistências nos relatórios.

## 🎯 **Objetivo**  
✔️ Validar os dados antes da atualização dos dashboards  
✔️ Detectar **outliers** na contagem de clientes e rentabilidade  
✔️ Alertar a equipe via **Microsoft Teams** em caso de inconsistências  
✔️ Reduzir retrabalho e garantir maior confiabilidade nos dashboards  

## ⚙️ **Funcionamento**  
1️⃣ **Consulta os dados** no ambiente PySpark SQL com filtros específicos.  
2️⃣ **Verifica a contagem de registros** e identifica possíveis anomalias.  
3️⃣ **Gera uma mensagem de monitoramento**, diferenciando casos normais e críticos.  
4️⃣ **Envia um alerta para o Microsoft Teams**, permitindo a intervenção antes da conclusão da atualização.  

## 🛠 **Tecnologias Utilizadas**  
- **Linguagens:** Python, SQL, PySpark  
- **Big Data:** Databricks, SparkSQL  
- **Notificação:** pymsteams (Microsoft Teams Webhook)  
- **Manipulação de Dados:** Pandas, PySpark DataFrames

## 📌 **Benefícios do Validador**  
✅ **Automação do processo de validação**, evitando inconsistências nos dashboards.  
✅ **Identificação de outliers em tempo real**, reduzindo necessidade de correções manuais.  
✅ **Integração direta com Microsoft Teams**, facilitando a comunicação da equipe.  
✅ **Flexível e escalável**, podendo ser ajustado para outros cenários.  

---

### 🚀 **Como Usar**  
1️⃣ Configure um **webhook** do Microsoft Teams para receber as notificações.  
2️⃣ Adapte a **consulta SQL** conforme a base de dados utilizada.  
3️⃣ Execute o código no **Databricks** ou outro ambiente compatível com PySpark. 
