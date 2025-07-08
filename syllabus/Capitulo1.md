# 1.1 O que é teste? 

- O teste de software é um conjunto de atividades para descobrir defeitos e avaliar a qualidade dos artefatos de software

- o teste de software também inclui outras atividades e deve estar alinhado com o ciclo de vida de desenvolvimento de software

# Os testes podem ser dinâmicos ou estáticos.

- O teste dinâmico envolve a execução do software
-  enquanto o teste estático não
  - O teste estático inclui revisões

# Objetivos do teste   

- Avaliar produtos de trabalho, como requisitos, histórias de usuários, projetos e código;
- Detectar falhas e defeitos;
- Garantir a cobertura necessária de um objeto de teste;
- Reduzindo o nível de risco de qualidade de software inadequado;
- Verificar se os requisitos especificados foram atendidos;
- Verificar se um objeto de teste está em conformidade com os requisitos contratuais, legais e normativos;
- Fornecer informações aos stakeholders para que eles possam tomar decisões informadas;
- Criar confiança na qualidade do objeto de teste;
- Validar se o objeto de teste está completo e funciona conforme o esperado pelos stakeholders

# Teste e depuração 

- O teste pode desencadear falhas causadas por defeitos no
software (teste dinâmico) ou pode encontrar defeitos diretamente no objeto de teste (teste estático).

- Quando o teste dinâmico (ver capítulo 4) aciona uma falha, a depuração se preocupa em encontrar as causas
dessa falha (defeitos), analisar essas causas e eliminá-las 

## O processo típico de depuração
- Reproduzir uma falha
- Diagnosticar (encontrar a causa principal)
- Corrigir a causa

- O teste de confirmação subsequente verifica se as correções resolveram o problema.

- Os testes de regressão subsequentes também podem ser realizados para verificar se as correções estão causando falhas em outras partes do objeto de teste

# Por que os testes são necessários?

- ajudam a atingir os objetivos acordados dentro do escopo, do tempo, da qualidade e das restrições orçamentárias estabelecidas.
- Qualquer stakeholder pode usar suas habilidades de
teste para trazer o projeto mais próximo do sucesso

## Contribuições para o sucesso dos testes
- Os testes também podem ser necessários para atender a requisitos contratuais ou legais, ou para cumprir normas regulatórias.

## Testes e Garantia da Qualidade (QA)
- teste e QA não são a mesma coisa
- O teste é uma forma de controle de qualidade (QC).
- A QA é uma abordagem preventiva e orientada para o processo que se concentra na implementação e no aprimoramento dos processos
- A QA se aplica aos processos de desenvolvimento e teste e é
responsabilidade de todos em um projeto.

- Os resultados dos testes são usados por QA e QC. No QC, eles são usados para corrigir defeitos, enquanto no QA eles fornecem feedback sobre a performance dos processos de desenvolvimento e teste

## Erros, Defeitos, Falhas e Causas-raiz 

#### erros
- Os seres humanos cometem erros

#### defeitos
- Os defeitos podem ser encontrados na documentação, como uma especificação de requisitos ou um script de teste, no código-fonte ou em um artefato de suporte, como um arquivo de compilação.
- Alguns defeitos sempre resultarão em falha se forem
executados, enquanto outros só resultarão em falhas em circunstâncias específicas, e alguns podem nunca resultar em falha.

#### falhas
- As falhas também podem ser causadas por condições ambientais, como quando a radiação ou o campo eletromagnético causam defeitos no firmware

#### causa Raiz 
-  É um motivo fundamental para a ocorrência de um problema
- As causas-raiz são identificadas por meio da análise de causa-raiz, que normalmente é realizada quando ocorre uma falha ou quando um defeito é identificado

## Princípios de Teste ( DECORAR)

####  O teste mostra a presença, não a ausência de defeitos
- Os testes podem mostrar que os defeitos estão
presentes no objeto de teste, mas não podem provar que não há defeitos

