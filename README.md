## Plano de Experimento – Scoping e Planejamento

### 1. Identificação básica

#### 1.1 Título do experimento
Design de API no Contexto de Arquitetura Distribuídas: Um Estudo Comparativo entre API-First e Code-First

#### 1.2 ID / código
gabrielreisresende-medicao-experimentacao-tcc

#### 1.3 Versão do documento e histórico de revisão
- v1.0 (23/11/2025): Inclusão da identificação básica, contexto e problema do projeto de pesquisa.
- v1.1 (23/11/2025): Escopo, Objetivo, Stakeholders/Impacto, Riscos de alto nível, premissas e critérios de sucesso
- v1.2 (25/11/2025): Modelo conceitual e hipóteses (Etapa 7), Variáveis, fatores, tratamentos e objetos de estudo (Etapa 8), Desenho experimental (Etapa 9)
- v1.3 (27/11/2025) População, sujeitos e amostragem; Instrumentação e protocolo operacional; Plano de análise de dados
- v1.4 (02/12/2025) Ameaças a validade
- v1.5 (05/12/2025) - Ajustes de legibilidade e formatações
 
#### 1.4 Datas (criação, última atualização)
- Data de criação: 23/11/2025
- Última atualização: 25/11/2025

#### 1.5 Autores (nome, área, contato)
- **Autor:** Gabriel Lourenço Reis Resende 
  - Área: Bacharelado em Engenharia de Software
  - Instituição: PUC Minas – Instituto de Informática e Ciências Exatas
  - E-mail: gabriel.lourenco@sga.pucminas.br
  
#### 1.6 Responsável principal (PI / dono do experimento)
- Gabriel Lourenço Reis Resende

#### 1.7 Projeto / produto / iniciativa relacionada
Planejamento de Trabalho de Conclusão de Curso (TCC) focado em medição e experimentação de software, com ênfase na comparação de abordagens de design de API em arquiteturas distribuídas.

---

### 2. Contexto e problema

#### 2.1 Descrição do problema / oportunidade
O design de APIs em arquiteturas distribuídas é um desafio crítico na engenharia de software moderna. Duas abordagens principais emergiram: **API-First**, na qual a especificação da API é definida antes da implementação e **Code-First**, no qual a API é gerada a partir do código implementado. Apesar da crescente adoção dessas abordagens, há uma escassez de evidências empíricas comparativas sobre suas vantagens, desvantagens e impacto em diferentes contextos organizacionais e técnicos. Este experimento busca preencher essa lacuna através de um estudo comparativo baseado em survey com profissionais que trabalham ou já trabalharam em arquiteturas distribuídas, permitindo identificar padrões, trade-offs e fatores de sucesso de cada abordagem.

#### 2.2 Contexto organizacional e técnico
O experimento será conduzido no contexto acadêmico de um TCC, mas com foco em profissionais da indústria que atuam ou já atuaram em projetos com arquiteturas distribuídas. O estudo abrangerá diferentes tipos de organizações (startups, empresas de médio e grande porte). O processo de desenvolvimento pode variar entre os participantes (ágil, DevOps, tradicional), mas todos devem ter experiência prática com design e implementação de APIs em sistemas distribuídos.

#### 2.3 Trabalhos e evidências prévias (internos e externos)
- **Literatura externa**: Estudos sobre API design patterns, arquiteturas de microsserviços, e comparações conceituais entre API-First e Code-First (principalmente em blogs técnicos e documentação de ferramentas)
- **Evidências internas**: Não há estudos prévios internos identificados
- **Lacuna identificada**: Falta de estudos empíricos quantitativos e qualitativos comparando sistematicamente as duas abordagens com base em experiências reais de profissionais

#### 2.4 Referencial teórico e empírico essencial
- **API-First Design**: Abordagem onde a especificação da API (OpenAPI/Swagger, GraphQL Schema, Protocol Buffers) é criada antes da implementação, servindo como contrato entre equipes e permitindo desenvolvimento paralelo
- **Code-First Design**: Abordagem onde a API é implementada diretamente no código e a documentação/especificação é gerada automaticamente a partir do código
- **Arquiteturas Distribuídas**: Sistemas compostos por múltiplos serviços independentes que se comunicam via APIs, incluindo microsserviços, sistemas orientados a serviços (SOA) e arquiteturas baseadas em eventos
- **GQM (Goal-Question-Metric)**: Framework para definição de objetivos mensuráveis através de perguntas e métricas associadas
- **Survey Research**: Metodologia de pesquisa baseada em questionários para coleta de dados de uma amostra representativa da população

---

### 3. Objetivos e questões (Goal / Question / Metric)

#### 3.1 Objetivo geral (Goal template)
Analisar as abordagens API-First e Code-First para design de APIs com o propósito de identificar e comparar suas vantagens, desvantagens e impacto em diferentes dimensões (produtividade, qualidade, manutenibilidade, colaboração) do ponto de vista de profissionais que trabalham em arquiteturas distribuídas no contexto de projetos de software reais em diferentes organizações.

#### 3.2 Objetivos específicos

**O1**: Identificar e comparar as vantagens percebidas da abordagem API-First em relação à Code-First, considerando aspectos de produtividade, qualidade de código, tempo de desenvolvimento e satisfação dos desenvolvedores.

**O2**: Identificar e comparar as desvantagens percebidas da abordagem API-First em relação à Code-First, considerando aspectos de complexidade, curva de aprendizado, custos de manutenção e dificuldades de implementação.

**O3**: Avaliar o impacto de cada abordagem na colaboração entre equipes, comunicação entre stakeholders, e na qualidade da documentação e especificação das APIs.

**O4**: Analisar fatores contextuais (tipo de organização, tamanho da equipe) que influenciam a escolha e o sucesso de cada abordagem.

#### 3.3 Questões de pesquisa / de negócio

**Q1.1**: Quais são as principais vantagens percebidas pelos profissionais que utilizam a abordagem API-First em relação à Code-First?

**Q1.2**: Qual é o impacto da abordagem API-First na produtividade dos desenvolvedores comparado à Code-First?

**Q1.3**: Como a abordagem API-First influencia a qualidade do código e a redução de defeitos em relação à Code-First?

**Q2.1**: Quais são as principais desvantagens percebidas pelos profissionais que utilizam a abordagem API-First em relação à Code-First?

**Q2.2**: Qual é o impacto da abordagem API-First na complexidade do processo de desenvolvimento comparado à Code-First?

**Q2.3**: Como a abordagem API-First afeta os custos de manutenção e a curva de aprendizado em relação à Code-First?

**Q3.1**: Qual é o impacto de cada abordagem na colaboração entre equipes e na comunicação entre desenvolvedores frontend e backend?

**Q3.2**: Como cada abordagem influencia a qualidade e completude da documentação das APIs?

**Q3.3**: Qual é o impacto de cada abordagem na facilidade de integração entre diferentes serviços e sistemas?

**Q4.1**: Quais fatores organizacionais (tipo de empresa, tamanho da equipe) influenciam a escolha entre API-First e Code-First?

**Q4.2**: Existe correlação entre a experiência dos profissionais e a preferência por uma das abordagens?

#### 3.4 Métricas associadas (GQM)

A tabela abaixo apresenta o mapeamento entre Objetivos, Questões e Métricas (GQM):

| Objetivo | Questão | Métricas |
|----------|---------|----------|
| O1 | Q1.1 | M1, M2, M3 |
| O1 | Q1.2 | M4 |
| O1 | Q1.3 | M5 |
| O2 | Q2.1 | M6, M7, M8 |
| O2 | Q2.2 | M9, M10 |
| O2 | Q2.3 | M11, M12 |
| O3 | Q3.1 | M13, M14 |
| O3 | Q3.2 | M15, M16 |
| O3 | Q3.3 | M17, M18 |
| O4 | Q4.1 | M19, M20 |
| O4 | Q4.2 | M21, M22 |

**Tabela de Métricas:**

| ID | Nome da Métrica | Descrição | Unidade |
|----|-----------------|-----------|---------|
| M1 | Número de Vantagens Identificadas | Quantidade total de vantagens distintas mencionadas pelos participantes para cada abordagem | Quantidade (número inteiro) |
| M2 | Frequência de Menção de Vantagens | Quantas vezes cada vantagem específica foi mencionada pelos participantes | Quantidade (número inteiro) |
| M3 | Score Médio de Importância das Vantagens | Média das avaliações de importância (escala Likert) atribuídas às vantagens identificadas | Escala (1-5 ou 1-10) |
| M4 | Produtividade Percebida | Autoavaliação dos desenvolvedores sobre sua produtividade usando cada abordagem | Escala (1-5 ou 1-10) |
| M5 | Qualidade Percebida do Código | Autoavaliação dos desenvolvedores sobre a qualidade do código gerado | Escala (1-5 ou 1-10) |
| M6 | Número de Desvantagens Identificadas | Quantidade total de desvantagens distintas mencionadas pelos participantes para cada abordagem | Quantidade (número inteiro) |
| M7 | Frequência de Menção de Desvantagens | Quantas vezes cada desvantagem específica foi mencionada pelos participantes | Quantidade (número inteiro) |
| M8 | Score Médio de Severidade das Desvantagens | Média das avaliações de severidade (escala Likert) atribuídas às desvantagens identificadas | Escala (1-5 ou 1-10) |
| M9 | Complexidade Percebida do Processo | Autoavaliação dos desenvolvedores sobre a complexidade do processo de desenvolvimento | Escala (1-5 ou 1-10) |
| M10 | Número de Ferramentas Necessárias | Quantidade média de ferramentas e tecnologias que precisam ser aprendidas/dominadas | Quantidade (número inteiro) |
| M11 | Tempo Médio de Manutenção | Tempo médio gasto em atividades de manutenção e evolução de APIs existentes | Tempo (horas ou dias por mês) |
| M12 | Tempo de Curva de Aprendizado | Tempo necessário para um desenvolvedor se tornar produtivo com a abordagem | Tempo (semanas ou meses) |
| M13 | Nível de Colaboração Percebida | Autoavaliação sobre a facilidade e qualidade da colaboração entre equipes | Escala (1-5 ou 1-10) |
| M14 | Frequência de Comunicação entre Equipes | Número médio de interações necessárias entre equipes frontend e backend durante o desenvolvimento | Quantidade (número de interações) |
| M15 | Completude da Documentação | Percentual de APIs que possuem documentação completa e atualizada | Percentual (%) |
| M16 | Qualidade Percebida da Documentação | Autoavaliação sobre a qualidade, clareza e utilidade da documentação gerada | Escala (1-5 ou 1-10) |
| M17 | Tempo Médio de Integração | Tempo médio necessário para integrar um novo serviço ou consumir uma API existente | Tempo (horas ou dias) |
| M18 | Taxa de Sucesso de Integrações | Proporção de tentativas de integração que são bem-sucedidas na primeira tentativa | Percentual (%) |
| M19 | Distribuição por Tipo de Organização | Proporção de participantes de cada tipo de organização (startup, média, grande) que usa cada abordagem | Percentual (%) |
| M20 | Distribuição por Tamanho de Equipe | Tamanho médio da equipe de desenvolvimento nos projetos que usam cada abordagem | Quantidade (número de pessoas) |
| M21 | Anos de Experiência Média | Anos médios de experiência profissional dos participantes que preferem cada abordagem | Tempo (anos) |
| M22 | Preferência por Abordagem | Proporção de participantes que preferem cada abordagem, estratificada por nível de experiência | Percentual (%) |

