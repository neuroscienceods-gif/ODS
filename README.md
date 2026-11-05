# ODS
Nome NeuroScience
Projeto NeuroPrevent AI: Sistema Inteligente de Prevenção e Monitoramento do Consumo Abusivo de Álcool e Outras Drogas
1. Descrição do Problema e Contextualização Epidemiológica
1.1 Delimitação do Problema e Contexto Social
O uso nocivo de álcool e outras substâncias psicoativas (SPA) configura-se como um dos problemas de saúde pública mais graves e complexos do Brasil contemporâneo, gerando impactos profundos na integridade física e mental dos indivíduos, na sustentabilidade das redes familiares e na eficiência dos sistemas de saúde e previdência social. Inserido no âmbito do Objetivo de Desenvolvimento Sustentável 3 da Organização das Nações Unidas (ODS 3 — Saúde e Bem-Estar), o combate ao abuso de substâncias demanda intervenções que ultrapassem o modelo reativo de contenção de crises e avancem na direção da prevenção primária e secundária baseada em evidências científicas e tecnologia da informação.   

A dimensão epidemiológica do consumo de álcool no país é evidenciada pelos dados do Terceiro Levantamento Nacional de Álcool e Drogas (LENAD III), desenvolvido pela Universidade Federal de São Paulo (UNIFESP) em parceria com a Secretaria Nacional de Políticas sobre Drogas (SENAD). O estudo aponta que 63,6% da população adulta brasileira já consumiu álcool em algum momento da vida, enquanto 44,2% relataram consumo nos últimos 12 meses e 31,6% no último mês. O padrão comportamental de maior gravidade para a saúde pública é o consumo episódico pesado — caracterizado pela ingestão de 4 ou mais doses por mulheres ou 5 ou mais por homens em uma única ocasião —, praticado por 34,7% da população adulta no âmbito domiciliar nacional. Estima-se que um em cada três adultos incorra nesse padrão de risco e um em cada nove indivíduos cumpra critérios diagnósticos formais para o Transtorno pelo Uso de Álcool (TUA).   

No que tange às substâncias psicoativas ilícitas, os levantamentos nacionais revelam uma expansão consistente tanto na experimentação quanto no consumo recente, com um crescimento acumulado próximo de 80% no consumo geral de drogas ilícitas na última década. A maconha figura como a substância ilícita de maior prevalência no país, tendo sido utilizada por 7,7% da população de 12 a 65 anos ao longo da vida. A cocaína em pó surge em segundo lugar, com uma prevalência de uso na vida de 5,38%, o que representa aproximadamente 9,3 milhões de brasileiros. Por sua vez, o uso de crack e derivados atinge cerca de 1,4% da população (2,32 milhões de pessoas), com consumo fortemente associado à exclusão social e ao espaço público. Paralelamente, observa-se o avanço silencioso do uso não prescrito de medicamentos controlados, com destaque para os analgésicos opiáceos e tranquilizantes benzodiazepínicos, consumidos de forma inadequada por 0,6% e 0,4% da população no último mês, respectivamente.   

Indicador Epidemiológico	Taxa de Prevalência / Volume	População Afetada / Parâmetro	Fonte de Dados
Uso de Álcool na Vida (Adultos)	63,6%	População adulta brasileira	
LENAD III

Consumo Episódico Pesado de Álcool	34,7%	Adultos 18+ (âmbito domiciliar)	
LENAD III

Transtorno pelo Uso de Álcool (TUA)	11,1% (1 em cada 9)	Critérios de dependência clínica	
LENAD III

Uso de Maconha na Vida	7,7%	População de 12 a 65 anos	
3º Levantamento Fiocruz

Uso de Cocaína na Vida	5,38%	~9,3 milhões de pessoas	
LENAD III

Uso de Crack na Vida	1,40%	~2,32 milhões de pessoas	
LENAD III

Internações Hospitalares (2012–2022)	461.356 autorizações	Diagnósticos CID F10 a F19	
SIH/SUS (DATASUS)

