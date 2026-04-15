# 📊 Financial Data Reconciliation Tool

![Status](https://img.shields.io/badge/status-active-success)
![Type](https://img.shields.io/badge/project-real_world-blue)
![Tech](https://img.shields.io/badge/tech-JavaScript%20%7C%20HTML%20%7C%20CSS-yellow)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 🧠 Visão Geral

Este projeto foi desenvolvido para resolver um problema real de negócio envolvendo um processo manual, repetitivo e crítico de geração de relatórios financeiros.

O fluxo consistia em consolidar e validar dados provenientes de múltiplas fontes independentes para gerar um relatório final de cobrança.

Com o aumento da frequência de execução (de semanal para diária), o processo manual tornou-se inviável.

Esta ferramenta automatiza todo o fluxo — desde a importação dos dados até a geração do relatório final — aumentando a eficiência e a confiabilidade.

---

## 🚨 O Problema

O processo original envolvia:

- Extração manual de relatórios de diferentes sistemas  
- Cruzamento manual de dados financeiros e operacionais  
- Identificação de itens já pagos ou provisionados  
- Validação de inconsistências  
- Geração manual de relatório final  

### Impactos:

- ⏱️ Horas de trabalho por execução  
- 📉 Alto risco de erro humano  
- 🔍 Baixa visibilidade de inconsistências  
- ⚠️ Falta de escalabilidade  

---

## 💡 A Solução

Uma aplicação web **100% client-side** que automatiza o processo de reconciliação de dados.

### Principais funcionalidades:

- 📂 Importação de arquivos (.xlsx / .csv)
- ⚙️ Normalização e tratamento de dados
- 🔄 Cruzamento entre múltiplas fontes
- 🚫 Exclusão automática de itens pagos ou previstos
- 🚨 Identificação de inconsistências
- 📊 Interface interativa para análise
- 📤 Exportação de relatório em Excel

---

## 🔄 Como Funciona

### 1. 📥 Upload dos dados
O usuário importa arquivos exportados de diferentes sistemas.

### 2. ⚙️ Processamento
O sistema:
- Padroniza os dados  
- Identifica documentos  
- Aplica regras de negócio  

### 3. 🔍 Análise
- Detecta inconsistências  
- Organiza os dados  
- Permite validação visual  

### 4. 📤 Exportação
- Gera arquivo Excel estruturado  
- Separado por categorias  
- Pronto para uso  

---

## 📥 Fontes de Dados

O sistema trabalha com quatro fontes principais:

### 🟦 Sistema Financeiro (Contas a Receber)

Base de dados com todos os valores registrados como a receber.

Inclui:
- Identificadores de documentos  
- Valores  
- Datas  

👉 Representa o que **deve ser cobrado**.

---

### 🟨 Portal de Pagamentos — Títulos Compensados

Registros de pagamentos já realizados.

👉 Utilizado para:
- Excluir itens já pagos  
- Evitar cobranças duplicadas  

---

### 🟨 Portal de Pagamentos — Títulos Abertos

Valores já programados para pagamento.

👉 Utilizado para:
- Evitar cobranças indevidas  
- Refinar a análise  

---

### 🟥 Sistema Operacional

Base de dados de origem operacional.

Inclui:
- Documentos gerados  
- Status  
- Valores  

👉 Utilizado para:
- Validar dados financeiros  
- Detectar inconsistências  

---

## 📊 Funcionalidades

- Upload múltiplo de arquivos
- Interface com drag & drop
- Dashboard com indicadores
- Filtros dinâmicos
- Separação por categoria
- Destaque de inconsistências
- Exportação automatizada

---

## 📈 Resultados

- ⏱️ Redução de horas para minutos  
- 📉 Redução de erros manuais  
- 🔍 Maior visibilidade de inconsistências  
- ⚡ Viabilização de execução diária  
- 📊 Aumento da confiabilidade dos dados  

---

## 🛠️ Tecnologias Utilizadas

- HTML5  
- CSS3  
- JavaScript (Vanilla)  
- SheetJS (manipulação de Excel no browser)  

---

## 🧠 O Que Este Projeto Demonstra

- Resolução de problema real de negócio  
- Manipulação e tratamento de dados complexos  
- Cruzamento de múltiplas fontes  
- Aplicação de regras de negócio  
- Criação de ferramentas com impacto operacional  

---

## ⚠️ Disclaimer

> Os dados utilizados neste projeto foram modificados e anonimizados para preservar a confidencialidade das informações originais.  
>  
> Identificadores (como notas fiscais e documentos), valores, nomes de empresas e demais dados sensíveis foram artificialmente gerados ou alterados.  
> A estrutura e a lógica do processo foram mantidas para fins de demonstração técnica.

---

## 🚀 Possíveis Evoluções

- Integração com APIs  
- Automação completa do fluxo  
- Histórico de execuções  
- Auditoria e rastreabilidade  
- Deploy como aplicação interna  

---

## 🖼️ Screenshots

Abaixo está o fluxo completo da aplicação, desde a importação dos dados até a geração do relatório final:

---

### 📥 1. Importação de Arquivos

Interface para upload dos dados provenientes de múltiplas fontes.

<img src="https://github.com/user-attachments/assets/0c9cabbc-3f14-422a-a270-b37839ee4153" alt="Importação de arquivos" width="100%" />

---

### 📂 2. Arquivos Carregados

Visualização dos arquivos importados e validação inicial dos dados.

<img src="https://github.com/user-attachments/assets/73d02aaf-9595-46f3-87ff-e88a86d60e4a" alt="Arquivos importados" width="100%" />

---

### 📊 3. Análise e Revisão

Tela principal de análise com:
- Separação por categorias  
- Indicadores gerais  
- Identificação de inconsistências  

<img src="https://github.com/user-attachments/assets/cd815e7b-b754-4d97-a3aa-7acb54c4ccf7" alt="Revisão e análise dos dados" width="100%" />

---

### 📤 4. Exportação do Relatório

Geração do arquivo final estruturado para envio.

<img src="https://github.com/user-attachments/assets/aa1ff3fb-df0f-48dd-8727-34c00786da48" alt="Exportação final" width="100%" />

---

### 🔍 5. Detalhamento dos Dados

Visualização detalhada com filtros e validações aplicadas.

<img src="https://github.com/user-attachments/assets/112206f8-11f3-42d1-92b4-660f95cf035f" alt="Detalhamento dos dados" width="100%" />

---

## 📎 Licença

Este projeto está sob a licença MIT — sinta-se livre para utilizar como base para estudos e melhorias.

---

## 👨‍💻 Autor

Desenvolvido como estudo de caso aplicado à automação de processos financeiros e análise de dados.
