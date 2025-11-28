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

A estratégia de análise seguirá uma abordagem mista (quantitativa e qualitativa), organizada por objetivos e questões de pesquisa. A análise será conduzida em etapas, começando com análises descritivas, seguidas de análises inferenciais e análises qualitativas.

**Estratégia por Objetivo:**

**O1: Identificar e comparar vantagens percebidas (Q1.1, Q1.2, Q1.3)**

- **Q1.1 (Vantagens percebidas)**:
  - **Análise qualitativa**: Codificação temática das respostas abertas sobre vantagens mencionadas por cada grupo
  - **Análise quantitativa**: Contagem de frequência de menção de cada vantagem (M2), número total de vantagens distintas (M1)
  - **Comparação**: Comparar distribuição de vantagens entre grupos (API-First vs. Code-First)
  - **Análise quantitativa**: Score médio de importância das vantagens (M3) por grupo, usando teste t ou Mann-Whitney

- **Q1.2 (Impacto na produtividade)**:
  - **Análise quantitativa**: Comparar produtividade percebida (M4) entre grupos usando teste t de duas amostras ou teste de Mann-Whitney
  - **Análise descritiva**: Calcular médias, medianas, desvios padrão por grupo
  - **Análise qualitativa**: Analisar comentários sobre produtividade nas respostas abertas

- **Q1.3 (Impacto na qualidade do código)**:
  - **Análise quantitativa**: Comparar qualidade percebida do código (M5) entre grupos usando teste t ou Mann-Whitney
  - **Análise descritiva**: Estatísticas descritivas por grupo
  - **Análise qualitativa**: Identificar padrões qualitativos sobre qualidade mencionados nas respostas abertas

**O2: Identificar e comparar desvantagens percebidas (Q2.1, Q2.2, Q2.3)**

- **Q2.1 (Desvantagens percebidas)**:
  - **Análise qualitativa**: Codificação temática das desvantagens mencionadas por cada grupo
  - **Análise quantitativa**: Frequência de menção (M7), número total de desvantagens (M6)
  - **Comparação**: Comparar distribuição de desvantagens entre grupos
  - **Análise quantitativa**: Score médio de severidade (M8) por grupo

- **Q2.2 (Impacto na complexidade)**:
  - **Análise quantitativa**: Comparar complexidade percebida (M9) e número de ferramentas (M10) entre grupos
  - **Testes estatísticos**: Teste t ou Mann-Whitney para M9, comparação de médias para M10

- **Q2.3 (Custos de manutenção e curva de aprendizado)**:
  - **Análise quantitativa**: Comparar tempo médio de manutenção (M11) e tempo de curva de aprendizado (M12) entre grupos
  - **Testes estatísticos**: Teste t ou Mann-Whitney
  - **Análise descritiva**: Estatísticas descritivas, identificação de outliers

**O3: Avaliar impacto na colaboração e documentação (Q3.1, Q3.2, Q3.3)**

- **Q3.1 (Colaboração entre equipes)**:
  - **Análise quantitativa**: Comparar nível de colaboração percebida (M13) e frequência de comunicação (M14) entre grupos
  - **Testes estatísticos**: Teste t ou Mann-Whitney para M13, comparação de médias para M14
  - **Análise qualitativa**: Identificar padrões sobre colaboração nas respostas abertas

- **Q3.2 (Qualidade da documentação)**:
  - **Análise quantitativa**: Comparar completude (M15) e qualidade percebida (M16) da documentação entre grupos
  - **Testes estatísticos**: Teste t ou Mann-Whitney
  - **Análise qualitativa**: Analisar comentários sobre documentação

- **Q3.3 (Facilidade de integração)**:
  - **Análise quantitativa**: Comparar tempo médio de integração (M17) e taxa de sucesso (M18) entre grupos
  - **Testes estatísticos**: Teste t ou Mann-Whitney para M17, teste de proporções para M18

**O4: Analisar fatores contextuais (Q4.1, Q4.2)**

- **Q4.1 (Fatores organizacionais)**:
  - **Análise quantitativa**: Análise de associação entre tipo de organização (M19) e tamanho de equipe (M20) com preferência de abordagem
  - **Testes estatísticos**: Teste qui-quadrado de independência, análise de tabelas de contingência
  - **Análise descritiva**: Distribuições percentuais por tipo de organização e tamanho de equipe