Custo Econômico Indireto do Álcool	R$ 17,7 bilhões	Perda de produtividade e previdência	
SENAD / HCPA

  
1.2 Público-Alvo e Desigualdades Socioeconômicas
O impacto do abuso de substâncias psicoativas recai de maneira assimétrica sobre a população, sendo influenciado por determinantes sociodemográficos como faixa etária, gênero, nível socioeconômico e localização geográfica.   

A iniciação no consumo de álcool ocorre predominantemente na adolescência. Dados da Pesquisa Nacional de Saúde do Escolar (PeNSE) revelam que 28,1% dos escolares de 13 a 17 anos consumiram bebidas alcoólicas nos 30 dias anteriores à pesquisa. Entre os jovens de 18 a 24 anos, identifica-se o pico de consumo recente de drogas ilícitas, alcançando 7,4% dessa população. No ambiente hospitalar do Sistema Único de Saúde (SUS), os adultos jovens de 20 a 29 anos representam a maior parcela individual das internações por transtornos mentais e comportamentais devido ao uso de substâncias (CID F10-F19), correspondendo a 34,12% dos casos.   

Em relação ao gênero, os homens apresentam os maiores índices de morbidade grave e hospitalização. Registra-se que 78,18% das internações hospitalares pelo grupo CID F10-F19 ocorrem no sexo masculino. A prevalência de consumo recente de cocaína entre homens é quase cinco vezes superior à observada entre mulheres (3,00% contra 0,63%), padrão que se repete no consumo de crack (0,88% entre homens contra 0,10% entre mulheres).   

Regionalmente, a vulnerabilidade varia de acordo com os padrões de circulação e acesso às substâncias. O Centro-Oeste lidera a prevalência de uso na vida de cocaína e/ou crack (10,23%), enquanto o Sudeste concentra a maior percepção populacional da presença do tráfico de drogas no bairro de residência (51,6%). Além disso, populações em situação de extrema vulnerabilidade social e de rua sofrem o impacto desproporcional do consumo de crack, apresentando alta taxa de dependência e barreiras severas de acesso aos serviços formais de atenção psicossocial.   

1.3 Bases de Dados Públicas Utilizadas
Para subsidiar o desenvolvimento do projeto NeuroPrevent AI, a equipe NeuroScience selecionou e integrou quatro repositórios de dados abertos governamentais, garantindo fundamentação científica e precisão na modelagem epidemiológica:

Base de Dados	Órgão Mantenedor	Conteúdo Analítico Extraído	Aplicação na Solução Tecnológica
LENAD III	SENAD / UNIFESP	
Prevalências de consumo de álcool, cocaína e crack; padrões de consumo episódico pesado; indicadores de dependência.

Calibração de algoritmos de triagem comportamental e perfilamento de risco.

SIH/SUS (DATASUS)	Ministério da Saúde	
Registros hospitalares por CID-10 (F10-F19), tempo de permanência, custos hospitalares e mortalidade por região.

Mapeamento territorial de focos de internação grave e projeção de demanda de leitos públicos.

PNS e PeNSE	IBGE / Ministério da Saúde	
Indicadores de consumo de álcool, tabaco e drogas entre adultos e adolescentes escolares.

Modelagem de trajetórias de iniciação precoce e estratégias de prevenção escolar.

CNES / RAPS	Ministério da Saúde	
Mapeamento de Centros de Atenção Psicossocial (CAPS ad), Unidades de Acolhimento e leitos em saúde mental.

Sistema de geolocalização e direcionamento automatizado do usuário para serviços de saúde.

  
1.4 Análise Sintética de Impacto Sistêmico
A análise aprofundada das evidências epidemiológicas revela uma encadeada relação de causa e efeito que sobrecarrega a rede de saúde e a economia pública. O ponto de origem dessa dinâmica reside no estigma social e na falta de ferramentas acessíveis de triagem precoce na Atenção Primária à Saúde. Embora 74,8% dos usuários frequentes de cocaína ou crack apresentem critérios de dependência, apenas 11,7% chegam a acessar os atendimentos especializados nos Centros de Atenção Psicossocial (CAPS ad).   

