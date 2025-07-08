# Testes ao longo do ciclo de vida do Desenvolvimento de Software

## Testes no contexto de um Ciclo de Vida de Desenvolvimento de Software 

- Um modelo SDLC define como as diferentes fases de desenvolvimento e os tipos de atividades realizadas nesse processo se relacionam entre si,  tanto lógica quanto cronologicamente.

- desenvolvimento orientado por testes de aceite (ATDD),

-  desenvolvimento orientado pelo comportamento (BDD), domain-driven design (DDD),
- extreme programming (XP), 
- feature-driven development (FDD), 
- Kanban, Lean IT, Scrum e desenvolvimento
- orientado por teste (TDD). 

- **Independente do modelo de ciclo escolhido, os testes devem começar nos estagios iniciais**

##  Impacto do Ciclo de Vida de Desenvolvimento de Software nos Testes (COMPREENDER)
- O teste deve ser **adaptado ao SDLC**

- A escolha do SDLC tem impacto sobre:
  - O escopo e cronograma das atividades de teste (p. ex., níveis de teste e tipos de teste);
  - O nível de detalhamento da documentação de teste;
  - A extensão da automação de testes;
  - O papel e responsabilidades de um Testador;

#### Desenvolvimento sequencial
- os Testadores normalmente **participam das revisões de requisitos**, da análise de testes e da modelagem de testes
- O código executável  é criado nas fases posteriores, os **testes dinâmicos não podem ser realizados** no início do SDLC. 

#### Alguns modelos de desenvolvimento iterativos e incrementais
- cada iteração entrega um protótipo funcional ou um incremento de produto
- **em cada iteração, os testes estáticos e dinâmicos podem ser realizados** em todos os níveis de teste
-  A entrega frequente de incrementos exige **feedback rápido e testes de regressão extensivos**.

#### O Desenvolvimento Ágil de Software
- **podem ocorrer mudanças ao longo do projeto**
- documentação leve do produto de trabalho 
- **ampla automação de testes** para facilitar os testes de regressão são favorecidas em projetos Ágeis.
- **testes manuais** tendem a ser feitos usando **tecnicas baseadas na experiencia**

## Ciclo de Vida de Desenvolvimento de Software e boas práticas de Teste (LEMBRAR)

- As boas práticas de teste:
  -Para **cada atividade de desenvolvimento de software, há uma atividade de teste correspondente**;
  - Diferentes **níveis de teste têm objetivos de teste específicos e diferentes**, evitando redundância;
  - A **análise e a modelagem do teste começam durante a fase de desenvolvimento** correspondente do SDLC, princípio do teste antecipado;
  - Os **Testadores estão envolvidos na revisão dos produtos de trabalho** assim que os rascunhos dessa documentação estiverem disponíveis, de modo que esse teste antecipado e a detecção de defeitos possam apoiar a estratégia shift-left;

## Teste como um motivador para o desenvolvimento de software (LEMBRAR)

- O TDD, ATDD e BDD são abordagens de desenvolvimento semelhantes, em que os testes são definidos como um meio de direcionar o desenvolvimento.
- os testes são definidos antes de o código ser escrito.

#### Desenvolvimento Orientado por Testes (TDD):

- **Direciona a codificação por meio de casos de teste**

- **Os testes são escritos primeiro, depois o código é escrito para satisfazer os testes** e, em seguida, os testes e o código são refatorados;

- ESCREVE UM TESTE DE UNIDADE QUE FALHA -> CRIAR O CODIGO PARA FAZER O TESTE PASSAR -> REFATORAR 

#### Desenvolvimento Orientado por Teste de Aceite (ATDD)

- **Deriva testes de critérios de aceite** como parte do processo de desenho do sistema

- Os testes são escritos antes que a parte do aplicativo relacionada seja desenvolvida para atender aos testes. 

- Baseados nas user stories, voltado ao usuario final

- discussão da historia de usuario -> detalhamento dos testes de aceite-> desenvolvimento -> demonstração de tudo funcionando


#### Desenvolvimento Orientado pelo Comportamento (BDD)

- Expressa o comportamento desejado de um aplicativo com casos de teste escritos em uma forma simples de linguagem natural, que é fácil de entender pelos stakeholders - geralmente usando o formato Dado/Quando/Então.
- Os casos de teste são então traduzidos automaticamente em testes executáveis.