#### Testes exaustivos são impossíveis.
- Testar tudo não é viável, exceto em casos triviais
- Em vez de tentar testar exaustivamente, as técnicas de teste  a priorização de casos de teste e os testes baseados em riscosdevem ser usados para concentrar os esforços de teste. 

#### Testes antecipados economizam tempo e dinheiro
-  Os defeitos que são removidos no início do processo
não causarão defeitos subsequentes nos produtos de trabalho derivados. O custo da qualidade será reduzido, pois menos falhas ocorrerão posteriormente

#### Os defeitos se agrupam
- Um pequeno número de componentes do sistema geralmente contém a maioria dos
defeitos descobertos ou é responsável pela maioria das falhas operacionais

#### Os testes se degradam
- Se os mesmos testes forem repetidos muitas vezes, eles se tornarão cada vez mais
ineficazes na detecção de novos defeitos
 Entretanto,
- em alguns casos, a repetição dos mesmos testes pode ter um resultado benéfico, por exemplo, em testes de regressão automatizados

#### Os testes dependem do contexto
- o. Não existe uma única abordagem universalmente aplicável aos testes. Os
testes são feitos de forma diferente em contextos diferentes

#### Falácia da ausência de defeitos
- É uma falácia esperar que a verificação
do software garanta o sucesso de um sistema

## Atividades de teste, Testware e Papéis no teste (COMPREENDER)

### Atividades e Tarefas de Teste (COMPREENDER)
-  Essas atividades de teste geralmente precisam ser adaptadas ao sistema e ao projeto

####  Planejamento do Teste (COMPREENDER)
- consiste em definir os objetivos do teste e, em seguida, selecionar uma abordagem
que melhor atinja os objetivos dentro das restrições impostas pelo contexto geral.

#### Monitoramento e Controle de Teste (COMPREENDER)
-  O monitoramento de teste envolve a verificação contínua de todas as
atividades de teste e a comparação do progresso real com o plano
- Controle: tomada de ações necessarias para atender aos objetivos do teste

#### Análise de Teste (COMPREENDER) **O QUE TESTAR?**
-  inclui a análise da base de teste para identificar os recursos testáveis e definir e priorizar as condições de teste associadas, juntamente com os riscos e níveis de risco relacionados
- A análise deteste responde à pergunta **"o que testar?"** em termos de critérios de cobertura mensuráveis.

#### Modelagem de Teste (COMPREENDER) **COMO TESTAR?**
-  inclui a elaboração das condições de teste em casos de teste e outros materiais
- identificação de itens de cobertura, que servem como guia para especificar as entradas do caso de teste.
- tecnicas de teste podem ser usadas para apoiar a modelagem
- inclue definição dos requisitos de dados de teste, projeto do ambiente de teste e indentificação de qualquer outra infraestrutura e ferramenta
-  A modelagem de teste responde à pergunta "como testar?".

####  Implementação do Teste (COMPREENDER)
- a **criação ou a aquisição do material de teste** necessário para a execução
- conseguir os dados de teste
- o dado da modelagem vai se tornar algo real
- Os casos de teste podem ser **organizados em procedimentos de teste** (passos) e geralmente são reunidos em conjuntos de testes (agrupar testes de determinada area do sistema).
- procedimentos de teste sao **priorizados e organizados em um cronograma** de execução de teste
- ambiente de teste ´´e criado e verificado quanto a configuração correta

#### Execução do Teste (COMPREENDER)
-  inclue a **execução dos testes** de acordo com o cronograma de execução
-  A execução do teste pode ser **manual ou automatizada**. A execução de testes pode assumir várias formas, inclusive **testes contínuos** ou sessões de **testes em pares**.
Os **resultados reais** dos testes são **comparados** com os
**resultados esperados** -> **Os resultados do teste são registrados** -> As **anomalias são analisadas** para identificar suas **causas prováveis**.

#### Conclusão de Teste (COMPREENDER)

