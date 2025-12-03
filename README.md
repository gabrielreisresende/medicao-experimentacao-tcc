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
9. **Aprovação ética**: Necessidade de aprovação do comitê de ética da instituição antes da coleta de dados

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

4. **Atrasos na aprovação ética**
   - **Risco**: Demora na aprovação do comitê de ética pode atrasar o início da coleta de dados
   - **Probabilidade**: Baixa-Média
   - **Impacto**: Médio
   - **Mitigação**: Submissão antecipada da documentação, acompanhamento regular do processo, planejamento de buffer de tempo

5. **Prazo insuficiente para coleta e análise**
   - **Risco**: Tempo limitado do TCC pode não ser suficiente para coleta adequada de dados e análise completa
   - **Probabilidade**: Média
   - **Impacto**: Alto
   - **Mitigação**: Planejamento realista de cronograma, definição de tamanho mínimo de amostra viável, priorização de análises essenciais

**Riscos técnicos:**

6. **Falhas em ferramentas de survey**
   - **Risco**: Problemas técnicos com a plataforma de survey (perda de dados, indisponibilidade)
   - **Probabilidade**: Baixa
   - **Impacto**: Alto
   - **Mitigação**: Escolha de ferramentas confiáveis, backup de dados, teste prévio da ferramenta, exportação regular de respostas

7. **Problemas de acesso ou compatibilidade**
   - **Risco**: Participantes podem ter dificuldades para acessar o survey devido a problemas de navegação ou compatibilidade
   - **Probabilidade**: Baixa
   - **Impacto**: Baixo-Médio
   - **Mitigação**: Teste do survey em diferentes navegadores e dispositivos, instruções claras, suporte para participantes

**Riscos metodológicos:**

8. **Compreensão inadequada das abordagens**
   - **Risco**: Participantes podem não compreender corretamente as diferenças entre API-First e Code-First, mesmo com definições fornecidas
   - **Probabilidade**: Média
   - **Impacto**: Alto
   - **Mitigação**: Definições claras e exemplos no questionário, perguntas de verificação de compreensão, exclusão de respostas inconsistentes

9. **Amostra desbalanceada entre grupos**
   - **Risco**: Desequilíbrio significativo entre número de participantes que usaram API-First vs. Code-First, dificultando comparações
   - **Probabilidade**: Média
   - **Impacto**: Médio
   - **Mitigação**: Estratégias de recrutamento direcionadas para ambos os grupos, análise de sensibilidade, uso de técnicas estatísticas apropriadas para amostras desbalanceadas

**Riscos de validade:**

10. **Viés de memória e recall**
    - **Risco**: Relatos sobre experiências passadas podem estar sujeitos a viés de memória
    - **Probabilidade**: Alta
    - **Impacto**: Médio
    - **Mitigação**: Foco em experiências recentes quando possível, perguntas sobre projetos específicos, transparência sobre limitações

11. **Falta de representatividade geográfica ou organizacional**
    - **Risco**: Amostra concentrada em uma região ou tipo de organização, limitando generalização
    - **Probabilidade**: Média-Alta
    - **Impacto**: Médio
    - **Mitigação**: Diversificação de canais de recrutamento, análise de características da amostra, discussão de limitações de generalização

#### 6.2 Critérios de sucesso globais (go / no-go)

O experimento será considerado bem-sucedido e útil se os seguintes critérios forem atendidos:

**Critérios de prontidão (go/no-go para início da coleta):**

1. **Aprovação ética**: Comitê de ética da instituição aprovou o protocolo de pesquisa
2. **Questionário validado**: Questionário revisado pelo orientador e testado em piloto (se aplicável)
3. **Canais de recrutamento definidos**: Pelo menos 3 canais diferentes identificados para recrutamento de participantes
4. **Ferramenta de survey funcional**: Plataforma de survey testada e pronta para coleta
5. **Plano de análise definido**: Estratégia de análise de dados documentada e aprovada

**Critérios de sucesso na coleta de dados:**

6. **Tamanho mínimo de amostra**: Pelo menos 50 participantes válidos no total
7. **Balanceamento mínimo**: Pelo menos 20 participantes em cada grupo (API-First e Code-First/nenhum)
8. **Taxa de resposta completa**: Pelo menos 80% dos questionários iniciados são completados
9. **Qualidade dos dados**: Menos de 10% de respostas inválidas ou inconsistentes

**Critérios de sucesso na análise:**

10. **Responder às questões de pesquisa**: Todas as 12 questões de pesquisa podem ser respondidas com os dados coletados
11. **Análise estatística adequada**: Análises estatísticas apropriadas aplicadas conforme planejado
12. **Insights identificados**: Pelo menos 3 insights principais ou padrões identificados sobre as abordagens
13. **Fatores contextuais identificados**: Pelo menos 2 fatores contextuais que influenciam a escolha/sucesso são identificados

**Critérios de sucesso do trabalho:**

14. **Documentação completa**: Todos os artefatos do experimento documentados (plano, questionário, dados, análise)
15. **Resultados comunicados**: Resultados apresentados de forma clara no TCC
16. **Contribuição científica**: Trabalho contribui com evidências empíricas para a área
17. **Aprovação da banca**: TCC aprovado pela banca examinadora

**Critérios de no-go (não prosseguir):**

- Aprovação ética negada sem possibilidade de ajuste
- Impossibilidade de recrutar pelo menos 30 participantes após esforços significativos
- Dados coletados revelam problemas metodológicos críticos que não podem ser corrigidos
- Mudanças significativas no contexto que tornam o experimento irrelevante ou inviável

#### 6.3 Critérios de parada antecipada (pré-execução)

O experimento deve ser **adiado ou cancelado** antes de iniciar a coleta de dados se qualquer uma das seguintes situações ocorrer:

1. **Reprovação ética sem possibilidade de ajuste**
   - Se o comitê de ética reprovar o protocolo e não houver possibilidade de ajustes que resolvam as questões éticas levantadas
   - **Ação**: Revisão completa do protocolo ou cancelamento do experimento

2. **Falta de recursos críticos**
   - Indisponibilidade de ferramentas de survey ou recursos computacionais necessários
   - **Ação**: Busca de alternativas ou adiamento até disponibilidade de recursos

3. **Mudanças significativas no contexto**
   - Mudanças no escopo do TCC, orientação ou requisitos acadêmicos que tornem o experimento inviável
   - **Ação**: Revisão do plano experimental ou redefinição do escopo

4. **Problemas metodológicos críticos identificados**
   - Identificação de problemas metodológicos fundamentais que comprometam a validade do estudo e não possam ser corrigidos
   - **Ação**: Revisão metodológica ou reformulação do experimento

5. **Falta de viabilidade de recrutamento**
   - Evidências claras de que não será possível recrutar número mínimo de participantes mesmo após esforços significativos
   - **Ação**: Revisão da estratégia de recrutamento ou ajuste do tamanho mínimo de amostra

6. **Conflitos de interesse não resolvidos**
   - Identificação de conflitos de interesse que comprometam a integridade do estudo
   - **Ação**: Resolução dos conflitos ou cancelamento

7. **Problemas de saúde ou pessoais do pesquisador**
   - Situações que impeçam o pesquisador de conduzir adequadamente o experimento
   - **Ação**: Adiamento ou transferência de responsabilidades (se viável)

**Durante a coleta de dados**, o experimento deve ser **interrompido temporariamente** se:

- Taxa de resposta extremamente baixa (< 5% após 2 semanas de divulgação)
- Problemas técnicos críticos com a plataforma de survey que resultem em perda de dados
- Identificação de problemas éticos durante a coleta que exijam revisão do protocolo

**Após a coleta**, o experimento pode ser considerado **incompleto** (mas não cancelado) se:

- Tamanho da amostra ficar significativamente abaixo do mínimo planejado (< 30 participantes)
- Qualidade dos dados for insuficiente para análises válidas (> 30% de respostas inválidas)
- Dados coletados não permitirem responder às questões de pesquisa principais

Nesses casos, o experimento pode ser ajustado (ex: reduzir escopo de questões) ou os resultados podem ser apresentados com limitações claramente documentadas.

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

**Nível de significância (α):**
- **α = 0,05**: Será utilizado o nível de significância padrão de 5% para testes estatísticos