Essa lacuna na prevenção secundária gera um efeito direto no perfil das admissões hospitalares no SUS. Sem suporte preventivo prévio, a busca por auxílio médico ocorre prevalentemente em situações de crise aguda. Entre os adolescentes hospitalizados por uso de substâncias psicoativas, 88,3% dos atendimentos são realizados em caráter de urgência emergencial. Essa concentração de diagnósticos tardios resulta em um tempo médio de internação de 21,2 dias por paciente, gerando custos diretos e a ocupação prolongada de leitos psiquiátricos e de terapia intensiva.   

Por fim, os desdobramentos de terceira ordem afetam diretamente a produtividade econômica nacional. O consumo excessivo de álcool e drogas gera perdas indiretas estimadas em R$ 17,7 bilhões por ano, decorrentes de aposentadorias precoces, licenças médicas prolongadas, acidentes de trabalho e mortalidade prematura em episódios associados ao trânsito e à violência interpessoal.   

2. Proposta de Solução Tecnológica
2.1 Arquitetura do Sistema NeuroPrevent AI
A proposta tecnológica concebida pelo grupo NeuroScience consiste no desenvolvimento da plataforma NeuroPrevent AI, uma solução digital voltada à prevenção primária e secundária do abuso de álcool e outras drogas. O sistema é estruturado em uma arquitetura modular desacoplada (API-First), dividida em dois ambientes integrados: uma aplicação Web/Mobile progressiva (PWA) voltada ao cidadão e um painel de inteligência epidemiológica direcionado aos gestores da Rede de Atenção Psicossocial (RAPS).   

O ambiente do cidadão foca no acolhimento anônimo e no monitoramento preventivo. Por meio do aplicativo, o usuário realiza autoavaliações comportamentais padronizadas, como o Alcohol Use Disorders Identification Test (AUDIT) e o Drug Abuse Screening Test (DAST-10). O sistema processa as respostas em tempo real por meio de um motor estatístico, devolvendo ao usuário um diagnóstico descritivo do seu nível de risco (baixo, moderado, alto ou severo), acompanhado de microintervenções baseadas em Terapia Cognitivo-Comportamental (TCC) e psicoeducação sobre neurobiologia do vício. Caso o nível de risco indicado exija acompanhamento profissional, a plataforma utiliza a API geográfica do CNES/RAPS para indicar as unidades de CAPS ad e Unidades de Acolhimento mais próximas da localização do usuário.   

O módulo voltado à gestão de saúde pública consolida e anonimiza os dados coletados na ponta, cruzando-os com as séries históricas do DATASUS e do LENAD III. Utilizando algoritmos de aprendizado de máquina supervisionado, o painel preditivo identifica a emergência de novos padrões de consumo em nível municipal e microrregional, permitindo que as Secretarias de Saúde planejem ações preventivas direcionadas e otimizem a alocação de recursos humanos e terapêuticos nos serviços comunitários.   

2.2 Stack Tecnológico Selecionado
A escolha das ferramentas e linguagens de programação orientou-se pelos critérios de robustez, interoperabilidade, conformidade com a Lei Geral de Proteção de Dados (LGPD) e custo zero de licenciamento, garantindo a viabilidade de desenvolvimento no ambiente acadêmico:

Camada da Solução	Tecnologia	Especificação e Bibliotecas	Justificativa Técnica
Frontend Cidadão	React Native / Next.js	TypeScript, Tailwind CSS, PWA Framework	Garantia de aplicação multi-plataforma leve, com suporte a acesso offline e excelente desempenho em dispositivos móveis populares.
Backend API	Python 3.11	FastAPI, Pydantic, Uvicorn	Processamento assíncrono de alta performance, facilidade de manutenção e suporte nativo às bibliotecas de inteligência artificial.
Banco de Dados	PostgreSQL 16	Extensão PostGIS, Alembic	
Banco relacional com suporte a operações transacionais ACID e processamento de consultas geoespaciais para mapeamento da RAPS.

Data Science / ML	Python Science Stack	Pandas, NumPy, Scikit-learn	
Tratamento dos microdados públicos (DATASUS/LENAD) e execução de modelos preditivos de classificação de risco.

