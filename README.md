# 📦 BI Logística

> Painel de Business Intelligence para acompanhamento e análise de indicadores logísticos: entregas, custos, prazos e desempenho operacional.

<!-- EDITE: ajuste a frase acima com o objetivo real do seu projeto -->

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![BI](https://img.shields.io/badge/BI-Power%20BI-F2C811)
<!-- EDITE: troque "Power BI" pela ferramenta que você usa (Tableau, Looker Studio, Metabase, Python...) -->

---
<iframe title="Analise_Logistica" width="100%" height="600"
  src="https://app.powerbi.com/view?r=eyJrIjoiNjk3OGFiMGMtYjM5Yi00ZWZlLTgzYmQtMDE2ZmQxMzQ0NDA5IiwidCI6IjFkYjljZTMzLWQ0MGEtNDQzMi04MGIxLWViZDM0NGNlYWFmMCJ9"
  frameborder="0" allowFullScreen="true"></iframe>

## 📌 Sobre o projeto

Descreva aqui, em 3 a 5 linhas:

- O que o projeto faz
- Para quem ele foi feito (gestores, time de operações, portfólio...)
- Qual a origem dos dados (planilhas, banco de dados, dataset público, dados simulados)

## 🎯 Problema de negócio

Explique qual pergunta ou dor o dashboard resolve. Exemplos:

- Quais rotas ou transportadoras concentram mais atrasos?
- Quanto a empresa gasta com frete por região?
- Como está a taxa de entregas no prazo ao longo do tempo?

## 📊 Indicadores (KPIs)

| Indicador | Descrição | Fórmula / Regra |
|---|---|---|
| OTIF (On Time In Full) | % de entregas no prazo e completas | Entregas OTIF ÷ Total de entregas |
| Lead time médio | Tempo médio entre pedido e entrega | Média (data entrega − data pedido) |
| Custo de frete por pedido | Gasto logístico médio por pedido | Custo total de frete ÷ Nº de pedidos |
| Taxa de devolução | % de pedidos devolvidos | Pedidos devolvidos ÷ Total de pedidos |
| Taxa de atraso | % de entregas fora do prazo | Entregas atrasadas ÷ Total de entregas |

<!-- EDITE: mantenha apenas os KPIs que existem no seu projeto -->

## 🛠 Tecnologias

- **Visualização:** Power BI *(ou a ferramenta que você usou)*
- **Tratamento de dados:** Power Query / Python (pandas) / SQL
- **Modelagem:** Modelo estrela (fato + dimensões)
- **Versionamento:** Git e GitHub


2. Abra o arquivo do dashboard na pasta `dashboard/` com a ferramenta de BI utilizada.
3. Se necessário, atualize o caminho da fonte de dados (`data/`) nas configurações da fonte.
4. Clique em **Atualizar** para carregar os dados.

**Pré-requisitos:**

- Power BI Desktop (versão atual) *(ou ferramenta equivalente)*
- Python 3.x, caso use os notebooks

## 🖼 Prévia do dashboard

![Dashboard Logística](images/Dash_Logistica.png)

## 💡 Principais insights

- Insight 1: descreva um achado relevante dos dados (ex.: "a região X concentra 40% dos atrasos").
- Insight 2: ...
- Insight 3: ...

## 🚀 Próximos passos

- [ ] Automatizar a atualização dos dados
- [ ] Adicionar análise de custo por transportadora
- [ ] Criar visão de previsão de demanda

## 👤 Autor

**Kayky Pramos**

- GitHub: [@KaykyPramoshttps](https://github.com/KaykyPramoshttps)
- LinkedIn: *adicione seu link*