---

### 4. Escopo e contexto do experimento

#### 4.1 Escopo funcional / de processo (incluído e excluído)

**Incluído no escopo:**
- Comparação entre as abordagens API-First e Code-First para design de APIs
- Análise de vantagens e desvantagens percebidas por profissionais da indústria
- Avaliação de impacto em dimensões como produtividade, qualidade, manutenibilidade e colaboração
- Identificação de fatores contextuais (organizacionais e técnicos) que influenciam a escolha e sucesso de cada abordagem
- Coleta de dados através de survey online com profissionais que trabalham ou trabalharam em arquiteturas distribuídas
- Análise de dados quantitativos e qualitativos obtidos através do questionário
- Separação dos participantes em dois grupos: profissionais que já utilizaram API-First e profissionais que nunca utilizaram (ou utilizaram apenas Code-First)

**Excluído do escopo:**
- Implementação prática de APIs usando ambas as abordagens (experimento controlado)
- Análise de código-fonte ou métricas de código de projetos reais
- Avaliação de ferramentas específicas de API-First ou Code-First
- Comparação de performance técnica ou benchmarks de APIs
- Análise de custos financeiros diretos de cada abordagem
- Estudo de caso em uma organização específica
- Avaliação de outras abordagens de design de API (como Schema-First, Design-First, etc.)

#### 4.2 Contexto do estudo (tipo de organização, projeto, experiência)

O estudo será conduzido através de um survey online distribuído para profissionais da indústria de software. O contexto abrange:

- **Tipo de organização**: Startups, empresas de médio porte e grandes corporações que desenvolvem software com arquiteturas distribuídas
- **Tipo de projeto**: Projetos de software que utilizam arquiteturas distribuídas, incluindo sistemas baseados em microsserviços, SOA ou arquiteturas orientadas a eventos
- **Criticidade**: Projetos de diferentes níveis de criticidade (desde sistemas internos até sistemas críticos de negócio)
- **Perfil de experiência dos participantes**: 
  - Profissionais com experiência prática em design e implementação de APIs
  - Desenvolvedores, arquitetos de software, tech leads e engenheiros de software
  - Experiência mínima de 1 ano trabalhando com arquiteturas distribuídas
  - Participantes devem ter trabalhado em pelo menos um projeto utilizando uma das abordagens (API-First ou Code-First)

#### 4.3 Premissas

As seguintes premissas são consideradas verdadeiras para o funcionamento do experimento:

1. **Disponibilidade de participantes**: Existe um número suficiente de profissionais disponíveis e dispostos a participar do survey, permitindo alcançar uma amostra representativa
2. **Honestidade nas respostas**: Os participantes fornecerão respostas honestas e baseadas em suas experiências reais, sem viés intencional
3. **Compreensão das abordagens**: Os participantes compreendem adequadamente as diferenças entre API-First e Code-First e podem identificar qual abordagem utilizaram em seus projetos
4. **Acesso a ferramentas de survey**: Ferramentas gratuitas ou de baixo custo para criação e distribuição de surveys estarão disponíveis (ex: Google Forms, Typeform, SurveyMonkey)
5. **Tempo de resposta**: Os participantes terão tempo disponível para preencher o questionário completo (estimado em 15-20 minutos)
6. **Conexão com internet**: Os participantes terão acesso à internet para acessar e preencher o survey online
7. **Validade das memórias**: As experiências relatadas pelos participantes sobre projetos passados são suficientemente precisas para análise
8. **Diversidade de contexto**: A amostra incluirá participantes de diferentes contextos organizacionais e técnicos, permitindo análise de fatores contextuais

#### 4.4 Restrições

As seguintes limitações práticas impõem limites ao desenho do experimento:

1. **Tempo**: O experimento deve ser concluído dentro do prazo estabelecido para o TCC, limitando o tempo disponível para coleta e análise de dados
2. **Orçamento**: Recursos financeiros limitados (ou inexistentes) para incentivos aos participantes ou ferramentas premium de survey
3. **Acesso a participantes**: Dependência de canais de recrutamento gratuitos (redes sociais, fóruns, grupos profissionais) sem acesso direto a bases de dados de profissionais
4. **Ferramentas**: Uso de ferramentas gratuitas ou de baixo custo, que podem ter limitações em funcionalidades avançadas de análise
5. **Amostra não probabilística**: Dificuldade em obter uma amostra probabilística verdadeiramente aleatória, resultando em amostra de conveniência
6. **Viés de autosseleção**: Participantes que optam por responder podem ter características diferentes daqueles que não respondem
7. **Língua**: O survey será conduzido em português, limitando a participação a profissionais que dominam o idioma
8. **Regras acadêmicas**: Necessidade de seguir normas e prazos estabelecidos pela instituição para TCCs

#### 4.5 Limitações previstas

Os seguintes fatores podem prejudicar a generalização dos resultados (validez externa):

1. **Amostra não representativa**: A amostra pode não ser estatisticamente representativa da população de profissionais que trabalham com arquiteturas distribuídas, limitando a generalização
2. **Viés geográfico**: Se a maioria dos participantes for de uma região específica (ex: Brasil), os resultados podem não ser generalizáveis para outros contextos culturais e organizacionais
3. **Viés de experiência**: Participantes com mais experiência ou interesse no tema podem estar mais propensos a participar, potencialmente superestimando ou subestimando certos aspectos
4. **Contexto específico**: Resultados podem ser influenciados por características específicas dos projetos e organizações dos participantes, não sendo diretamente aplicáveis a todos os contextos
5. **Memória e recall bias**: Relatos sobre experiências passadas podem estar sujeitos a viés de memória, com participantes lembrando-se mais de experiências positivas ou negativas recentes
6. **Definições subjetivas**: A compreensão de "API-First" e "Code-First" pode variar entre participantes, mesmo com definições fornecidas no survey
7. **Falta de grupo controle experimental**: Por ser um survey observacional, não há controle experimental rigoroso sobre variáveis de confusão
8. **Tamanho da amostra**: Se o número de participantes for insuficiente, especialmente para análises estratificadas por grupos, o poder estatístico pode ser limitado

---

### 5. Stakeholders e impacto esperado

#### 5.1 Stakeholders principais

Os principais stakeholders do experimento incluem:

1. **Autor do TCC (Gabriel Lourenço Reis Resende)**
   - Responsável pela execução do experimento, coleta de dados, análise e redação do trabalho

2. **Orientador do TCC**
   - Responsável pela orientação científica, revisão do plano experimental e validação metodológica

3. **Banca examinadora**
   - Avaliará a qualidade científica do trabalho, metodologia e contribuições

4. **Profissionais participantes do survey**
   - Fornecerão dados através de suas respostas ao questionário
   - Podem se beneficiar dos resultados finais do estudo

5. **Comunidade acadêmica**
   - Pesquisadores e estudantes interessados em design de APIs, arquiteturas distribuídas e medição de software

6. **Comunidade de desenvolvedores e arquitetos de software**
   - Profissionais da indústria que podem se beneficiar das evidências e insights gerados pelo estudo

7. **Organizações de software**
   - Empresas que desenvolvem software com arquiteturas distribuídas e que podem usar os resultados para orientar decisões sobre abordagens de design de API

8. **Gestores de tecnologia e líderes técnicos**
   - Tomadores de decisão que precisam escolher entre abordagens de design de API para seus projetos

#### 5.2 Interesses e expectativas dos stakeholders

**Autor do TCC:**
- Completar com sucesso o trabalho de conclusão de curso
- Contribuir com evidências empíricas para a área de engenharia de software
- Desenvolver competências em pesquisa empírica e análise de dados
- Publicar ou apresentar os resultados em eventos acadêmicos ou profissionais

**Orientador:**
- Garantir a qualidade científica e metodológica do trabalho
- Orientar o desenvolvimento de competências de pesquisa do aluno
- Contribuir para o avanço do conhecimento na área

**Banca examinadora:**
- Avaliar a rigorosidade metodológica do estudo
- Verificar a validade e confiabilidade dos resultados
- Avaliar a contribuição científica do trabalho

**Profissionais participantes:**
- Contribuir para o avanço do conhecimento na área
- Potencialmente obter insights sobre as abordagens que utilizam
- Acesso aos resultados finais do estudo (se disponibilizados)

**Comunidade acadêmica:**
- Acesso a evidências empíricas sobre comparação de abordagens de design de API
- Base para pesquisas futuras e estudos de replicação
- Validação ou refutação de hipóteses existentes na literatura

**Comunidade de desenvolvedores:**
- Evidências práticas para orientar decisões de design
- Compreensão de trade-offs entre abordagens
- Identificação de fatores contextuais que influenciam o sucesso

**Organizações de software:**
- Evidências para apoiar decisões estratégicas sobre abordagens de design
- Redução de incerteza na escolha entre API-First e Code-First
- Compreensão de fatores que influenciam o sucesso de cada abordagem

**Gestores de tecnologia:**
- Dados objetivos para fundamentar decisões arquiteturais
- Compreensão de impactos em produtividade, qualidade e colaboração
- Identificação de contextos onde cada abordagem é mais adequada

#### 5.3 Impactos potenciais no processo / produto

**Durante o estudo:**

1. **Carga de trabalho do autor:**
   - Tempo dedicado ao desenvolvimento do questionário, recrutamento de participantes, coleta de dados e análise
   - Impacto no cronograma do TCC e outras atividades acadêmicas

2. **Tempo dos participantes:**
   - Participantes do survey dedicarão aproximadamente 15-20 minutos para preencher o questionário
   - Impacto mínimo, mas ainda assim um investimento de tempo

3. **Recursos computacionais:**
   - Uso de ferramentas de survey online (recursos mínimos)
   - Armazenamento de dados coletados

**Após o estudo:**

1. **Contribuição científica:**
   - Geração de evidências empíricas que podem influenciar futuras pesquisas
   - Base para estudos de replicação ou extensão

2. **Impacto na prática:**
   - Possível influência nas decisões de design de API em organizações que tomarem conhecimento dos resultados
   - Orientação para profissionais que precisam escolher entre abordagens

3. **Desenvolvimento profissional:**
   - Desenvolvimento de competências de pesquisa do autor
   - Potencial publicação em eventos ou periódicos

4. **Processo de desenvolvimento de software:**
   - Se os resultados forem amplamente divulgados, podem influenciar práticas da indústria
   - Potencial adoção mais informada de abordagens baseada em evidências

5. **Produtos de software:**
   - Impacto indireto: decisões mais informadas sobre design de API podem resultar em produtos de melhor qualidade, mais manuteníveis ou mais produtivos
   - Impacto a longo prazo e difícil de medir diretamente

---

### 6. Riscos de alto nível, premissas e critérios de sucesso

#### 6.1 Riscos de alto nível (negócio, técnicos, etc.)

**Riscos relacionados à coleta de dados:**

1. **Baixa taxa de resposta ao survey**
   - **Risco**: Número insuficiente de participantes, comprometendo o poder estatístico e a validade dos resultados
   - **Probabilidade**: Média
   - **Impacto**: Alto
   - **Mitigação**: Diversificação de canais de recrutamento, mensagens claras sobre o propósito, follow-up com lembretes, parcerias com comunidades técnicas