**Poder estatístico (1 - β):**
- **Tamanho de efeito esperado**: Baseado na literatura e natureza do estudo, espera-se efeitos de tamanho médio (Cohen's d ≈ 0,5) para comparações entre grupos
- **Tamanho de amostra mínimo**: Para detectar efeitos médios com poder de 80% e α = 0,05 em testes t de duas amostras, são necessários aproximadamente 64 participantes por grupo (128 no total). No entanto, considerando as restrições práticas do estudo, será aceito um tamanho mínimo de 50 participantes no total (25 por grupo), o que reduz o poder para aproximadamente 60-65% para efeitos médios

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

**Estratégia de bloqueio:**
- Análises serão realizadas tanto no nível agregado quanto estratificadas por variáveis de controle relevantes
- Comparações entre grupos serão ajustadas ou estratificadas quando necessário para controlar variáveis de confusão

#### 8.7 Possíveis variáveis de confusão conhecidas

Variáveis que podem distorcer os resultados e que serão monitoradas:

| Variável de Confusão | Impacto Potencial | Estratégia de Monitoramento/Mitigação |
|---------------------|------------------|--------------------------------------|
| **Viés de memória e recall** | Participantes podem lembrar mais de experiências positivas ou negativas recentes | Pergunta sobre recência da experiência; foco em projetos específicos quando possível |
| **Viés de autosseleção** | Participantes mais experientes ou engajados podem estar mais propensos a participar | Análise de características demográficas da amostra; comparação com população-alvo quando possível |
| **Compreensão das definições** | Diferentes interpretações de "API-First" e "Code-First" | Definições claras no questionário; perguntas de verificação de compreensão |
| **Viés de desejabilidade social** | Participantes podem responder de forma socialmente desejável | Anonimato garantido; perguntas diretas e objetivas |
| **Experiência mista** | Participantes podem ter experiência com ambas as abordagens | Identificação de participantes com experiência mista; análise separada ou exclusão |
| **Contexto organizacional específico** | Características específicas da organização podem influenciar mais que a abordagem | Coleta de dados sobre contexto organizacional; análise estratificada |
| **Motivação e engajamento** | Participantes com maior motivação podem ter experiências diferentes | Análise de qualidade das respostas; identificação de respostas apressadas |
| **Viés geográfico/cultural** | Diferenças culturais ou regionais podem influenciar percepções | Coleta de dados demográficos geográficos; discussão de limitações de generalização |
| **Maturidade do projeto** | Projetos em diferentes estágios podem ter necessidades diferentes | Pergunta sobre estágio do projeto; análise considerando maturidade |
| **Pressão de tempo e recursos** | Restrições de tempo podem influenciar escolha e percepção da abordagem | Pergunta sobre restrições de recursos; análise considerando contexto de pressão |
| **Viés de confirmação** | Participantes podem buscar confirmar suas escolhas anteriores | Perguntas sobre vantagens e desvantagens de ambas as abordagens; análise balanceada |

---

### 9. Desenho experimental

#### 9.1 Tipo de desenho (completamente randomizado, blocos, fatorial, etc.)

**Tipo de desenho**: **Estudo observacional comparativo (quase-experimental) com grupos não equivalentes**

Este estudo utiliza um desenho observacional baseado em survey, onde os participantes são agrupados naturalmente baseados em sua experiência prévia (API-First vs. Code-First), sem randomização experimental. O desenho pode ser caracterizado como:

- **Estudo transversal**: Coleta de dados em um único ponto no tempo sobre experiências passadas
- **Desenho de grupos comparativos**: Comparação entre dois grupos baseados em experiência prévia
- **Desenho quase-experimental**: Não há randomização, mas há comparação sistemática entre grupos

**Justificativa da escolha:**

1. **Natureza do fenômeno**: A escolha entre API-First e Code-First em projetos reais não pode ser manipulada experimentalmente de forma ética ou prática, pois envolve decisões organizacionais e de projeto que já foram tomadas

2. **Contexto real**: O estudo busca capturar experiências em contextos reais de desenvolvimento, onde múltiplos fatores contextuais influenciam os resultados, tornando um experimento controlado artificial

3. **Viabilidade**: Um experimento controlado exigiria recrutar equipes completas, alocar projetos reais e manipular abordagens, o que é inviável dentro do escopo de um TCC

4. **Validade ecológica**: Estudos observacionais baseados em experiências reais têm maior validade ecológica para generalização para contextos organizacionais reais

5. **Ética e praticidade**: Não é ético ou prático forçar organizações a mudar suas abordagens estabelecidas para fins de pesquisa

**Limitações reconhecidas:**
- Ausência de randomização pode introduzir viés de seleção
- Grupos podem não ser equivalentes em todas as dimensões
- Relação causal não pode ser estabelecida com certeza absoluta
- Viés de memória pode afetar relatos sobre experiências passadas

Essas limitações serão mitigadas através de:
- Análise de características demográficas e contextuais dos grupos
- Estratificação por variáveis de controle
- Transparência sobre limitações metodológicas
- Foco em associações e padrões, com discussão cuidadosa de causalidade

#### 9.2 Randomização e alocação

**Randomização**: **Não aplicável** (estudo observacional)

Como este é um estudo observacional baseado em survey, não há randomização experimental de participantes para tratamentos. Os participantes são alocados naturalmente aos grupos baseados em sua experiência prévia:

- **Grupo API-First**: Participantes que já utilizaram API-First
- **Grupo Code-First**: Participantes que nunca utilizaram API-First

**Alocação aos grupos:**

A alocação ocorre através de **autoclassificação** baseada em respostas ao questionário:

1. **Pergunta de triagem**: "Você já utilizou a abordagem API-First em algum projeto profissional?"
   - Resposta "Sim" → Grupo API-First
   - Resposta "Não" → Grupo Code-First

2. **Validação**: Perguntas adicionais verificam a compreensão e experiência real:
   - Descrição da experiência com a abordagem
   - Identificação de características da abordagem utilizada
   - Exclusão de participantes que não conseguem descrever adequadamente sua experiência

**Randomização de elementos do questionário:**

Para reduzir viés de ordem e efeitos de fadiga, os seguintes elementos serão randomizados ou balanceados:

- **Ordem das perguntas sobre vantagens/desvantagens**: Apresentação alternada de perguntas sobre API-First e Code-First
- **Ordem das opções em questões de múltipla escolha**: Quando aplicável, ordem das opções será variada
- **Ordem das escalas**: Direção das escalas (positiva/negativa) será balanceada

**Ferramentas para randomização:**
- Funcionalidades de randomização da plataforma de survey (ex: Google Forms, Typeform)
- Scripts de randomização para versões do questionário, se necessário

#### 9.3 Balanceamento e contrabalanço

**Balanceamento entre grupos:**

Como não há randomização experimental, o balanceamento será verificado e, quando possível, ajustado através de:

1. **Análise de características demográficas**:
   - Comparação de distribuições de idade, experiência, tipo de organização, tamanho de equipe entre grupos
   - Identificação de desequilíbrios significativos

2. **Estratificação e matching**:
   - Se possível, matching de participantes por características relevantes (experiência, tipo de organização)
   - Análises estratificadas por variáveis de controle

3. **Recrutamento direcionado**:
   - Estratégias de recrutamento específicas para garantir representação adequada em ambos os grupos
   - Monitoramento do balanceamento durante a coleta de dados

4. **Análises ajustadas**:
   - Uso de modelos estatísticos que ajustam para variáveis de confusão
   - Análises de sensibilidade considerando diferentes composições de grupos

**Critérios de balanceamento aceitável:**
- Diferenças não significativas (p > 0,10) em características demográficas principais entre grupos
- Proporção mínima de 40:60 entre grupos (idealmente 50:50)
- Representação similar de tipos de organização em ambos os grupos

**Contrabalanço (efeitos de ordem):**

Como cada participante responde apenas uma vez ao questionário (não há múltiplas sessões), não há efeitos de ordem entre tratamentos. No entanto, serão aplicadas estratégias de contrabalanço para elementos internos do questionário:

1. **Ordem de apresentação de questões**:
   - Versões alternadas do questionário com ordem diferente de seções
   - Randomização da ordem de perguntas sobre vantagens/desvantagens

2. **Direção das escalas**:
   - Balanceamento de escalas positivas e negativas
   - Evitar viés de resposta por direção da escala

3. **Ordem de opções**:
   - Variação na ordem de opções de múltipla escolha quando aplicável

**Efeitos de aprendizagem**: Não aplicável, pois não há múltiplas sessões ou exposição sequencial a diferentes condições.

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

**Justificativa:**

1. **Natureza do estudo**: Estudo observacional sobre experiências passadas, não requer múltiplas exposições
2. **Viabilidade**: Múltiplas sessões seriam inviáveis devido a:
   - Dificuldade de recrutamento e retenção de participantes
   - Carga de tempo para participantes voluntários
   - Complexidade logística de coordenação
3. **Validade**: Uma sessão é suficiente para capturar percepções e experiências dos participantes
4. **Ética**: Minimiza carga sobre participantes voluntários

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

**Características demográficas da população-alvo:**
- **Geográfico**: Inicialmente focado em profissionais que dominam português (principalmente Brasil), mas não limitado geograficamente
- **Setor**: Indústria de software em geral (produtos, serviços, consultoria, etc.)
- **Nível de experiência**: Desde profissionais júnior (com pelo menos 1 ano de experiência) até profissionais sênior
- **Contexto organizacional**: Diferentes tipos de organizações, desde startups até grandes corporações

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

6. **Idioma**:
   - Domínio suficiente do português para compreender e responder ao questionário

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

**Justificativa do tamanho da amostra:**

1. **Poder estatístico**:
   - Para detectar efeitos médios (Cohen's d ≈ 0,5) com poder de 80% e α = 0,05 em testes t de duas amostras, seriam necessários aproximadamente 64 participantes por grupo (128 no total)
   - Considerando restrições práticas do estudo (TCC, recursos limitados, amostra de conveniência), o tamanho mínimo de 50 participantes (25 por grupo) reduz o poder para aproximadamente 60-65% para efeitos médios
   - Este poder é considerado aceitável para um estudo exploratório e comparativo

2. **Análises estratificadas**:
   - O tamanho ideal (60-80 participantes) permite análises estratificadas por variáveis de controle (tipo de organização, tamanho de equipe, experiência) com tamanhos de subgrupos razoáveis
   - Análises estratificadas terão poder estatístico limitado, mas permitirão identificação de padrões qualitativos

3. **Recursos e viabilidade**:
   - O tamanho mínimo de 50 participantes é viável considerando:
     - Canais de recrutamento disponíveis (redes sociais, fóruns, grupos profissionais)
     - Tempo disponível para coleta de dados
     - Ausência de incentivos financeiros
     - Natureza voluntária da participação

4. **Critérios de sucesso**:
   - O tamanho mínimo atende aos critérios de sucesso definidos na seção 6.2:
     - Pelo menos 50 participantes válidos no total
     - Pelo menos 20 participantes em cada grupo

5. **Balanceamento**:
   - Será buscado balanceamento entre grupos (proporção ideal de 50:50, aceitável de 40:60)
   - Se houver desbalanceamento significativo, estratégias de recrutamento direcionadas serão aplicadas

**Plano de recrutamento incremental:**
- **Fase 1**: Recrutamento inicial até atingir 50 participantes
- **Fase 2**: Se houver desbalanceamento ou baixa qualidade, recrutamento adicional até 60-80 participantes
- **Fase 3**: Recrutamento adicional apenas se necessário para análises específicas ou se houver oportunidade

#### 10.5 Método de seleção / recrutamento

**Tipo de amostragem**: **Amostra de conveniência (convenience sampling)** com elementos de **amostra por bola de neve (snowball sampling)**

**Justificativa:**
- Não é viável obter uma amostra probabilística verdadeiramente aleatória da população-alvo devido a:
  - Ausência de lista completa e acessível da população
  - Recursos limitados para recrutamento sistemático
  - Natureza do estudo (survey voluntário sem incentivos)
- Amostra de conveniência é comum e aceitável em estudos de survey na área de engenharia de software
- Limitações de generalização serão claramente documentadas

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

4. **Estratégias para balanceamento**:
   - Monitoramento contínuo da distribuição entre grupos durante a coleta
   - Mensagens de recrutamento direcionadas se houver desbalanceamento:
     - Se Grupo API-First estiver sub-representado: ênfase em recrutar profissionais com experiência em API-First
     - Se Grupo Code-First estiver sub-representado: ênfase em recrutar profissionais sem experiência em API-First

5. **Controle de qualidade**:
   - Verificação de critérios de elegibilidade através de perguntas de triagem no início do questionário
   - Exclusão automática de participantes que não atendem critérios mínimos
   - Análise de respostas para identificar participação duplicada ou inválida

**Cronograma de recrutamento:**
- **Semana 1-2**: Divulgação inicial em canais primários
- **Semana 3-4**: Divulgação em canais secundários e amostra por bola de neve
- **Semana 5-6**: Recrutamento direcionado se necessário para balanceamento
- **Semana 7+**: Recrutamento adicional apenas se necessário para atingir tamanho mínimo

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

**Não será fornecido**:
- Treinamento formal sobre as abordagens (assume-se que participantes já têm experiência)
- Material de estudo extensivo (o estudo busca percepções baseadas em experiências reais, não conhecimento teórico)
- Sessões de treinamento presenciais ou online

**Justificativa:**
- O estudo busca capturar percepções e experiências reais dos participantes, não conhecimento adquirido através de treinamento
- Fornecer treinamento poderia introduzir viés, influenciando as percepções dos participantes
- As definições fornecidas servem apenas para garantir que todos compreendam os termos, não para ensinar as abordagens
- Participantes já devem ter experiência prática, então apenas precisam de clarificação terminológica

---

### 11. Instrumentação e protocolo operacional

#### 11.1 Instrumentos de coleta (questionários, logs, planilhas, etc.)

**1. Questionário Online (Instrumento Principal)**

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

**2. Planilha de Dados (Artefato de Análise)**

- **Ferramenta**: Microsoft Excel ou Google Sheets
- **Formato**: Planilha estruturada com colunas para cada variável
- **Papel**: Armazenamento e organização dos dados coletados para análise
- **Estrutura**:
  - Uma linha por participante
  - Colunas para cada variável dependente e independente
  - Colunas para identificadores de grupo
  - Colunas para dados demográficos
  - Colunas para respostas qualitativas (texto)
- **Convenções**:
  - Codificação numérica para variáveis categóricas
  - Valores ausentes marcados como "NA" ou vazios
  - Preservação de respostas originais em texto para validação

**3. Log de Coleta de Dados**

- **Ferramenta**: Documento de texto ou planilha
- **Formato**: Registro estruturado de atividades de coleta
- **Papel**: Rastreabilidade e controle de qualidade da coleta
- **Informações registradas**:
  - Data e hora de início da coleta
  - Canais de recrutamento utilizados
  - Número de respostas recebidas por dia/semana
  - Distribuição entre grupos ao longo do tempo
  - Problemas técnicos ou questões identificadas
  - Ajustes realizados durante a coleta

**4. Scripts de Análise de Dados (Futuro)**

- **Ferramenta**: Python (com pandas, numpy, scipy, matplotlib) ou R
- **Formato**: Scripts executáveis para análise estatística
- **Papel**: Análise automatizada e reprodutível dos dados
- **Conteúdo previsto**:
  - Importação e limpeza de dados
  - Análises estatísticas descritivas
  - Testes estatísticos (t-teste, qui-quadrado, etc.)
  - Visualizações (gráficos, tabelas)
  - Análises qualitativas (codificação de respostas abertas)

**5. Documento de Consentimento Informado**

- **Ferramenta**: Integrado no questionário online
- **Formato**: Texto com checkbox de aceite
- **Papel**: Registro de consentimento dos participantes
- **Conteúdo**:
  - Objetivo do estudo
  - Procedimentos
  - Riscos e benefícios
  - Confidencialidade e anonimato
  - Direito de retirada
  - Contato do pesquisador

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

**Para Administradores do Experimento (Pesquisador):**

1. **Guia de Operação do Survey**:
   - Instruções sobre como configurar o questionário na plataforma escolhida
   - Checklist de configurações (anonimato, validações, lógica condicional)
   - Instruções sobre exportação de dados
   - Procedimentos de backup de dados

2. **Guia de Recrutamento**:
   - Templates de mensagens para diferentes canais
   - Calendário de divulgação
   - Estratégias para balanceamento de grupos
   - Procedimentos para follow-up

3. **Guia de Controle de Qualidade**:
   - Critérios para identificar respostas inválidas
   - Procedimentos para exclusão de participantes
   - Checklist de validação de dados
   - Procedimentos para lidar com problemas técnicos

4. **Protocolo de Resolução de Problemas**:
   - Problemas técnicos comuns e soluções
   - Como lidar com questões éticas durante a coleta
   - Contatos para suporte técnico da plataforma
   - Procedimentos de comunicação com participantes

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
   - Configurar backup automático de respostas

4. **Aprovação Ética**:
   - Submissão ao comitê de ética (se necessário)
   - Aguardar aprovação antes de iniciar coleta

5. **Preparação de Materiais de Recrutamento**:
   - Preparar mensagens de recrutamento para diferentes canais
   - Preparar calendário de divulgação
   - Identificar canais de recrutamento

**FASE 2: COLETA DE DADOS**

6. **Início da Coleta**:
   - Publicar questionário online (tornar acessível)
   - Registrar data e hora de início
   - Iniciar log de coleta de dados

7. **Divulgação Inicial (Semana 1-2)**:
   - Publicar mensagem de recrutamento em canais primários:
     - LinkedIn (posts em grupos relevantes)
     - Reddit (subreddits de desenvolvimento)
     - Grupos de WhatsApp/Telegram
     - Comunidades técnicas online
   - Monitorar respostas recebidas
   - Registrar no log de coleta

8. **Divulgação Secundária (Semana 3-4)**:
   - Solicitar aos participantes iniciais compartilhamento (snowball sampling)
   - Divulgação em canais secundários
   - Parcerias com comunidades técnicas
   - Continuar monitoramento de respostas

9. **Monitoramento Contínuo**:
   - Verificar diariamente número de respostas recebidas
   - Verificar distribuição entre grupos (API-First vs. Code-First)
   - Identificar problemas técnicos ou questões
   - Exportar backup de dados regularmente (semanalmente)

10. **Recrutamento Direcionado (Se Necessário - Semana 5-6)**:
    - Se houver desbalanceamento entre grupos, ajustar estratégia de recrutamento
    - Mensagens direcionadas para grupo sub-representado
    - Continuar monitoramento

11. **Validação de Respostas (Contínuo)**:
    - Revisar respostas recebidas para identificar:
      - Respostas incompletas
      - Respostas inconsistentes
      - Participantes que não atendem critérios de inclusão
    - Excluir respostas inválidas conforme critérios definidos
    - Registrar exclusões no log

12. **Decisão sobre Encerramento**:
    - Quando atingir tamanho mínimo (50 participantes) e balanceamento aceitável:
      - Avaliar se é necessário continuar recrutamento
      - Se sim, continuar até tamanho ideal (60-80)
      - Se não, proceder para encerramento

**FASE 3: ENCERRAMENTO DA COLETA**

13. **Encerramento da Coleta**:
    - Fechar questionário para novas respostas (ou definir data limite)
    - Exportar dados finais em formato CSV/Excel
    - Fazer backup final dos dados
    - Registrar data e hora de encerramento no log

14. **Validação Final dos Dados**:
    - Revisar todas as respostas coletadas
    - Aplicar critérios de exclusão finais
    - Identificar e remover duplicatas (se houver)
    - Verificar completude dos dados
    - Registrar número final de participantes válidos

15. **Organização dos Dados**:
    - Organizar dados em planilha estruturada
    - Codificar variáveis categóricas
    - Criar variáveis derivadas se necessário
    - Documentar estrutura dos dados

16. **Comunicação com Participantes (Opcional)**:
    - Agradecer participantes (se houver mecanismo de contato)
    - Informar sobre próximos passos (análise, resultados)
    - Oferecer acesso aos resultados finais (se prometido)

**FASE 4: PÓS-COLETA**

17. **Análise de Dados**:
    - Executar análises estatísticas planejadas
    - Realizar análises qualitativas de respostas abertas
    - Gerar visualizações e relatórios

18. **Documentação**:
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

**Escopo do Piloto:**

- **Número de participantes**: 5-8 participantes
- **Seleção de participantes**:
  - Pelo menos 3 participantes com experiência em API-First
  - Pelo menos 3 participantes com experiência apenas em Code-First
  - Diversidade em experiência profissional (júnior, pleno, sênior)
  - Participantes que não serão incluídos na coleta principal (para evitar viés)
- **Duração**: 1-2 semanas
- **Formato**: Mesmo questionário que será usado na coleta principal

**Critérios de Ajuste do Protocolo:**

**Ajustes obrigatórios (devem ser feitos antes da coleta principal):**

1. **Problemas críticos de compreensão**:
   - Se mais de 50% dos participantes do piloto não compreenderem as definições → Revisar e simplificar definições
   - Se mais de 30% não conseguirem responder perguntas de verificação → Adicionar mais exemplos ou reformular

2. **Problemas técnicos críticos**:
   - Falhas na lógica condicional → Corrigir configuração
   - Problemas de exportação de dados → Trocar plataforma ou corrigir configuração
   - Incompatibilidade com navegadores comuns → Ajustar ou trocar plataforma

3. **Tempo de preenchimento excessivo**:
   - Se tempo médio > 30 minutos → Simplificar questionário, remover questões não essenciais
   - Se houver abandono significativo → Identificar seções problemáticas e simplificar

4. **Problemas de triagem**:
   - Se participantes não conseguirem se classificar → Reformular perguntas de triagem
   - Se classificação for ambígua → Adicionar perguntas de validação

**Ajustes recomendados (devem ser considerados):**

1. **Melhorias de clareza**:
   - Reformular perguntas identificadas como ambíguas
   - Adicionar exemplos onde necessário
   - Melhorar instruções de preenchimento

2. **Otimizações de navegação**:
   - Reorganizar ordem de seções se necessário
   - Adicionar indicadores de progresso
   - Melhorar transições entre seções

3. **Ajustes de conteúdo**:
   - Adicionar ou remover opções em questões de múltipla escolha
   - Ajustar escalas se necessário
   - Adicionar questões opcionais baseadas em feedback

**Processo de Ajuste:**

1. **Coleta de feedback do piloto**:
   - Solicitar feedback qualitativo dos participantes do piloto
   - Perguntas sobre: clareza, tempo, dificuldades, sugestões
   - Análise de padrões de resposta e abandono

2. **Revisão com orientador**:
   - Apresentar resultados do piloto
   - Discutir ajustes necessários
   - Obter aprovação para mudanças

3. **Implementação de ajustes**:
   - Fazer ajustes no questionário
   - Testar ajustes antes de iniciar coleta principal
   - Documentar mudanças realizadas

4. **Validação final**:
   - Se ajustes forem significativos, considerar segundo piloto menor (2-3 participantes)
   - Caso contrário, proceder para coleta principal

**Critérios de sucesso do piloto:**

O piloto será considerado bem-sucedido se:
- Pelo menos 80% dos participantes conseguirem completar o questionário
- Tempo médio de preenchimento estiver entre 15-25 minutos
- Pelo menos 80% dos participantes compreenderem as definições (respostas corretas nas perguntas de verificação)
- Não houver problemas técnicos críticos
- Classificação em grupos for clara para pelo menos 80% dos participantes

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

**Análises Descritivas:**
- Estatísticas básicas: médias, medianas, desvios padrão para variáveis quantitativas
- Frequências e percentuais para variáveis categóricas
- Gráficos: histogramas, boxplots, gráficos de barras
- Verificação de normalidade dos dados para escolha de testes apropriados

**Testes Estatísticos Principais:**

1. **Comparação entre grupos (API-First vs. Code-First)**:
   - **Teste t de Student**: Para variáveis contínuas normalmente distribuídas (ex: produtividade, qualidade)
   - **Teste de Mann-Whitney**: Alternativa não paramétrica quando dados não são normais
   - Aplicado às métricas: M4, M5, M9, M11, M12, M13, M16, M17

2. **Análise de associação**:
   - **Teste qui-quadrado**: Para verificar associação entre variáveis categóricas (ex: tipo de organização vs. abordagem)
   - Aplicado às métricas: M19, M22

3. **Comparação de múltiplos grupos**:
   - **ANOVA**: Para comparar médias entre 3+ grupos (ex: por tipo de organização)
   - **Kruskal-Wallis**: Alternativa não paramétrica à ANOVA

**Configurações:**
- Nível de significância: α = 0,05
- Ajuste para múltiplas comparações quando necessário (correção de Bonferroni)
- Cálculo de tamanhos de efeito para interpretar significância prática

**Ferramentas:**
- Software: Python (pandas, scipy) ou R
- Visualizações: matplotlib/seaborn ou ggplot2

#### 12.3 Tratamento de dados faltantes e outliers

**Dados Faltantes:**

**Regras básicas:**
- **Questões obrigatórias faltantes**: Investigar problema técnico; excluir participante se questões críticas estiverem faltando
- **Questões opcionais faltantes**:
  - Se < 10% faltantes: Excluir da análise específica
  - Se 10-30% faltantes: Considerar imputação (média/mediana) ou análise de sensibilidade
  - Se > 30% faltantes: Excluir variável da análise
- **Respostas qualitativas**: Tratar como "não fornecido", não imputar
- Documentar percentual de dados faltantes e método de tratamento

**Outliers:**

**Tratamento:**
- **Manter**: Se for valor válido representando experiência real legítima
- **Corrigir**: Se for claramente erro de digitação (ex: 1000 em vez de 10)
- **Excluir**: Se for erro não corrigível e afetar análises críticas (< 2% dos dados)
- Realizar análise de sensibilidade (com e sem outliers) para avaliar impacto

**Validação de Dados:**
- Verificar respostas inconsistentes (ex: diz nunca ter usado API-First mas descreve experiência)
- Verificar valores impossíveis (ex: anos de experiência maior que idade)
- Excluir participantes com > 50% de dados faltantes em questões críticas ou padrões de resposta suspeitos
- Documentar todas as exclusões e razões

#### 12.4 Plano de análise para dados qualitativos (se houver)

**Dados Qualitativos:**
- VQ1: Lista de vantagens identificadas (respostas abertas)
- VQ2: Lista de desvantagens identificadas (respostas abertas)
- VQ3: Comentários e observações adicionais

**Estratégia de Análise:**

**Abordagem**: Análise de conteúdo temática com análise de frequência

**Processo:**

1. **Preparação**: Organizar respostas por grupo (API-First vs. Code-First) e tipo (vantagens, desvantagens, comentários)

2. **Codificação**:
   - Identificar unidades de significado nas respostas
   - Criar códigos descritivos (ex: "desenvolvimento paralelo", "complexidade inicial")
   - Agrupar códigos relacionados em categorias temáticas
   - Identificar temas principais que emergem das categorias

3. **Análise**:
   - Contar frequência de menção de cada tema por grupo
   - Comparar distribuição de temas entre grupos
   - Identificar temas exclusivos de cada grupo e temas comuns

4. **Integração**:
   - Relacionar temas qualitativos com resultados quantitativos
   - Usar insights qualitativos para interpretar resultados quantitativos
   - Identificar padrões principais e contraditórios

**Ferramentas:**
- Codificação manual usando Excel/planilhas
- Software de análise qualitativa (NVivo, Atlas.ti) se disponível

**Validação:**
- Revisão de códigos e temas pelo pesquisador e orientador
- Comparação com resultados quantitativos (triangulação)
- Documentação do processo de codificação

**Apresentação:**
- Tabelas de frequência de temas por grupo
- Citações representativas para ilustrar cada tema
- Narrativa integrando temas e padrões

---

### 13. Avaliação de validade (ameaças e mitigação)

#### 13.1 Validade de conclusão

Ameaças que podem comprometer a robustez das conclusões estatísticas:

**1. Baixo poder estatístico:**
- **Ameaça**: Tamanho de amostra insuficiente pode não detectar diferenças reais entre grupos (erro tipo II)
- **Mitigação**: 
  - Planejamento de tamanho mínimo de amostra (50 participantes) com cálculo de poder a priori
  - Aceitação de poder reduzido (60-65%) para efeitos médios, mas documentação clara dessa limitação
  - Análises de sensibilidade considerando diferentes tamanhos de efeito
  - Interpretação cautelosa de resultados não significativos (não concluir que não há diferença, mas que não foi detectada)

**2. Violação de suposições estatísticas:**
- **Ameaça**: Testes paramétricos assumem normalidade e homogeneidade de variâncias, que podem não ser atendidas
- **Mitigação**:
  - Verificação de normalidade através de testes (Shapiro-Wilk) e inspeção visual (histogramas, Q-Q plots)
  - Uso de testes não paramétricos (Mann-Whitney, Kruskal-Wallis) quando suposições não são atendidas
  - Transformações de dados quando apropriado (log, raiz quadrada)
  - Uso de testes robustos que são menos sensíveis a violações de suposições

**3. Erros de medida:**
- **Ameaça**: Respostas auto-relatadas podem conter erros sistemáticos ou aleatórios
- **Mitigação**:
  - Uso de escalas validadas (Likert) quando possível
  - Múltiplas perguntas para medir o mesmo constructo (triangulação)
  - Perguntas de verificação de compreensão para reduzir erros de interpretação
  - Validação de respostas inconsistentes e exclusão quando necessário

**4. Múltiplas comparações:**
- **Ameaça**: Realizar múltiplos testes aumenta probabilidade de falsos positivos (erro tipo I)
- **Mitigação**:
  - Correção de Bonferroni ou FDR (False Discovery Rate) quando múltiplas comparações são realizadas
  - Priorização de análises principais vs. exploratórias
  - Documentação clara de quais análises são confirmatórias vs. exploratórias

**5. Dados faltantes e outliers:**
- **Ameaça**: Dados faltantes ou outliers podem distorcer resultados
- **Mitigação**:
  - Estratégias claras de tratamento de dados faltantes (documentadas na seção 12.3)
  - Análise de sensibilidade com e sem outliers
  - Documentação de todas as exclusões e justificativas

#### 13.2 Validade interna

Ameaças relacionadas a causas alternativas para os efeitos observados:

**1. Viés de seleção (Selection Bias):**
- **Ameaça**: Grupos API-First e Code-First podem diferir sistematicamente em características que influenciam os resultados (ex: experiência, tipo de organização)
- **Estratégia de controle**:
  - Análise de características demográficas e contextuais entre grupos para identificar diferenças
  - Estratificação por variáveis de controle (experiência, tipo de organização, tamanho de equipe)
  - Análises ajustadas usando modelos estatísticos que controlam para variáveis de confusão
  - Matching de participantes por características relevantes quando possível

**2. História (History):**
- **Ameaça**: Eventos externos (mudanças tecnológicas, tendências da indústria) podem influenciar percepções dos participantes sobre as abordagens
- **Estratégia de controle**:
  - Coleta de dados em período relativamente curto (6-8 semanas) para minimizar mudanças contextuais
  - Perguntas sobre recência da experiência para controlar efeito de tempo
  - Análise considerando período em que a experiência ocorreu
  - Documentação de limitações relacionadas a mudanças no contexto tecnológico

**3. Maturação (Maturation):**
- **Ameaça**: Mudanças naturais nos participantes ao longo do tempo (aumento de experiência) podem influenciar percepções
- **Estratégia de controle**:
  - Estudo transversal (não longitudinal), então maturação não se aplica diretamente
  - Controle de experiência profissional através de estratificação
  - Perguntas sobre quando a experiência ocorreu para controlar efeito de tempo desde a experiência

**4. Viés de memória e recall (Recall Bias):**
- **Ameaça**: Participantes podem lembrar incorretamente ou de forma enviesada experiências passadas
- **Estratégia de controle**:
  - Foco em experiências recentes quando possível (pergunta sobre recência)
  - Perguntas sobre projetos específicos para ancorar memórias
  - Análise considerando recência da experiência
  - Transparência sobre limitações relacionadas a viés de memória

**5. Regressão à média:**
- **Ameaça**: Participantes com experiências extremas (muito positivas ou negativas) podem relatar percepções que regridem à média em medições subsequentes
- **Estratégia de controle**:
  - Estudo transversal com uma única medição, então regressão à média não se aplica diretamente
  - Análise de outliers e valores extremos para identificar padrões

**6. Mortalidade experimental (Attrition):**
- **Ameaça**: Participantes que abandonam o questionário podem diferir sistematicamente daqueles que completam
- **Estratégia de controle**:
  - Monitoramento de taxa de abandono e análise de características dos que abandonam
  - Design do questionário para minimizar abandono (progresso claro, tempo razoável)
  - Análise de padrões de resposta incompleta
  - Exclusão de respostas incompletas em questões críticas

**7. Instrumentação:**
- **Ameaça**: Mudanças no instrumento de medida durante a coleta podem afetar resultados
- **Estratégia de controle**:
  - Questionário fixo após validação do piloto
  - Sem mudanças durante a coleta principal
  - Documentação de qualquer ajuste necessário e análise de impacto

**8. Viés de desejabilidade social:**
- **Ameaça**: Participantes podem responder de forma socialmente desejável em vez de honesta
- **Estratégia de controle**:
  - Garantia de anonimato explícita
  - Perguntas diretas e objetivas
  - Perguntas sobre vantagens e desvantagens de ambas as abordagens para reduzir viés de confirmação
  - Análise de padrões de resposta suspeitos

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

**5. Efeito de halo:**
- **Ameaça**: Percepção geral positiva ou negativa de uma abordagem pode influenciar todas as avaliações
- **Mitigação**:
  - Perguntas sobre vantagens e desvantagens de ambas as abordagens
  - Ordem aleatória ou balanceada de perguntas
  - Análise de consistência entre diferentes dimensões de avaliação
  - Identificação de padrões de resposta que sugerem efeito de halo

**6. Viés de confirmação:**
- **Ameaça**: Participantes podem buscar confirmar suas escolhas anteriores
- **Mitigação**:
  - Perguntas sobre experiências reais, não sobre preferências
  - Perguntas sobre vantagens e desvantagens de ambas as abordagens
  - Análise de participantes com experiência mista (se houver)
  - Foco em comportamentos e resultados observáveis, não apenas opiniões

**7. Construção de grupos pode não refletir diferenças reais:**
- **Ameaça**: Classificação em grupos API-First vs. Code-First pode não capturar diferenças reais na experiência
- **Mitigação**:
  - Validação através de descrição detalhada da experiência
  - Perguntas sobre características específicas da abordagem utilizada
  - Exclusão de participantes com experiência ambígua ou mista (se necessário)
  - Análise de sensibilidade considerando diferentes critérios de classificação

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

2. **Viés geográfico e cultural:**
   - **Limitação**: Se maioria dos participantes for de uma região específica (ex: Brasil), resultados podem não se aplicar a outros contextos culturais ou organizacionais
   - **Impacto**: Práticas e percepções podem variar entre países e culturas organizacionais
   - **Mitigação**: Coleta de dados demográficos geográficos, análise de sensibilidade, discussão de limitações de generalização geográfica

3. **Viés de experiência:**
   - **Limitação**: Participantes que optam por responder podem ter características diferentes (mais experientes, mais engajados)
   - **Impacto**: Resultados podem superestimar ou subestimar certos aspectos
   - **Mitigação**: Análise de características demográficas, comparação com população-alvo quando possível

4. **Contexto temporal:**
   - **Limitação**: Resultados refletem percepções em um momento específico; práticas e tecnologias evoluem
   - **Impacto**: Resultados podem se tornar menos relevantes com mudanças tecnológicas
   - **Mitigação**: Documentação do período de coleta, discussão de relevância temporal dos resultados

5. **Tipo de projeto específico:**
   - **Limitação**: Experiências relatadas podem ser de tipos específicos de projetos (ex: projetos web, mobile, enterprise)
   - **Impacto**: Resultados podem não se aplicar a todos os tipos de projetos
   - **Mitigação**: Coleta de dados sobre tipo de projeto, análise estratificada por tipo de projeto quando possível

6. **Tamanho da amostra:**
   - **Limitação**: Tamanho mínimo de amostra (50 participantes) pode limitar generalização estatística
   - **Impacto**: Intervalos de confiança mais amplos, menor poder estatístico
   - **Mitigação**: Documentação clara de tamanho da amostra e limitações, interpretação cautelosa

7. **Idioma e cultura:**
   - **Limitação**: Survey em português limita participação a profissionais que dominam o idioma
   - **Impacto**: Resultados podem não se aplicar a contextos onde português não é o idioma principal
   - **Mitigação**: Documentação clara da limitação, possibilidade de replicação em outros idiomas

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
| | Violação de suposições estatísticas | Médio | Verificação de normalidade; uso de testes não paramétricos quando necessário |
| | Múltiplas comparações | Médio | Correção de Bonferroni ou FDR; priorização de análises |
| **Validade Interna** | Viés de seleção | Alto | Análise de características demográficas; estratificação; análises ajustadas |
| | Viés de memória/recall | Alto | Foco em experiências recentes; perguntas sobre projetos específicos; transparência sobre limitações |
| | Viés de desejabilidade social | Médio | Garantia de anonimato; perguntas diretas; análise de padrões suspeitos |
| **Validade de Constructo** | Definições ambíguas | Alto | Definições claras; exemplos; perguntas de verificação; validação através de descrição |
| | Medidas não representam constructos | Médio | Múltiplas métricas; triangulação quantitativa/qualitativa; base teórica |
| | Efeito de halo | Médio | Perguntas sobre vantagens e desvantagens; ordem balanceada; análise de consistência |
| **Validade Externa** | Amostra não probabilística | Alto | Documentação de características; transparência sobre limitações; diversificação de canais |
| | Viés geográfico/cultural | Médio | Coleta de dados demográficos; análise de sensibilidade; discussão de limitações |
| | Contexto temporal | Médio | Documentação do período; discussão de relevância temporal |

**Ameaças mais críticas (prioridade alta):**

1. **Viés de seleção**: Grupos podem diferir sistematicamente → Mitigação através de análise de características, estratificação e análises ajustadas
2. **Viés de memória**: Relatos sobre experiências passadas podem ser enviesados → Mitigação através de foco em experiências recentes e perguntas sobre projetos específicos
3. **Definições ambíguas**: Diferentes interpretações de API-First/Code-First → Mitigação através de definições claras, exemplos e validação
4. **Amostra não probabilística**: Limitações de generalização → Mitigação através de documentação detalhada, diversificação e transparência
5. **Baixo poder estatístico**: Pode não detectar diferenças reais → Mitigação através de tamanho mínimo planejado e documentação de limitações

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

**2. Uso de profissionais (não estudantes):**
- **Questão**: Estudo foca em profissionais da indústria, não estudantes
- **Tratamento**:
  - Critérios de inclusão exigem experiência profissional mínima (1 ano)
  - Estudantes sem experiência profissional são excluídos
  - Foco em experiências profissionais reais, não acadêmicas

**3. Ausência de incentivos financeiros:**
- **Questão**: Não há incentivos financeiros ou materiais para participação
- **Tratamento**:
  - Participação baseada em contribuição voluntária para pesquisa
  - Oferecimento de acesso aos resultados finais como benefício (não como incentivo)
  - Transparência sobre ausência de compensação financeira
  - Sem pressão para participar devido a incentivos

**4. Riscos de exposição e confidencialidade:**
- **Questão**: Participantes podem se preocupar com exposição de informações sensíveis sobre suas organizações
- **Tratamento**:
  - Anonimato completo garantido (sem coleta de identificadores pessoais)
  - Dados agregados e anonimizados na análise e publicação
  - Sem coleta de nomes de organizações ou projetos específicos
  - Informações contextuais coletadas de forma genérica (tipo de organização, não nome)
  - Dados armazenados de forma segura e acessíveis apenas ao pesquisador

**5. Carga de tempo e esforço:**
- **Questão**: Participantes dedicam tempo (15-20 minutos) sem compensação
- **Tratamento**:
  - Tempo estimado claramente comunicado
  - Questionário otimizado para ser eficiente
  - Direito de abandonar a qualquer momento
  - Reconhecimento do tempo dedicado na comunicação

**6. Uso de dados para pesquisa acadêmica:**
- **Questão**: Dados serão usados para TCC e possivelmente publicações
- **Tratamento**:
  - Transparência sobre uso dos dados no consentimento informado
  - Participantes informados sobre objetivos acadêmicos
  - Possibilidade de acesso aos resultados finais (se desejado)

**7. Vulnerabilidade dos participantes:**
- **Questão**: Verificação de se há grupos vulneráveis que precisam proteção especial
- **Tratamento**:
  - Participantes são profissionais adultos com capacidade de consentimento
  - Sem grupos vulneráveis identificados (não são crianças, pessoas com deficiência cognitiva, etc.)
  - Critérios de exclusão para menores de idade sem consentimento apropriado

**8. Conflitos de interesse:**
- **Questão**: Possíveis conflitos de interesse do pesquisador
- **Tratamento**:
  - Exclusão de participantes com relação profissional direta com pesquisador
  - Transparência sobre objetivos da pesquisa
  - Análise objetiva dos dados, sem viés intencional

**9. Retorno de benefícios:**
- **Questão**: Participantes contribuem sem receber benefício direto imediato
- **Tratamento**:
  - Oferecimento de acesso aos resultados finais do estudo
  - Contribuição para avanço do conhecimento na área
  - Benefício indireto através de evidências que podem orientar decisões futuras

#### 14.2 Consentimento informado

**Processo de consentimento informado:**

**1. Informações fornecidas aos participantes:**

O consentimento informado será integrado ao questionário online e incluirá as seguintes informações:

- **Título do estudo**: Design de API no Contexto de Arquiteturas Distribuídas: Um Estudo Comparativo entre API-First e Code-First

- **Objetivo**: Explicação clara do propósito da pesquisa, objetivos e questões de pesquisa

- **Procedimentos**: 
  - Descrição do que será solicitado (preenchimento de questionário online)
  - Tempo estimado (15-20 minutos)
  - Natureza das perguntas (experiências, percepções, dados demográficos)

- **Riscos e desconfortos**:
  - Riscos mínimos (carga de tempo)
  - Sem riscos físicos, psicológicos ou sociais significativos
  - Possível desconforto ao relembrar experiências negativas (mínimo)

- **Benefícios**:
  - Contribuição para avanço do conhecimento na área
  - Acesso aos resultados finais do estudo (se desejado)
  - Benefício indireto através de evidências que podem orientar decisões futuras

- **Confidencialidade e anonimato**:
  - Garantia de anonimato completo
  - Dados agregados e anonimizados
  - Sem identificação de participantes ou organizações
  - Armazenamento seguro dos dados
  - Uso dos dados apenas para fins de pesquisa acadêmica

- **Participação voluntária**:
  - Natureza voluntária da participação
  - Direito de retirada a qualquer momento, sem consequências
  - Possibilidade de abandonar o questionário sem penalização

- **Contato**:
  - Informações de contato do pesquisador (e-mail)
  - Informações de contato do orientador (se aplicável)
  - Informações sobre comitê de ética (se aplicável)

**2. Formato do consentimento:**

- **Integrado ao questionário**: Primeira seção do questionário online
- **Checkbox obrigatório**: Participante deve marcar checkbox confirmando que leu e concorda
- **Não é possível prosseguir sem consentimento**: Validação técnica impede avanço sem aceite
- **Texto claro e acessível**: Linguagem simples, sem jargão excessivo

**3. Registro do consentimento:**

- **Registro digital**: Aceite do consentimento registrado junto com as respostas do questionário
- **Timestamp**: Data e hora do consentimento registrados automaticamente
- **Armazenamento**: Consentimentos armazenados de forma segura junto com dados do estudo
- **Sem identificação pessoal**: Consentimento não vinculado a identificadores pessoais (anonimato mantido)

**4. Consentimento para menores de idade:**

- **Critério**: Participantes devem ser maiores de idade ou ter consentimento de responsável legal
- **Verificação**: Pergunta sobre idade no início do questionário
- **Exclusão**: Menores sem consentimento apropriado serão excluídos

**5. Reconsentimento (se necessário):**

- **Mudanças significativas**: Se houver mudanças significativas no protocolo, novo consentimento será solicitado
- **Uso futuro dos dados**: Se houver necessidade de uso futuro dos dados para outros fins, novo consentimento será solicitado

**6. Retirada do consentimento:**

- **Direito de retirada**: Participantes podem retirar consentimento a qualquer momento
- **Processo**: Contato com pesquisador para solicitar retirada
- **Tratamento de dados**: Dados já coletados podem ser mantidos se anonimizados (conforme aprovação ética), mas novos dados não serão coletados

#### 14.3 Privacidade e proteção de dados

**Dados coletados:**

**Dados não identificáveis (anonimizados):**
- Respostas ao questionário sobre experiências e percepções
- Dados demográficos genéricos (tipo de organização, tamanho de equipe, anos de experiência)
- Avaliações e opiniões sobre abordagens de design de API
- Respostas qualitativas (texto livre sobre vantagens, desvantagens, comentários)

**Dados não coletados (para garantir anonimato):**
- Nome completo
- E-mail pessoal ou profissional
- Nome da organização ou empresa
- Nome de projetos específicos
- Endereço ou localização específica
- Qualquer outro identificador pessoal direto

**Proteção de dados:**

**1. Anonimização:**
- **Coleta anônima**: Questionário configurado para não coletar identificadores automáticos (IP, cookies, etc.) quando possível
- **Dados já anonimizados na coleta**: Não há processo de anonimização posterior, pois dados já são coletados de forma anônima
- **Agregação**: Dados serão agregados para análise e publicação (sem identificação individual)

**2. Pseudoanonimização (se aplicável):**
- **Códigos de identificação**: Se necessário para rastreabilidade técnica, códigos numéricos serão usados (não vinculados a identificadores pessoais)
- **Separação de identificadores**: Qualquer identificador técnico será mantido separado dos dados de pesquisa

**3. Controle de acesso:**
- **Acesso restrito**: Apenas o pesquisador principal terá acesso aos dados brutos
- **Orientador**: Acesso apenas a dados agregados ou anonimizados para revisão
- **Sem compartilhamento**: Dados não serão compartilhados com terceiros sem aprovação ética
- **Armazenamento seguro**: Dados armazenados em local seguro (computador pessoal com senha, ou serviço de nuvem com autenticação)

**4. Armazenamento:**
- **Local**: Dados armazenados localmente em computador pessoal do pesquisador ou em serviço de nuvem seguro (Google Drive, OneDrive) com acesso restrito
- **Backup**: Backups regulares em local seguro
- **Formato**: Dados em formato estruturado (CSV, Excel) com proteção por senha quando possível

**5. Transmissão:**
- **Conexão segura**: Questionário online usando HTTPS (conexão criptografada)
- **Plataforma confiável**: Uso de plataformas de survey com políticas de privacidade adequadas (Google Forms, Typeform, SurveyMonkey)

**6. Retenção de dados:**
- **Período de retenção**: Dados serão mantidos por período necessário para conclusão do TCC e possíveis publicações (estimativa: 2-3 anos)
- **Destruição**: Após período de retenção, dados serão destruídos de forma segura (exclusão permanente de arquivos, sem possibilidade de recuperação)
- **Documentação**: Período de retenção documentado no consentimento informado

**7. Uso futuro dos dados:**
- **Uso secundário**: Se houver necessidade de uso futuro dos dados para outros fins de pesquisa, novo consentimento será solicitado
- **Publicação**: Dados agregados e anonimizados podem ser publicados em artigos ou repositórios acadêmicos (conforme aprovação ética)

**8. Direitos dos participantes:**
- **Acesso aos dados**: Participantes têm direito de solicitar informações sobre seus dados (limitado pelo anonimato)
- **Correção**: Participantes podem solicitar correção de dados (limitado pelo anonimato e natureza do estudo)
- **Exclusão**: Participantes podem solicitar exclusão de seus dados (se identificáveis, o que não é o caso devido ao anonimato)

**9. Conformidade com regulamentações:**
- **LGPD (Lei Geral de Proteção de Dados)**: Conformidade com LGPD brasileira
- **Aprovação ética**: Conformidade com diretrizes do comitê de ética da instituição
- **Boas práticas**: Seguimento de boas práticas de proteção de dados em pesquisa

**10. Incidentes de segurança:**
- **Plano de resposta**: Em caso de violação de dados (improvável devido ao anonimato), notificação imediata ao comitê de ética e participantes (se identificáveis)
- **Prevenção**: Medidas preventivas para evitar incidentes (armazenamento seguro, acesso restrito, backups)

#### 14.4 Aprovações necessárias (comitê de ética, jurídico, DPO, etc.)

**Aprovações necessárias:**

**1. Comitê de Ética em Pesquisa (CEP) da PUC Minas:**
- **Órgão**: Comitê de Ética em Pesquisa da PUC Minas (ou equivalente)
- **Documentação necessária**:
  - Protocolo de pesquisa completo
  - Termo de consentimento livre e esclarecido (TCLE)
  - Questionário completo
  - Plano de análise de dados
  - Documentação sobre proteção de dados
- **Status atual**: A ser submetido
- **Prazo estimado**: 4-8 semanas após submissão
- **Bloqueio**: Coleta de dados não pode iniciar sem aprovação

**2. Orientador do TCC:**
- **Pessoa**: Professor orientador do trabalho de conclusão de curso
- **Aprovação necessária para**:
  - Plano experimental completo
  - Questionário antes da submissão ao CEP
  - Estratégia de análise de dados
  - Qualquer mudança significativa no protocolo
- **Status atual**: Em revisão contínua
- **Formato**: Revisão e aprovação verbal ou por e-mail, documentada

**3. Coordenação do Curso (se necessário):**
- **Órgão**: Coordenação do Bacharelado em Engenharia de Software da PUC Minas
- **Aprovação necessária para**: Validação de que o estudo está alinhado com requisitos do TCC
- **Status atual**: A verificar necessidade
- **Formato**: Aprovação informal ou formal conforme políticas do curso

**4. Comitê de Proteção de Dados (DPO - Data Protection Officer):**
- **Órgão**: DPO da PUC Minas (se existir) ou responsável por proteção de dados
- **Aprovação necessária para**: Conformidade com LGPD e políticas de proteção de dados da instituição
- **Status atual**: A verificar necessidade e processo
- **Observação**: Pode estar incluído no processo de aprovação do CEP

**5. Banca examinadora (pós-execução):**
- **Órgão**: Banca examinadora do TCC
- **Aprovação necessária para**: Avaliação final do trabalho completo
- **Status atual**: Não aplicável (após execução)
- **Formato**: Apresentação e defesa do TCC

**Cronograma de aprovações:**

1. **Fase 1 - Preparação (Antes da submissão ao CEP)**:
   - [ ] Revisão do protocolo pelo orientador
   - [ ] Finalização do questionário
   - [ ] Preparação da documentação para CEP
   - **Prazo**: 2-3 semanas

2. **Fase 2 - Submissão ao CEP**:
   - [ ] Submissão da documentação ao CEP
   - [ ] Aguardar análise e possíveis solicitações de ajustes
   - [ ] Responder a solicitações do CEP
   - [ ] Receber aprovação final
   - **Prazo**: 4-8 semanas após submissão

3. **Fase 3 - Validação final**:
   - [ ] Validação do questionário após aprovação ética (se necessário)
   - [ ] Teste piloto (se aprovado pelo CEP)
   - [ ] Aprovação final do orientador para início da coleta
   - **Prazo**: 1-2 semanas

**Documentação para aprovação:**

- Plano experimental completo (este documento)
- Termo de consentimento livre e esclarecido (TCLE)
- Questionário completo
- Plano de análise de dados
- Documentação sobre proteção de dados e privacidade
- Informações sobre pesquisador e orientador
- Justificativa científica do estudo

**Status atual das aprovações:**

- **Comitê de Ética**: Pendente (a ser submetido)
- **Orientador**: Em revisão contínua
- **Coordenador do Curso**: A verificar necessidade
- **DPO**: A verificar necessidade
- **Banca Examinadora**: Não aplicável (após execução)

**Observações:**

- Todas as aprovações necessárias devem ser obtidas antes do início da coleta de dados
- Qualquer mudança significativa no protocolo após aprovação pode exigir nova submissão ou comunicação ao CEP
- Documentação de todas as aprovações será mantida para registro

---

### 15. Recursos, infraestrutura e orçamento

#### 15.1 Recursos humanos e papéis

**Equipe do experimento:**

**1. Pesquisador Principal / Autor do TCC:**
- **Nome**: Gabriel Lourenço Reis Resende
- **Papel**: Executor principal do experimento
- **Responsabilidades**:
  - Desenvolvimento do plano experimental
  - Criação e validação do questionário
  - Submissão ao comitê de ética
  - Recrutamento de participantes
  - Coleta de dados
  - Análise de dados (quantitativa e qualitativa)
  - Redação do trabalho de conclusão de curso
  - Comunicação com participantes
  - Documentação do processo experimental
- **Carga horária estimada**: 200-300 horas ao longo do período do TCC
- **Disponibilidade**: Tempo parcial (concomitante com outras atividades acadêmicas)

**2. Orientador do TCC:**
- **Nome**: A definir (professor orientador)
- **Papel**: Orientador científico e supervisor metodológico
- **Responsabilidades**:
  - Orientação científica sobre metodologia de pesquisa
  - Revisão e validação do plano experimental
  - Revisão e aprovação do questionário
  - Revisão da estratégia de análise de dados
  - Supervisão da execução do experimento
  - Revisão de resultados e interpretações
  - Revisão do trabalho escrito
  - Apoio na submissão ao comitê de ética
- **Carga horária estimada**: 20-40 horas de orientação
- **Disponibilidade**: Conforme cronograma de orientação acadêmica

**3. Participantes do Survey (Voluntários):**
- **Número**: 50-80 participantes
- **Papel**: Fornecedores de dados através de respostas ao questionário
- **Responsabilidades**:
  - Preenchimento honesto e completo do questionário
  - Fornecimento de informações baseadas em experiências reais
- **Carga horária por participante**: 15-20 minutos
- **Compensação**: Voluntária, sem compensação financeira

**4. Banca Examinadora (Pós-execução):**
- **Número**: 2-3 membros (a definir)
- **Papel**: Avaliação final do trabalho
- **Responsabilidades**:
  - Avaliação da qualidade científica do trabalho
  - Avaliação da metodologia e resultados
  - Avaliação da contribuição científica
  - Aprovação ou solicitação de ajustes
- **Carga horária**: 2-4 horas por membro (leitura e avaliação)
- **Disponibilidade**: Após conclusão do trabalho escrito

**5. Comitê de Ética em Pesquisa (CEP):**
- **Órgão**: Comitê de Ética da PUC Minas
- **Papel**: Avaliação ética do protocolo de pesquisa
- **Responsabilidades**:
  - Revisão do protocolo de pesquisa
  - Avaliação de aspectos éticos
  - Aprovação, solicitação de ajustes ou reprovação
- **Carga horária**: Processo institucional
- **Disponibilidade**: Conforme cronograma do CEP

**Estrutura organizacional:**

```
Pesquisador Principal (Gabriel)
    │
    ├── Orientador (Supervisão)
    │
    ├── CEP (Aprovação ética)
    │
    ├── Participantes (Coleta de dados)
    │
    └── Banca Examinadora (Avaliação final)
```

**Comunicação e coordenação:**

- **Pesquisador ↔ Orientador**: Reuniões regulares de orientação (semanal ou quinzenal), comunicação por e-mail
- **Pesquisador ↔ Participantes**: Comunicação através do questionário e mensagens de recrutamento
- **Pesquisador ↔ CEP**: Comunicação formal através de sistema de submissão do CEP
- **Pesquisador ↔ Banca**: Comunicação através de apresentação e defesa do TCC

**Observações:**

- Equipe enxuta, focada em pesquisa acadêmica de TCC
- Sem equipe técnica adicional (pesquisador realiza todas as atividades técnicas)
- Sem necessidade de equipe de análise de dados externa (pesquisador realiza análises)
- Suporte do orientador em questões metodológicas e científicas

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

**2. Computador do Pesquisador:**
- **Requisitos**:
  - Computador pessoal com sistema operacional (Windows, macOS ou Linux)
  - Navegador web atualizado
  - Acesso à internet estável
  - Software de planilhas (Microsoft Excel, Google Sheets ou LibreOffice Calc)
- **Uso**: Criação do questionário, análise de dados, redação do trabalho
- **Disponibilidade**: Já disponível

**3. Software de Análise de Dados:**
- **Ferramentas**:
  - **Python** (com bibliotecas: pandas, numpy, scipy, matplotlib, seaborn) OU
  - **R** (com pacotes: dplyr, ggplot2, etc.) OU
  - **Microsoft Excel / Google Sheets** (para análises básicas)
- **Requisitos**:
  - Capacidade de importar dados CSV/Excel
  - Análises estatísticas (testes t, qui-quadrado, etc.)
  - Visualizações (gráficos, tabelas)
  - Análises qualitativas (codificação de texto)
- **Custo**: Gratuito (Python, R) ou já disponível (Excel)
- **Disponibilidade**: Instalação local ou uso online

**4. Armazenamento de Dados:**
- **Opções**:
  - **Armazenamento local**: Computador pessoal com backup
  - **Armazenamento em nuvem**: Google Drive, OneDrive, Dropbox (com acesso restrito)
- **Requisitos**:
  - Segurança (proteção por senha, acesso restrito)
  - Backup regular
  - Capacidade suficiente para dados do estudo (mínimo: alguns MB)
- **Custo**: Gratuito (planos básicos de nuvem) ou já disponível
- **Disponibilidade**: Já disponível

**5. Repositório de Código (Opcional):**
- **Ferramenta**: GitHub, GitLab ou similar
- **Uso**: Versionamento de scripts de análise, documentação
- **Requisitos**: Conta gratuita
- **Custo**: Gratuito
- **Disponibilidade**: Criar se necessário

**6. Software de Documentação:**
- **Ferramentas**:
  - Editor de texto (Microsoft Word, Google Docs, LaTeX)
  - Software de apresentação (PowerPoint, Google Slides) para defesa
- **Requisitos**: Capacidade de criar documentos acadêmicos
- **Custo**: Gratuito (Google Docs) ou já disponível
- **Disponibilidade**: Já disponível

**7. Comunicação:**
- **Ferramentas**:
  - E-mail (para comunicação com orientador, CEP, participantes)
  - Plataforma de videoconferência (Zoom, Google Meet) para reuniões com orientador
- **Requisitos**: Acesso a e-mail e internet
- **Custo**: Gratuito
- **Disponibilidade**: Já disponível

**8. Navegadores para Teste:**
- **Requisitos**: Testar questionário em diferentes navegadores (Chrome, Firefox, Safari, Edge)
- **Uso**: Validação de compatibilidade do questionário
- **Disponibilidade**: Já disponível ou acessível

**Resumo de infraestrutura:**

| Componente | Ferramenta | Custo | Status |
|------------|-----------|-------|--------|
| Plataforma de Survey | Google Forms / Typeform | Gratuito/Baixo | A configurar |
| Computador | Computador pessoal | Já disponível | Disponível |
| Análise de Dados | Python/R ou Excel | Gratuito | A instalar/configurar |
| Armazenamento | Local + Nuvem | Gratuito | Disponível |
| Repositório | GitHub (opcional) | Gratuito | A criar se necessário |
| Documentação | Word/Google Docs | Gratuito | Disponível |
| Comunicação | E-mail, Zoom | Gratuito | Disponível |

**Dependências técnicas:**

- **Internet**: Necessária para acesso à plataforma de survey, comunicação, armazenamento em nuvem
- **Eletricidade**: Necessária para operação do computador
- **Navegadores atualizados**: Necessários para funcionamento adequado da plataforma de survey

**Plano de contingência:**

- **Falha na plataforma de survey**: Ter backup em plataforma alternativa (ex: se Google Forms falhar, usar Typeform)
- **Perda de dados**: Backups regulares em múltiplos locais (local + nuvem)
- **Problemas de software**: Uso de alternativas gratuitas (Python/R em vez de software pago)
- **Problemas de internet**: Trabalho offline quando possível, sincronização quando internet estiver disponível

#### 15.3 Materiais e insumos

**Materiais e insumos necessários:**

**1. Questionário Online:**
- **Tipo**: Formulário digital criado na plataforma de survey
- **Conteúdo**: Baseado no plano experimental (seções: consentimento, definições, triagem, coleta de dados)
- **Status**: A ser criado após aprovação ética e validação do piloto
- **Custo**: Gratuito (plataformas gratuitas) ou baixo (planos básicos)

**2. Termo de Consentimento Livre e Esclarecido (TCLE):**
- **Tipo**: Documento digital integrado ao questionário
- **Conteúdo**: Informações sobre o estudo, riscos, benefícios, confidencialidade
- **Status**: A ser criado e aprovado pelo CEP
- **Custo**: Nenhum (criação pelo pesquisador)

**3. Planilha de Dados:**
- **Tipo**: Arquivo digital (CSV, Excel)
- **Uso**: Armazenamento e organização dos dados coletados
- **Status**: A ser criado após início da coleta
- **Custo**: Nenhum (software gratuito)

**4. Scripts de Análise:**
- **Tipo**: Scripts em Python ou R (opcional)
- **Uso**: Análise automatizada e reprodutível dos dados
- **Status**: A ser criado durante fase de análise
- **Custo**: Nenhum (software gratuito)

**5. Documentação do Experimento:**
- **Tipo**: Documentos digitais (Word, PDF, Markdown)
- **Conteúdo**: 
  - Plano experimental (este documento)
  - Protocolo de pesquisa para CEP
  - Guias de operação
  - Relatórios de coleta
- **Status**: Em desenvolvimento (plano experimental) e a criar (outros)
- **Custo**: Nenhum (software gratuito)

**6. Materiais de Recrutamento:**
- **Tipo**: Mensagens digitais (texto para redes sociais, fóruns, grupos)
- **Conteúdo**: 
  - Mensagens de recrutamento para diferentes canais
  - Links para o questionário
  - Informações sobre o estudo
- **Status**: A ser criado antes da coleta
- **Custo**: Nenhum

**7. Log de Coleta de Dados:**
- **Tipo**: Documento digital (planilha ou documento de texto)
- **Uso**: Registro de atividades de coleta, problemas, ajustes
- **Status**: A ser criado no início da coleta
- **Custo**: Nenhum

**8. Licenças de Software (se necessário):**
- **Tipo**: Licenças para software pago (se optar por ferramentas pagas)
- **Opções**: 
  - Planos básicos de plataformas de survey (Typeform, SurveyMonkey) - se necessário
  - Licenças de software de análise (improvável, usando ferramentas gratuitas)
- **Status**: A avaliar necessidade
- **Custo**: Baixo (se necessário, planos básicos ~$10-20/mês)

**9. Dispositivos:**
- **Computador**: Já disponível (computador pessoal do pesquisador)
- **Smartphone/Tablet**: Opcional, para teste de compatibilidade do questionário
- **Status**: Disponível

**10. Acesso a Comunidades e Canais:**
- **Tipo**: Acesso a redes sociais, fóruns, grupos profissionais
- **Canais**:
  - LinkedIn (conta pessoal)
  - Reddit (conta gratuita)
  - Grupos de WhatsApp/Telegram
  - Comunidades técnicas online
- **Status**: Já disponível ou a criar
- **Custo**: Gratuito

**Resumo de materiais:**

| Material | Tipo | Status | Custo |
|----------|------|--------|-------|
| Questionário Online | Digital | A criar | Gratuito |
| TCLE | Digital | A criar | Gratuito |
| Planilha de Dados | Digital | A criar | Gratuito |
| Scripts de Análise | Digital | A criar | Gratuito |
| Documentação | Digital | Em desenvolvimento | Gratuito |
| Materiais de Recrutamento | Digital | A criar | Gratuito |
| Log de Coleta | Digital | A criar | Gratuito |
| Licenças de Software | Licença | A avaliar | Baixo (se necessário) |
| Computador | Físico | Disponível | Já disponível |
| Acesso a Canais | Digital | Disponível | Gratuito |

**Checklist de prontidão de materiais:**

Antes do início da coleta de dados, os seguintes materiais devem estar prontos:

- [ ] Questionário online criado e testado
- [ ] TCLE integrado ao questionário e aprovado pelo CEP
- [ ] Planilha de dados estruturada (template)
- [ ] Materiais de recrutamento preparados
- [ ] Log de coleta criado
- [ ] Documentação do experimento atualizada
- [ ] Acesso a canais de recrutamento verificado
- [ ] Software de análise instalado e testado (se aplicável)

**Observações:**

- Todos os materiais são digitais (sem necessidade de materiais físicos)
- Maioria dos materiais tem custo zero (uso de ferramentas gratuitas)
- Materiais serão criados pelo pesquisador (sem necessidade de terceiros)
- Foco em ferramentas gratuitas e de baixo custo para manter orçamento mínimo

#### 15.4 Orçamento e custos estimados

**Estimativa de custos:**

**1. Recursos Humanos:**

| Recurso | Horas Estimadas | Custo por Hora | Custo Total | Observação |
|---------|----------------|----------------|-------------|------------|
| Pesquisador Principal | 200-300 horas | R$ 0 (voluntário) | R$ 0 | Trabalho acadêmico voluntário |
| Orientador | 20-40 horas | R$ 0 (orientação acadêmica) | R$ 0 | Orientação incluída nas responsabilidades acadêmicas |
| Participantes | 50-80 × 0,3h = 15-24h | R$ 0 (voluntários) | R$ 0 | Participação voluntária |
| **Subtotal Recursos Humanos** | | | **R$ 0** | |

**2. Infraestrutura e Serviços:**

| Item | Descrição | Custo Mensal | Período | Custo Total |
|------|-----------|--------------|---------|-------------|
| Plataforma de Survey | Google Forms (gratuito) ou Typeform (plano básico) | R$ 0 - R$ 50 | 3 meses | R$ 0 - R$ 150 |
| Armazenamento em Nuvem | Google Drive / OneDrive (plano gratuito) | R$ 0 | 3 meses | R$ 0 |
| Software de Análise | Python/R (gratuito) ou Excel (já disponível) | R$ 0 | - | R$ 0 |
| **Subtotal Infraestrutura** | | | | **R$ 0 - R$ 150** |

**3. Licenças de Software:**

| Software | Necessidade | Custo | Observação |
|----------|-------------|-------|------------|
| Microsoft Office | Opcional (alternativas gratuitas) | R$ 0 | Google Docs como alternativa |
| Software de Análise Estatística | Não necessário (Python/R gratuito) | R$ 0 | Ferramentas open-source |
| Plataforma de Survey Premium | Opcional | R$ 0 - R$ 50/mês | Planos gratuitos disponíveis |
| **Subtotal Licenças** | | | **R$ 0 - R$ 150** |

**4. Materiais e Insumos:**

| Material | Custo | Observação |
|----------|-------|------------|
| Materiais digitais | R$ 0 | Criação pelo pesquisador |
| Impressões | R$ 0 | Tudo digital |
| **Subtotal Materiais** | | **R$ 0** |

**5. Comunicação e Divulgação:**

| Item | Custo | Observação |
|------|-------|------------|
| Divulgação em redes sociais | R$ 0 | Canais gratuitos |
| Comunicação por e-mail | R$ 0 | E-mail institucional/pessoal |
| **Subtotal Comunicação** | | **R$ 0** |

**6. Outros Custos:**

| Item | Custo | Observação |
|------|-------|------------|
| Taxas de submissão (CEP) | R$ 0 | Geralmente gratuito para estudantes |
| Taxas de publicação (futuro) | R$ 0 | Não aplicável no momento |
| **Subtotal Outros** | | **R$ 0** |

**Resumo de custos:**

| Categoria | Custo Mínimo | Custo Máximo | Observação |
|-----------|--------------|--------------|------------|
| Recursos Humanos | R$ 0 | R$ 0 | Voluntário |
| Infraestrutura | R$ 0 | R$ 150 | Maioria gratuita |
| Licenças | R$ 0 | R$ 150 | Opcionais |
| Materiais | R$ 0 | R$ 0 | Digitais |
| Comunicação | R$ 0 | R$ 0 | Gratuito |
| Outros | R$ 0 | R$ 0 | Não aplicável |
| **TOTAL** | **R$ 0** | **R$ 300** | |

**Cenário mais provável:**
- **Custo estimado**: R$ 0 - R$ 50 (uso de ferramentas gratuitas)
- **Custo máximo**: R$ 300 (se optar por planos premium de plataformas de survey)

**Fonte de financiamento:**

- **Financiamento próprio**: Pesquisador arcará com custos mínimos (se houver)
- **Sem financiamento externo**: Não há solicitação de bolsas ou financiamento externo
- **Recursos da instituição**: Uso de recursos já disponíveis (e-mail institucional, acesso a biblioteca, orientação acadêmica)
- **Ferramentas gratuitas**: Priorização de ferramentas gratuitas para manter custos zero

**Plano de contingência para custos:**

- **Cenário 1 - Custo zero**: Uso exclusivo de ferramentas gratuitas (Google Forms, Python, Google Drive)
- **Cenário 2 - Custo baixo**: Se necessário, uso de planos básicos de plataformas de survey (R$ 50/mês por 2-3 meses = R$ 100-150)
- **Cenário 3 - Custo médio**: Se necessário, uso de múltiplas ferramentas premium (improvável, máximo R$ 300)

**Observações:**

- Experimento projetado para ter custo mínimo ou zero
- Foco em ferramentas gratuitas e de código aberto
- Sem necessidade de financiamento externo
- Custos serão arcados pelo pesquisador se necessário (valores baixos)
- Priorização de alternativas gratuitas sempre que possível

---

### 16. Cronograma, marcos e riscos operacionais

#### 16.1 Macrocronograma (até o início da execução)

**Macrocronograma do experimento:**

**FASE 1: PLANEJAMENTO E PREPARAÇÃO (8-12 semanas)**

**Semana 1-2: Finalização do Plano Experimental**
- [ ] Revisão final do plano experimental
- [ ] Validação do plano pelo orientador
- [ ] Ajustes baseados em feedback
- **Marco**: Plano experimental aprovado pelo orientador

**Semana 3-4: Desenvolvimento do Questionário**
- [ ] Criação da estrutura do questionário
- [ ] Desenvolvimento de todas as seções (consentimento, definições, perguntas)
- [ ] Revisão do questionário pelo orientador
- [ ] Ajustes baseados em feedback
- **Marco**: Questionário completo e revisado

**Semana 5-6: Preparação para Submissão ao CEP**
- [ ] Preparação da documentação para CEP (protocolo, TCLE, questionário)
- [ ] Revisão final da documentação
- [ ] Submissão ao Comitê de Ética em Pesquisa (CEP)
- **Marco**: Documentação submetida ao CEP

**Semana 7-10: Aguardar Aprovação Ética**
- [ ] Acompanhamento do processo no CEP
- [ ] Resposta a solicitações de ajustes (se houver)
- [ ] Aprovação final do CEP
- **Marco**: Aprovação ética obtida

**FASE 2: VALIDAÇÃO E PILOTO (2-3 semanas)**

**Semana 11-12: Teste Piloto**
- [ ] Configuração do questionário na plataforma de survey
- [ ] Recrutamento de participantes para piloto (5-8 participantes)
- [ ] Execução do piloto
- [ ] Coleta de feedback dos participantes do piloto
- [ ] Análise dos resultados do piloto
- [ ] Ajustes no questionário baseados no piloto
- [ ] Validação final do questionário
- **Marco**: Questionário validado e pronto para coleta principal

**FASE 3: PREPARAÇÃO FINAL (1-2 semanas)**

**Semana 13: Preparação para Coleta**
- [ ] Configuração final do questionário na plataforma
- [ ] Preparação de materiais de recrutamento
- [ ] Identificação e contato com canais de recrutamento
- [ ] Teste final do questionário
- [ ] Preparação de planilha de dados e log de coleta
- **Marco**: Tudo pronto para início da coleta

**FASE 4: COLETA DE DADOS (6-8 semanas)**

**Semana 14-15: Início da Coleta**
- [ ] Abertura do questionário para respostas
- [ ] Divulgação inicial em canais primários
- [ ] Monitoramento inicial de respostas
- **Marco**: Coleta de dados iniciada

**Semana 16-17: Divulgação Secundária**
- [ ] Divulgação em canais secundários
- [ ] Amostra por bola de neve
- [ ] Monitoramento contínuo de respostas e balanceamento

**Semana 18-19: Recrutamento Direcionado (se necessário)**
- [ ] Ajuste de estratégia se houver desbalanceamento
- [ ] Recrutamento direcionado para grupos sub-representados
- [ ] Continuar monitoramento

**Semana 20-21: Finalização da Coleta**
- [ ] Avaliar se tamanho mínimo foi atingido
- [ ] Decisão sobre continuar ou encerrar coleta
- [ ] Encerramento da coleta (fechar questionário)
- [ ] Exportação final dos dados
- **Marco**: Coleta de dados concluída

**Cronograma resumido:**

| Fase | Atividades | Duração | Marcos |
|------|-----------|---------|--------|
| **Planejamento** | Finalização do plano, desenvolvimento do questionário, submissão ao CEP | 8-12 semanas | Plano aprovado, CEP aprovado |
| **Validação** | Teste piloto, ajustes | 2-3 semanas | Questionário validado |
| **Preparação Final** | Configuração, materiais de recrutamento | 1-2 semanas | Pronto para coleta |
| **Coleta** | Recrutamento, coleta de dados | 6-8 semanas | Dados coletados |
| **TOTAL** | | **17-25 semanas** | |

**Datas estimadas (exemplo):**

Assumindo início em janeiro de 2025:

- **Início do planejamento**: Janeiro 2025
- **Submissão ao CEP**: Março 2025
- **Aprovação do CEP**: Maio 2025 (após 4-8 semanas)
- **Piloto**: Junho 2025
- **Início da coleta**: Julho 2025
- **Fim da coleta**: Setembro 2025

**Observações sobre o cronograma:**

- **Flexibilidade**: Cronograma pode ser ajustado conforme disponibilidade e prazos do TCC
- **Dependências críticas**: Aprovação do CEP é bloqueante para início da coleta
- **Buffer de tempo**: Incluído para imprevistos e atrasos
- **Paralelização**: Algumas atividades podem ser feitas em paralelo (ex: preparação de materiais enquanto aguarda CEP)
- **Realismo**: Cronograma considera prazos típicos de CEP (4-8 semanas) e tempo necessário para recrutamento

#### 16.2 Dependências entre atividades

**Dependências críticas do experimento:**

**1. Desenvolvimento do Questionário → Revisão pelo Orientador**
- **Dependência**: Questionário deve ser desenvolvido antes da revisão
- **Tipo**: Sequencial obrigatória
- **Bloqueio**: Não pode revisar questionário que não existe
- **Flexibilidade**: Pode haver iterações (revisão → ajustes → revisão)

**2. Questionário Revisado → Preparação para CEP**
- **Dependência**: Questionário final deve estar pronto para incluir na documentação do CEP
- **Tipo**: Sequencial obrigatória
- **Bloqueio**: Não pode submeter ao CEP sem questionário completo
- **Flexibilidade**: Pequenos ajustes podem ser feitos após submissão (com comunicação ao CEP)

**3. Preparação da Documentação → Submissão ao CEP**
- **Dependência**: Toda documentação deve estar pronta antes da submissão
- **Tipo**: Sequencial obrigatória
- **Bloqueio**: CEP não aceita submissões incompletas
- **Flexibilidade**: Documentação pode ser preparada em paralelo com outras atividades

**4. Submissão ao CEP → Aprovação do CEP → Início da Coleta**
- **Dependência**: **CRÍTICA** - Coleta não pode iniciar sem aprovação ética
- **Tipo**: Sequencial obrigatória e bloqueante
- **Bloqueio**: **Não é possível iniciar coleta sem aprovação do CEP**
- **Flexibilidade**: Nenhuma - esta é uma dependência rígida e obrigatória
- **Tempo**: 4-8 semanas típicas para aprovação

**5. Aprovação do CEP → Configuração do Questionário na Plataforma**
- **Dependência**: Questionário deve estar aprovado antes de configurar na plataforma
- **Tipo**: Sequencial obrigatória
- **Bloqueio**: Não deve configurar questionário que pode precisar de ajustes após aprovação
- **Flexibilidade**: Configuração pode ser feita em paralelo com outras preparações

**6. Questionário Configurado → Teste Piloto**
- **Dependência**: Questionário deve estar configurado e funcional antes do piloto
- **Tipo**: Sequencial obrigatória
- **Bloqueio**: Não pode testar questionário que não está configurado
- **Flexibilidade**: Piloto pode ser feito com versão preliminar para validação técnica

**7. Teste Piloto → Ajustes no Questionário → Validação Final**
- **Dependência**: Ajustes devem ser feitos após análise do piloto
- **Tipo**: Sequencial obrigatória
- **Bloqueio**: Não deve iniciar coleta principal sem ajustar problemas identificados no piloto
- **Flexibilidade**: Ajustes podem ser menores ou maiores dependendo dos resultados

**8. Validação Final → Preparação de Materiais de Recrutamento**
- **Dependência**: Questionário final deve estar pronto antes de preparar materiais (que referenciam o questionário)
- **Tipo**: Sequencial recomendada (não crítica)
- **Bloqueio**: Não crítico, mas recomendado
- **Flexibilidade**: Materiais podem ser preparados com link provisório

**9. Materiais de Recrutamento Prontos → Início da Coleta**
- **Dependência**: Materiais devem estar prontos para divulgação
- **Tipo**: Sequencial recomendada
- **Bloqueio**: Não crítico, mas eficiente ter materiais prontos
- **Flexibilidade**: Materiais podem ser ajustados durante a coleta

**10. Início da Coleta → Monitoramento → Encerramento**
- **Dependência**: Coleta deve iniciar antes de monitorar e encerrar
- **Tipo**: Sequencial obrigatória
- **Bloqueio**: Lógico
- **Flexibilidade**: Monitoramento contínuo, encerramento quando critérios atendidos

**Diagrama de dependências (simplificado):**

```
Plano Experimental
    ↓
Desenvolvimento do Questionário
    ↓
Revisão pelo Orientador
    ↓
Preparação para CEP
    ↓
Submissão ao CEP
    ↓
[AGUARDAR 4-8 SEMANAS]
    ↓
Aprovação do CEP
    ↓
Configuração na Plataforma
    ↓
Teste Piloto
    ↓
Ajustes
    ↓
Validação Final
    ↓
Preparação de Materiais
    ↓
Início da Coleta 
    ↓
Monitoramento
    ↓
Encerramento da Coleta
```

**Dependências paralelas (podem ser feitas simultaneamente):**

- Preparação de materiais de recrutamento pode ser feita enquanto aguarda aprovação do CEP
- Desenvolvimento de scripts de análise pode ser feito em paralelo com outras atividades
- Estudo de literatura e referencial teórico pode continuar em paralelo
- Preparação de planilhas e logs pode ser feita antecipadamente

**Pontos de bloqueio críticos:**

1. **Aprovação do CEP**: Bloqueia todo o processo de coleta
2. **Validação do questionário**: Bloqueia início da coleta principal
3. **Tamanho mínimo de amostra**: Pode exigir extensão do período de coleta

**Estratégias para gerenciar dependências:**

- **Antecipação**: Iniciar atividades que não dependem de outras o mais cedo possível
- **Paralelização**: Fazer atividades independentes em paralelo
- **Buffer de tempo**: Incluir margem de segurança para dependências críticas (ex: CEP)
- **Monitoramento**: Acompanhar status de dependências críticas regularmente
- **Comunicação**: Manter comunicação com dependentes (orientador, CEP) para evitar atrasos

#### 16.3 Riscos operacionais e plano de contingência

**Riscos operacionais e planos de contingência:**

**1. Atraso na aprovação do CEP:**
- **Risco**: CEP pode levar mais de 8 semanas para aprovar, atrasando todo o cronograma
- **Probabilidade**: Média
- **Impacto**: Alto (bloqueia início da coleta)
- **Contingência**:
  - Submissão antecipada (o mais cedo possível)
  - Preparação cuidadosa da documentação para evitar solicitações de ajustes
  - Acompanhamento regular do status no CEP
  - Comunicação proativa com CEP em caso de atrasos
  - Ajuste do cronograma do TCC se necessário (comunicação com orientador)
  - Uso do tempo de espera para outras atividades (literatura, preparação de materiais)

**2. Indisponibilidade do orientador:**
- **Risco**: Orientador pode estar indisponível para revisões ou orientações, atrasando aprovações
- **Probabilidade**: Baixa-Média
- **Impacto**: Médio
- **Contingência**:
  - Agendamento antecipado de reuniões de orientação
  - Comunicação clara sobre prazos e urgências
  - Planejamento de buffer de tempo para revisões
  - Uso de comunicação assíncrona (e-mail) quando reuniões não são possíveis
  - Documentação clara para facilitar revisões rápidas

**3. Problemas técnicos com plataforma de survey:**
- **Risco**: Plataforma escolhida pode ter problemas técnicos, indisponibilidade ou limitações
- **Probabilidade**: Baixa
- **Impacto**: Alto (bloqueia coleta)
- **Contingência**:
  - Identificação de plataforma alternativa de backup (ex: se Google Forms falhar, usar Typeform)
  - Teste da plataforma antes do início da coleta
  - Exportação regular de dados durante a coleta (backup)
  - Migração para plataforma alternativa se necessário (com comunicação aos participantes)

**4. Baixa taxa de resposta ao survey:**
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

**5. Desbalanceamento entre grupos:**
- **Risco**: Desequilíbrio significativo entre participantes API-First vs. Code-First
- **Probabilidade**: Média
- **Impacto**: Médio
- **Contingência**:
  - Monitoramento contínuo da distribuição durante a coleta
  - Recrutamento direcionado para grupo sub-representado
  - Mensagens de recrutamento específicas para cada grupo
  - Extensão do período de coleta se necessário
  - Uso de técnicas estatísticas apropriadas para amostras desbalanceadas
  - Análise com grupos desbalanceados, documentando limitações

**6. Problemas de saúde ou pessoais do pesquisador:**
- **Risco**: Situações pessoais podem impedir progresso do experimento
- **Probabilidade**: Baixa
- **Impacto**: Alto
- **Contingência**:
  - Planejamento com margem de tempo para imprevistos
  - Comunicação proativa com orientador em caso de problemas
  - Priorização de atividades críticas
  - Ajuste de cronograma quando necessário
  - Documentação do progresso para facilitar retomada

**7. Mudanças nos requisitos do TCC:**
- **Risco**: Mudanças nos requisitos acadêmicos podem exigir ajustes no experimento
- **Probabilidade**: Baixa
- **Impacto**: Médio-Alto
- **Contingência**:
  - Comunicação regular com orientador sobre requisitos
  - Flexibilidade no desenho experimental para permitir ajustes
  - Documentação clara de decisões metodológicas
  - Revisão do plano se necessário, com aprovação do orientador

**8. Problemas com qualidade dos dados coletados:**
- **Risco**: Dados coletados podem ter problemas de qualidade (respostas inválidas, inconsistentes)
- **Probabilidade**: Média
- **Impacto**: Médio
- **Contingência**:
  - Validação contínua durante a coleta
  - Exclusão de respostas inválidas conforme critérios definidos
  - Análise de qualidade dos dados antes do encerramento
  - Recrutamento adicional se qualidade comprometer tamanho da amostra
  - Documentação de problemas de qualidade e tratamento aplicado

**9. Indisponibilidade de recursos técnicos:**
- **Risco**: Problemas com computador, internet ou software podem impedir trabalho
- **Probabilidade**: Baixa
- **Impacto**: Médio
- **Contingência**:
  - Backup de dados em múltiplos locais (local + nuvem)
  - Uso de alternativas (biblioteca da universidade, computadores públicos)
  - Trabalho offline quando possível
  - Uso de ferramentas online que não dependem de instalação local

**10. Conflitos de agenda:**
- **Risco**: Conflitos com outras atividades acadêmicas ou pessoais
- **Probabilidade**: Média
- **Impacto**: Médio
- **Contingência**:
  - Planejamento realista considerando outras atividades
  - Priorização de atividades críticas
  - Comunicação proativa sobre conflitos
  - Ajuste de cronograma quando necessário

**Resumo de riscos operacionais:**

| Risco | Probabilidade | Impacto | Prioridade | Contingência Principal |
|-------|---------------|---------|------------|----------------------|
| Atraso no CEP | Média | Alto | Alta | Submissão antecipada, acompanhamento |
| Baixa taxa de resposta | Média-Alta | Alto | Alta | Diversificação de canais, extensão de prazo |
| Desbalanceamento | Média | Médio | Média | Recrutamento direcionado, monitoramento |
| Problemas técnicos | Baixa | Alto | Média | Plataforma alternativa, backups |
| Indisponibilidade orientador | Baixa-Média | Médio | Média | Agendamento antecipado, comunicação clara |
| Problemas pessoais | Baixa | Alto | Baixa | Margem de tempo, priorização |
| Qualidade dos dados | Média | Médio | Média | Validação contínua, exclusão criteriosa |

**Plano de monitoramento de riscos:**

- **Revisão semanal**: Avaliação de status de riscos durante fase de coleta
- **Indicadores**: Taxa de resposta, distribuição entre grupos, qualidade dos dados
- **Ações preventivas**: Implementação de contingências antes que riscos se materializem
- **Comunicação**: Informar orientador sobre riscos materializados e ações tomadas

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

**Matriz de responsabilidades (RACI):**

| Atividade | Pesquisador | Orientador | CEP | Participantes | Banca |
|-----------|-------------|------------|-----|---------------|-------|
| Desenvolvimento do plano | R/A | C | I | - | - |
| Desenvolvimento do questionário | R/A | C | I | - | - |
| Submissão ao CEP | R/A | C | A | - | - |
| Aprovação ética | I | I | A | - | - |
| Recrutamento | R/A | I | - | - | - |
| Coleta de dados | R/A | I | - | R | - |
| Análise de dados | R/A | C | - | - | - |
| Redação do trabalho | R/A | C | - | - | - |
| Apresentação final | R/A | I | - | - | A |

**Legenda RACI:**
- **R (Responsible)**: Executa a atividade
- **A (Accountable)**: Responsável final, toma decisões
- **C (Consulted)**: Consultado, fornece input
- **I (Informed)**: Informado sobre progresso/resultados
- **-**: Não envolvido

**Fluxo de decisão:**

```
Decisões Operacionais (dia a dia)
    ↓
Pesquisador (decide e executa)
    ↓
Informa Orientador (se necessário)

Decisões Metodológicas Significativas
    ↓
Pesquisador (proposta)
    ↓
Orientador (aprova/rejeita)
    ↓
Pesquisador (executa se aprovado)

Decisões Éticas
    ↓
Pesquisador (prepara documentação)
    ↓
CEP (aprova/rejeita/solicita ajustes)
    ↓
Pesquisador (executa se aprovado)

Decisões sobre Início da Coleta
    ↓
Requer: Aprovação do Orientador + Aprovação do CEP
    ↓
Pesquisador (inicia coleta se ambos aprovados)
```

**Comunicação e reporte:**

- **Pesquisador → Orientador**: 
  - Reuniões regulares (semanal/quinzenal)
  - E-mail para questões urgentes
  - Relatórios de progresso
- **Pesquisador → CEP**: 
  - Submissão formal
  - Resposta a solicitações
  - Comunicação de mudanças significativas
- **Pesquisador → Participantes**: 
  - Através do questionário (TCLE)
  - Mensagens de recrutamento
  - Comunicação sobre resultados (se prometido)

**Escalação de problemas:**

1. **Nível 1 - Operacional**: Pesquisador resolve sozinho (ex: ajustes menores no questionário)
2. **Nível 2 - Metodológico**: Consulta orientador (ex: mudanças no desenho experimental)
3. **Nível 3 - Ético**: Comunicação com CEP (ex: mudanças que afetam aspectos éticos)
4. **Nível 4 - Crítico**: Decisão conjunta pesquisador + orientador + CEP (ex: cancelamento do experimento)

#### 17.2 Ritos de acompanhamento pré-execução

**Reuniões e checkpoints:**

- **Reuniões de orientação**: Semanal ou quinzenal com orientador para acompanhamento do progresso
- **Checkpoint 1 - Finalização do plano**: Revisão e aprovação do plano experimental completo
- **Checkpoint 2 - Questionário**: Revisão e aprovação do questionário antes da submissão ao CEP
- **Checkpoint 3 - Aprovação ética**: Validação da aprovação do CEP e preparação para piloto
- **Checkpoint 4 - Pós-piloto**: Revisão dos resultados do piloto e ajustes necessários
- **Checkpoint 5 - Pronto para coleta**: Validação final antes do início da coleta principal

**Participantes**: Pesquisador e orientador (reuniões bilaterais)

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
- **TCLE**: Integrado ao questionário
- **Planilha de dados**: Template Excel/CSV com colunas para todas as variáveis
- **Log de coleta**: Documento de texto ou planilha para registro de atividades
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
- **CEP**: Protocolo completo, justificativa científica, aspectos éticos
- **Participantes potenciais**: Objetivo do estudo, tempo estimado, benefícios, anonimato garantido
- **Comunidades técnicas**: Convite para participação, link do questionário, propósito da pesquisa
- **Coordenação do curso** (se necessário): Informação sobre o estudo e cronograma

**Mensagens-chave**: Pesquisa acadêmica voluntária, anonimato garantido, contribuição para área, tempo estimado 15-20 minutos

#### 19.2 Canais e frequência de comunicação

**Canais:**
- **Orientador**: E-mail + reuniões presenciais/videoconferência (semanal/quinzenal)
- **CEP**: Sistema formal de submissão + e-mail quando necessário
- **Participantes**: Questionário online (TCLE) + mensagens de recrutamento (redes sociais, fóruns)
- **Comunidades**: Posts em redes sociais, fóruns, grupos (LinkedIn, Reddit, WhatsApp, Telegram)

**Frequência**: Reuniões regulares com orientador; comunicação com participantes conforme necessidade de recrutamento

#### 19.3 Pontos de comunicação obrigatórios

**Eventos que exigem comunicação formal:**
- **Aprovação do plano**: Comunicação ao orientador e CEP
- **Aprovação ética**: Comunicação ao orientador e início de preparação para coleta
- **Mudanças significativas no protocolo**: Comunicação ao orientador e CEP (se necessário)
- **Início da coleta**: Comunicação ao orientador
- **Problemas críticos durante coleta**: Comunicação imediata ao orientador e CEP (se necessário)
- **Encerramento da coleta**: Comunicação ao orientador com resumo dos dados coletados
- **Cancelamento ou adiamento**: Comunicação formal ao orientador, CEP e participantes (se aplicável)

---

### 20. Critérios de prontidão para execução (Definition of Ready)

#### 20.1 Checklist de prontidão (itens que devem estar completos)

**Checklist obrigatório antes do início da coleta:**

- [ ] Plano experimental completo e aprovado pelo orientador
- [ ] Questionário desenvolvido, revisado e validado
- [ ] Aprovação ética do CEP obtida
- [ ] TCLE integrado ao questionário e aprovado
- [ ] Teste piloto realizado e ajustes implementados
- [ ] Questionário configurado na plataforma de survey e testado
- [ ] Materiais de recrutamento preparados
- [ ] Planilha de dados estruturada (template)
- [ ] Log de coleta criado
- [ ] Canais de recrutamento identificados
- [ ] Software de análise instalado e testado (se aplicável)
- [ ] Backup de dados configurado
- [ ] Aprovação final do orientador para início da coleta

**Critério**: Todos os itens devem estar completos antes de iniciar a coleta principal

#### 20.2 Aprovações finais para iniciar a operação

**Aprovações necessárias:**

1. **Comitê de Ética em Pesquisa (CEP)**: Aprovação formal do protocolo (documento oficial do CEP)
2. **Orientador do TCC**: Aprovação verbal ou por e-mail após revisão do checklist de prontidão

**Registro das aprovações:**
- Aprovação do CEP: Documento oficial arquivado
- Aprovação do orientador: Registro em e-mail ou ata de reunião
- Checklist de prontidão: Preenchido e arquivado com data

**Critério de início**: Ambas as aprovações obtidas + todos os itens do checklist completos