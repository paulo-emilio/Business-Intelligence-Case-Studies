<p align="center">

# Governança Executiva da Implantação SAP

### Business Intelligence Case Study

> **Como automatizei a governança de um projeto SAP utilizando Power BI, Python e Microsoft Project.**

<br>

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Microsoft Project](https://img.shields.io/badge/Microsoft_Project-107C41?style=for-the-badge&logo=microsoft&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)

</p>

---

# 📌 Visão Geral

> **Projeto desenvolvido durante a implantação do SAP na CostaFoods Brasil.**

Durante um projeto de implantação SAP, a diretoria precisava acompanhar semanalmente o andamento das atividades, riscos, orçamento, capacidade das equipes e evolução do cronograma.

Na prática, esse processo era altamente manual.

Os PMOs exportavam informações do Microsoft Project para Excel, consolidavam diversos arquivos manualmente e montavam apresentações em PowerPoint para cada reunião executiva.

Além do tempo gasto, qualquer atualização exigia repetir todo o processo.

Para resolver esse problema desenvolvi uma plataforma analítica responsável por automatizar a consolidação das informações e disponibilizar dashboards executivos atualizados para acompanhamento do projeto.

---

# 🎯 O Desafio

A implantação envolvia centenas de atividades distribuídas entre diferentes frentes de trabalho, consultorias, fornecedores e áreas internas.

Alguns desafios enfrentados eram:

- Atualização manual dos Status Reports;
- Exportações frequentes do Microsoft Project;
- Consolidação manual em Excel;
- Ausência de histórico consolidado;
- Alto tempo gasto para preparação das reuniões executivas;
- Baixa visibilidade sobre riscos e capacidade das equipes.

---

# 💡 A Solução

Foi desenvolvida uma plataforma completa de Business Intelligence composta por:

- Dashboards executivos em Power BI;
- Automações em Python para coleta dos dados;
- Consolidação automática das informações;
- Base histórica da implantação;
- Indicadores estratégicos;
- Monitoramento em tempo real da evolução do projeto.

A solução passou a centralizar todas as informações relevantes da implantação em um único ambiente.

---

# 🏗 Arquitetura da Solução

> *(Diagrama será inserido aqui.)*

```text
Microsoft Project
        │
        ▼
Automação em Python
(download • tratamento • consolidação • backup)
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
 └── Dashboards Executivos
```

---

# 👨‍💻 Minha Atuação

Durante aproximadamente um ano fui responsável por toda a camada analítica do projeto.

### Levantamento de requisitos

- Definição dos indicadores junto aos PMOs e GMOs;
- Entendimento das necessidades executivas;
- Evolução contínua dos dashboards.

### Desenvolvimento

- Modelagem dos dados;
- Construção dos dashboards em Power BI;
- Desenvolvimento das automações em Python;
- Consolidação da base histórica;
- Publicação e manutenção dos relatórios.

---

# 📊 Dashboards Desenvolvidos

## 📈 Status Geral

> *(Imagem será inserida aqui.)*

Dashboard executivo utilizado para acompanhar a evolução geral da implantação, consolidando indicadores estratégicos como progresso do projeto, curva S, SPI e evolução por fornecedor.

---

## 👥 Capacity

> *(Imagem será inserida aqui.)*

Painel responsável por monitorar a distribuição das horas entre os recursos do projeto, identificando sobrecarga, disponibilidade e conflitos de alocação.

---

## 🚀 Cutover

> *(Imagem será inserida aqui.)*

Dashboard utilizado durante a fase crítica de Cutover para acompanhar atividades concluídas, atrasadas, em andamento e indicadores da virada operacional.

---

## ⚠️ Book de Riscos

> *(Imagem será inserida aqui.)*

Painel para acompanhamento dos riscos da implantação, permitindo analisar impacto, probabilidade, responsáveis, fornecedores e planos de ação.

---

# ⚙️ Automação

> *(Imagem da automação será inserida aqui.)*

Como não havia integração direta entre Microsoft Project e Power BI, desenvolvi uma automação em Python responsável por:

- baixar automaticamente os arquivos do Microsoft Project;
- consolidar todas as informações em uma base única;
- manter o histórico completo da implantação;
- gerar backups automáticos;
- alimentar o modelo analítico utilizado pelos dashboards.

Essa automação eliminou praticamente todo o processo manual anteriormente realizado pelos PMOs.

---

# 📈 Resultados

Após a implantação da solução foi possível:

✅ Eliminar a consolidação manual das informações;

✅ Automatizar a atualização dos dashboards;

✅ Criar uma base histórica da implantação;

✅ Reduzir significativamente o tempo de preparação das reuniões executivas;

✅ Disponibilizar indicadores atualizados para PMOs, GMOs, gerentes e diretoria;

✅ Aumentar a visibilidade sobre cronograma, riscos, capacidade e evolução do projeto.

---

# 🛠 Stack Tecnológica

- Power BI
- Python
- Microsoft Project
- Excel
- Power Query
- DAX

---

# 📚 Principais Aprendizados

Este projeto reforçou que Business Intelligence vai muito além da construção de dashboards.

Grande parte do valor entregue esteve na organização dos dados, automação dos processos e transformação de informações dispersas em indicadores capazes de apoiar decisões estratégicas durante uma das fases mais críticas da empresa.

---

# 🔒 Confidencialidade

Este estudo de caso foi adaptado para fins de portfólio.

Os dashboards apresentados utilizam dados anonimizados para preservar a confidencialidade do projeto original e das informações da empresa.

---

## 👤 Autor

**Paulo Oliveira**

Analista de BI | Analytics

- LinkedIn: https://www.linkedin.com/in/paulo-emilio
- Portfólio: https://paulo-emilio.github.io
- GitHub: https://github.com/paulo-emilio