2. **Viés de autosseleção**
   - **Risco**: Participantes com características específicas (ex: mais experientes, mais engajados) podem não representar a população-alvo
   - **Probabilidade**: Média-Alta
   - **Impacto**: Médio
   - **Mitigação**: Análise de características demográficas da amostra, comparação com dados da população quando disponíveis, transparência sobre limitações

3. **Respostas incompletas ou de baixa qualidade**
   - **Risco**: Participantes preencherem o survey de forma apressada ou sem atenção, gerando dados inválidos
   - **Probabilidade**: Média
   - **Impacto**: Médio
   - **Mitigação**: Validação de respostas (ex: perguntas de verificação), remoção de respostas incompletas, design do questionário que incentive respostas cuidadosas

**Riscos relacionados ao cronograma:**

4. **Prazo insuficiente para coleta e análise**
   - **Risco**: Tempo limitado do TCC pode não ser suficiente para coleta adequada de dados e análise completa
   - **Probabilidade**: Média
   - **Impacto**: Alto
   - **Mitigação**: Planejamento realista de cronograma, definição de tamanho mínimo de amostra viável, priorização de análises essenciais

**Riscos técnicos:**

5. **Falhas em ferramentas de survey**
   - **Risco**: Problemas técnicos com a plataforma de survey (perda de dados, indisponibilidade)
   - **Probabilidade**: Baixa
   - **Impacto**: Alto
   - **Mitigação**: Escolha de ferramentas confiáveis, backup de dados, teste prévio da ferramenta, exportação regular de respostas

6. **Problemas de acesso ou compatibilidade**
   - **Risco**: Participantes podem ter dificuldades para acessar o survey devido a problemas de navegação ou compatibilidade
   - **Probabilidade**: Baixa
   - **Impacto**: Baixo-Médio
   - **Mitigação**: Teste do survey em diferentes navegadores e dispositivos, instruções claras, suporte para participantes

**Riscos metodológicos:**

7. **Compreensão inadequada das abordagens**
   - **Risco**: Participantes podem não compreender corretamente as diferenças entre API-First e Code-First, mesmo com definições fornecidas
   - **Probabilidade**: Média
   - **Impacto**: Alto
   - **Mitigação**: Definições claras e exemplos no questionário, perguntas de verificação de compreensão, exclusão de respostas inconsistentes

8. **Amostra desbalanceada entre grupos**
   - **Risco**: Desequilíbrio significativo entre número de participantes que usaram API-First vs. Code-First, dificultando comparações
   - **Probabilidade**: Média
   - **Impacto**: Médio
   - **Mitigação**: Estratégias de recrutamento direcionadas para ambos os grupos, análise de sensibilidade, uso de técnicas estatísticas apropriadas para amostras desbalanceadas

**Riscos de validade:**

11. **Viés de memória e recall**
    - **Risco**: Relatos sobre experiências passadas podem estar sujeitos a viés de memória
    - **Probabilidade**: Alta
    - **Impacto**: Médio
    - **Mitigação**: Foco em experiências recentes quando possível, perguntas sobre projetos específicos, transparência sobre limitações

12. **Falta de representatividade geográfica ou organizacional**
    - **Risco**: Amostra concentrada em uma região ou tipo de organização, limitando generalização
    - **Probabilidade**: Média-Alta
    - **Impacto**: Médio
    - **Mitigação**: Diversificação de canais de recrutamento, análise de características da amostra, discussão de limitações de generalização

#### 6.2 Critérios de sucesso globais (go / no-go)

O experimento será considerado bem-sucedido e útil se os seguintes critérios forem atendidos:

**Critérios de prontidão (go/no-go para início da coleta):**

1. **Questionário validado**: Questionário revisado pelo orientador e testado em piloto (se aplicável)
2. **Canais de recrutamento definidos**: Pelo menos 3 canais diferentes identificados para recrutamento de participantes
3. **Ferramenta de survey funcional**: Plataforma de survey testada e pronta para coleta
4. **Plano de análise definido**: Estratégia de análise de dados documentada e aprovada

**Critérios de sucesso na coleta de dados:**

5. **Tamanho mínimo de amostra**: Pelo menos 50 participantes válidos no total
6. **Balanceamento mínimo**: Pelo menos 20 participantes em cada grupo (API-First e Code-First/nenhum)
7. **Taxa de resposta completa**: Pelo menos 80% dos questionários iniciados são completados
8. **Qualidade dos dados**: Menos de 10% de respostas inválidas ou inconsistentes

**Critérios de sucesso na análise:**
9. **Responder às questões de pesquisa**: Todas as 12 questões de pesquisa podem ser respondidas com os dados coletados
10. **Análise estatística adequada**: Análises estatísticas apropriadas aplicadas conforme planejado
11. **Insights identificados**: Pelo menos 3 insights principais ou padrões identificados sobre as abordagens
12. **Fatores contextuais identificados**: Pelo menos 2 fatores contextuais que influenciam a escolha/sucesso são identificados

**Critérios de sucesso do trabalho:**

13. **Documentação completa**: Todos os artefatos do experimento documentados (plano, questionário, dados, análise)
14. **Resultados comunicados**: Resultados apresentados de forma clara no TCC
15. **Contribuição científica**: Trabalho contribui com evidências empíricas para a área
16. **Aprovação da banca**: TCC aprovado pela banca examinadora

**Critérios de no-go (não prosseguir):**

- Impossibilidade de recrutar pelo menos 30 participantes após esforços significativos
- Dados coletados revelam problemas metodológicos críticos que não podem ser corrigidos
- Mudanças significativas no contexto que tornam o experimento irrelevante ou inviável

#### 6.3 Critérios de parada antecipada (pré-execução)

O experimento deve ser **adiado ou cancelado** antes de iniciar a coleta de dados se qualquer uma das seguintes situações ocorrer:

1. **Falta de recursos críticos**
   - Indisponibilidade de ferramentas de survey ou recursos computacionais necessários
   - **Ação**: Busca de alternativas ou adiamento até disponibilidade de recursos

2. **Mudanças significativas no contexto**
   - Mudanças no escopo do TCC, orientação ou requisitos acadêmicos que tornem o experimento inviável
   - **Ação**: Revisão do plano experimental ou redefinição do escopo

3. **Problemas metodológicos críticos identificados**
   - Identificação de problemas metodológicos fundamentais que comprometam a validade do estudo e não possam ser corrigidos
   - **Ação**: Revisão metodológica ou reformulação do experimento

4. **Falta de viabilidade de recrutamento**
   - Evidências claras de que não será possível recrutar número mínimo de participantes mesmo após esforços significativos
   - **Ação**: Revisão da estratégia de recrutamento ou ajuste do tamanho mínimo de amostra


**Durante a coleta de dados**, o experimento deve ser **interrompido temporariamente** se:

- Taxa de resposta extremamente baixa
- Problemas técnicos críticos com a plataforma de survey que resultem em perda de dados

**Após a coleta**, o experimento pode ser considerado **incompleto** (mas não cancelado) se:

- Tamanho da amostra ficar significativamente abaixo do mínimo planejado (< 30 participantes)
- Qualidade dos dados for insuficiente para análises válidas (> 30% de respostas inválidas)
- Dados coletados não permitirem responder às questões de pesquisa principais

Nesses casos, o experimento pode ser ajustado ou os resultados podem ser apresentados com limitações claramente documentadas.

---

### 7. Modelo conceitual e hipóteses

#### 7.1 Modelo conceitual do experimento

O modelo conceitual deste experimento postula que a escolha entre as abordagens **API-First** e **Code-First** para design de APIs em arquiteturas distribuídas influencia múltiplas dimensões de resultado através de diferentes mecanismos e fatores contextuais.

**Modelo de influência direta:**
- A abordagem de design (API-First vs. Code-First) atua como fator principal que influencia diretamente:
  - **Produtividade**: API-First pode reduzir tempo de desenvolvimento através de desenvolvimento paralelo e contratos claros, enquanto Code-First pode acelerar prototipação inicial
  - **Qualidade**: API-First pode melhorar qualidade através de especificação prévia e validação antecipada, enquanto Code-First pode ter maior risco de inconsistências entre especificação e implementação
  - **Colaboração**: API-First pode facilitar colaboração entre equipes através de contratos explícitos, enquanto Code-First pode exigir mais comunicação ad-hoc
  - **Manutenibilidade**: API-First pode melhorar manutenibilidade através de documentação gerada e contratos versionados, enquanto Code-First pode ter documentação desatualizada

**Modelo de influência contextual:**
- Fatores contextuais moderam a relação entre abordagem e resultados:
  - **Tipo de organização**: Startups podem se beneficiar mais de Code-First (velocidade), enquanto grandes organizações podem preferir API-First (governança)
  - **Tamanho da equipe**: Equipes maiores podem se beneficiar mais de API-First (coordenação), enquanto equipes pequenas podem preferir Code-First (simplicidade)
  - **Experiência dos profissionais**: Profissionais mais experientes podem extrair mais benefícios de API-First devido à compreensão de arquiteturas complexas

**Modelo de medição:**
- As dimensões de resultado são medidas através de:
  - Percepções subjetivas dos profissionais (escalas Likert)
  - Métricas objetivas relatadas (tempo, frequência, percentuais)
  - Identificação qualitativa de vantagens e desvantagens


#### 7.2 Hipóteses formais (H0, H1)

As hipóteses são formuladas para as principais questões de pesquisa, considerando comparações entre profissionais que utilizaram API-First e aqueles que utilizaram apenas Code-First.

**Hipóteses relacionadas ao Objetivo O1 (Vantagens e Produtividade):**

**H1.1**: Profissionais que utilizaram API-First percebem mais vantagens em relação à produtividade do que profissionais que utilizaram apenas Code-First.
- **H0.1**: Não há diferença na percepção de vantagens relacionadas à produtividade entre os grupos
- **H1.1**: Profissionais que utilizaram API-First percebem significativamente mais vantagens relacionadas à produtividade (M4 maior)

**H1.2**: Profissionais que utilizaram API-First relatam maior qualidade percebida do código do que profissionais que utilizaram apenas Code-First.
- **H0.2**: Não há diferença na qualidade percebida do código entre os grupos
- **H1.2**: Profissionais que utilizaram API-First relatam significativamente maior qualidade percebida (M5 maior)

**Hipóteses relacionadas ao Objetivo O2 (Desvantagens e Complexidade):**

**H2.1**: Profissionais que utilizaram API-First percebem mais desvantagens relacionadas à complexidade do que profissionais que utilizaram apenas Code-First.
- **H0.3**: Não há diferença na percepção de desvantagens relacionadas à complexidade entre os grupos
- **H1.3**: Profissionais que utilizaram API-First percebem significativamente mais desvantagens relacionadas à complexidade (M9, M10 maiores)

**H2.2**: Profissionais que utilizaram API-First relatam maior tempo de curva de aprendizado do que profissionais que utilizaram apenas Code-First.
- **H0.4**: Não há diferença no tempo de curva de aprendizado entre os grupos
- **H1.4**: Profissionais que utilizaram API-First relatam significativamente maior tempo de curva de aprendizado (M12 maior)

**Hipóteses relacionadas ao Objetivo O3 (Colaboração e Documentação):**