- geralmente **ocorrem nos marcos** do projeto (p. ex., lançamento, fim da
iteração, conclusão do nível de teste) para quaisquer defeitos não resolvidos, solicitações de alteração ou itens do backlog do produto criados.
- qualquer **material de teste que possa ser util** é arquivado ou entregue as equipes apropriadas
- **ambiente de teste é encerrado** em um estado acordado
- **relatorio de conclusão do teste** é criado e comunicado aos stakeholders

## Processo de Teste no Contexto (COMPREENDER)

- Os testes são financiados pelos stakeholders e seu objetivo
final é ajudar a atender às necessidades de negócio deles

- **Stakeholders** (necessidades, expectativas, requisitos, disposição para cooperar etc.).
- **Membros da equipe** (habilidades, conhecimento, nível de experiência, disponibilidade, necessidades de
treinamento etc.).
- **Domínio do negócio** (criticidade do objeto de teste, riscos identificados, necessidades do mercado, normas legais específicas etc.).
- **Fatores técnicos** (tipo de software, arquitetura do produto, tecnologia usada etc.).
- **Restrições do projeto** (escopo, tempo, orçamento, recursos etc.).
- **Fatores organizacionais** (estrutura organizacional, políticas existentes, práticas utilizadas etc.).
- **Ciclo de vida do desenvolvimento de software** (práticas de engenharia, métodos de desenvolvimento etc.).
- **Ferramentas** (disponibilidade, usabilidade, conformidade etc.).

## Testware (COMPREENDER)
- O testware é criado como produto de trabalho de saída das atividades de teste descritas na seção 1.4.1.

- **analise**
  - condições de teste definidas e priorizadas
  - relatorios de defeitos nao corrigidos diretamente

- **modelagem**
  - casos de teste
  - carta de teste
  - dados de teste, cobertura, ambiente

- **implementação**
  - procedimentos (passo a passo)  
  - scripts de teste automatizado
  - conjunto de teste / dados de teste
  - cronograma de execução

- **execução** 
  - registros de teste
  - relatorios de defeitos

- **conclusão**
  - relatorios de teste
  - itens de ação / lições aprendidas documentadas para melhorias dos proximos projetos  
 

#### Os produtos de trabalho do planejamento de testes incluem: 
-  plano de testes, cronograma de testes,
registro de riscos e critérios de entrada e saída 

- O registro de riscos é uma lista de riscos
juntamente com a probabilidade de risco, o impacto do risco e informações sobre a mitigação do risco

#### Os produtos de trabalho do monitoramento e controle de testes
-  relatórios de progresso de testes , documentação de diretrizes de controle  e informações sobre riscos

#### Os produtos de trabalho da análise de teste incluem:
- Condições de teste (priorizadas) (p. ex., critérios de
aceite, ver seção 4.5.2) e relatórios de defeitos referentes a defeitos na base de teste (se não forem
corrigidos diretamente). 

#### Os produtos de trabalho da modelagem de teste incluem:
- Casos de teste (priorizados), cartas de teste, itens de cobertura, requisitos de dados de teste e requisitos de ambiente de teste. 

#### Os produtos de trabalho da implementação de teste incluem
- procedimentos de teste, scripts de teste automatizados, conjuntos de teste, dados de teste, cronograma de execução de teste e elementos do ambiente de teste.

#### Os produtos de trabalho da execução de testes incluem:
-  registros de testes e relatórios de defeitos

#### Os produtos de trabalho da conclusão do teste incluem:
- relatório de conclusão do teste, itens de ação para melhoria de projetos ou iterações subsequentes, lições aprendidas documentadas e solicitações de alteração

## Rastreabilidade entre a Base de Teste e o Testware (compreender)

- Para implementar o monitoramento e o controle eficazes dos testes, é importante estabelecer e manter a **rastreabilidade em todo o processo de teste** entre os elementos da base de teste, o testware associado a esses elementos os resultados dos testes e os defeitos detectados. 

  - A **rastreabilidade dos casos de teste aos requisitos** pode verificar se os requisitos são cobertos pelos casos de teste.

  - A **rastreabilidade dos resultados dos testes aos riscos** pode ser usada para avaliar o nível de risco residual em um objeto de teste.

  - uma boa rastreabilidade permite determinar o **impacto das mudanças**, facilita as auditorias de teste e ajuda a atender os critérios de governança de TI

