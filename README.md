## Plano de Experimento – Scoping e Planejamento

### 1. Identificação básica

#### 1.1 Título do experimento
Design de API no Contexto de Arquitetura Distribuídas: Um Estudo Comparativo entre API-First e Code-First

#### 1.2 ID / código
gabrielreisresende-medicao-experimentacao-tcc

#### 1.3 Versão do documento e histórico de revisão
- v1.0 (23/11/2025): Inclusão da identificação básica, contexto e problema do projeto de pesquisa.
- v1.1 (23/11/2025): Escopo, Objetivo, Stakeholders/Impacto, Riscos de alto nível, premissas e critérios de sucesso

#### 1.4 Datas (criação, última atualização)
- Data de criação: 23/11/2025
- Última atualização: 23/11/2025

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
O experimento será conduzido no contexto acadêmico de um TCC, mas com foco em profissionais da indústria que atuam ou já atuaram em projetos com arquiteturas distribuídas. O estudo abrangerá diferentes tipos de organizações (startups, empresas de médio e grande porte), domínios diversos (e-commerce, fintech, SaaS, etc.) e diferentes tecnologias (REST, GraphQL, gRPC, etc.). O processo de desenvolvimento pode variar entre os participantes (ágil, DevOps, tradicional), mas todos devem ter experiência prática com design e implementação de APIs em sistemas distribuídos.

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
Analisar as abordagens API-First e Code-First para design de APIs com o propósito de identificar e comparar suas vantagens, desvantagens e impacto em diferentes dimensões (produtividade, qualidade, manutenibilidade, colaboração) do ponto de vista de profissionais que trabalham em arquiteturas distribuídas no contexto de projetos de software reais em diferentes organizações e domínios.

#### 3.2 Objetivos específicos

**O1**: Identificar e comparar as vantagens percebidas da abordagem API-First em relação à Code-First, considerando aspectos de produtividade, qualidade de código, tempo de desenvolvimento e satisfação dos desenvolvedores.

**O2**: Identificar e comparar as desvantagens percebidas da abordagem API-First em relação à Code-First, considerando aspectos de complexidade, curva de aprendizado, custos de manutenção e dificuldades de implementação.

**O3**: Avaliar o impacto de cada abordagem na colaboração entre equipes, comunicação entre stakeholders, e na qualidade da documentação e especificação das APIs.

**O4**: Analisar fatores contextuais (tipo de organização, tamanho da equipe, domínio do projeto, tecnologias utilizadas) que influenciam a escolha e o sucesso de cada abordagem.

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

**Q4.2**: Quais fatores técnicos (tecnologias utilizadas, domínio do projeto) influenciam o sucesso de cada abordagem?

**Q4.3**: Existe correlação entre a experiência dos profissionais e a preferência por uma das abordagens?

#### 3.4 Métricas associadas (GQM)

A tabela abaixo apresenta o mapeamento entre Objetivos, Questões e Métricas (GQM):

| Objetivo | Questão | Métricas |
|----------|---------|----------|
| O1 | Q1.1 | M1, M2, M3 |
| O1 | Q1.2 | M4, M5, M6 |
| O1 | Q1.3 | M7, M8 |
| O2 | Q2.1 | M9, M10, M11 |
| O2 | Q2.2 | M12, M13 |
| O2 | Q2.3 | M14, M15 |
| O3 | Q3.1 | M16, M17 |
| O3 | Q3.2 | M18, M19 |
| O3 | Q3.3 | M20, M21 |
| O4 | Q4.1 | M22, M23 |
| O4 | Q4.2 | M24, M25 |
| O4 | Q4.3 | M26, M27 |

**Tabela de Métricas:**