**H3.1**: Profissionais que utilizaram API-First percebem maior nível de colaboração entre equipes do que profissionais que utilizaram apenas Code-First.
- **H0.5**: Não há diferença no nível de colaboração percebida entre os grupos
- **H1.5**: Profissionais que utilizaram API-First percebem significativamente maior nível de colaboração (M13 maior, M14 menor)

**H3.2**: Profissionais que utilizaram API-First relatam maior qualidade e completude da documentação do que profissionais que utilizaram apenas Code-First.
- **H0.6**: Não há diferença na qualidade e completude da documentação entre os grupos
- **H1.6**: Profissionais que utilizaram API-First relatam significativamente maior qualidade e completude da documentação (M15, M16 maiores)

**Hipóteses relacionadas ao Objetivo O4 (Fatores Contextuais):**

**H4.1**: O tipo de organização influencia a preferência entre API-First e Code-First.
- **H0.7**: Não há associação entre tipo de organização e preferência de abordagem
- **H1.7**: Existe associação significativa entre tipo de organização e preferência de abordagem (M19 mostra distribuições diferentes)

**H4.2**: A experiência dos profissionais influencia a preferência entre API-First e Code-First.
- **H0.8**: Não há associação entre experiência profissional e preferência de abordagem
- **H1.8**: Existe associação significativa entre experiência profissional e preferência de abordagem (M21, M22 mostram diferenças)

#### 7.3 Nível de significância e considerações de poder

**Nível de significância (α):**  **α = 0,05** <br> Será utilizado o nível de significância padrão de 5% para testes estatísticos
Como o experimento será conduzido no contexto de uma disciplina, o tamanho da amostra tende a ser reduzido. Consequentemente, o poder estatístico poderá ser limitado, o que dificulta a detecção de efeitos de pequena magnitude. Diante disso, a interpretação dos resultados considerará não apenas os testes de significância estatística, mas também os tamanhos de efeito e a coerência dos achados em relação ao modelo conceitual adotado e à literatura existente. Essa abordagem permite uma análise mais robusta, mesmo em cenários com restrições amostrais.

---

### 8. Variáveis, fatores, tratamentos e objetos de estudo

#### 8.1 Objetos de estudo

Os objetos de estudo neste experimento são as experiências e percepções dos profissionais que trabalharam com design de APIs em arquiteturas distribuídas. Especificamente:

- **Experiências profissionais relatadas**: Projetos reais nos quais os participantes trabalharam utilizando abordagens API-First ou Code-First
- **Percepções e avaliações subjetivas**: Opiniões, avaliações e julgamentos dos participantes sobre vantagens, desvantagens e impacto das abordagens
- **Métricas autorrelatadas**: Dados quantitativos fornecidos pelos participantes sobre tempo, frequência, percentuais e outras medidas relacionadas às suas experiências
- **Fatores contextuais**: Características dos projetos, organizações e contextos técnicos nos quais as abordagens foram utilizadas


#### 8.2 Sujeitos / participantes (visão geral)

Os participantes deste estudo são profissionais da indústria de software que possuem experiência prática em design e implementação de APIs em arquiteturas distribuídas. Especificamente:

- **Perfil principal**: Desenvolvedores de software, arquitetos de software, tech leads e engenheiros de software
- **Experiência mínima**: Profissionais com pelo menos 1 ano de experiência trabalhando com arquiteturas distribuídas
- **Contexto de trabalho**: Profissionais que trabalham ou trabalharam em projetos que utilizam arquiteturas distribuídas (microsserviços, SOA, sistemas orientados a eventos)
- **Conhecimento necessário**: Compreensão prática das diferenças entre API-First e Code-First (ou capacidade de identificar qual abordagem utilizaram)
- **Diversidade**: Participantes de diferentes tipos de organizações (startups, médio porte, grandes empresas)

Os participantes serão divididos em dois grupos principais baseados em sua experiência:
- **Grupo 1**: Profissionais que já utilizaram a abordagem API-First em pelo menos um projeto
- **Grupo 2**: Profissionais que nunca utilizaram API-First (ou utilizaram apenas Code-First)

#### 8.3 Variáveis independentes (fatores) e seus níveis

**Fator principal (manipulado através de seleção de grupos):**

| Fator | Níveis | Descrição |
|-------|--------|-----------|
| **Abordagem de Design** | API-First | Participantes que utilizaram API-First em pelo menos um projeto |
| | Code-First | Participantes que nunca utilizaram o modelo API-First |

**Fatores contextuais (variáveis de agrupamento/estratificação):**

| Fator | Níveis | Descrição |
|-------|--------|-----------|
| **Tipo de Organização** | Startup | Empresas em estágio inicial ou de pequeno porte |
| | Médio Porte | Empresas de médio porte |
| | Grande Porte | Grandes corporações |
| **Tamanho da Equipe** | Pequena (1-5 pessoas) | Equipes pequenas |
| | Média (6-15 pessoas) | Equipes de tamanho médio |
| | Grande (16+ pessoas) | Equipes grandes |
| **Anos de Experiência** | Junior | Profissionais iniciantes na carreira |
| | Pleno | Profissionais intermediários na carreira |
| | Senior | Profissionais avançados na carreira |

#### 8.4 Tratamentos (condições experimentais)

Este estudo utiliza um desenho observacional comparativo com dois grupos principais baseados na experiência dos participantes:

**Tratamento 1 - Grupo API-First:**
- **Descrição**: Participantes que já utilizaram a abordagem API-First em pelo menos um projeto profissional
- **Critério de inclusão**: Resposta afirmativa à pergunta sobre experiência com API-First e capacidade de descrever essa experiência
- **O que distingue**: Experiência prática com design de API onde a especificação foi criada antes da implementação
- **Número esperado**: Mínimo de 20 participantes, idealmente 30-40

**Tratamento 2 - Grupo Code-First (Grupo de Comparação):**
- **Descrição**: Participantes que nunca utilizaram API-First ou utilizaram apenas Code-First (onde a API é gerada a partir do código)
- **Critério de inclusão**: Resposta negativa à pergunta sobre experiência com API-First OU experiência apenas com Code-First
- **O que distingue**: Experiência prática apenas com abordagem onde a API é implementada diretamente no código
- **Número esperado**: Mínimo de 20 participantes, idealmente 30-40

#### 8.5 Variáveis dependentes (respostas)

As variáveis dependentes são medidas através de respostas ao questionário e incluem métricas quantitativas e qualitativas. A tabela abaixo apresenta todas as variáveis dependentes organizadas por dimensão:

**Tabela de Variáveis Dependentes:**

| ID | Nome da Variável | Descrição | Tipo | Escala/Unidade |
|----|-----------------|-----------|------|----------------|
| **Dimensão: Vantagens e Produtividade** |
| M1 | Número de Vantagens Identificadas | Quantidade total de vantagens distintas mencionadas | Quantitativa | Número inteiro |
| M2 | Frequência de Menção de Vantagens | Quantas vezes cada vantagem foi mencionada | Quantitativa | Número inteiro |
| M3 | Score Médio de Importância das Vantagens | Média das avaliações de importância | Quantitativa | Escala Likert (1-5) |
| M4 | Produtividade Percebida | Autoavaliação sobre produtividade | Quantitativa | Escala Likert (1-5) |
| M5 | Qualidade Percebida do Código | Autoavaliação sobre qualidade do código | Quantitativa | Escala Likert (1-5) |
| **Dimensão: Desvantagens e Complexidade** |
| M6 | Número de Desvantagens Identificadas | Quantidade total de desvantagens distintas mencionadas | Quantitativa | Número inteiro |
| M7 | Frequência de Menção de Desvantagens | Quantas vezes cada desvantagem foi mencionada | Quantitativa | Número inteiro |
| M8 | Score Médio de Severidade das Desvantagens | Média das avaliações de severidade | Quantitativa | Escala Likert (1-5) |
| M9 | Complexidade Percebida do Processo | Autoavaliação sobre complexidade | Quantitativa | Escala Likert (1-5) |
| M10 | Número de Ferramentas Necessárias | Quantidade média de ferramentas a aprender | Quantitativa | Número inteiro |
| M11 | Tempo Médio de Manutenção | Tempo médio gasto em manutenção | Quantitativa | Horas/dias por mês |
| M12 | Tempo de Curva de Aprendizado | Tempo para se tornar produtivo | Quantitativa | Semanas ou meses |
| **Dimensão: Colaboração e Documentação** |
| M13 | Nível de Colaboração Percebida | Autoavaliação sobre colaboração entre equipes | Quantitativa | Escala Likert (1-5) |
| M14 | Frequência de Comunicação entre Equipes | Número médio de interações necessárias | Quantitativa | Número de interações |
| M15 | Completude da Documentação | Percentual de APIs com documentação completa | Quantitativa | Percentual (%) |
| M16 | Qualidade Percebida da Documentação | Autoavaliação sobre qualidade da documentação | Quantitativa | Escala Likert (1-5) |
| M17 | Tempo Médio de Integração | Tempo necessário para integrar novo serviço | Quantitativa | Horas ou dias |
| M18 | Taxa de Sucesso de Integrações | Proporção de integrações bem-sucedidas na primeira tentativa | Quantitativa | Percentual (%) |
| **Dimensão: Fatores Contextuais** |
| M19 | Distribuição por Tipo de Organização | Proporção de participantes por tipo de organização | Quantitativa | Percentual (%) |
| M20 | Distribuição por Tamanho de Equipe | Tamanho médio da equipe de desenvolvimento | Quantitativa | Número de pessoas |
| M21 | Anos de Experiência Média | Anos médios de experiência profissional | Quantitativa | Anos |
| M22 | Preferência por Abordagem | Proporção de participantes que preferem cada abordagem | Quantitativa | Percentual (%) |
| **Dimensão: Qualitativa** |
| VQ1 | Lista de Vantagens Identificadas | Lista qualitativa de vantagens mencionadas | Qualitativa | Texto livre |
| VQ2 | Lista de Desvantagens Identificadas | Lista qualitativa de desvantagens mencionadas | Qualitativa | Texto livre |
| VQ3 | Comentários e Observações | Comentários adicionais dos participantes | Qualitativa | Texto livre |

#### 8.6 Variáveis de controle / bloqueio

As seguintes variáveis serão controladas ou utilizadas para estratificação/bloqueio, mas não são o foco principal do estudo:

| Variável de Controle | Método de Controle | Justificativa |
|---------------------|-------------------|---------------|
| **Experiência Profissional** | Estratificação em blocos (iniciante, intermediário, avançado) | Controlar efeito da experiência nas percepções |
| **Tipo de Organização** | Análise estratificada por tipo | Identificar se resultados variam por contexto organizacional |
| **Tamanho da Equipe** | Análise estratificada por tamanho | Controlar efeito do tamanho da equipe na colaboração |
| **Tempo desde a experiência** | Pergunta sobre recência da experiência | Controlar viés de memória (priorizar experiências recentes) |
| **Idioma do questionário** | Fixo em português | Garantir compreensão uniforme |
| **Formato do questionário** | Mesmo questionário para todos | Garantir consistência na coleta |

#### 8.7 Possíveis variáveis de confusão conhecidas

Variáveis que podem distorcer os resultados e que serão monitoradas:

