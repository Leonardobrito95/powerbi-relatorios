# 📊 Portfólio de Relatórios Power BI

> Catálogo de **50+ relatórios e modelos analíticos** em Power BI desenvolvidos para a operação de uma ISP regional, cobrindo Call Center, Campo, Comercial, Estoque, Governança e Infraestrutura.

![Power BI](https://img.shields.io/badge/Power_BI-modelagem_&_DAX-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-medidas-blue)
![Power Query](https://img.shields.io/badge/Power_Query-ETL-376C2E)

---

## 🔒 Sobre este repositório

Arquivos `.pbix` carregam **dados de clientes e strings de conexão embutidos**, então não são versionados aqui (estão no `.gitignore`). Este repositório **documenta** o trabalho de BI — escopo, fontes e modelagem de cada relatório. Demonstrações com dados reais são apresentadas sob solicitação.

## 🧱 Fontes e modelagem

Os relatórios consomem o ERP **IXC** (MySQL), bases analíticas em **PostgreSQL**, planilhas operacionais e o VoIP. O trabalho envolve:

- **Power Query (M)** — extração e tratamento das fontes, modelagem em estrela.
- **DAX** — medidas de negócio (inadimplência, ticket médio, fidelidade, SLA, reincidência, comissões).
- **Painéis de TV** — versões otimizadas para exibição contínua em monitores na operação.

---

## 📁 Relatórios por área

### ☎️ Call Center & Cobrança (17 relatórios)
Gestão financeira, inadimplência e performance do atendimento.
- Gestão Financeira · Inadimplência · Lista SPC
- Análise de boletos prescritos/cancelados que geraram remessa
- Análise de ticket médio de cancelados · Análise de fidelidade
- Análise de desistência precoce · Reincidência de atendimento
- Acompanhamento de recebimentos (cobrança IA) · Renegociação
- Monitoria individual de conformidade · Painel TV · Assinatura de contratos
- Relatórios diários, gerenciais e do centro de soluções · IXC unificado

### 🔧 Campo (9 relatórios)
Operação de campo, técnicos e ordens de serviço.
- Acompanhamento de serviços · Análise de instalação e cancelamento
- Clientes campo · Auditorias · Visita improdutiva
- CLTs e comissão de terceirizados · Consulta de atendimentos
- Projeto de organização de caixas (CTOs)

### 💼 Comercial (8 relatórios)
Acompanhamento de vendas e comissões.
- Relatório de vendas · Acompanhamento de vendas (BSB) · Relatórios de vendas (TV)
- Comissões · Relatórios diários · Chamados de TI

### 📦 Estoque (7 relatórios)
Patrimônio, movimentação e RMA.
- Comodato e patrimônio · Relatórios de comodato
- Movimentação de equipamentos e produtos
- Compras × NF · Documento auxiliar de RMA

### 🛡️ Governança (5 relatórios)
Indicadores executivos e controle de acesso.
- Relatório de login ativo · Inadimplência
- Clientes CAV e CANV

### 🌐 Infraestrutura (3 relatórios)
Saúde da rede de fibra óptica.
- OTDR Preventivo · Acompanhamento de estrutura
- (relacionado ao [otdr-dashboard](../otdr-dashboard) deste portfólio)

### 🧩 Modelos semânticos
Camadas semânticas reutilizáveis para múltiplos relatórios.
- Contrato por região · Geolocalização de atendimentos · OTDR Preventivo

---

## 💡 Destaques

- **Cobrança com IA** — relatório de acompanhamento de recebimentos integrado à régua de cobrança automatizada.
- **Painéis de TV** — dashboards de Call Center e Comercial em exibição contínua na operação.
- **OTDR Preventivo** — modelo que antecipa manutenção de fibra, par do dashboard de código [otdr-dashboard](../otdr-dashboard).
- **Modelos semânticos reaproveitáveis** — camadas centrais que alimentam vários relatórios sem duplicar lógica.

---

<sub>Relatórios desenvolvidos para a operação de uma ISP regional. Arquivos com dados reais não são publicados.</sub>