| ID | Nome da Métrica | Descrição | Unidade |
|----|-----------------|-----------|---------|
| M1 | Número de Vantagens Identificadas | Quantidade total de vantagens distintas mencionadas pelos participantes para cada abordagem | Quantidade (número inteiro) |
| M2 | Frequência de Menção de Vantagens | Quantas vezes cada vantagem específica foi mencionada pelos participantes | Quantidade (número inteiro) |
| M3 | Score Médio de Importância das Vantagens | Média das avaliações de importância (escala Likert) atribuídas às vantagens identificadas | Escala (1-5 ou 1-10) |
| M4 | Tempo Médio de Desenvolvimento de API | Tempo médio gasto para desenvolver uma API completa (do design à implementação) | Tempo (horas ou dias) |
| M5 | Produtividade Percebida | Autoavaliação dos desenvolvedores sobre sua produtividade usando cada abordagem | Escala (1-5 ou 1-10) |
| M6 | Taxa de Conclusão de Tarefas | Proporção de tarefas relacionadas a APIs concluídas dentro do prazo estimado | Percentual (%) |
| M7 | Densidade de Defeitos | Número de defeitos encontrados por unidade de código ou por API desenvolvida | Quantidade por API ou por KLOC |
| M8 | Qualidade Percebida do Código | Autoavaliação dos desenvolvedores sobre a qualidade do código gerado | Escala (1-5 ou 1-10) |
| M9 | Número de Desvantagens Identificadas | Quantidade total de desvantagens distintas mencionadas pelos participantes para cada abordagem | Quantidade (número inteiro) |
| M10 | Frequência de Menção de Desvantagens | Quantas vezes cada desvantagem específica foi mencionada pelos participantes | Quantidade (número inteiro) |
| M11 | Score Médio de Severidade das Desvantagens | Média das avaliações de severidade (escala Likert) atribuídas às desvantagens identificadas | Escala (1-5 ou 1-10) |
| M12 | Complexidade Percebida do Processo | Autoavaliação dos desenvolvedores sobre a complexidade do processo de desenvolvimento | Escala (1-5 ou 1-10) |
| M13 | Número de Ferramentas Necessárias | Quantidade média de ferramentas e tecnologias que precisam ser aprendidas/dominadas | Quantidade (número inteiro) |
| M14 | Tempo Médio de Manutenção | Tempo médio gasto em atividades de manutenção e evolução de APIs existentes | Tempo (horas ou dias por mês) |
| M15 | Tempo de Curva de Aprendizado | Tempo necessário para um desenvolvedor se tornar produtivo com a abordagem | Tempo (semanas ou meses) |
| M16 | Nível de Colaboração Percebida | Autoavaliação sobre a facilidade e qualidade da colaboração entre equipes | Escala (1-5 ou 1-10) |
| M17 | Frequência de Comunicação entre Equipes | Número médio de interações necessárias entre equipes frontend e backend durante o desenvolvimento | Quantidade (número de interações) |
| M18 | Completude da Documentação | Percentual de APIs que possuem documentação completa e atualizada | Percentual (%) |
| M19 | Qualidade Percebida da Documentação | Autoavaliação sobre a qualidade, clareza e utilidade da documentação gerada | Escala (1-5 ou 1-10) |
| M20 | Tempo Médio de Integração | Tempo médio necessário para integrar um novo serviço ou consumir uma API existente | Tempo (horas ou dias) |
| M21 | Taxa de Sucesso de Integrações | Proporção de tentativas de integração que são bem-sucedidas na primeira tentativa | Percentual (%) |
| M22 | Distribuição por Tipo de Organização | Proporção de participantes de cada tipo de organização (startup, média, grande) que usa cada abordagem | Percentual (%) |
| M23 | Distribuição por Tamanho de Equipe | Tamanho médio da equipe de desenvolvimento nos projetos que usam cada abordagem | Quantidade (número de pessoas) |
| M24 | Distribuição por Tecnologia | Proporção de uso de cada abordagem por tipo de tecnologia (REST, GraphQL, gRPC, etc.) | Percentual (%) |
| M25 | Distribuição por Domínio | Proporção de uso de cada abordagem por domínio do projeto (e-commerce, fintech, SaaS, etc.) | Percentual (%) |
| M26 | Anos de Experiência Média | Anos médios de experiência profissional dos participantes que preferem cada abordagem | Tempo (anos) |
| M27 | Preferência por Abordagem | Proporção de participantes que preferem cada abordagem, estratificada por nível de experiência | Percentual (%) |

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
Explique, em texto ou esquema, como você acredita que os fatores influenciam as respostas (por exemplo, “técnica A reduz defeitos em relação a B”).

#### 7.2 Hipóteses formais (H0, H1)
Formule explicitamente as hipóteses nulas e alternativas para cada questão principal, incluindo a direção esperada do efeito quando fizer sentido.

#### 7.3 Nível de significância e considerações de poder
Defina o nível de significância (por exemplo, α = 0,05) e comente o que se espera em termos de poder estatístico, relacionando-o ao tamanho de amostra planejado.

---

### 8. Variáveis, fatores, tratamentos e objetos de estudo

#### 8.1 Objetos de estudo
Descreva o que será efetivamente manipulado ou analisado (módulos de código, requisitos, tarefas, casos de teste, issues, etc.).

#### 8.2 Sujeitos / participantes (visão geral)
Caracterize em alto nível quem serão os participantes (desenvolvedores, testadores, estudantes, etc.), sem ainda entrar em detalhes de seleção.