-> levantamento de requisitos -> scenarios -> scenarios guiam o desenvolvimento e testes

## DevOps e Testes (COMPREENDER)

- DevOps é uma abordagem organizacional fazendo com que o desenvolvimento (incluindo os testes) e as operações trabalhem juntos para atingir um conjunto de objetivos comuns

- O DevOps promove a autonomia da equipe, feedback
rápido, cadeias de ferramentas integradas e práticas técnicas como Integração Contínua e Entrega Contínua

-  Isso permite que as equipes criem, testem e liberem
códigos de alta qualidade mais rapidamente por meio de um pipeline de entrega de DevOps

#### Benefícios do DevOps são:
  
- Feedback rápido sobre a **qualidade do codigo**
-  CI (integração continua) abordagem **shift-left**
- Promove processos automatizados, como CI/CD (integração continua / entrega continua)
- Aumenta a visão das características de qualidade não funcionais
- A automação por meio de um pipeline de entrega reduz a necessidade de testes manuais repetitivos
- O risco na regressão é minimizado devido à escala e ao alcance dos testes de regressão automatizados;

#### O DevOps tem seus riscos e desafios, que incluem:
- O **pipeline de entrega** de DevOps deve ser definido e estabelecido
- As **ferramentas** de CI/CD devem ser **introduzidas e mantidas**;
- A automação de testes requer recursos adicionais e **pode ser difícil de estabelecer e manter.**

## Abordagem Shift-Left 
- O princípio do teste antecipado às vezes é chamado de shift-left porque é uma abordagem em que o **teste é realizado mais cedo** no SDLC

#### Boas práticas que ilustram como obter um "shift-left" nos testes
- **Revisão da especificação sob a perspectiva de testes.** Essas atividades de revisão das especificações geralmente encontram possíveis defeitos, como ambiguidades, incompletude e inconsistências;
- **Escrever casos de teste antes de o código ser escrito** e fazer com que o código seja executado em um conjunto de testes durante a sua implementação;
- Usar a CI e, melhor ainda, a CD, pois ela vem com feedback rápido e testes de componentes automatizados para acompanhar o código-fonte quando ele é enviado ao repositório de código
- Concluir a **análise estática do código-fonte antes do teste dinâmic** ou como parte de um processo automatizado;
- **Realizar testes não funcionais começando no nível de teste do componente, sempre que possível.**

## Retrospectivas e melhoria de processos 
- As retrospectivas  discutem:
  -  O que foi bem-sucedido e deve ser mantido?
  -  O que não foi bem-sucedido e poderia ser melhorado?
  -  Como incorporar as melhorias e manter os sucessos no futuro?

#### Os típicos benefícios dos testes incluem:  
- Aumento da eficácia/eficiência do teste
- Aumento da qualidade do material de teste
- Vínculo e aprendizado da equipe
- Melhoria da qualidade da base de teste 
- Melhor cooperação entre desenvolvimento e testes

## Níveis de Teste e Tipos de Teste
- são **grupos de atividades de teste** que são organizadas e gerenciadas em conjunto
- níveis de teste são geralmente definidos de forma que os critérios de saída de um nível façam parte dos critérios de entrada do próximo nível.

### Níveis de Teste (DECORAR)

#### O Teste de Componente (Teste de Unidade)
- Concentra-se em testar componentes isoladamente (função / componente / classe)
- Requer **acesso ao codigo**
- Normalmente **realizado pelo desenvolvedor**
- Deve ser **isolado, sem integração** com outro componente
- Tdd
- Deve ser um **teste automatizado**

- **objetivos do teste de componente:**
  - Reduzir o risco
  - verificar comportamentos funcional e nao funcional do componente
  - confiança na qualidade do componente
  - encontrar defeitos
  - **evitar que os defeitos se espalhem para niveis mais altos de teste**


#### O Teste de Integração de Componentes
- integrações entre os componentes ou sistemas.
- Requer **acesso ao codigo**
- Pode ser **realizado pelo desenvolvedor**
- Quanto **maior o escopo** da integração, **mais dificil é isolar os defeitos**.

- **objetivos do teste de integração:**
  - Reduzir o risco
  - verificar comportamentos funcional e nao funcional do componente

#### O Teste de Sistema - executado perto do fim do processo