Serviços de Mapas	OpenStreetMap API	Leaflet.js, OpenRouteService	Solução de geolocalização de código aberto para cálculo de rotas até os pontos de atenção sem custos de API proprietária.
Hospedagem / CI/CD	GitHub / Render	Docker, GitHub Actions	
Deploy automatizado e controle de versão centralizado para acompanhamento da evolução do código pelo grupo.

  
2.3 Justificativa Técnica e Viabilidade Semestral
A implementação do NeuroPrevent AI demonstra plena viabilidade técnica para o ciclo de desenvolvimento do semestre 2026.2. A opção pela arquitetura baseada em microsserviços via FastAPI reduz significativamente o tempo de integração entre a interface e o banco de dados. A automatização de protocolos clínicos de triagem (AUDIT/DAST) elimina a necessidade de construir validações complexas do zero, utilizando instrumentos amplamente respaldados pela literatura médica e pela OMS.   

Ademais, a utilização de modelos de machine learning leve (como classificadores baseados em árvores de decisão e Random Forest da biblioteca Scikit-learn) possibilita a execução do motor preditivo em servidores de menor capacidade computacional, dispensando infraestruturas caras de GPU e garantindo o funcionamento do protótipo dentro do prazo estipulado pelo programa de inovação universitário.   

3. Identidade Visual Inicial
3.1 Conceito da Logomarca e Fundamentação Simbólica
A identidade gráfica desenvolvida para o NeuroPrevent AI reflete a união entre a neurociência, a tecnologia digital e a proteção à vida. O conceito visual central articula o desenho de uma sinapse neuronal em formato orgânico cujos prolongamentos axônicos se entrelaçam para formar a silhueta contínua de um escudo.

Essa composição gráfica simboliza a plasticidade cerebral e a capacidade de reestruturação comportamental do indivíduo quando amparado por estratégias preventivas eficientes. A forma do escudo reafirma a função primordial do software: proteger o bem-estar mental e evitar que o consumo experimental de substâncias evolua para quadros severos de dependência química ou hospitalização.   

3.2 Paleta de Cores
A definição cromática do projeto baseia-se em estudos de psicologia das cores aplicados a interfaces de saúde e apoio emocional, priorizando tons que transmitam serenidade, profissionalismo e segurança, evitando cores que possam desencadear estresse visual ou ansiedade:   

Nome da Cor	Código Hexadecimal	Aplicação na Interface (UI)	Significado e Efeito Neuropsicológico
Azul Neuro	#1A2B4C	Estruturas principais, cabeçalhos e textos.	Transmite seriedade científica, autoridade, estabilidade e confiança institucional.
Verde Regeneração	#2E8B57	Botões de ação principais, confirmações e progresso.	Representa saúde, neuroplasticidade, renovação comportamental e equilíbrio psicológico.
Ciano Digital	#00A8E8	Destaques, ícones interativos e links de navegação.	Evoca modernidade tecnológica, clareza de informação e acessibilidade digital intuitiva.
Cinza Neutro	#F4F6F9	Plano de fundo das telas e cards de informação.	
Proporciona alto contraste de leitura, reduzindo a fadiga visual do usuário.

Âmbar de Alerta	#E65100	Sinalizações de risco moderado/elevado e avisos.	Comunica a necessidade de atenção e cuidado sem gerar alarmismo ou pânico.
  
3.3 Tipografia
A seleção tipográfica prioriza a legibilidade em diferentes tamanhos de tela e a acessibilidade visual para usuários em momentos de alteração emocional ou fadiga cognitiva:

Tipografia Principal (Corpo de Texto e Interfaces): Inter — Fonte sans-serif consagrada na indústria do software pela excelente proporção de caracteres e leitura fluida em telas de dispositivos móveis.

Tipografia Secundária (Títulos e Elementos de Destaque): Poppins — Fonte sans-serif com geometria suave e cantos arredondados, que confere um tom humanizado, acolhedor e moderno aos títulos de seções e conteúdos de psicoeducação.

