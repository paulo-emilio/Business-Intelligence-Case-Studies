# <p align="center">

# 

# \# Otimização de Custos de Licenciamento ERP

# 

# \### Enterprise Analytics Case Study

# 

# > Como uma plataforma analítica transformou dados de licenciamento em oportunidades de redução de custos.

# 

# <img src="imgs/banner.png" width="100%">

# 

# <br>

# 

# !\[Power BI](https://img.shields.io/badge/Power\_BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)

# !\[SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge)

# !\[Apache Airflow](https://img.shields.io/badge/Apache\_Airflow-017CEE?style=for-the-badge\&logo=apacheairflow\&logoColor=white)

# !\[PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)

# !\[MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge\&logo=mysql\&logoColor=white)

# 

# </p>

# 

# \---

# 

# \# 📌 Visão Geral

# 

# Licenças de ERP representam um dos custos recorrentes mais relevantes da área de Tecnologia.

# 

# Apesar disso, muitas organizações possuem pouca visibilidade sobre quem realmente utiliza cada tipo de licença, quais funcionalidades justificam licenças premium e onde existem oportunidades reais de otimização.

# 

# Neste projeto foi desenvolvida uma plataforma analítica capaz de consolidar dados de usuários, perfis, acessos e licenças do ERP, permitindo identificar oportunidades de redução de custos de forma objetiva e baseada em dados.

# 

# <br>

# 

# <img src="imgs/visao\_geral\_dashboards.png" width="100%">

# 

# \---

# 

# \# 🎯 O Desafio

# 

# As informações necessárias para análise estavam distribuídas entre diferentes tabelas do ERP.

# 

# A identificação de oportunidades exigia consultas manuais e cruzamento de diversos conjuntos de dados, tornando praticamente inviável uma análise recorrente.

# 

# Os principais desafios eram:

# 

# \- Baixa visibilidade sobre o uso das licenças;

# \- Dados distribuídos em diversas tabelas;

# \- Ausência de uma visão consolidada;

# \- Dificuldade para identificar licenças superdimensionadas;

# \- Pouco conhecimento sobre quais funcionalidades elevavam o custo de cada usuário.

# 

# \---

# 

# \# 💡 A Solução

# 

# Foi desenvolvida uma plataforma analítica composta por:

# 

# \- consultas SQL utilizando CTEs;

# \- pipelines de dados com Apache Airflow;

# \- arquitetura em camadas (Silver → Gold);

# \- Data Lake em PostgreSQL;

# \- DataMart em MySQL;

# \- dashboards executivos em Power BI.

# 

# A solução consolidou automaticamente todas as informações necessárias para análise de custos.

# 

# \---

# 

# \# 🏗 Arquitetura da Solução

# 

# <img src="imgs/arquitetura\_da\_solucao.png" width="100%">

# 

# A arquitetura foi estruturada em múltiplas camadas para facilitar manutenção, escalabilidade e reutilização dos dados.

# 

# Fluxo da solução:

# 

# ERP

# 

# ↓

# 

# Consultas SQL

# 

# ↓

# 

# Apache Airflow

# 

# ↓

# 

# Silver (PostgreSQL)

# 

# ↓

# 

# Gold

# 

# ↓

# 

# DataMart (MySQL)

# 

# ↓

# 

# Power BI

# 

# \---

# 

# \# ⚙️ Pipeline de Dados

# 

# As transformações foram desenvolvidas utilizando consultas SQL complexas baseadas em CTEs.

# 

# O Apache Airflow era responsável por:

# 

# \- executar múltiplas DAGs;

# \- atualizar as tabelas Silver;

# \- consolidar as tabelas Gold;

# \- alimentar automaticamente o DataMart;

# \- manter a atualização recorrente dos dashboards.

# 

# A atualização ocorria automaticamente a cada duas horas.

# 

# <img src="imgs/automacao.png" width="100%">

# 

# \---

# 

# \# 👨‍💻 Minha Atuação

# 

# Fui responsável por toda a construção da solução analítica.

# 

# Principais atividades desenvolvidas:

# 

# \- entendimento das regras de licenciamento junto ao time BASIS;

# \- levantamento dos requisitos;

# \- desenvolvimento das consultas SQL;

# \- modelagem das camadas Silver e Gold;