- **Q4.2 (Experiência dos profissionais)**:
  - **Análise quantitativa**: Comparar anos de experiência média (M21) e preferência por abordagem (M22) estratificada por nível de experiência
  - **Testes estatísticos**: Análise de variância (ANOVA) ou Kruskal-Wallis para comparar M21 entre grupos de experiência, teste qui-quadrado para M22
  - **Análise descritiva**: Distribuições de preferência por nível de experiência

**Análises Adicionais:**

- **Análises estratificadas**: Repetir análises principais estratificando por variáveis de controle (tipo de organização, tamanho de equipe, experiência)
- **Análises exploratórias**: Identificar padrões não previstos, correlações entre variáveis
- **Síntese qualitativa**: Integrar insights qualitativos com resultados quantitativos

#### 12.2 Métodos estatísticos planejados

**Análises Descritivas:**

1. **Estatísticas descritivas para variáveis quantitativas**:
   - Média, mediana, desvio padrão, mínimo, máximo
   - Quartis e intervalo interquartil (IQR)
   - Gráficos: histogramas, boxplots, gráficos de barras

2. **Estatísticas descritivas para variáveis categóricas**:
   - Frequências absolutas e relativas (percentuais)
   - Gráficos: gráficos de barras, gráficos de pizza

3. **Análise de distribuições**:
   - Testes de normalidade: Shapiro-Wilk ou Kolmogorov-Smirnov
   - Inspeção visual através de Q-Q plots
   - Determinação de uso de testes paramétricos vs. não paramétricos

**Testes de Hipóteses para Comparações entre Grupos:**

1. **Comparação de médias (variáveis contínuas)**:
   - **Teste t de Student para duas amostras independentes**:
     - Quando: dados normalmente distribuídos, variâncias homogêneas
     - Variáveis: M4, M5, M9, M11, M12, M13, M16, M17, M21
   - **Teste de Mann-Whitney U (não paramétrico)**:
     - Quando: dados não normalmente distribuídos ou amostras pequenas
     - Alternativa não paramétrica ao teste t
   - **Teste de Levene**: Verificação de homogeneidade de variâncias antes do teste t

2. **Comparação de proporções (variáveis categóricas)**:
   - **Teste qui-quadrado de independência**:
     - Quando: testar associação entre variáveis categóricas
     - Variáveis: M19 (tipo de organização vs. abordagem), M22 (preferência vs. experiência)
   - **Teste exato de Fisher**:
     - Quando: amostras pequenas (esperado < 5 em células da tabela)

3. **Comparação de múltiplos grupos**:
   - **ANOVA de um fator**:
     - Quando: comparar médias entre 3+ grupos (ex: por tipo de organização)
     - Variáveis: M4, M5, M9, etc. estratificadas por variáveis categóricas
   - **Teste de Kruskal-Wallis**:
     - Quando: alternativa não paramétrica à ANOVA
   - **Teste post-hoc** (se ANOVA significativa):
     - Teste de Tukey HSD ou Bonferroni para comparações múltiplas

4. **Análise de frequências**:
   - **Análise de frequência de menção**: Contagem e comparação de frequências de vantagens/desvantagens mencionadas
   - **Teste qui-quadrado de aderência**: Comparar distribuições observadas vs. esperadas

**Análises de Associação e Correlação:**

1. **Correlação**:
   - **Correlação de Pearson**: Para variáveis contínuas normalmente distribuídas
   - **Correlação de Spearman**: Para variáveis ordinais ou não normalmente distribuídas
   - Identificar correlações entre variáveis dependentes

2. **Análise de tabelas de contingência**:
   - Tabelas cruzadas para variáveis categóricas
   - Cálculo de medidas de associação (V de Cramér, coeficiente de contingência)

**Análises Ajustadas (se necessário):**

1. **Análise de covariância (ANCOVA)**:
   - Se necessário ajustar comparações entre grupos para variáveis de confusão contínuas
   - Exemplo: ajustar comparação de M4 (produtividade) por anos de experiência

2. **Modelos de regressão** (análise exploratória):
   - Regressão linear múltipla: Explorar relações entre múltiplas variáveis independentes e dependentes
   - Regressão logística: Se necessário modelar preferência binária (API-First vs. Code-First)