4. Pitch Inicial
O abuso de álcool e drogas gera um impacto de R$ 17,7 bilhões na economia brasileira e motiva mais de 460 mil internações hospitalares no SUS, sendo 88% delas concentradas em emergências devido à falta de triagem precoce e ao estigma que afasta 88% dos dependentes do tratamento comunitário. O NeuroPrevent AI, idealizado pelo grupo NeuroScience, transforma a prevenção ao unir análise preditiva de dados abertos públicos, autoavaliação comportamental anônima e neuroinformática em uma plataforma digital acessível e livre de julgamentos. Ao contrário das abordagens reativas tradicionais, a solução identifica os primeiros sinais de risco comportamental, entrega orientações baseadas em evidências científicas e conecta o usuário à Rede de Atenção Psicossocial (RAPS) antes que o quadro evolua para a urgência médica. Trata-se de uma tecnologia estratégica que apoia o ODS 3 da ONU, reduz a sobrecarga do sistema de saúde e preserva vidas por meio da intervenção preventiva oportuna.   

5. Repositório Público no GitHub e Organização da Equipe NeuroScience
5.1 Estrutura do Repositório GitHub
O repositório do projeto NeuroPrevent AI foi configurado de forma pública no GitHub, garantindo transparência, versionamento adequado e facilidade de avaliação conforme os requisitos do projeto de inovação. A estrutura de arquivos organiza-se da seguinte forma:   

Diretório / Arquivo	Descrição e Finalidade
README.md	
Documento principal contendo o título, contextualização epidemiológica, arquitetura, paleta de cores, pitch e membros.

/docs	
Documentação técnica complementar, dicionários de dados do DATASUS/LENAD III e manuais de integração de APIs.

/src/frontend	Código-fonte da aplicação React Native / Next.js, incluindo telas de triagem, componentes visuais e PWA.
/src/backend	Serviços da API RESTful construídos em Python (FastAPI), contendo as regras de negócio e rotas de comunicação.
/src/database	
Scripts de modelagem PostgreSQL, migrações Alembic e arquivos de carga de dados geográficos dos CAPS ad.

/src/ml_models	
Scripts em Python para limpeza dos microdados governamentais e treinamento dos algoritmos de classificação de risco.

/assets	Vetores e arquivos da identidade visual (logomarca, guia de estilos gráficos e protótipos de tela).
  
5.2 Divisão de Papéis da Equipe NeuroScience
A atribuição de responsabilidades entre os integrantes do grupo NeuroScience visa assegurar a participação visível de todos os membros e a entrega com excelência técnica de todas as etapas do projeto:   

Integrante do Grupo	Função Principal	Atribuições Específicas no Projeto e Repositório
Integrante 1	Liderança & Data Scientist	
Análise e tratamento das bases públicas (DATASUS, LENAD III), desenvolvimento dos algoritmos de aprendizado de máquina e redação da documentação.

Integrante 2	Engenheiro Backend	
Desenvolvimento da API RESTful em Python (FastAPI), estruturação do banco de dados PostgreSQL e integração com a extensão PostGIS.

Integrante 3	Designer UI/UX & Frontend	Criação da identidade visual (logo, cores, tipografia), prototipagem de interfaces e desenvolvimento dos componentes da aplicação web/mobile.
Integrante 4	Engenheiro DevOps & QA	Configuração do fluxo de integração contínua (CI/CD) no GitHub Actions, conteinerização da aplicação via Docker e execução dos testes de software.
  
6. Conclusão
A elaboração da proposta do NeuroPrevent AI fundamenta-se na compreensão de que o combate ao abuso de substâncias psicoativas no Brasil exige uma transição paradigmática: a passagem de uma abordagem centrada quase exclusivamente no tratamento tardio das complicações de saúde para um modelo de prevenção ativa, descentralizada e baseada em dados públicos.   

A análise das estatísticas nacionais demonstra a existência de uma grande massa de indivíduos em risco moderado que não é captada pelos serviços tradicionais de saúde até que ocorra um evento agudo de urgência. A solução tecnológica desenvolvida pelo grupo NeuroScience preenche essa lacuna assistencial ao oferecer uma porta de entrada anônima, segura e informada pela neurociência. Ao combinar rigor metodológico na triagem, design centrado na acessibilidade do usuário e inteligência preditiva para a gestão pública, o projeto reafirma o papel da tecnologia como vetor de transformação social e garantia do direito à saúde.   

