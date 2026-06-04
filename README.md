# 🎬 Netflix Analytics - Análise de Dados de Streaming

## 📌 Sobre o Projeto

Este foi o meu **primeiro projeto completo de portfólio** na área de dados. O objetivo foi praticar todo o fluxo de análise: desde a limpeza dos dados (ETL) até a criação de um dashboard interativo no Power BI.

⚠️ **Importante:** Os dados utilizados foram **GERADOS POR INTELIGÊNCIA ARTIFICIAL** exclusivamente para fins de estudo e prática. Não se tratam de dados reais da Netflix.

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Finalidade |
| :--- | :--- |
| **Python (Pandas)** | Limpeza e transformação dos dados |
| **Power BI Desktop** | Criação do dashboard e visualizações |
| **Git/GitHub** | Versionamento e portfólio |

---

## 🐍 Etapa 1 - ETL com Python (Pandas)

Nesta etapa, realizei todo o processo de limpeza e transformação dos dados:

| Etapa | O que foi feito |
| :--- | :--- |
| 1 | Carregamento e exploração inicial dos dados |
| 2 | Identificação de valores negativos (-999, -10.0) |
| 3 | Substituição de valores negativos por NaN (nulos) |
| 4 | Tratamento de placeholders numéricos (99.99, 3.2878...) |
| 5 | Correção de categorias inválidas ("Desconhecido", "Unknown") |
| 6 | Padronização de nomes de países ("Reino Unido" → "UK") |
| 7 | Substituição de valores nulos pela MÉDIA das respectivas colunas |
| 8 | Exportação dos dados limpos para um novo arquivo CSV |

---

## 📊 Etapa 2 - Dashboard no Power BI

Com os dados já tratados, parti para a visualização:

- Conexão com o arquivo CSV limpo
- Criação de matriz de gasto mensal por país
- Formatação e padronização dos visuais
- Criação de métricas e indicadores
- Desenvolvimento do dashboard interativo

---

## 📈 Resultados do Estudo

Os dados simulados apontaram os seguintes mercados como maiores em receita:

| Posição | País | Receita Simulada |
| :--- | :--- | :--- |
| 🥇 1º | **USA** | R$ 289.849,90 |
| 🥈 2º | **Brasil** | R$ 163.936,40 |
| 🥉 3º | **França** | R$ 119.327,90 |

**Receita total simulada:** R$ 1.204.364,20

---

## 📊 Principais Visuais do Dashboard

| Visual | O que mostra |
| :--- | :--- |
| **Matriz de países** | Gasto mensal por país |
| **Gráfico de barras** | Comparação entre mercados |
| **Cartões** | Totais e médias |
| **Segmentadores** | Filtros interativos |

---

## 🎓 Aprendizagens

Este primeiro projeto me ensinou:

| Aprendizado | Por que é importante |
| :--- | :--- |
| **Importância da limpeza de dados** | Análise confiável começa com dados limpos |
| **Identificar e tratar valores inconsistentes** | Saber o que fazer com -999, null, "Desconhecido" |
| **ETL completo com Python/Pandas** | Extrair, Transformar e Carregar dados |
| **Visualizações profissionais com Power BI** | Transformar números em insights |
| **Storytelling com dados** | Contar a história por trás dos números |

---

## 📁 Estrutura do Repositório