**Considerações Estatísticas:**

- **Nível de significância**: α = 0,05 para todos os testes
- **Ajuste para comparações múltiplas**: 
  - Correção de Bonferroni ou FDR (False Discovery Rate) se múltiplos testes forem realizados
  - Considerar ajuste especialmente para análises estratificadas
- **Poder estatístico**: Documentar poder observado para testes não significativos
- **Tamanho de efeito**: 
  - Calcular tamanhos de efeito (Cohen's d para testes t, eta² para ANOVA, V de Cramér para qui-quadrado)
  - Interpretar significância prática além de significância estatística

**Ferramentas Estatísticas:**

- **Software**: Python (pandas, scipy, statsmodels) ou R
- **Visualizações**: matplotlib/seaborn (Python) ou ggplot2 (R)
- **Relatórios**: Jupyter Notebooks ou R Markdown para documentação reprodutível

#### 12.3 Tratamento de dados faltantes e outliers

**Tratamento de Dados Faltantes (Missing Data):**

**Identificação de dados faltantes:**
- Verificar sistematicamente todas as variáveis para valores ausentes
- Classificar tipos de dados faltantes:
  - **MCAR (Missing Completely At Random)**: Ausência aleatória, não relacionada a variáveis observadas ou não observadas
  - **MAR (Missing At Random)**: Ausência relacionada a variáveis observadas, mas não à variável ausente em si
  - **MNAR (Missing Not At Random)**: Ausência relacionada ao valor da variável ausente

**Regras para tratamento:**

1. **Dados faltantes em questões obrigatórias**:
   - Se questão era obrigatória mas está faltando → Investigar problema técnico
   - Se > 5% de respostas obrigatórias estão faltando → Investigar problema sistemático
   - **Ação**: Excluir participante se questões críticas de triagem estiverem faltando

2. **Dados faltantes em questões opcionais**:
   - **Variáveis quantitativas**: 
     - Se < 10% faltantes: Usar exclusão por caso (listwise deletion) para análises específicas
     - Se 10-30% faltantes: Considerar imputação (média, mediana, ou modelo) ou análise de sensibilidade
     - Se > 30% faltantes: Excluir variável da análise ou tratar como variável separada
   - **Variáveis qualitativas (texto aberto)**:
     - Tratar como "não fornecido" ou categoria separada
     - Não imputar respostas qualitativas

3. **Métodos de imputação (se aplicável)**:
   - **Imputação simples**: Média ou mediana para variáveis contínuas, moda para categóricas
   - **Imputação por grupo**: Imputar usando estatísticas do grupo (API-First vs. Code-First)
   - **Análise de sensibilidade**: Comparar resultados com e sem imputação

4. **Documentação**:
   - Registrar percentual de dados faltantes por variável
   - Documentar método de tratamento escolhido
   - Reportar impacto dos dados faltantes nas análises

**Tratamento de Outliers:**

**Identificação de outliers:**

1. **Métodos estatísticos**:
   - **Método IQR (Interquartile Range)**: Valores fora de Q1 - 1.5×IQR ou Q3 + 1.5×IQR
   - **Método Z-score**: Valores com |z| > 3 (ou |z| > 2.5 para amostras pequenas)
   - **Método de distância de Mahalanobis**: Para múltiplas variáveis (se aplicável)

2. **Métodos visuais**:
   - Boxplots para identificar outliers visuais
   - Scatter plots para identificar padrões anômalos
   - Histogramas para identificar distribuições com caudas longas

**Regras para tratamento de outliers:**

1. **Investigação inicial**:
   - Verificar se outlier é erro de entrada de dados (ex: 1000 horas em vez de 10 horas)
   - Verificar se outlier é valor válido mas extremo (ex: experiência muito alta)
   - Verificar consistência com outras respostas do mesmo participante

2. **Decisão sobre tratamento**:

   **Manter outlier se**:
   - É valor válido e representa experiência real legítima
   - Não é claramente um erro
   - Remoção alteraria significativamente resultados (análise de sensibilidade)

   **Corrigir outlier se**:
   - É claramente um erro de entrada (ex: digitação incorreta)
   - Pode ser corrigido com base em outras respostas do participante
   - **Ação**: Corrigir valor ou marcar como faltante se correção não for possível

   **Excluir outlier se**:
   - É erro não corrigível e afeta análises críticas
   - Representa < 2% dos dados e é claramente inválido
   - **Ação**: Excluir apenas para análises específicas, manter em conjunto completo

3. **Análise de sensibilidade**:
   - Realizar análises principais com e sem outliers
   - Comparar resultados para avaliar impacto
   - Documentar se conclusões mudam

4. **Tratamento específico por tipo de variável**:

   **Variáveis de tempo (M11, M12, M17)**:
   - Valores extremamente altos (ex: > 3 desvios padrão da média) → Investigar se são erros
   - Se válidos, manter mas documentar
   - Considerar transformação logarítmica se distribuição for muito assimétrica

   **Escalas Likert (M3, M4, M5, M8, M9, M13, M16)**:
   - Valores fora da escala (ex: 0 ou 6 em escala 1-5) → Corrigir ou excluir
   - Valores extremos dentro da escala são válidos → Manter

   **Percentuais (M15, M18)**:
   - Valores > 100% ou < 0% → Corrigir ou excluir
   - Valores extremos mas válidos (ex: 0% ou 100%) → Manter

5. **Documentação**:
   - Listar todos os outliers identificados
   - Documentar decisão sobre cada outlier (manter, corrigir, excluir)
   - Reportar impacto nas análises

**Validação de Dados:**

1. **Verificação de consistência**:
   - Verificar respostas inconsistentes (ex: participante diz nunca ter usado API-First mas descreve experiência com API-First)
   - Verificar valores impossíveis (ex: anos de experiência maior que idade)
   - Verificar padrões suspeitos (ex: mesma resposta para todas as questões)

2. **Critérios de exclusão de participantes**:
   - Respostas claramente inconsistentes ou inválidas
   - > 50% de dados faltantes em questões críticas
   - Padrões de resposta indicando falta de engajamento (ex: mesma resposta para todas as escalas)

3. **Documentação de exclusões**:
   - Registrar número de participantes excluídos e razões
   - Reportar no documento final

#### 12.4 Plano de análise para dados qualitativos (se houver)

**Dados Qualitativos Coletados:**

1. **VQ1 - Lista de Vantagens Identificadas**: Respostas abertas sobre vantagens de cada abordagem
2. **VQ2 - Lista de Desvantagens Identificadas**: Respostas abertas sobre desvantagens de cada abordagem
3. **VQ3 - Comentários e Observações**: Comentários adicionais dos participantes

**Estratégia de Análise Qualitativa:**

**Abordagem**: **Análise de conteúdo temática** (Thematic Content Analysis) com elementos de análise de frequência

**Fase 1: Preparação dos Dados**

1. **Organização**:
   - Compilar todas as respostas abertas em documentos de texto
   - Separar por grupo (API-First vs. Code-First) e por tipo de resposta (vantagens, desvantagens, comentários)
   - Remover identificadores pessoais (se houver)
   - Preservar contexto (qual pergunta gerou a resposta)

2. **Limpeza inicial**:
   - Remover respostas vazias ou inválidas (ex: "não sei", "n/a")
   - Padronizar formatação básica (capitalização, pontuação)
   - Manter originalidade das respostas

**Fase 2: Codificação (Coding)**

1. **Codificação aberta (Open Coding)**:
   - Leitura cuidadosa de todas as respostas
   - Identificação de unidades de significado (frases, parágrafos relacionados a um conceito)
   - Criação de códigos iniciais (labels descritivos) para cada unidade de significado
   - Exemplo de códigos iniciais: "desenvolvimento paralelo", "documentação automática", "complexidade inicial"

2. **Codificação axial (Axial Coding)**:
   - Agrupar códigos relacionados em categorias temáticas
   - Identificar relações entre códigos
   - Exemplo: códigos "desenvolvimento paralelo", "contrato claro", "menos retrabalho" → categoria "Vantagens de Colaboração"

3. **Codificação seletiva (Selective Coding)**:
   - Identificar temas centrais que emergem das categorias
   - Integrar categorias em temas principais
   - Exemplo: tema "Facilitação de Colaboração" integra categorias relacionadas a trabalho em equipe

**Fase 3: Análise Temática**

1. **Identificação de temas**:
   - Temas principais: Padrões recorrentes de significado relacionados aos objetivos de pesquisa
   - Temas secundários: Padrões menos frequentes mas relevantes
   - Temas emergentes: Padrões não previstos que surgem dos dados

2. **Estruturação de temas**:
   - Organizar temas hierarquicamente (tema principal → sub-temas → categorias → códigos)
   - Criar definições claras para cada tema
   - Identificar exemplos representativos (quotations) para cada tema

3. **Validação de temas**:
   - Verificar se temas capturam adequadamente os dados
   - Verificar se há sobreposição ou redundância entre temas
   - Refinar temas conforme necessário

**Fase 4: Análise Quantitativa de Dados Qualitativos**

1. **Frequência de menção**:
   - Contar quantas vezes cada tema/categoria é mencionado
   - Calcular frequências absolutas e relativas por grupo
   - Identificar temas mais e menos frequentes

2. **Comparação entre grupos**:
   - Comparar distribuição de temas entre grupo API-First e Code-First
   - Identificar temas exclusivos de cada grupo
   - Identificar temas comuns mas com frequências diferentes

3. **Análise de importância**:
   - Se houver avaliação de importância nas respostas, integrar com análise temática
   - Identificar temas mencionados como mais importantes

**Fase 5: Síntese e Integração**

1. **Integração qualitativa-quantitativa**:
   - Relacionar temas qualitativos com resultados quantitativos
   - Usar insights qualitativos para interpretar resultados quantitativos
   - Identificar convergências e divergências

2. **Identificação de padrões**:
   - Padrões principais: Temas que aparecem consistentemente
   - Padrões contextuais: Temas que variam por tipo de organização, tamanho de equipe, etc.
   - Padrões contraditórios: Temas onde há opiniões divergentes

3. **Geração de insights**:
   - Síntese dos principais achados qualitativos
   - Identificação de recomendações práticas
   - Identificação de áreas para pesquisa futura

**Ferramentas e Validação:**

1. **Ferramentas**:
   - **Codificação manual**: Excel ou planilhas para organização inicial
   - **Software de análise qualitativa** (opcional): NVivo, Atlas.ti, ou MAXQDA se disponível
   - **Alternativa**: Codificação manual com suporte de planilhas e documentos de texto

2. **Validação e Confiabilidade**:
   - **Validação pelo pesquisador**: Revisão de códigos e temas pelo pesquisador principal
   - **Validação pelo orientador**: Revisão de uma amostra de códigos e temas pelo orientador
   - **Triangulação**: Comparar resultados qualitativos com resultados quantitativos
   - **Documentação**: Manter registro detalhado do processo de codificação e decisões

3. **Apresentação dos Resultados**:
   - Tabelas de frequência de temas por grupo
   - Citações representativas (quotations) para ilustrar cada tema
   - Diagramas ou mapas conceituais mostrando relações entre temas
   - Narrativa descritiva integrando temas e padrões

**Critérios de Qualidade:**

- **Credibilidade**: Temas são apoiados por evidências nos dados (citações)
- **Transferibilidade**: Temas são descritos com contexto suficiente para aplicação em outros contextos
- **Dependabilidade**: Processo de análise é documentado e reprodutível
- **Confirmabilidade**: Resultados são baseados nos dados, não em preconceitos do pesquisador

---

### 13. Avaliação de validade (ameaças e mitigação)

#### 13.1 Validade de conclusão
Liste ameaças que podem comprometer a robustez das conclusões estatísticas (baixo poder, violação de suposições, erros de medida) e como pretende mitigá-las.

#### 13.2 Validade interna
Identifique ameaças relacionadas a causas alternativas para os efeitos observados (history, maturation, selection, etc.) e explique suas estratégias de controle.

#### 13.3 Validade de constructo
Refleta se as medidas escolhidas realmente representam os conceitos de interesse e descreva como você reduzirá ambiguidades de interpretação.

#### 13.4 Validade externa
Discuta em que contextos os resultados podem ser generalizados e quais diferenças de cenário podem limitar essa generalização.

#### 13.5 Resumo das principais ameaças e estratégias de mitigação
Faça uma síntese das ameaças mais críticas e das ações planejadas, de preferência em forma de lista ou tabela simples.

---

### 14. Ética, privacidade e conformidade

#### 14.1 Questões éticas (uso de sujeitos, incentivos, etc.)
Descreva potenciais questões éticas (pressão para participar, uso de estudantes, incentivos, riscos de exposição) e como serão tratadas.

#### 14.2 Consentimento informado
Explique como os participantes serão informados sobre objetivos, riscos, benefícios e como registrarão seu consentimento.

#### 14.3 Privacidade e proteção de dados
Indique que dados pessoais serão coletados, como serão protegidos (anonimização, pseudoanonimização, controle de acesso) e por quanto tempo serão mantidos.

#### 14.4 Aprovações necessárias (comitê de ética, jurídico, DPO, etc.)
Liste órgãos ou pessoas que precisam aprovar o experimento (comitê de ética, jurídico, DPO, gestores) e o status atual dessas aprovações.

---

### 15. Recursos, infraestrutura e orçamento

#### 15.1 Recursos humanos e papéis
Identifique os membros da equipe do experimento e descreva brevemente o papel e responsabilidade de cada um.

#### 15.2 Infraestrutura técnica necessária
Liste ambientes, servidores, ferramentas, repositórios e integrações que devem estar disponíveis para executar o experimento.

#### 15.3 Materiais e insumos
Relacione materiais físicos ou digitais necessários (máquinas, licenças, formulários, dispositivos) que precisam estar prontos antes da operação.

#### 15.4 Orçamento e custos estimados
Faça uma estimativa dos principais custos envolvidos (horas de pessoas, serviços, licenças, infraestrutura) e a fonte de financiamento.

---

### 16. Cronograma, marcos e riscos operacionais

#### 16.1 Macrocronograma (até o início da execução)
Defina as principais datas e marcos (conclusão do plano, piloto, revisão, início da operação) com uma visão de tempo realista.

#### 16.2 Dependências entre atividades
Indique quais atividades dependem de outras para começar (por exemplo, treinamento após aprovação ética), deixando essas dependências claras.

#### 16.3 Riscos operacionais e plano de contingência
Liste riscos ligados a cronograma, disponibilidade de pessoas ou recursos, e descreva ações de contingência caso esses riscos se materializem.

---

### 17. Governança do experimento

#### 17.1 Papéis e responsabilidades formais
Defina quem decide, quem executa, quem revisa e quem apenas deve ser informado, deixando claro o fluxo de responsabilidade.

#### 17.2 Ritos de acompanhamento pré-execução
Descreva as reuniões, checkpoints e revisões previstos antes da execução, incluindo frequência e participantes.

#### 17.3 Processo de controle de mudanças no plano
Explique como mudanças no desenho ou no escopo do experimento serão propostas, analisadas, aprovadas e registradas.

---

### 18. Plano de documentação e reprodutibilidade

#### 18.1 Repositórios e convenções de nomeação
Indique onde o plano, instrumentos, scripts e dados (futuros) serão armazenados e quais convenções de nomes serão usadas.

#### 18.2 Templates e artefatos padrão
Liste os modelos (questionários, formulários, checklists, scripts) que serão usados e onde podem ser encontrados.

#### 18.3 Plano de empacotamento para replicação futura
Descreva o que será organizado desde já (documentos, scripts, instruções) para facilitar a replicação do experimento por outras equipes ou no futuro.

---

### 19. Plano de comunicação

#### 19.1 Públicos e mensagens-chave pré-execução
Liste os grupos que precisam ser comunicados e quais mensagens principais devem receber (objetivos, escopo, datas, impactos esperados).

#### 19.2 Canais e frequência de comunicação
Defina por quais canais (e-mail, reuniões, Slack/Teams, etc.) e com que frequência as comunicações serão feitas.

#### 19.3 Pontos de comunicação obrigatórios
Especifique os eventos que exigem comunicação formal (aprovação do plano, mudanças relevantes, adiamentos, cancelamentos).

---

### 20. Critérios de prontidão para execução (Definition of Ready)

#### 20.1 Checklist de prontidão (itens que devem estar completos)
Liste os itens que precisam estar finalizados e aprovados (plano, instrumentos, aprovação ética, recursos, comunicação) para autorizar o início da operação.

#### 20.2 Aprovações finais para iniciar a operação
Indique quem precisa dar o “ok final” (nomes ou cargos) e como esse aceite será registrado antes da execução começar.