| Variável de Confusão | Impacto Potencial | Estratégia de Monitoramento/Mitigação |
|---------------------|------------------|--------------------------------------|
| **Viés de autosseleção** | Participantes mais experientes ou engajados podem estar mais propensos a participar | Análise de características demográficas da amostra; comparação com população-alvo quando possível |
| **Compreensão das definições** | Diferentes interpretações de "API-First" e "Code-First" | Definições claras no questionário; perguntas de verificação de compreensão |
| **Contexto organizacional específico** | Características específicas da organização podem influenciar mais que a abordagem | Coleta de dados sobre contexto organizacional; análise estratificada |
| **Motivação e engajamento** | Participantes com maior motivação podem ter experiências diferentes | Análise de qualidade das respostas; identificação de respostas apressadas |
| **Maturidade do projeto** | Projetos em diferentes estágios podem ter necessidades diferentes | Pergunta sobre estágio do projeto; análise considerando maturidade |

---

### 9. Desenho experimental

#### 9.1 Tipo de desenho (completamente randomizado, blocos, fatorial, etc.)

**Tipo de desenho**: **Estudo observacional comparativo (quase-experimental) com grupos não equivalentes**

Este estudo utiliza um desenho observacional baseado em survey, onde os participantes são agrupados naturalmente baseados em sua experiência prévia (API-First vs. Code-First), sem randomização experimental. O desenho pode ser caracterizado como:

- **Estudo transversal**: Coleta de dados em um único ponto no tempo sobre experiências passadas
- **Desenho de grupos comparativos**: Comparação entre dois grupos baseados em experiência prévia
- **Desenho quase-experimental**: Não há randomização, mas há comparação sistemática entre grupos


#### 9.2 Randomização e alocação

**Randomização**: **Não aplicável** (estudo observacional)

Como este é um estudo observacional baseado em survey, não há randomização experimental de participantes para tratamentos. Os participantes são alocados naturalmente aos grupos baseados em sua experiência prévia:

- **Grupo API-First**: Participantes que já utilizaram API-First
- **Grupo Code-First**: Participantes que nunca utilizaram API-First

**Alocação aos grupos:**

A alocação ocorre através de **autoclassificação** baseada em respostas ao questionário:

**Pergunta de triagem**: "Você já utilizou a abordagem API-First em algum projeto profissional?"
   - Resposta "Sim" → Grupo API-First

#### 9.3 Balanceamento e contrabalanço

**Balanceamento entre grupos:**

Como não há randomização experimental, o balanceamento será verificado e, quando possível, ajustado através de:

1. **Análise de características demográficas**:
   - Comparação de distribuições de idade, experiência, tipo de organização, tamanho de equipe entre grupos
   - Identificação de desequilíbrios significativos

2. **Recrutamento direcionado**:
   - Estratégias de recrutamento específicas para garantir representação adequada em ambos os grupos
   - Monitoramento do balanceamento durante a coleta de dados

**Contrabalanço (efeitos de ordem):**

Como cada participante responde apenas uma vez ao questionário (não há múltiplas sessões), não há efeitos de ordem entre tratamentos. No entanto, serão aplicadas estratégias de contrabalanço para elementos internos do questionário:

#### 9.4 Número de grupos e sessões

**Número de grupos**: **2 grupos principais**

1. **Grupo API-First**: Participantes com experiência em API-First
2. **Grupo Code-First**: Participantes sem experiência em API-First (apenas Code-First)

**Subgrupos para análises estratificadas** (não são grupos experimentais separados, mas estratificações para análise):

- Por tipo de organização (3 níveis: Startup, Médio Porte, Grande Porte)
- Por tamanho de equipe (3 níveis: Pequena, Média, Grande)
- Por experiência profissional (3 níveis: Júnior, Pleno, Sênior)

**Número de sessões**: **1 sessão por participante**

Cada participante preenche o questionário uma única vez, estimado em 15-20 minutos. Não há múltiplas sessões ou rodadas experimentais.

**Tamanho planejado dos grupos:**

- **Total de participantes**: Mínimo de 50, idealmente 60-80
- **Grupo API-First**: Mínimo de 20, idealmente 30-40
- **Grupo Code-First**: Mínimo de 20, idealmente 30-40

**Considerações para análises estratificadas:**

Análises por subgrupos terão tamanhos de amostra menores, limitando o poder estatístico. Análises estratificadas serão interpretadas com cautela e focarão em padrões qualitativos quando o tamanho da amostra for insuficiente para inferência estatística robusta.

**Tabela de Fatores, Tratamentos e Combinações:**

| Fator Principal | Níveis/Tratamentos | Descrição | Critério de Alocação |
|----------------|-------------------|-----------|---------------------|
| **Abordagem de Design** | API-First | Participantes com experiência em API-First | Resposta "Sim" à pergunta sobre experiência com API-First + validação através de descrição da experiência |
| | Code-First | Participantes sem experiência em API-First (apenas Code-First) | Resposta "Não" à pergunta sobre experiência com API-First OU experiência apenas com Code-First |

**Combinações de Fatores (para análises estratificadas):**

| Combinação | Abordagem | Tipo de Org. | Tamanho Equipe | Experiência |
|-----------|-----------|--------------|----------------|-------------|
| 1 | API-First | Startup | Pequena | Júnior |
| 2 | API-First | Startup | Pequena | Pleno |
| 3 | API-First | Médio Porte | Média | Sênior |
| 4 | Code-First | Grande Porte | Grande | Pleno |
| ... | ... | ... | ... | ... |


---

### 10. População, sujeitos e amostragem

#### 10.1 População-alvo

A população-alvo deste experimento compreende profissionais da indústria de software que trabalham ou trabalharam em projetos com arquiteturas distribuídas, especificamente:

- Desenvolvedores de software, arquitetos de software, tech leads e engenheiros de software que possuem experiência prática em design e implementação de APIs
- Profissionais que atuam ou atuaram em organizações de diferentes portes (startups, empresas de médio porte e grandes corporações)
- Profissionais que trabalham ou trabalharam em projetos que utilizam arquiteturas distribuídas, incluindo:
  - Sistemas baseados em microsserviços
  - Arquiteturas orientadas a serviços (SOA)
  - Sistemas orientados a eventos
  - Outras arquiteturas distribuídas modernas
- Profissionais com experiência mínima de 1 ano trabalhando com arquiteturas distribuídas
- Profissionais que têm ou tiveram experiência prática com pelo menos uma das abordagens** (API-First ou Code-First) em projetos reais

#### 10.2 Critérios de inclusão de sujeitos

Para ser elegível para participar do estudo, o participante deve atender a **todos** os seguintes critérios:

1. **Experiência profissional mínima**:
   - Pelo menos 1 ano de experiência trabalhando com arquiteturas distribuídas
   - Experiência prática em design e/ou implementação de APIs

2. **Experiência com abordagens de design de API**:
   - Ter trabalhado em pelo menos um projeto profissional utilizando API-First OU Code-First
   - Capacidade de identificar e descrever qual abordagem foi utilizada

3. **Papel profissional relevante**:
   - Desenvolvedor de software, arquitetos de software, tech lead, engenheiro de software, ou papel similar
   - Participação ativa em projetos de desenvolvimento de software

4. **Compreensão das abordagens**:
   - Capacidade de compreender as definições de API-First e Code-First fornecidas no questionário
   - Capacidade de responder perguntas sobre suas experiências com as abordagens

5. **Disponibilidade e consentimento**:
   - Disponibilidade para preencher o questionário completo (estimado em 15-20 minutos)
   - Consentimento informado para participação no estudo
   - Acesso à internet e capacidade de acessar a plataforma de survey

#### 10.3 Critérios de exclusão de sujeitos

Os seguintes critérios **impedem** a participação no estudo:

1. **Falta de experiência relevante**:
   - Menos de 1 ano de experiência com arquiteturas distribuídas
   - Nenhuma experiência prática em design ou implementação de APIs
   - Apenas experiência teórica ou acadêmica, sem experiência profissional prática

2. **Incapacidade de identificar abordagem utilizada**:
   - Participantes que não conseguem identificar qual abordagem (API-First ou Code-First) utilizaram em seus projetos
   - Participantes que não conseguem descrever adequadamente sua experiência após receberem as definições

3. **Conflitos de interesse**:
   - Participantes que trabalham diretamente com o pesquisador em projetos relacionados
   - Participantes que têm relação profissional ou pessoal que possa comprometer a objetividade das respostas

4. **Restrições legais ou éticas**:
   - Menores de idade (sem consentimento de responsável legal, se aplicável)
   - Participantes que não podem fornecer consentimento informado válido

5. **Respostas inválidas ou inconsistentes**:
   - Participantes que fornecem respostas claramente inconsistentes ou inválidas
   - Participantes que não completam seções críticas do questionário
   - Respostas que indicam falta de compreensão das perguntas ou das abordagens

6. **Participação duplicada**:
   - Participantes que já responderam ao questionário anteriormente (identificados através de controles técnicos ou análise de respostas)

#### 10.4 Tamanho da amostra planejado (por grupo)

**Tamanho total da amostra:**
- **Mínimo**: 50 participantes válidos
- **Ideal**: 60-80 participantes válidos
- **Máximo viável**: 100 participantes (considerando restrições de tempo e recursos)

**Tamanho por grupo:**
- **Grupo API-First**: 
  - Mínimo: 20 participantes
  - Ideal: 30-40 participantes
- **Grupo Code-First**: 
  - Mínimo: 20 participantes
  - Ideal: 30-40 participantes

#### 10.5 Método de seleção / recrutamento

**Estratégias de recrutamento:**

1. **Canais de recrutamento primários**:
   - **Redes sociais profissionais**: LinkedIn (posts em grupos de desenvolvedores, arquitetos de software)
   - **Fóruns e comunidades técnicas**: Reddit (r/softwaredevelopment, r/programming), Stack Overflow, Dev.to
   - **Grupos de WhatsApp/Telegram**: Grupos de desenvolvedores, arquitetos de software, comunidades técnicas
   - **Comunidades acadêmicas e profissionais**: Grupos de ex-alunos, comunidades de PUC Minas, grupos de profissionais de software

2. **Canais de recrutamento secundários**:
   - **Amostra por bola de neve**: Solicitação aos participantes iniciais para compartilhar o survey com colegas elegíveis
   - **Parcerias com comunidades**: Contato com organizadores de meetups, comunidades técnicas, grupos de estudo
   - **Divulgação em eventos**: Se houver oportunidade, divulgação em eventos de tecnologia (presenciais ou online)

3. **Mensagens de recrutamento**:
   - Mensagem clara sobre o propósito do estudo
   - Tempo estimado de preenchimento (15-20 minutos)
   - Benefícios de participação (acesso aos resultados, contribuição para pesquisa)
   - Garantia de anonimato e confidencialidade
   - Link direto para o questionário

4. **Controle de qualidade**:
   - Verificação de critérios de elegibilidade através de perguntas de triagem no início do questionário
   - Exclusão automática de participantes que não atendem critérios mínimos
   - Análise de respostas para identificar participação duplicada ou inválida

#### 10.6 Treinamento e preparação dos sujeitos

**Estratégia de preparação:**

Como este é um estudo observacional baseado em survey sobre experiências passadas, não há necessidade de treinamento extensivo. No entanto, será fornecido material preparatório para garantir compreensão adequada das abordagens e reduzir viés por falta de conhecimento.