- **Sistema em si sendo executado**
- Fluxos de **ponta a ponta (end to end)**
- Produz **informações** que sao usadas para **tomar decisões** de liberação
- Concentra-se no **comportamento geral e nos recursos de todo um sistema ou produto.**
- Tambem pode **verificar requisitos legais / regulatorios**
- **Executado pelos testadores**

- **objetivos do teste de sistema:**
  - Reduzir o risco
  - verificar comportamentos funcionais e nao funcionais
  - validar se o sistema esta completo e funcionando
  - Encontrar defeitos
  - Evita que os defeitos espalhem para niveis mais altos ou produção


#### O Teste de Integração de Sistema
- Concentra-se no **teste das interfaces do sistema e de outros sistemas e serviços externos**

#### O Teste de Aceite

- concentra-se na **validação e na demonstração da disposição para a implantação, o que significa que o sistema atende às necessidades (requisitos) de negócio do usuário**

- **Garantir que o sistema ta funcionando conforme especificado para o usuario final**

- Os níveis de teste são diferenciados pela seguinte lista de atributos:
  -  Objeto de teste;
  -  Objetivos do teste;
  -  Base de teste - referencia para casos de teste;
  -  Defeitos e falhas;
  -  Abordagem e responsabilidades.

- **Teste de aceite de usuario UAT**
  - certificar que o sistema atenda as necessidades do usuario
  - valida o uso do sistema por usuarios em um ambiente de produção ou simulado


- **Teste de aceite operacional**
  - Garantir que os operadores ou ADS possam manter o sistema funcionando para os usuarios no ambiente de produção
  - São realizados testes como: Backups e restauração, performance e vulnerabilidades  

- **Teste de aceite contratual e regularotio**
  - Garantir que a conformidade contratual foi alcançada  

- **Teste alfa**
  - Realizado no site da organização

- **Teste Beta**
  - Testes realizados em um local proprio  

### Tipos de Teste  

#### O Teste Funcional 
- "o que" o sistema deve fazer
- avalia as funções que um componente ou sistema deve executar

#### O Teste Não Funcional
- "Quão bem" o sistema se comporta
-  classificação das características não funcionais de qualidade do software:
  - Eficiência de Performance;
  - Compatibilidade;
  - Usabilidade;
  - Confiabilidade;
  - Segurança;
  - Capacidade de manutenção;
  - Portabilidade

### O Teste Caixa-Preta  
- teste baseado nas **especificações do sistema**
- **Deriva testes da documentação externa**
- **Verificar o comportamento do sistema em relação as suas especificações**

### O Teste Caixa-Branca (código, arquitetura, fluxos de trabalho e fluxos de dados)
- Teste com acesso ao codigo
- cobrir a estrutura subjacente pelos testes até o nível aceitável. 
- Exige conhecimentos em codigo

### Testes de Confirmação e Teste de Regressão (DECORAR)

#### Teste de confirmação
- **Confirma que um defeito original foi corrigido com sucesso**
  - executando todos os casos de teste que falharam anteriormente devido ao defeito
  - adicionar novos testes para cobrir quaisquer alterações necessárias para corrigir o defeito

#### Teste de Regressão
- **Confirmam que nenhuma consequência adversa foi causada por uma alteração.**
- Essas consequências adversas podem afetar o mesmo componente em que a alteração foi feita, outros componentes do mesmo sistema ou até mesmo outros sistemas conectados.
- **É aconselhável realizar primeiro uma análise de impacto para otimizar a extensão do teste de regressão.**
  -  A análise de impacto mostra quais partes do software podem ser afetadas. 

- **A automação desses testes deve começar no início do projeto**
- é uma boa prática incluir também testes de regressão automatizados


### Teste de Manutenção (DECORAR)

- manutenção pode envolver **versões/implantações planejadas e versões/implantações não planejadas (hot fixes)**
  - adicionar funcionalidades
  - alterar funcionalidades entregues

- **O escopo dos testes de manutenção geralmente depende de:** 
  - O grau de risco da mudança;
  - O tamanho do sistema existente; 
  - O tamanho da mudança.

- **Os fatores para manutenção e teste de manutenção podem ser classificados:** (DECORAR)

- **Modificações**, como aprimoramentos planejados (ou seja, baseados em versões), alterações corretivas ou hot fixes; 
- **Atualizações ou migrações do ambiente operacional**, como de uma plataforma para outra, o que pode exigir testes associados ao novo ambiente
- **Aposentadoria**, por exemplo, quando um aplicativo chega ao fim de sua vida úti
