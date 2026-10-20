# 🚧 Lead Radar — Business Intelligence & Lead Analysis

> **Status: Em desenvolvimento**

O **Lead Radar** é um projeto de **Business Intelligence desenvolvido em Power BI** para análise geográfica de empresas e identificação de oportunidades de prospecção comercial.


O Lead Radar foi pensado a partir de uma pergunta:

> **Como transformar informações sobre empresas de uma determinada região em oportunidades de análise e prospecção?**

A proposta é transformar dados de estabelecimentos, localização e informações comerciais em uma solução visual para **explorar mercados, comparar empresas e futuramente priorizar leads de acordo com critérios definidos**.

> 📌 Este projeto ainda está em desenvolvimento. Novas análises, indicadores e funcionalidades serão adicionados durante sua evolução.

## 🎯 Objetivo

O projeto busca responder perguntas como:

- Quantas empresas existem em determinada região?
- Quais categorias possuem maior presença?
- Como os estabelecimentos estão distribuídos geograficamente?
- Quais empresas possuem website?
- Quais possuem telefone?
- Quais apresentam melhores avaliações?
- Quais possuem maior quantidade de avaliações?
- Onde estão concentradas determinadas categorias?
- Quais empresas apresentam características que podem indicar uma oportunidade de prospecção?

O objetivo é transformar dados em **informações úteis para análise e tomada de decisão**.

## 📊 Dashboard atual

### Visão Geral

A página principal permite explorar os estabelecimentos através de filtros e apresenta informações como:

- Rating
- Total de avaliações
- Endereço e localização
- Telefone
- Website
- Categoria
- Cidade
- Horário de funcionamento
- Place ID
- Status

### Filtros

- Cidade
- Categoria
- Status
- Status do website
- Status do telefone
- Ano
- Mês
- Nome do estabelecimento

## 🗺️ Análise geográfica

Um dos diferenciais do Lead Radar é o uso de um **mapa interativo** para visualizar a distribuição dos estabelecimentos.

A análise geográfica permite explorar:

- concentração de empresas;
- distribuição por cidade;
- localização de categorias;
- comparação entre regiões;
- áreas com maior quantidade de estabelecimentos.

## 🌙 Dark Mode & ☀️ Light Mode

O projeto possui duas experiências visuais:

- **Dark Mode:** interface escura com identidade visual em roxo e destaques coloridos.
- **Light Mode:** alternativa de visualização com interface clara.

A troca entre os modos utiliza **Bookmarks do Power BI**.

# 🚀 Funcionalidade em desenvolvimento: Lead Score

Uma das próximas etapas é criar um **Lead Score de 0 a 100** para auxiliar na priorização dos estabelecimentos.

A primeira versão considera critérios como:

| Critério | Pontuação |
|---|---:|
| Não possui website | +30 |
| Não possui telefone | +20 |
| Rating ≥ 4,0 | +25 |
| Mais de 100 avaliações | +25 |
| **Máximo** | **100** |

A classificação planejada é:

- 🟢 **80–100 — Alta oportunidade**
- 🟡 **50–79 — Média oportunidade**
- 🔴 **0–49 — Baixa oportunidade**

> ⚠️ A metodologia ainda está em desenvolvimento e poderá ser ajustada conforme a evolução da análise e dos critérios de negócio.

## 🛠️ Tecnologias

- **Power BI** — dashboard, modelagem e visualizações
- **Power Query** — tratamento e transformação dos dados
- **DAX** — medidas e cálculos, incluindo o Lead Score
- **Visualização geográfica** — análise baseada em localização
- **Bookmarks** — alternância entre Dark Mode e Light Mode

## 📚 Principais aprendizados

- Business Intelligence
- Power BI
- Power Query
- DAX
- Modelagem de dados
- Análise exploratória
- Análise geográfica
- Criação de KPIs
- Visualização de dados
- UX/UI para dashboards
- Filtros e interações
- Transformação de dados em informações de negócio
- Definição de métricas orientadas a objetivos

## 📷 Preview

As imagens do dashboard serão adicionadas conforme o projeto evoluir.

Versão Dark
<img width="1771" height="984" alt="image" src="https://github.com/user-attachments/assets/4427036f-617c-409d-807c-31f70dd031f8" />

Versão Light
<img width="1756" height="982" alt="image" src="https://github.com/user-attachments/assets/3885cfe0-5496-41f5-adff-b482d60ac466" />


## ⚠️ Observação sobre os dados

Este projeto possui finalidade **educacional e de portfólio**.

Os dados representam informações de estabelecimentos utilizadas para demonstrar técnicas de tratamento, análise, modelagem e visualização.

A utilização de informações disponíveis no Google Maps não significa necessariamente que este projeto represente uma integração oficial ou direta com a API do Google Maps.

## 🚧 Status

**Em desenvolvimento**

O foco das próximas versões será:

1. desenvolvimento e refinamento do **Lead Score**;
2. criação de uma página para **análise e priorização de leads**;
3. criação de uma página de **análise de mercado**;
4. aprimoramento da análise geográfica;
5. melhorias de UX/UI;
6. documentação do tratamento e da modelagem.

## 👨‍💻 Sobre o projeto

O **Lead Radar** faz parte do meu portfólio de projetos de **Dados e Business Intelligence**.

A proposta é demonstrar minha capacidade de trabalhar com dados desde o tratamento e modelagem até a construção de dashboards interativos e métricas orientadas a problemas de negócio.

> **Projeto em desenvolvimento — novas funcionalidades e melhorias serão adicionadas ao longo do processo.**