## Papéis no Teste (m papel de gerenciamento de testes e um papel de testador) (COMPREENDER)

- O **papel de gerenciamento de teste** assume a responsabilidade geral pelo 
  - processo de teste, pela equipe de teste e pela liderança das atividades de teste.
  - atividades de planejamento, monitoramento e controle, e conclusão de testes.
  - no desenvolvimento agil, algumas tarefas de gerenciamento podem ser realizadas pela equipe

- O **papel de testador** assume a responsabilidade geral pelo aspecto de engenharia (técnico) do teste  
  - atividades de análise, modelagem, implementação e execução de teste.
  - executar os testes
  - automatizar conforme necessario
  - avaliar as caracteristicas nao funcionais

- É possivel que uma pessoa assuma o papel de testador e gerenciamento de teste ao mesmo tempo  


## Habilidades essenciais e boas práticas em testes   

#### Habilidades genéricas necessárias para testes (COMPREENDER)

- **Conhecimento sobre testes** (para aumentar a eficácia dos testes, por exemplo, usando técnicas de teste)

- **Meticulosidade**, cuidado, curiosidade, atenção aos detalhes, ser metódico (para identificar defeitos, especialmente aqueles que são difíceis de encontrar)

- **Boas habilidades de comunicação**, ser um bom ouvinte, e trabalhar em equipe (para interagir efetivamente com todos os stakeholders, transmitir informações a outras pessoas, ser compreendido, e relatar e discutir defeitos)

- **Pensamento analítico**, pensamento crítico, criatividade (para aumentar a eficácia dos testes)

- **Conhecimento técnico** (para aumentar a eficiência dos testes, por exemplo, usando ferramentas de teste adequadas)

- **Conhecimento do domínio / regra de negocio** (para poder entender e se comunicar com usuários finais/representantes de negócio) 

#### Abordagem de equipe completa (DECORAR)

- qualquer membro da equipe com o conhecimento e as habilidades necessárias pode executar qualquer tarefa
- todos são responsáveis pela qualidade.
- melhora a dinâmica da equipe
  - aprimora a comunicação e a colaboração dentro da equipe e cria sinergia ao permitir que os vários conjuntos de habilidades da equipe sejam aproveitados para o benefício do projeto. 
- Os testadores podem transferir conhecimento sobre testes para outros membros da equipe  
- em sistemas criticos pode ser necessario um alto nivel de independencia dos testes

#### Independência dos testes (COMPREENDER)

- **São testes realizados por alguem que não seja o autor do codigo**

- O principal benefício da independência dos testes é que os **Testadores independentes provavelmente reconhecerão diferentes tipos de falhas e defeitos em comparação com os desenvolvedores**, devido às suas diferentes formações, perspectivas técnicas e preconceitos.

#### Tabela da Independencia (DECORAR)

- **Sem Independencia**
    - Sem testadores independentes, testadores testam seu proprio codigo

- **Alguma Independencia**
  - Testadores dentro das equipes de desenvolvimento

- **Alta independencia**
  - Realicado por testadores de fora da equipe do autor

- **Independencia muito alta (testadores de empresa terceirizada)** 
  - Testadores independentes externos a organização, trabalhando dentro ou fora do escritorio        

#### Vantagens
- Encontrar **diferentes tipos de falhas** em comparação aos desenvolvedores
- são mais imparciais
- Um testador independente pode **verificar, desafiar ou refutar as suposições** feitas pelos stakeholders

#### Desvantagens
- Os Testadores independentes podem ficar **isolados da equipe de desenvolvimento** o que pode levar à **falta de colaboração**, a problemas de comunicação ou a uma relação adversa com a equipe de desenvolvimento. 
- Os desenvolvedores podem **perder o senso de responsabilidade pela qualidade**. 
Os Testadores independentes podem ser vistos como um **gargalo ou ser responsabilizados por atrasos no lançamento**. 