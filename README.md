# 🧩 Análise Socioeconômica dos Assistidos de uma Instituição do Terceiro Setor

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Pentaho](https://img.shields.io/badge/ETL-Pentaho-blue?style=for-the-badge&logo=data)
![Projeto Acadêmico](https://img.shields.io/badge/Projeto-Acadêmico-9cf?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Este repositório reúne os artefatos de um projeto de Business Intelligence (BI) desenvolvido para uma instituição do terceiro setor que presta atendimento a pessoas com deficiência (PcDs). O objetivo central é fornecer uma base visual clara, acessível e funcional para apoiar **tomadas de decisão estratégicas por parte de gestores e coordenadores da organização**.

---

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como Verificação de Aprendizagem para a disciplina de **Sistemas de Apoio à Decisão**, do curso de **Bacharelado em Sistemas de Informação da UFRPE/UAST**, sob orientação da **Profª Drª Ellen Souza**.

A modelagem adotada foi a **dimensional em estrela (Star Schema)** com abordagem **bottom-up**, partindo dos dados operacionais até a camada analítica.

---

## 🔄 ETL com Pentaho Data Integration (PDI)

Antes da análise no Power BI, os dados foram tratados com um processo completo de **ETL (Extração, Transformação e Carga)** utilizando o **Pentaho Data Integration (PDI)**.

### Etapas:
- Extração de dados brutos (.csv, base local);
- Tratamento de inconsistências e limpeza;
- Normalização de campos categóricos e multivalorados (como diagnósticos);
- Geração da dimensão tempo e faixas etárias;
- Carga em base relacional pronta para uso analítico.

---

## 📊 Dashboards no Power BI

O painel foi dividido em **3 páginas temáticas** com navegação via botões personalizados e design minimalista.

### 1️⃣ Perfil Quantitativo
- Quantidade de assistidos por município
- Ano de entrada, sexo, faixa etária
- Tipos de deficiência, status do cadastro

### 2️⃣ Análise Socioeconômica
- Faixa de renda familiar (baseada no salário mínimo)
- Renda per capita
- Benefícios sociais, escolaridade

### 3️⃣ Condições de Vida e Mobilidade
- Transporte até a instituição
- Estado civil, tipo de imóvel
- Vínculo empregatício e posse de veículos

---

## 🛠️ Tecnologias e Ferramentas

- ⚙️ **Pentaho Data Integration (PDI)** – ETL
- 📊 **Power BI Desktop** – Dashboards e modelagem

---

## 📌 Observações Finais

Este painel foi desenvolvido com foco em **uso interno e estratégico**, para melhorar a **tomada de decisões baseada em dados reais**.  
Toda a estrutura foi pensada para manter **clareza, acessibilidade, interatividade e performance**.

---
> 📁 Caso queira visualizar os diagramas relacionais e dimensionais e o SQL do projeto, confira a pasta `/Modelagem`.
> 📁 Caso queira visualizar os planos de carga do Pentaho, confira a pasta `/Plano de Carga`.
> 📁 Caso queira visualizar os prints do dashboard, confira a pasta `/Dashboards`.

