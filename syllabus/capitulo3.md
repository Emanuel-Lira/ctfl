# Teste Estatico

## Noções basicas de teste estatico

#### Revisões - Manual (DECORAR)
- Exame manual dos produtos de trabalho  

#### Análise Estatica - Ferramentas (DECORAR)
- Avaliação por meio de ferramentas (Sonar, verificação de ortografia)

- **Avaliação é feita sem executar codigo**

### Objetivos

- Melhoria da qualidade
- Detecção de defeitos
- Avaliação de caracteristicas - integridade, testabilidade
- Tanto para **verificação quanto para validação**
- Garantir que as historias de usuarios sejam completas e compreensiveis e incluam criterios de aceite testaveis
- Pode **identificar problemas antes dos testes dinamicos**
- **Análise estatica** frequentemente **incorporada as estruturas de CI**


## Produtos de trabalho que sao examinaveis por testes estaticos

- **Qualquer produto de trabalho pode ser examinado por testes estaticos**
- **Qualquer produto de trabalho que seja possivel ler e entender**

  - Especificações
  - Historias de usuario
  - Arquitetura
  - Codigo
  - Paginas web
  - Documentação do projeto
  - Contratos
  - Planos de projeto
  - Planos de teste
  - Casos de teste
  - Cartas de teste

## Valor do Teste estatico

- Detectar defeitos nas primeiras fases do SDLC
- Pode **identificar defeitos que não podem ser detectados por testes dinamicos**
- Avaliar a **qualidade e criar confiança** nos produtos de trabalho
- Stakeholders podem se certificar de que **requisitos descrevem suas necessidades reais**
- **Comunicação entre os stakeholders sera aprimorada.**
- **Os custos gerais do projeto geralmente são muito menores** do que quando não sao realizadas revisões.
- **Os defeitos de codigo podem ser detectados usando a analise estatica de forma mais eficiente** do que em testes dinamicos


## Diferença entre Teste Estatico e Dinamico
- Se complementam, encontrando **diferentes tipos de defeitos**

#### Teste Estatico
- **Encontra DEFEITOS direto nos produtos de trabalho**
- Usado para melhorar a qualidade interna dos produtos de trabalho
- **Defeitos encontrados são mais baratos de corrigir**
 
- **Defeitos mais comuns:**
  - Requisitos (inconsistencias, ambiguidades..)
  - Desenho (algoritmos ineficientes)
  - Codificação (variaveis inutilizadas, codigo duplicado)
  - Desvios dos padrões
  - Vulnerabilidades de segurança

#### Teste Dinamico
- Se concentra em **comportamentos extremamente visiveis**

## Processo de feedback e revisão

#### Beneficios do feedback antecipado
- Permite a **comunicação precoce de possiveis problemas** de qualidade
- **Evitar mal-entendidos sobre os requisitos** garantindo que as alterações sejam compreendidas e implementados mais cedo
- **Melhora a compreensão** do que esta sendo desenvolvido
- **Permite que a equipe se concentre nos recursos que agregam mais valor**
- 
#### Atividades do processo de revisão

- **Planejamento**
  - Escopo
  - Objetivo
  - Produto de trabalho a ser revisado
  - Caracteristicas de qualidade a serem avaliadas
  - Criterios de saida
  - Padrões / esforço

-  **Inicio da revisão**
  - Todos preparados para a revisão
  - Todos tenham acesso ao produto de trabalho
  - Todos entendam suas funções e responsabilidades
  - 

- **Revisão individual**
  - Cada revisor realiza uma revisão
  - Observar possiveis defeitos

- **Comunicação e analise de problemas**
  - Comunicar anomalias encontradas
  - Analisar anomalias encontradas
  - Tomar decisão sobre status e ações

- **Correção e relatorio**
  - Criado um relatorio de defeitos
  - Quando os criterios de saida forem atingidos, o produto de trabalho podera ser aceito
  - Os resultados da revisão sao relatados

#### Funções e Responsabilidades em uma revisão formal
- **Gerente**
  - Decide o que deve ser revisado e fornece recursos

- **Autor**
  - Cria e corrige o produto de trabalho em analise
  
- **Moderador**
  - Garante o andamento da reunião

- **Relator**
  - Reune as anomalias dos revisores e registra as informações da revisão

- **Revisor**
  - Realiza as revisões

- **Lider da revisão**
  - Assume a responsabilidade geral pela revisão
  - Decidir quem estara envolvido e organizar quando e onde a revisão sera realizada

#### Tipos de revisão (DECORAR)
- **Informal**
  - Sem processo formal
  - Detectar anomalias e resolver pequenos problemas
  - Mais usado no agil

- **Acompanhamento - walkthrough**
  - Conduzida pelo proprio autor
  - Pode servir a muitos objetivos, como avaliar a qualidade, criar confiança no produto..
  - Os revisores podem realizar uma revisão individual antes, mas não é obrigatorio

- **Revisão tecnica**
  - Realizado por revisores tecnicamente qualificados e liderada por um moderador
  - Objetivo é obtenção de consenso sobre problemas tecnicos e detecção de anomalias
  

- **Inspeção**
  - Encontrar o numero maximo de anomalias
  - Avaliar a qualidade, criar confiança..
  - Metricas são usadas para aprimorar o SDLC
  - Autor não pode atuar como lider ou relator


#### Fatores de sucesso para revisões

- Definir objetivos claros e criterios de saída mensuraveis
- Escolher o tipo de revisão apropriado para atingir os objetivos 
- Revisões em pequenas partes, onde revisores não percam a concentração
- Fornecer feedback das revisões aos stackeholders
- Fornecer tempo suficiente para que os participantes se prepares para a revisão
- Apoio da gerencia para o processo de revisão
- Tornar as revisões parte da cultura da organização
- Fornecer treinamento adequado a todos os participantes sobre suas funções
- Ter facilitação de reuniões