**Materiais de preparação fornecidos no questionário:**

1. **Seção introdutória com definições claras**:
   - **Definição de API-First**: 
     - "Abordagem onde a especificação da API (OpenAPI/Swagger, GraphQL Schema, Protocol Buffers) é criada antes da implementação, servindo como contrato entre equipes e permitindo desenvolvimento paralelo. A especificação é o artefato principal e a implementação segue a especificação."
   - **Definição de Code-First**: 
     - "Abordagem onde a API é implementada diretamente no código e a documentação/especificação é gerada automaticamente a partir do código. O código é o artefato principal e a especificação é derivada do código."
   - **Exemplos práticos** de cada abordagem
   - **Diferenças principais** entre as abordagens

2. **Perguntas de verificação de compreensão**:
   - Após as definições, perguntas que verificam se o participante compreendeu as diferenças
   - Exemplos de cenários para que o participante identifique qual abordagem está sendo descrita
   - Se o participante não conseguir responder corretamente, será direcionado para releitura das definições ou excluído se não houver compreensão

3. **Instruções claras sobre o preenchimento**:
   - Instruções sobre como responder cada tipo de pergunta (escalas Likert, questões abertas, múltipla escolha)
   - Explicação sobre a importância de respostas honestas e baseadas em experiências reais
   - Estimativa de tempo de preenchimento

4. **Contextualização do estudo**:
   - Explicação do propósito do estudo
   - Garantia de anonimato e confidencialidade
   - Informação sobre como os dados serão utilizados

---

### 11. Instrumentação e protocolo operacional

#### 11.1 Instrumentos de coleta (questionários, logs, planilhas, etc.)

**Questionário Online (Instrumento Principal)**

- **Ferramenta**: Google Forms, Typeform ou SurveyMonkey (ferramenta gratuita ou de baixo custo)
- **Formato**: Questionário web estruturado com múltiplas seções
- **Papel**: Coleta de dados primários sobre experiências, percepções e métricas dos participantes
- **Estrutura prevista**:
  - Seção 1: Consentimento informado e informações sobre o estudo
  - Seção 2: Definições de API-First e Code-First
  - Seção 3: Perguntas de triagem e classificação em grupos
  - Seção 4: Dados demográficos e contextuais (tipo de organização, tamanho de equipe, experiência)
  - Seção 5: Experiências e percepções sobre a abordagem utilizada
  - Seção 6: Comparações e avaliações (escalas Likert, questões abertas)
  - Seção 7: Fatores contextuais e preferências
  - Seção 8: Comentários adicionais (opcional)
- **Características técnicas**:
  - Respostas anônimas (sem coleta de identificadores pessoais)
  - Exportação de dados em formato CSV/Excel
  - Validação de respostas obrigatórias
  - Lógica condicional para direcionamento baseado em respostas

#### 11.2 Materiais de suporte (instruções, guias)

**Para Participantes:**

1. **Página de Introdução do Questionário**:
   - Título do estudo
   - Breve descrição do objetivo
   - Tempo estimado de preenchimento (15-20 minutos)
   - Garantia de anonimato
   - Informações de contato do pesquisador

2. **Seção de Definições**:
   - Definições claras e concisas de API-First e Code-First
   - Exemplos práticos de cada abordagem
   - Tabela comparativa destacando diferenças principais
   - Ilustrações ou diagramas (se aplicável)

3. **Instruções de Preenchimento**:
   - Como responder escalas Likert (explicação da escala 1-5)
   - Como responder questões abertas (exemplos de respostas esperadas)
   - Indicação de questões obrigatórias vs. opcionais
   - Instruções sobre como navegar entre seções

4. **Perguntas de Verificação de Compreensão**:
   - Questões que verificam se o participante compreendeu as definições
   - Feedback imediato sobre respostas incorretas
   - Opção de reler definições antes de continuar

#### 11.3 Procedimento experimental (protocolo – visão passo a passo)

**FASE 1: PREPARAÇÃO (Antes da Coleta)**

1. **Desenvolvimento do Questionário**:
   - Criar estrutura do questionário baseada no plano experimental
   - Incluir todas as seções definidas (consentimento, definições, triagem, coleta de dados)
   - Configurar lógica condicional para direcionamento baseado em respostas
   - Configurar validações de respostas obrigatórias
   - Testar navegação e funcionalidades

2. **Revisão e Validação**:
   - Revisão do questionário pelo orientador
   - Teste piloto com 3-5 participantes (ver seção 11.4)
   - Ajustes baseados em feedback do piloto
   - Validação final do questionário

3. **Configuração Técnica**:
   - Configurar anonimato na plataforma
   - Configurar exportação de dados
   - Testar em diferentes navegadores e dispositivos

4. **Preparação de Materiais de Recrutamento**:
   - Preparar mensagens de recrutamento para diferentes canais
   - Preparar calendário de divulgação
   - Identificar canais de recrutamento

**FASE 2: COLETA DE DADOS**

6. **Início da Coleta**:
   - Publicar questionário online

7. **Divulgação Inicial**:
   - Publicar mensagens de recrutamento

8. **Validação de Respostas (Contínuo)**:
    - Revisar respostas recebidas

9. **Encerramento da Coleta**:
    - Fechar questionário para novas respostas
    - Exportar dados finais em formato CSV/Excel
    - Fazer backup final dos dados

10. **Organização dos Dados**:
    - Organizar dados em planilha estruturada
    - Codificar variáveis categóricas
    - Criar variáveis derivadas se necessário
    - Documentar estrutura dos dados

**FASE 4: PÓS-COLETA**

11. **Análise de Dados**:
    - Executar análises estatísticas planejadas
    - Realizar análises qualitativas de respostas abertas
    - Gerar visualizações e relatórios

12. **Documentação**:
    - Documentar processo de coleta
    - Registrar problemas encontrados e soluções
    - Documentar decisões sobre exclusão de participantes
    - Preparar relatório de coleta

#### 11.4 Plano de piloto (se haverá piloto, escopo e critérios de ajuste)

**Sim, será realizado um piloto antes da coleta principal.**

**Objetivos do Piloto:**

1. **Validar compreensão das perguntas**:
   - Verificar se os participantes compreendem as definições de API-First e Code-First
   - Identificar perguntas ambíguas ou confusas
   - Verificar se as instruções são claras

2. **Avaliar tempo de preenchimento**:
   - Medir tempo real de preenchimento
   - Verificar se a estimativa de 15-20 minutos é realista
   - Identificar seções que podem ser simplificadas

3. **Testar funcionalidades técnicas**:
   - Verificar funcionamento da lógica condicional
   - Testar validações de respostas
   - Verificar exportação de dados
   - Testar em diferentes navegadores e dispositivos

4. **Identificar problemas de navegação**:
   - Verificar se o fluxo do questionário é intuitivo
   - Identificar pontos de confusão ou abandono
   - Verificar se as instruções são suficientes

5. **Validar critérios de triagem**:
   - Verificar se as perguntas de triagem classificam corretamente os participantes
   - Identificar se há participantes que não se encaixam claramente em nenhum grupo

---

### 12. Plano de análise de dados (pré-execução)

#### 12.1 Estratégia geral de análise (como responderá às questões)

A análise seguirá uma abordagem mista (quantitativa e qualitativa), organizada por objetivos de pesquisa. O processo será: (1) análises descritivas, (2) comparações estatísticas entre grupos, (3) análises qualitativas de respostas abertas.

**Resumo por Objetivo:**

- **O1 (Vantagens)**: Comparar vantagens, produtividade e qualidade percebidas entre grupos usando testes estatísticos e análise de respostas abertas
- **O2 (Desvantagens)**: Comparar desvantagens, complexidade, tempo de manutenção e curva de aprendizado entre grupos
- **O3 (Colaboração e Documentação)**: Comparar colaboração, qualidade da documentação e facilidade de integração entre grupos
- **O4 (Fatores Contextuais)**: Analisar associação entre tipo de organização, tamanho de equipe e experiência profissional com preferência de abordagem

**Análises Adicionais:**
- Análises estratificadas por variáveis de controle (tipo de organização, tamanho de equipe, experiência)
- Integração de insights qualitativos com resultados quantitativos

#### 12.2 Métodos estatísticos planejados

- Estatísticas básicas: médias, medianas, desvios padrão para variáveis quantitativas
- Frequências e percentuais para variáveis categóricas
- Gráficos: histogramas, boxplots, gráficos de barras
- Verificação de normalidade dos dados para escolha de testes apropriados
- Comparação entre grupos (API-First vs. Code-First)

#### 12.3 Tratamento de dados faltantes e outliers

**Dados Faltantes:**

**Regras básicas:**
- **Questões obrigatórias faltantes**: Investigar problema técnico; excluir participante se questões críticas estiverem faltando
- **Respostas qualitativas**: Tratar como "não fornecido", não imputar
- Documentar percentual de dados faltantes e método de tratamento

#### 12.4 Plano de análise para dados qualitativos (se houver)

**Dados Qualitativos:**
- VQ1: Lista de vantagens identificadas (respostas abertas)
- VQ2: Lista de desvantagens identificadas (respostas abertas)
- VQ3: Comentários e observações adicionais

**Estratégia de Análise:**

**Abordagem**: Análise de conteúdo temática com análise de frequência

**Apresentação:** Tabelas de frequência de temas por grupo

---

### 13. Avaliação de validade (ameaças e mitigação)

#### 13.1 Validade de conclusão

Ameaças que podem comprometer a robustez das conclusões estatísticas:

**1. Baixo poder estatístico:**
- **Ameaça**: Tamanho de amostra insuficiente pode não detectar diferenças reais entre grupos (erro tipo II)
- **Mitigação**: 
  - Aceitação de poder reduzido (60-65%) para efeitos médios, mas documentação clara dessa limitação
  - Análises de sensibilidade considerando diferentes tamanhos de efeito

#### 13.2 Validade interna

Ameaças relacionadas a causas alternativas para os efeitos observados:

**1. Viés de seleção (Selection Bias):**
- **Ameaça**: Grupos API-First e Code-First podem diferir sistematicamente em características que influenciam os resultados (ex: experiência, tipo de organização)
- **Estratégia de controle**:
  - Análise de características demográficas e contextuais entre grupos para identificar diferenças
  - Estratificação por variáveis de controle (experiência, tipo de organização, tamanho de equipe)
  - Análises ajustadas usando modelos estatísticos que controlam para variáveis de confusão
  - Matching de participantes por características relevantes quando possível

#### 13.3 Validade de constructo

**Ameaças à validade de constructo:**

**1. Definições ambíguas de API-First e Code-First:**
- **Ameaça**: Diferentes interpretações dos termos podem levar participantes a se classificarem incorretamente
- **Mitigação**:
  - Definições claras e explícitas fornecidas no início do questionário
  - Exemplos práticos de cada abordagem
  - Perguntas de verificação de compreensão
  - Exclusão de participantes que não conseguem descrever adequadamente sua experiência
  - Validação através de descrição da experiência pelos participantes

**2. Medidas não representam os constructos de interesse:**
- **Ameaça**: Métricas escolhidas podem não capturar adequadamente os conceitos (produtividade, qualidade, colaboração)
- **Mitigação**:
  - Uso de múltiplas métricas para medir cada constructo (triangulação)
  - Combinação de medidas quantitativas (escalas Likert) e qualitativas (respostas abertas)
  - Base teórica para escolha de métricas (literatura sobre medição em engenharia de software)
  - Validação através de análise qualitativa que verifica se respostas abertas confirmam métricas quantitativas