# \- estruturação do DataMart;

# \- desenvolvimento dos dashboards em Power BI;

# \- validação dos indicadores;

# \- publicação da solução.

# 

# \---

# 

# \# 📊 Dashboards Desenvolvidos

# 

# \## Visão Executiva

# 

# Dashboard responsável por apresentar uma visão consolidada dos custos de licenciamento do ERP.

# 

# Principais indicadores:

# 

# \- custo total das licenças;

# \- usuários por categoria;

# \- custos por área;

# \- custos por perfil;

# \- usuários ativos;

# \- usuários inativos;

# \- oportunidades de redução.

# 

# <img src="imgs/dashboard\_executivo.png" width="100%">

# 

# \---

# 

# \## Oportunidades de Redução

# 

# Dashboard desenvolvido para identificar quais usuários possuíam maior potencial de redução de custos.

# 

# A análise considerava:

# 

# \- funcionalidades utilizadas;

# \- categoria da licença;

# \- custo individual;

# \- possibilidade de migração para licenças mais econômicas.

# 

# <img src="imgs/oportunidades.png" width="100%">

# 

# \---

# 

# \## Análise por Área

# 

# Painel utilizado para identificar quais departamentos concentravam maior custo com licenciamento.

# 

# Também permitia priorizar iniciativas de otimização por área de negócio.

# 

# <img src="imgs/areas.png" width="100%">

# 

# \---

# 

# \# 💰 Principal Insight

# 

# O projeto demonstrou que o maior custo nem sempre estava relacionado à quantidade de funcionalidades utilizadas.

# 

# Em muitos casos, uma única funcionalidade específica era suficiente para enquadrar um usuário em uma categoria de licença significativamente mais cara.

# 

# Essa visibilidade permitia identificar oportunidades de otimização muito mais precisas, direcionando os esforços para os usuários com maior potencial de redução de custos.

# 

# \---

# 

# \# 📦 Entregáveis

# 

# \- Plataforma analítica de licenciamento;

# \- Arquitetura Silver → Gold;

# \- DataMart para BI;

# \- Dashboards executivos;

# \- Dashboards analíticos;

# \- Classificação automática das oportunidades de redução;

# \- Indicadores estratégicos para gestão do licenciamento.

# 

# \---

# 

# \# 📈 Resultados

# 

# A solução passou a fornecer uma visão completa do licenciamento do ERP.

# 

# Entre os principais benefícios obtidos:

# 

# \- centralização das informações;

# \- eliminação das análises manuais;

# \- atualização automática dos dados;

# \- identificação das maiores oportunidades de redução de custos;

# \- priorização das iniciativas com maior retorno financeiro;

# \- apoio à tomada de decisão baseada em dados.

# 

# \---

# 

# \# 🛠 Stack Tecnológica

# 

# \### Analytics

# 

# \- Power BI

# \- DAX

# \- Power Query

# 

# \### Engenharia de Dados

# 

# \- SQL

# \- Apache Airflow

# 

# \### Banco de Dados

# 

# \- PostgreSQL

# \- MySQL

# 

# \### Arquitetura

# 

# \- Silver Layer

# \- Gold Layer

# \- Data Lake

# \- DataMart

# 

# \---

# 

# \# 📚 Principais Aprendizados

# 

# Mais do que construir dashboards, este projeto demonstrou como uma arquitetura de dados bem estruturada pode transformar informações operacionais em oportunidades reais de redução de custos.

# 

# O maior valor entregue não foi a visualização dos dados, mas a capacidade de direcionar decisões estratégicas sobre o licenciamento do ERP com base em evidências concretas.

# 

# \---

# 

# \# 🔒 Confidencialidade

# 

# Este estudo de caso foi adaptado para fins de portfólio.

# 

# Os dados apresentados são ilustrativos e algumas informações técnicas foram abstraídas para preservar a confidencialidade do ambiente original.

# 

# \---

# 

# \## 👤 Autor

# 

# \*\*Paulo Oliveira\*\*

# 

# \### Data Solutions • Analytics • AI

# 

# \- LinkedIn: https://www.linkedin.com/in/paulo-emilio

# \- Portfólio: https://paulo-emilio.github.io

# \- GitHub: https://github.com/paulo-emilio