#### 8.3 Variáveis independentes (fatores) e seus níveis
Liste os fatores que serão manipulados (por exemplo, técnica, ferramenta, processo) e indique os níveis de cada um (A/B, X/Y, alto/baixo).

#### 8.4 Tratamentos (condições experimentais)
Descreva claramente cada condição de experimento (grupo controle, tratamento 1, tratamento 2, etc.) e o que distingue uma da outra.

#### 8.5 Variáveis dependentes (respostas)
Informe as medidas de resultado que você observará (por exemplo, número de defeitos, esforço em horas, tempo de conclusão, satisfação).

#### 8.6 Variáveis de controle / bloqueio
Liste fatores que você não está estudando diretamente, mas que serão mantidos constantes ou usados para formar blocos (por exemplo, experiência, tipo de tarefa).

#### 8.7 Possíveis variáveis de confusão conhecidas
Identifique fatores que podem distorcer os resultados (como diferenças de contexto, motivação ou carga de trabalho) e que você pretende monitorar.

---

### 9. Desenho experimental

#### 9.1 Tipo de desenho (completamente randomizado, blocos, fatorial, etc.)
Indique qual tipo de desenho será utilizado e justifique brevemente por que ele é adequado ao problema e às restrições.

#### 9.2 Randomização e alocação
Explique o que será randomizado (sujeitos, tarefas, ordem de tratamentos) e como a randomização será feita na prática (ferramentas, procedimentos).

#### 9.3 Balanceamento e contrabalanço
Descreva como você garantirá que os grupos fiquem comparáveis (balanceamento) e como lidará com efeitos de ordem ou aprendizagem (contrabalanço).

#### 9.4 Número de grupos e sessões
Informe quantos grupos existirão e quantas sessões ou rodadas cada sujeito ou grupo irá executar, com uma breve justificativa.

---

### 10. População, sujeitos e amostragem

#### 10.1 População-alvo
Descreva qual é a população real que você deseja representar com o experimento (por exemplo, “desenvolvedores Java de times de produto web”).

#### 10.2 Critérios de inclusão de sujeitos
Especifique os requisitos mínimos para um participante ser elegível (experiência, conhecimento, papel, disponibilidade, etc.).

#### 10.3 Critérios de exclusão de sujeitos
Liste condições que impedem participação (conflitos de interesse, falta de skills essenciais, restrições legais ou éticas).

#### 10.4 Tamanho da amostra planejado (por grupo)
Defina quantos participantes você pretende ter no total e em cada grupo, relacionando a decisão com poder, recursos e contexto.

#### 10.5 Método de seleção / recrutamento
Explique como os participantes serão escolhidos (amostra de conveniência, sorteio, convite aberto, turma de disciplina, time específico).

#### 10.6 Treinamento e preparação dos sujeitos
Descreva qual treinamento ou material preparatório será fornecido para nivelar entendimento e reduzir vieses por falta de conhecimento.

---

### 11. Instrumentação e protocolo operacional

#### 11.1 Instrumentos de coleta (questionários, logs, planilhas, etc.)
Liste todos os instrumentos que serão usados para coletar dados (arquivos, formulários, scripts, ferramentas), com uma breve descrição do papel de cada um.

#### 11.2 Materiais de suporte (instruções, guias)
Descreva as instruções escritas, guias rápidos, slides ou outros materiais que serão fornecidos a participantes e administradores do experimento.

#### 11.3 Procedimento experimental (protocolo – visão passo a passo)
Escreva, em ordem, o que acontecerá na operação (do convite ao encerramento), de modo que alguém consiga executar o experimento seguindo esse roteiro.

#### 11.4 Plano de piloto (se haverá piloto, escopo e critérios de ajuste)
Indique se um piloto será realizado, com que participantes e objetivos, e defina que tipo de ajuste do protocolo poderá ser feito com base nesse piloto.

---

### 12. Plano de análise de dados (pré-execução)

#### 12.1 Estratégia geral de análise (como responderá às questões)
Explique, em alto nível, como os dados coletados serão usados para responder cada questão de pesquisa ou de negócio.

#### 12.2 Métodos estatísticos planejados
Liste os principais testes ou técnicas estatísticas que pretende usar (por exemplo, t-teste, ANOVA, testes não paramétricos, regressão).

#### 12.3 Tratamento de dados faltantes e outliers
Defina previamente as regras para lidar com dados ausentes e valores extremos, evitando decisões oportunistas após ver os resultados.

#### 12.4 Plano de análise para dados qualitativos (se houver)
Descreva como você tratará dados qualitativos (entrevistas, comentários, observações), especificando a técnica de análise (codificação, categorias, etc.).

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