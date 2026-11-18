<div align="center">
  
# 🧠 NeuroPrevent AI

### Sistema Inteligente de Prevenção e Monitoramento do Consumo Abusivo de Álcool e Outras Drogas

**Uma iniciativa do grupo NeuroScience**

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-2E8B57?style=for-the-badge)]()<br>
[![ODS](https://img.shields.io/badge/ONU-ODS%203-00A8E8?style=for-the-badge)]()<br>
[![Licença](https://img.shields.io/badge/licenciamento-custo%20zero-1A2B4C?style=for-the-badge)]()<br>

*Tecnologia, neurociência e prevenção para promover saúde e bem-estar.*
</div>

---

## 📌 Sobre o projeto
O **NeuroPrevent AI** é uma plataforma digital proposta pelo grupo **NeuroScience** para apoiar a prevenção primária e secundária do uso abusivo de álcool e outras drogas.

A solução combina autoavaliações comportamentais, orientações fundamentadas em evidências científicas e análise de dados públicos. Seu objetivo é identificar sinais de risco precocemente, oferecer informações acolhedoras e aproximar o cidadão dos serviços da Rede de Atenção Psicossocial (RAPS).
O projeto está alinhado ao **Objetivo de Desenvolvimento Sustentável 3 (ODS 3) — Saúde e Bem-Estar**, da Organização das Nações Unidas.
> **Nossa proposta:** transformar dados e tecnologia em ferramentas de prevenção, acolhimento e cuidado, antes que situações de risco evoluam para crises de saúde.

## 🎯 Objetivos
- Incentivar a identificação precoce de padrões de consumo de risco.
- Disponibilizar autoavaliações anônimas e acessíveis.
- Oferecer orientações educativas e microintervenções.
- Facilitar o acesso a serviços especializados da RAPS.
- Apoiar gestores públicos com indicadores epidemiológicos e análises preditivas.

---

## 📊 1. O problema em números

O uso nocivo de álcool e outras substâncias psicoativas representa um desafio importante para a saúde pública brasileira. Seus efeitos atingem a saúde física e mental, as relações familiares, os serviços de saúde e a economia.
Os dados reunidos na proposta evidenciam a dimensão do problema:

| Indicador | Prevalência / Volume | População ou parâmetro | Fonte |
|---|---:|---|---|
| Uso de álcool na vida | **63,6%** | População adulta brasileira | LENAD III |
| Consumo episódico pesado de álcool | **34,7%** | Adultos com 18 anos ou mais | LENAD III |
| Transtorno pelo Uso de Álcool (TUA) | **11,1%** | Aproximadamente 1 em cada 9 adultos | LENAD III |
| Uso de maconha na vida | **7,7%** | População de 12 a 65 anos | 3º Levantamento Fiocruz |
| Uso de cocaína na vida | **5,38%** | Aproximadamente 9,3 milhões de pessoas | LENAD III |
| Uso de crack na vida | **1,40%** | Aproximadamente 2,32 milhões de pessoas | LENAD III |
| Internações hospitalares (2012–2022) | **461.356 autorizações** | Diagnósticos CID F10 a F19 | SIH/SUS (DATASUS) |
| Custo econômico indireto do álcool | **R$ 17,7 bilhões** | Perdas de produtividade e previdência | SENAD / HCPA |

### 👥 Público-alvo e vulnerabilidades

O impacto do consumo abusivo não é igual para todos. A proposta considera fatores como idade, gênero, condição socioeconômica e localização geográfica.
- **Adolescentes:** a iniciação no consumo de álcool ocorre frequentemente nessa fase. A PeNSE aponta que 28,1% dos escolares de 13 a 17 anos consumiram bebidas alcoólicas nos 30 dias anteriores à pesquisa.
- **Jovens adultos:** entre pessoas de 18 a 24 anos, o consumo recente de drogas ilícitas alcança 7,4%. A faixa de 20 a 29 anos representa 34,12% das internações por transtornos relacionados ao uso de substâncias (CID F10–F19).
- **Diferenças de gênero:** homens correspondem a 78,18% das internações hospitalares do grupo CID F10–F19.
- **Desigualdades regionais e sociais:** a vulnerabilidade varia conforme a circulação de substâncias, a presença de serviços de atendimento e as condições de acesso à rede de saúde.

### ⚠️ Um desafio de prevenção e acesso
A proposta destaca a distância entre a necessidade de cuidado e o acesso aos serviços especializados. Entre os usuários frequentes de cocaína ou crack considerados no levantamento, 74,8% apresentam critérios de dependência, mas apenas 11,7% acessam atendimentos especializados nos CAPS ad.
A ausência de acompanhamento preventivo pode contribuir para a procura por atendimento apenas em situações agudas, aumentando a pressão sobre os serviços hospitalares.

---

## 🧩 2. Bases de dados utilizadas

O projeto prevê a integração de quatro conjuntos de dados públicos para fundamentar a análise epidemiológica e apoiar o desenvolvimento da solução.

| Base de dados | Órgão / instituição | Aplicação no NeuroPrevent AI |
|---|---|---|
| **LENAD III** | SENAD / UNIFESP | Prevalências e padrões de consumo de álcool, cocaína e crack; calibração de indicadores de risco. |
| **SIH/SUS (DATASUS)** | Ministério da Saúde | Análise de internações, permanência hospitalar, custos e distribuição regional. |
| **PNS e PeNSE** | IBGE / Ministério da Saúde | Estudo dos indicadores de consumo entre adultos e adolescentes; apoio à prevenção escolar. |
| **CNES / RAPS** | Ministério da Saúde | Localização de CAPS ad, Unidades de Acolhimento e serviços de saúde mental. |

---

## 💡 3. A solução: como funciona

A plataforma será organizada em uma arquitetura modular **API-First**, com dois ambientes integrados.

### 📱 Ambiente do cidadão

Voltado ao acolhimento anônimo e ao monitoramento preventivo.

1. **Autoavaliação:** preenchimento de instrumentos padronizados, como AUDIT e DAST-10.
2. **Análise das respostas:** processamento por um motor estatístico.
3. **Retorno de risco:** apresentação de uma classificação descritiva — baixo, moderado, alto ou severo.
4. **Orientação educativa:** disponibilização de conteúdos de psicoeducação e microintervenções baseadas em Terapia Cognitivo-Comportamental (TCC).
5. **Encaminhamento:** indicação de serviços próximos da RAPS, quando necessário, com apoio de dados do CNES.

### 🏥 Painel de gestão em saúde pública

Direcionado aos gestores da Rede de Atenção Psicossocial (RAPS).
- Consolidação e anonimização dos dados coletados.
- Cruzamento com séries históricas do DATASUS e do LENAD III.
- Identificação de possíveis mudanças nos padrões de consumo.
- Apoio ao planejamento de ações preventivas.
- Suporte à distribuição de recursos humanos e terapêuticos.

<sub>Os resultados da autoavaliação têm finalidade informativa e de triagem; não substituem diagnóstico ou acompanhamento realizado por profissionais de saúde.</sub>

---

## 🏗️ 4. Arquitetura e tecnologias

A seleção tecnológica considera robustez, interoperabilidade, proteção de dados e ferramentas de código aberto ou sem custo de licenciamento para o desenvolvimento acadêmico.

| Camada | Tecnologia | Ferramentas / bibliotecas |
|---|---|---|
| **Frontend** | React Native / Next.js | TypeScript, Tailwind CSS, PWA |
| **Backend** | Python 3.11 | FastAPI, Pydantic, Uvicorn |
| **Banco de dados** | PostgreSQL 16 | PostGIS, Alembic |
| **Data Science / ML** | Python | Pandas, NumPy, Scikit-learn |
| **Mapas** | OpenStreetMap | Leaflet.js, OpenRouteService |
| **Hospedagem e CI/CD** | GitHub / Render | Docker, GitHub Actions |

### 🔍 Inteligência artificial e análise preditiva
A proposta prevê o uso de modelos supervisionados de aprendizado de máquina, incluindo classificadores baseados em árvores de decisão e **Random Forest**, por meio da biblioteca Scikit-learn.
Esses modelos poderão apoiar a identificação de padrões e a classificação de indicadores de risco, utilizando dados públicos tratados e anonimizados.

### 🔐 Privacidade e proteção de dados
A arquitetura considera a conformidade com a **Lei Geral de Proteção de Dados (LGPD)**. O projeto prevê acolhimento anônimo no ambiente do cidadão e anonimização dos dados utilizados no painel de gestão.

---

## 🎨 5. Identidade visual

A identidade do NeuroPrevent AI representa a integração entre neurociência, tecnologia e proteção à vida.
O conceito da logomarca combina uma **sinapse neuronal** com a silhueta de um **escudo**, simbolizando a plasticidade cerebral, a prevenção e o cuidado com a saúde mental.

### Paleta de cores

| Cor | Código | Aplicação / significado |
|---|---|---|
| Azul Neuro | `#1A2B4C` | Estruturas principais; transmite confiança e estabilidade. |
| Verde Regeneração | `#2E8B57` | Ações e confirmações; representa saúde e renovação. |
| Ciano Digital | `#00A8E8` | Destaques e links; reforça a dimensão tecnológica. |
| Cinza Neutro | `#F4F6F9` | Fundos e cards; favorece a leitura. |
| Âmbar de Alerta | `#E65100` | Avisos e sinalizações de risco; indica atenção. |

### Tipografia

- **Inter:** textos, corpo de conteúdo e interfaces.
- **Poppins:** títulos e elementos de destaque.

---

## 🗂️ 6. Estrutura do repositório

A organização do GitHub foi planejada para separar documentação, interface, serviços, dados e recursos visuais.

```text
NeuroPrevent-AI/
│
├── README.md
│
├── docs/
│   ├── documentacao-tecnica/
│   ├── dicionarios-de-dados/
│   └── integracao-de-apis/
│
├── src/
│   ├── frontend/
│   ├── backend/
│   ├── database/
│   └── ml_models/
│
└── assets/
    ├── logo/
    ├── identidade-visual/
    └── prototipos/
```

| Diretório / arquivo | Finalidade |
|---|---|
| `README.md` | Apresentação geral, contexto, arquitetura e informações da equipe. |
| `docs/` | Documentação técnica, dicionários de dados e manuais de integração. |
| `src/frontend/` | Telas, componentes e aplicação web/mobile. |
| `src/backend/` | API RESTful, regras de negócio e rotas de comunicação. |
| `src/database/` | Modelagem PostgreSQL, migrações e dados geográficos. |
| `src/ml_models/` | Tratamento de dados e treinamento dos modelos de classificação. |
| `assets/` | Logomarca, guia visual e protótipos de interface. |

---

## 👨‍💻 7. Equipe NeuroScience

Integrante	Responsabilidade	Principais atribuições
Mateus Santos	Líder do Projeto	Coordenação da equipe, planejamento estratégico, organização das atividades e acompanhamento do desenvolvimento.
Lucas Brito	Cientista de Dados e Machine Learning	Análise das bases públicas, tratamento de dados epidemiológicos e desenvolvimento de modelos de aprendizado de máquina.
Matheus Fernandes	Desenvolvedor Backend	Desenvolvimento da API com FastAPI, implementação das regras de negócio e integração com o banco PostgreSQL.
Rafael Tadano	Desenvolvedor Frontend e UI/UX	Criação das interfaces, prototipação das telas, identidade visual e desenvolvimento da experiência do usuário.
Nathan	Engenheiro DevOps e Infraestrutura	Configuração do ambiente de desenvolvimento, Docker, pipelines CI/CD e gerenciamento da infraestrutura.
Mailon José	Analista de QA e Documentação	Realização de testes, validação das funcionalidades, identificação de erros e elaboração da documentação técnica.
---

## 🚀 8. Pitch do projeto

O abuso de álcool e outras drogas gera impactos expressivos na saúde pública e na economia brasileira. O **NeuroPrevent AI**, idealizado pelo grupo NeuroScience, propõe uma nova forma de atuar nesse cenário: unir análise de dados públicos, autoavaliação comportamental anônima e tecnologia para fortalecer a prevenção.
Em vez de agir somente quando o problema chega a uma situação de urgência, a plataforma busca identificar sinais de risco, oferecer orientações baseadas em evidências científicas e facilitar a conexão com a Rede de Atenção Psicossocial.
**NeuroPrevent AI: prevenção inteligente, acolhimento sem julgamentos e tecnologia a favor da vida.**

---

## 🌍 9. Impacto esperado
- **Prevenção:** ampliar as oportunidades de identificação precoce de comportamentos de risco.
- **Acesso:** facilitar a localização de serviços de atenção psicossocial.
- **Gestão pública:** fornecer indicadores para apoiar decisões e planejamento.
- **Conscientização:** disponibilizar informação acessível sobre saúde e uso de substâncias.
- **ODS 3:** contribuir para a promoção da saúde e do bem-estar.

---

## 📚 10. Referências e fontes de dados

As fontes institucionais e bases mencionadas na proposta incluem:
- **LENAD III** — Universidade Federal de São Paulo (UNIFESP) / Secretaria Nacional de Políticas sobre Drogas (SENAD).
- **SIH/SUS (DATASUS)** — Ministério da Saúde.
- **PNS e PeNSE** — IBGE / Ministério da Saúde.
- **CNES / RAPS** — Ministério da Saúde.
- **3º Levantamento Nacional sobre o Uso de Drogas pela População Brasileira** — Fiocruz.

---

<div align="center">

### 🧠 NeuroPrevent AI

**NeuroScience · Saúde · Tecnologia · Prevenção**<br>
*Promovendo cuidado antes que o risco se torne uma emergência.*
</div>
