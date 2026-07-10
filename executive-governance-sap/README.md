<p align="center">

# Governança Executiva da Implantação SAP

### Business Intelligence Case Study

Plataforma analítica desenvolvida para apoiar a governança de um projeto de implantação SAP através de Business Intelligence, automação de processos e dashboards executivos.

<br>

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Microsoft Project](https://img.shields.io/badge/Microsoft_Project-107C41?style=for-the-badge&logo=microsoft&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)

</p>

---

# 📖 Visão Geral

Durante a implantação do SAP, o acompanhamento executivo do projeto dependia da consolidação manual de informações provenientes do Microsoft Project.

Sem integração entre as ferramentas utilizadas, os PMOs precisavam exportar arquivos, consolidar dados em planilhas Excel e montar apresentações em PowerPoint para as reuniões executivas.

Além do elevado esforço operacional, não existia uma visão única da implantação, histórico consolidado ou atualização automatizada das informações.

Para solucionar esse cenário, desenvolvi uma plataforma de Business Intelligence responsável por automatizar a coleta dos dados, manter o histórico da implantação e disponibilizar dashboards executivos para acompanhamento do projeto.

---

# 🎯 O Problema

O processo utilizado até então apresentava diversos desafios.

| Antes | Depois |
|--------|---------|
| Consolidação manual | Atualização automatizada |
| Exportação do Microsoft Project | Pipeline em Python |
| PowerPoint atualizado manualmente | Dashboards em Power BI |
| Histórico descentralizado | Base histórica consolidada |
| Alto esforço operacional | Informações disponíveis em segundos |

---

# 🏗 Arquitetura da Solução

> *(Diagrama será adicionado na próxima versão)*

```
Microsoft Project
        │
        ▼
Automação Python
(download + consolidação + backup)
        │
        ▼
Base Histórica
        │
        ▼
Power BI
        │
 ├── Status Geral
 ├── Capacity
 ├── Cutover
 ├── Book de Riscos
 └── Indicadores Executivos
```

---

# 👨‍💻 Minha Atuação

Durante aproximadamente um ano fui responsável por:

- Levantamento de requisitos junto aos PMOs e GMOs;
- Estruturação da solução analítica;
- Modelagem dos dados;
- Desenvolvimento dos dashboards em Power BI;
- Desenvolvimento das automações em Python;
- Consolidação da base histórica;
- Documentação técnica;
- Evolução contínua da plataforma.

---

# 📊 Dashboards

## Status Geral

> `img/status-geral.png`

Dashboard executivo utilizado para acompanhamento geral da implantação, consolidando indicadores estratégicos do projeto em uma única visão.

---

## Capacity

> `img/capacity.png`

Monitoramento da capacidade das equipes, distribuição das atividades e disponibilidade dos recursos envolvidos na implantação.

---

## Cutover

> `img/cutover.png`

Painel utilizado durante a fase crítica de Cutover para acompanhamento das atividades planejadas, execução e andamento da virada operacional.

---

## Gestão de Riscos

> `img/riscos.png`

Dashboard para monitoramento dos riscos do projeto, permitindo acompanhar impacto, probabilidade, responsáveis e planos de ação.

---

# ⚙ Automação

> `img/python.png`

Como não havia integração nativa entre Microsoft Project e Power BI, desenvolvi uma automação em Python responsável por:

- baixar automaticamente os arquivos exportados do Project;
- consolidar todas as informações;
- manter uma base histórica da implantação;
- gerar backups automáticos;
- alimentar a camada analítica utilizada pelo Power BI.

Essa automação eliminou praticamente todo o processo manual realizado anteriormente pelos PMOs.

---

# 🚀 Resultados

A solução passou a fornecer uma visão única da implantação para PMOs, GMOs, gerentes e diretoria.

Entre os principais ganhos obtidos estavam:

- Centralização das informações do projeto;
- Atualização automatizada dos indicadores;
- Redução significativa do trabalho manual;
- Histórico consolidado da implantação;
- Apoio às reuniões executivas;
- Maior visibilidade sobre cronograma, capacidade e riscos.

---

# 🛠 Tecnologias

- Power BI
- Python
- Microsoft Project
- Excel
- DAX
- Power Query

---

# 📚 Principais Aprendizados

Esse projeto reforçou que Business Intelligence vai muito além da construção de dashboards.

O maior valor entregue esteve na automação dos processos, organização dos dados e disponibilização de informações confiáveis para apoiar decisões estratégicas durante uma das fases mais importantes da empresa.

---

# 🔒 Confidencialidade

Este estudo de caso foi adaptado para fins de portfólio.

Algumas informações, imagens e identificações foram anonimizadas para preservar a confidencialidade do projeto original.