**3. Viés de método:**
- **Ameaça**: Todas as medidas são auto-relatadas, podendo introduzir viés sistemático
- **Mitigação**:
  - Reconhecimento explícito da limitação
  - Uso de perguntas sobre comportamentos observáveis quando possível (ex: tempo gasto, frequência de interações)
  - Triangulação com respostas qualitativas que podem revelar inconsistências
  - Documentação clara de que resultados refletem percepções, não medidas objetivas

**4. Ambigüidade na interpretação de escalas:**
- **Ameaça**: Participantes podem interpretar escalas Likert de forma diferente
- **Mitigação**:
  - Instruções claras sobre como usar escalas
  - Rótulos descritivos para cada ponto da escala (ex: 1 = Muito Baixo, 5 = Muito Alto)
  - Consistência no uso de escalas ao longo do questionário
  - Análise de distribuições de respostas para identificar padrões suspeitos

#### 13.4 Validade externa

**Contextos onde os resultados podem ser generalizados:**

1. **Profissionais de software com experiência em arquiteturas distribuídas:**
   - Desenvolvedores, arquitetos, tech leads com pelo menos 1 ano de experiência
   - Profissionais que trabalham em projetos com microsserviços, SOA ou arquiteturas orientadas a eventos
   - Contextos onde decisões sobre design de API são relevantes

2. **Organizações de diferentes portes:**
   - Startups, empresas de médio porte e grandes corporações
   - Diferentes modelos de negócio (produtos, serviços, consultoria)
   - Diferentes setores que desenvolvem software

3. **Contextos técnicos similares:**
   - Projetos que utilizam APIs REST, GraphQL ou outras tecnologias de API
   - Equipes de desenvolvimento de software (frontend, backend, full-stack)
   - Projetos com diferentes níveis de maturidade

**Limitações de generalização:**

1. **Amostra não probabilística:**
   - **Limitação**: Amostra de conveniência pode não representar toda a população
   - **Impacto**: Resultados podem não ser generalizáveis para todos os profissionais da área
   - **Mitigação**: Documentação clara de características da amostra, comparação com dados populacionais quando disponíveis, transparência sobre limitações

2. **Viés de experiência:**
   - **Limitação**: Participantes que optam por responder podem ter características diferentes (mais experientes, mais engajados)
   - **Impacto**: Resultados podem superestimar ou subestimar certos aspectos
   - **Mitigação**: Análise de características demográficas, comparação com população-alvo quando possível

3. **Tipo de projeto específico:**
   - **Limitação**: Experiências relatadas podem ser de tipos específicos de projetos (ex: projetos web, mobile, enterprise)
   - **Impacto**: Resultados podem não se aplicar a todos os tipos de projetos
   - **Mitigação**: Coleta de dados sobre tipo de projeto, análise estratificada por tipo de projeto quando possível

4. **Tamanho da amostra:**
   - **Limitação**: Tamanho mínimo de amostra (50 participantes) pode limitar generalização estatística
   - **Impacto**: Intervalos de confiança mais amplos, menor poder estatístico
   - **Mitigação**: Documentação clara de tamanho da amostra e limitações, interpretação cautelosa

**Estratégias para aumentar validade externa:**

1. **Diversificação da amostra:**
   - Recrutamento através de múltiplos canais
   - Busca de diversidade em tipo de organização, tamanho de equipe, experiência

2. **Documentação detalhada:**
   - Características demográficas e contextuais da amostra
   - Processo de recrutamento e critérios de inclusão/exclusão
   - Limitações de generalização claramente discutidas

3. **Análises estratificadas:**
   - Análises por tipo de organização, tamanho de equipe, experiência
   - Identificação de padrões que se mantêm ou variam entre subgrupos

4. **Transparência metodológica:**
   - Documentação completa do processo experimental
   - Facilitação de replicação em outros contextos

#### 13.5 Resumo das principais ameaças e estratégias de mitigação

| Tipo de Ameaça | Ameaça Específica | Impacto | Estratégia de Mitigação |
|----------------|-------------------|---------|------------------------|
| **Validade de Conclusão** | Baixo poder estatístico | Alto | Tamanho mínimo de amostra planejado; documentação de limitações; análises de sensibilidade |
| **Validade Interna** | Viés de seleção | Alto | Análise de características demográficas; estratificação; análises ajustadas |
| **Validade de Constructo** | Definições ambíguas | Alto | Definições claras; exemplos; perguntas de verificação; validação através de descrição |
| | Medidas não representam constructos | Médio | Múltiplas métricas; triangulação quantitativa/qualitativa; base teórica |
| **Validade Externa** | Amostra não probabilística | Alto | Documentação de características; transparência sobre limitações; diversificação de canais |

---

### 14. Ética, privacidade e conformidade

#### 14.1 Questões éticas (uso de sujeitos, incentivos, etc.)

**Questões éticas identificadas e tratamento:**

**1. Consentimento voluntário e ausência de coerção:**
- **Questão**: Participantes devem participar voluntariamente, sem pressão ou coerção
- **Tratamento**:
  - Participação completamente voluntária
  - Mensagens de recrutamento claras sobre natureza voluntária
  - Direito de retirada a qualquer momento, sem consequências
  - Sem pressão de superiores ou colegas para participar
  - Questionário pode ser abandonado sem penalização

**2. Ausência de incentivos financeiros:**
- **Questão**: Não há incentivos financeiros ou materiais para participação
- **Tratamento**:
  - Participação baseada em contribuição voluntária para pesquisa
  - Oferecimento de acesso aos resultados finais como benefício (não como incentivo)
  - Transparência sobre ausência de compensação financeira
  - Sem pressão para participar devido a incentivos

**3. Riscos de exposição e confidencialidade:**
- **Questão**: Participantes podem se preocupar com exposição de informações sensíveis sobre suas organizações
- **Tratamento**:
  - Anonimato completo garantido (sem coleta de identificadores pessoais)
  - Dados agregados e anonimizados na análise e publicação
  - Sem coleta de nomes de organizações ou projetos específicos
  - Informações contextuais coletadas de forma genérica (tipo de organização, não nome)
  - Dados armazenados de forma segura e acessíveis apenas ao pesquisador

**4. Uso de dados para pesquisa acadêmica:**
- **Questão**: Dados serão usados para TCC e possivelmente publicações
- **Tratamento**:
  - Transparência sobre uso dos dados no consentimento informado
  - Participantes informados sobre objetivos acadêmicos
  - Possibilidade de acesso aos resultados finais (se desejado)

#### 14.2 Consentimento informado

Antes do início da coleta de dados, os profissionais receberão uma explicação clara e detalhada sobre os objetivos do estudo, os tipos de dados que serão coletados, a finalidade exclusiva acadêmica e de pesquisa, bem como o direito de recusar a participação ou se retirar a qualquer momento, sem qualquer prejuízo.

#### 14.3 Privacidade e proteção de dados

Serão coletadas apenas as informações estritamente necessárias para a caracterização da amostra e a análise dos resultados, tais como experiência prévia, respostas a questionários, tempos de execução e desempenho nas tarefas. Todos os dados serão armazenados utilizando identificadores anônimos ou pseudoanônimos, sem qualquer associação direta a nomes, e-mails ou números de matrícula. O acesso a dados potencialmente identificáveis, quando existente, será restrito ao professor responsável e a membros previamente autorizados da equipe. As informações serão mantidas apenas pelo período necessário para a conclusão da disciplina e para a elaboração de eventuais publicações acadêmicas, de acordo com as diretrizes institucionais vigentes.

#### 14.4 Aprovações necessárias (comitê de ética, jurídico, DPO, etc.)

**Aprovações necessárias:**

- Comitê de Ética em Pesquisa (CEP) da PUC Minas

- 2. Orientador do TCC

- 4. Comitê de Proteção de Dados (DPO - Data Protection Officer)

- 5. Banca examinadora

### 15. Recursos, infraestrutura e orçamento

#### 15.1 Recursos humanos e papéis

**Equipe do experimento:**

**1. Pesquisador Principal / Autor do TCC:**
- **Nome**: Gabriel Lourenço Reis Resende
- **Papel**: Executor principal do experimento

**2. Orientador do TCC:**
- **Nome**: A definir (professor orientador)
- **Papel**: Orientador científico e supervisor metodológico

**3. Participantes do Survey (Voluntários):**
- **Papel**: Fornecedores de dados através de respostas ao questionário
- **Carga horária por participante**: 15-20 minutos q

#### 15.2 Infraestrutura técnica necessária

**Infraestrutura necessária:**

**1. Plataforma de Survey Online:**
- **Ferramenta**: Google Forms, Typeform, SurveyMonkey ou similar
- **Requisitos**:
  - Suporte a questionários estruturados com múltiplas seções
  - Lógica condicional (direcionamento baseado em respostas)
  - Validação de respostas obrigatórias
  - Exportação de dados em CSV/Excel
  - Configuração de anonimato
  - Suporte a diferentes tipos de perguntas (múltipla escolha, escala Likert, texto livre)
  - Acesso via navegador web (sem necessidade de instalação)
- **Custo**: Gratuito ou plano básico (baixo custo)
- **Disponibilidade**: Acesso via internet

**2. Software de Análise de Dados:**
- **Ferramentas**:
  - **Python** (com bibliotecas: pandas, numpy, scipy, matplotlib, seaborn) OU
  - **Microsoft Excel / Google Sheets** (para análises básicas)
- **Requisitos**:
  - Capacidade de importar dados CSV/Excel
  - Análises estatísticas (testes t, qui-quadrado, etc.)
  - Visualizações (gráficos, tabelas)
  - Análises qualitativas (codificação de texto)
- **Custo**: Gratuito (Python, R) ou já disponível (Excel)
- **Disponibilidade**: Instalação local ou uso online

**3. Armazenamento de Dados:**
- **Opções**:
  - **Armazenamento local**: Computador pessoal com backup
  - **Armazenamento em nuvem**: Google Drive, OneDrive, Dropbox (com acesso restrito)
- **Requisitos**:
  - Segurança (proteção por senha, acesso restrito)
  - Backup regular
  - Capacidade suficiente para dados do estudo (mínimo: alguns MB)
- **Custo**: Gratuito (planos básicos de nuvem) ou já disponível
- **Disponibilidade**: Já disponível

**4. Repositório de Código (Opcional):**
- **Ferramenta**: GitHub, GitLab ou similar
- **Uso**: Versionamento de scripts de análise, documentação
- **Requisitos**: Conta gratuita
- **Custo**: Gratuito
- **Disponibilidade**: Criar se necessário

#### 15.3 Materiais e insumos

**Materiais e insumos necessários:**

**1. Questionário Online:**
- **Tipo**: Formulário digital criado na plataforma de survey
- **Conteúdo**: Baseado no plano experimental (seções: consentimento, definições, triagem, coleta de dados)
- **Status**: A ser criado após aprovação ética e validação do piloto
- **Custo**: Gratuito (plataformas gratuitas) ou baixo (planos básicos)

