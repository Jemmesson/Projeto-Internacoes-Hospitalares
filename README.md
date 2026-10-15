# 🏥 Análise de Internações Hospitalares | Python + Power BI

## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar dados de internações hospitalares, explorando indicadores relacionados ao perfil dos pacientes, faturamento, condições médicas e seguradoras.

O desenvolvimento envolveu desde o **tratamento dos dados com Python** até a criação de um **dashboard interativo no Power BI**, aplicando conceitos de análise, modelagem dimensional e visualização de dados.

## 🛠️ Ferramentas Utilizadas

- **Python e Pandas:** exploração, limpeza e tratamento dos dados.
- **VS Code / Jupyter:** desenvolvimento do código.
- **Power Query:** transformação e padronização dos dados.
- **Power BI:** modelagem e construção dos dashboards.
- **DAX:** criação de medidas e indicadores.

## 📂 Fonte dos Dados

Dataset: [Healthcare Dataset — Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

A base original contém **55.500 registros** de internações hospitalares.

## 🐍 Tratamento dos Dados

No Python, foram realizadas as seguintes etapas:

- Verificação de valores nulos e duplicados.
- Renomeação de colunas e correção dos tipos de dados.
- Conversão das datas.
- Investigação e remoção de **534 registros duplicados**.
- Criação da classificação etária: menor de idade, adulto e idoso.
- Exportação dos dados tratados em CSV.

Após o tratamento, a base passou a conter **54.966 registros**.

No Power Query, foram realizadas padronizações, correções de valores monetários e preparação das tabelas para a modelagem.

## 🔗 Modelagem Dimensional

Foi desenvolvido um **modelo estrela**, composto por uma tabela fato e quatro dimensões:

| Tabela | Finalidade |
|---|---|
| FInternacoes | Registros e indicadores das internações |
| DHospital | Informações dos hospitais |
| DCondicao_Medica | Condições médicas |
| DSeguradora | Seguradoras |
| DTipo_Admissao | Tipos de admissão |

Os relacionamentos foram configurados como **1:N**, permitindo análises integradas.

## 📊 Dashboard Interativo

O relatório foi dividido em três páginas:

**1. Visão Geral do Hospital**

Indicadores de internações, faturamento, idade média, tempo médio de internação e evolução dos registros.

**2. Análise dos Pacientes**

Distribuição das internações por gênero, faixa etária, tipo sanguíneo e condição médica, além do tempo médio de internação por condição.

**3. Análise das Seguradoras**

Participação das seguradoras, faturamento, volume de internações e ticket médio por internação.

Foram utilizadas medidas DAX, segmentações de dados e navegação entre páginas.

## 📈 Principais Indicadores

| Indicador | Resultado |
|---|---:|
| Total de internações | 54.966 |
| Faturamento registrado | Aproximadamente 1,4 bilhão |
| Idade média | 52 anos |
| Tempo médio de internação | 15,5 dias |
| Condições médicas | 6 |
| Seguradoras | 5 |

*Os valores financeiros são provenientes do dataset. A apresentação em R$ não representa conversão cambial.*

## 🎨 Design e Visualização

O dashboard utiliza uma identidade visual inspirada no ambiente hospitalar, priorizando organização, clareza e facilidade de navegação.

O layout foi desenvolvido no Power BI com apoio de referências visuais geradas por inteligência artificial e adaptadas ao projeto.

## 💡 Aprendizados

Este projeto permitiu colocar em prática conhecimentos de **Python, Pandas, Power Query, modelagem estrela, DAX e Power BI**.

O principal aprendizado foi compreender a importância de investigar os dados antes de tratá-los, validar as transformações e escolher indicadores que realmente contribuam para a análise.

**Limitação:** a base não possui identificadores únicos confiáveis de pacientes e internações, o que exige cuidado na interpretação de registros repetidos.

---

**Projeto desenvolvido para fins educacionais e composição de portfólio em Análise de Dados.**

<img width="1271" height="713" alt="Captura de tela 2026-10-15 130250" src="https://github.com/user-attachments/assets/bfca3b8a-825c-4ff6-ba62-9544de272305" />
<img width="1265" height="712" alt="2" src="https://github.com/user-attachments/assets/84a10d99-8f56-415d-ad9d-496361259e66" />
<img width="1269" height="713" alt="3" src="https://github.com/user-attachments/assets/0705a4ca-8e12-423c-bb2b-0d3e9bc6c5e9" />