**2. Planilha de Dados:**
- **Tipo**: Arquivo digital (CSV, Excel)
- **Uso**: Armazenamento e organização dos dados coletados
- **Status**: A ser criado após início da coleta
- **Custo**: Nenhum (software gratuito)

**4. Scripts de Análise:**
- **Tipo**: Scripts em Python ou R (opcional)
- **Uso**: Análise automatizada e reprodutível dos dados
- **Status**: A ser criado durante fase de análise
- **Custo**: Nenhum (software gratuito)

**5. Materiais de Recrutamento:**
- **Tipo**: Mensagens digitais (texto para redes sociais, fóruns, grupos)
- **Conteúdo**: 
  - Mensagens de recrutamento para diferentes canais
  - Links para o questionário
  - Informações sobre o estudo
- **Status**: A ser criado antes da coleta
- **Custo**: Nenhum


#### 15.4 Orçamento e custos estimados

Espera-se que os custos diretos sejam mínimos, uma vez que o experimento será conduzido utilizando a infraestrutura já disponível na instituição. Os principais custos envolvem o tempo dedicado à preparação, execução e análise por parte do professor orientador e do estudante pesquisador, contabilizado como carga horária da disciplina ou de projeto de pesquisa. Além disso, podem ocorrer custos marginais eventuais, como a impressão de materiais de apoio.
---

### 16. Cronograma, marcos e riscos operacionais

#### 16.1 Macrocronograma (até o início da execução)

| Fase | Atividades | Duração | Marcos |
|------|-----------|---------|--------|
| **Planejamento** | Finalização do plano, desenvolvimento do questionário, submissão ao CEP | Início do semestre | Plano aprovado, CEP aprovado |
| **Validação** | Teste piloto, ajustes | 2-3 semanas | Questionário validado |
| **Preparação Final** | Configuração, materiais de recrutamento | 3-4 semanas | Pronto para coleta |
| **Coleta** | Recrutamento, coleta de dados | 6-8 semanas | Dados coletados |

#### 16.2 Dependências entre atividades

#### 16.2 Dependências entre Atividades

| Atividade            | Depende de                | Justificativa |
|----------------------|---------------------------|----------------|
| **Validação**        | Planejamento              | O questionário e o plano precisam estar finalizados antes do teste piloto. |
| **Preparação Final** | Validação                 | Ajustes identificados no piloto devem ser incorporados antes da configuração final. |
| **Coleta**           | Preparação Final          | A coleta só pode começar após a configuração do ambiente e materiais de recrutamento. |

#### 16.3 Riscos operacionais e plano de contingência

**Riscos operacionais e planos de contingência:**

**1. Problemas técnicos com plataforma de survey:**
- **Risco**: Plataforma escolhida pode ter problemas técnicos, indisponibilidade ou limitações
- **Probabilidade**: Baixa
- **Impacto**: Alto (bloqueia coleta)
- **Contingência**:
  - Identificação de plataforma alternativa de backup (ex: se Google Forms falhar, usar Typeform)
  - Teste da plataforma antes do início da coleta
  - Exportação regular de dados durante a coleta (backup)
  - Migração para plataforma alternativa se necessário (com comunicação aos participantes)

**2. Baixa taxa de resposta ao survey:**
- **Risco**: Número insuficiente de participantes, não atingindo tamanho mínimo
- **Probabilidade**: Média-Alta
- **Impacto**: Alto (compromete validade do estudo)
- **Contingência**:
  - Diversificação de canais de recrutamento desde o início
  - Estratégias de follow-up e lembretes
  - Parcerias com comunidades técnicas
  - Extensão do período de coleta se necessário
  - Ajuste do tamanho mínimo de amostra (com justificativa metodológica) se necessário
  - Análise com amostra menor, documentando limitações

---

### 17. Governança do experimento

#### 17.1 Papéis e responsabilidades formais

**Estrutura de papéis e responsabilidades:**

**1. Pesquisador Principal (Gabriel Lourenço Reis Resende):**
- **Papel**: Executor e responsável principal
- **Decisões**:
  - Decisões operacionais do dia a dia
  - Decisões sobre recrutamento e coleta de dados
  - Decisões sobre análise de dados (com orientação)
  - Decisões sobre exclusão de participantes (conforme critérios definidos)
- **Execução**:
  - Todas as atividades operacionais do experimento
  - Desenvolvimento do questionário
  - Recrutamento de participantes
  - Coleta de dados
  - Análise de dados
  - Redação do trabalho
- **Revisão**: Não aplicável (é o executor)
- **Informação**: Informa orientador sobre progresso e problemas

**2. Orientador do TCC:**
- **Papel**: Supervisor científico e metodológico
- **Decisões**:
  - Aprovação do plano experimental
  - Aprovação do questionário
  - Aprovação de mudanças significativas no protocolo
  - Validação de estratégias de análise
  - Aprovação para início da coleta (após aprovação ética)
- **Execução**: Não executa atividades operacionais
- **Revisão**:
  - Revisão do plano experimental
  - Revisão do questionário
  - Revisão de resultados e interpretações
  - Revisão do trabalho escrito
- **Informação**: Informado sobre progresso, problemas e resultados

**3. Comitê de Ética em Pesquisa (CEP):**
- **Papel**: Avaliador ético
- **Decisões**:
  - Aprovação, solicitação de ajustes ou reprovação do protocolo
  - Aprovação ética é obrigatória para início da coleta
- **Execução**: Não executa atividades do experimento
- **Revisão**: Revisão ética do protocolo
- **Informação**: Informado através de submissão formal do protocolo

**4. Participantes do Survey:**
- **Papel**: Fornecedores de dados
- **Decisões**: Decisão sobre participar ou não (voluntário)
- **Execução**: Preenchimento do questionário
- **Revisão**: Não aplicável
- **Informação**: Informados sobre objetivos, riscos, benefícios através do TCLE

**5. Banca Examinadora:**
- **Papel**: Avaliador final (pós-execução)
- **Decisões**:
  - Aprovação ou solicitação de ajustes no trabalho final
  - Avaliação da qualidade científica
- **Execução**: Não executa atividades do experimento
- **Revisão**: Revisão do trabalho completo após execução
- **Informação**: Informados através de apresentação e defesa do TCC

#### 17.2 Ritos de acompanhamento pré-execução

**Reuniões e checkpoints:**

- **Reuniões de orientação**: Semanal ou quinzenal com orientador para acompanhamento do progresso
- **Checkpoint 1 - Finalização do plano**: Revisão e aprovação do plano experimental completo
- **Checkpoint 2 - Questionário**: Revisão e aprovação do questionário antes da submissão ao CEP
- **Checkpoint 3 - Aprovação ética**: Validação da aprovação do CEP e preparação para piloto
- **Checkpoint 4 - Pós-piloto**: Revisão dos resultados do piloto e ajustes necessários
- **Checkpoint 5 - Pronto para coleta**: Validação final antes do início da coleta principal

#### 17.3 Processo de controle de mudanças no plano

**Processo de mudanças:**

1. **Proposta**: Pesquisador identifica necessidade de mudança e documenta justificativa
2. **Análise**: Orientador analisa impacto da mudança (metodológico, ético, cronograma)
3. **Aprovação**: 
   - Mudanças menores: Aprovação do orientador
   - Mudanças significativas: Aprovação do orientador + comunicação ao CEP (se necessário)
4. **Registro**: Mudanças documentadas no plano experimental com data e justificativa
5. **Comunicação**: Participantes informados se mudança afetar coleta de dados

---

### 18. Plano de documentação e reprodutibilidade

#### 18.1 Repositórios e convenções de nomeação

**Repositórios:**
- **Plano e documentação**: Repositório Git (GitHub/GitLab) ou Google Drive
- **Dados coletados**: Armazenamento local seguro + backup em nuvem (acesso restrito)
- **Scripts de análise**: Repositório Git ou pasta local organizada

**Convenções de nomeação:**
- **Plano**: `plano-experimento-vX.X.md`
- **Questionário**: `questionario-vX.X.pdf` ou link da plataforma
- **Dados**: `dados-coleta-YYYY-MM-DD.csv`
- **Scripts**: `analise-dados-vX.X.py` ou `analise-dados-vX.X.R`
- **Documentação**: `README.md`, `log-coleta.md`, `protocolo-cep.pdf`

#### 18.2 Templates e artefatos padrão

**Artefatos principais:**
- **Plano experimental**: Este documento (README.md)
- **Questionário**: Template na plataforma de survey (Google Forms/Typeform)
- **Planilha de dados**: Template Excel/CSV com colunas para todas as variáveis
- **Scripts de análise**: Templates Python/R para análises estatísticas básicas

**Localização**: Repositório Git ou pasta organizada no Google Drive

#### 18.3 Plano de empacotamento para replicação futura

**Pacote de replicação incluirá:**
- **Documentação completa**: Plano experimental, protocolo, questionário final
- **Scripts de análise**: Código comentado e documentado para reproduzir análises
- **Dados anonimizados**: Dados agregados para validação (sem identificadores)
- **Instruções de replicação**: Guia passo a passo para replicar o estudo
- **Materiais de recrutamento**: Templates de mensagens e materiais utilizados
- **Checklist de replicação**: Lista de itens necessários para replicação

**Formato**: Repositório Git público ou pacote ZIP documentado

---

### 19. Plano de comunicação

#### 19.1 Públicos e mensagens-chave pré-execução

**Públicos e mensagens:**

- **Orientador**: Objetivos, progresso, aprovações necessárias, problemas encontrados
- **Participantes potenciais**: Objetivo do estudo, tempo estimado, benefícios, anonimato garantido
- **Comunidades técnicas**: Convite para participação, link do questionário, propósito da pesquisa
- **Coordenação do curso** (se necessário): Informação sobre o estudo e cronograma

#### 19.2 Canais e frequência de comunicação

**Canais:**
- **Orientador**: E-mail + reuniões presenciais/videoconferência (semanal/quinzenal)
- **Participantes**: Questionário online + mensagens de recrutamento (redes sociais, fóruns)
- **Comunidades**: Posts em redes sociais, fóruns, grupos (LinkedIn, Reddit, WhatsApp, Telegram)

#### 19.3 Pontos de comunicação obrigatórios

**Eventos que exigem comunicação formal:**
- **Aprovação do plano**: Comunicação ao orientador e CEP
- **Aprovação ética**: Comunicação ao orientador e início de preparação para coleta
- **Início da coleta**: Comunicação ao orientador
- **Encerramento da coleta**: Comunicação ao orientador com resumo dos dados coletados

---

### 20. Critérios de prontidão para execução (Definition of Ready)

#### 20.1 Checklist de prontidão (itens que devem estar completos)

**Checklist obrigatório antes do início da coleta:**

- Plano experimental completo e aprovado pelo orientador
- Questionário desenvolvido, revisado e validado
- Aprovação ética do CEP obtida
- Teste piloto realizado e ajustes implementados
- Questionário configurado na plataforma de survey e testado
- Materiais de recrutamento preparados
- Planilha de dados estruturada
- Canais de recrutamento identificados
- Aprovação final do orientador para início da coleta

#### 20.2 Aprovações finais para iniciar a operação

**Aprovações necessárias:**

1. **Comitê de Ética em Pesquisa (CEP)**: Aprovação formal do protocolo (documento oficial do CEP)
2. **Orientador do TCC**: Aprovação verbal ou por e-mail após revisão do checklist de prontidão