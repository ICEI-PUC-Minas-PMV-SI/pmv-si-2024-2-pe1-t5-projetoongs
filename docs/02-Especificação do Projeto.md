# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

### 1º Persona: Gerente de ONGs

Fatos:  
- Responsável pela administração geral e pela execução dos projetos da ONG;
- Precisa prestar contas de recursos e resultados para doadores e financiadores;
- Lida com várias tarefas operacionais e falta de recursos humanos capacitados.

Desconfortos:
- Dificuldade em organizar e centralizar as informações da ONG;
- Falta de ferramentas tecnológicas que facilitem a captação de recursos e gestão eficiente;
- Pressão para aumentar a transparência e demonstrar resultados concretos, mas sem ferramentas adequadas para isso.

Comportamento:
- Busca constantemente soluções que possam otimizar a gestão e melhorar a comunicação com doadores;
- Acessa várias plataformas de forma dispersa, o que gera perda de tempo e pouca integração;
- Está aberta à implementação de novas tecnologias, mas enfrenta resistência interna.

Objetivos: 
- Melhorar a eficiência na gestão das operações da ONG;
- Centralizar todas as informações e resultados em uma plataforma intuitiva;
- Proporcionar maior visibilidade e confiabilidade para os doadores e financiadores.

### 2º Persona: Doador

Fatos: 
- Interessado em contribuir para causas sociais, ambientais e humanitárias;
- Gosta de saber como os recursos são aplicados e quais os impactos reais das doações;
- Pode ser um doador recorrente ou pontual, mas valoriza transparência nas doações.

Desconfortos:
- Falta de clareza sobre como as ONGs utilizam os recursos doados;
- Dificuldade em acompanhar o impacto real das doações;
- Desconfiança devido à falta de transparência em algumas organizações.  

Comportamento:
- Tende a doar para organizações com as quais se identifica e que transmitem confiança;
- Pesquisa e compara diferentes ONGs antes de tomar uma decisão de doação;
- Deseja um canal claro de comunicação e um retorno sobre o impacto de suas contribuições.

Objetivos:
- Contribuir para causas alinhadas com seus valores e acompanhar o impacto gerado;
- Sentir-se seguro de que sua doação está sendo bem utilizada e aplicada em projetos significativos;
- Estabelecer uma relação de confiança e transparência com a ONG.

### 3º Persona: CEO 

Fatos: 
- Responsável pela estratégia geral e pelo crescimento da ONG;
- Enfrenta desafios de captação de recursos e gestão de equipe;
- Precisa equilibrar o propósito social com a visibilidade financeira e a sustentabilidade da organização.
  
Desconfortos:
- Dificuldade em atrair e reter doadores por falta de visibilidade e ferramentas adequadas;
- Preocupação com a falta de transparência de outras ONGs e como a sua pode ser diferente neste sentido;
- Falta de controle e análise de dados, o que impacta a tomada de decisões mais estratégicas e organização.
  
Comportamento:
- Procura sempre oportunidades para otimizar a gestão e melhorar a captação de recursos;
- Toma decisões baseadas em dados, mas tem pouca visibilidade de informações relevantes;
- Preocupado com a reputação da ONG e como é vista pela sociedade e pelos doadores.

Objetivos:
- Aumentar a captação de recursos por meio de uma comunicação clara e eficiente com doadores;
- Implementar tecnologias que otimizem a operação e a transparência da ONG;
- Garantir a sustentabilidade financeira da organização e seu impacto positivo na sociedade.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE` | PARA ... `MOTIVO/VALOR`                |
| -------------------- | ---------------------------------- | -------------------------------------- |
| Gerente administrativo   | De uma página de gerenciamento com interface intuitiva para atualizar e analisar dados e resultados.          | Melhorar a eficiencia e garantir que informações estejam acessíveis aos doadores e financiadores, criando confiança.                 |
| Administrador        | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
>
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

Aqui está uma separação clara entre os requisitos funcionais, requisitos não funcionais e restrições para o seu projeto:

### Requisitos Funcionais

São as funcionalidades que o sistema deve ter para atender às necessidades do usuário.

| ID     | Descrição do Requisito                                           | Prioridade |
| ------ | ---------------------------------------------------------------- | ---------- |
| RF-001 | Permitir que os usuários se cadastrem no sistema                 | ALTA       |
| RF-002 | Permitir que os usuários façam login e logout                    | ALTA       |
| RF-003 | permitir que as organizações possam exportar relatórios semanais e mensais                        | ALTA       |
| RF-004 | Desenvolver uma página onde as Instituições possam registrar suas atividades, métricas mensais e relatórios de retorno            | MÉDIA      |
| RF-005 | Desenvolver uma página com conteúdos básicos sobre gestão e negócio             | ALTA       |
| RF-006 | Facilitar a busca por oportunidades de voluntariado              | MÉDIA      |
| RF-007 | Notificar os usuários sobre novas oportunidades de voluntariado  | BAIXA      |
| RF-008 | permitir que o usuário cadastre suas preferências de área de atuação das ONGs | MÉDIA      |
| RF-009 | Desenvolver uma página com o dashboard de dados mensais e semanais          | ALTA      |
| RF-010 | permitir que os usuários doadores possam visualizar as métricas e ficar a par dos resultados das ONGs | ALTA      |

### Requisitos Não Funcionais

São as características técnicas que o sistema deve ter para garantir qualidade, desempenho e usabilidade.

| ID      | Descrição do Requisito                                           | Prioridade |
| ------- | ---------------------------------------------------------------- | ---------- |
| RNF-001 | O sistema deve ser responsivo e funcionar em dispositivos móveis | ALTA       |
| RNF-002 | A plataforma deve garantir a segurança dos dados dos usuários    | ALTA       |
| RNF-003 | O tempo de resposta do sistema deve ser inferior a 3 segundos    | MÉDIA      |
| RNF-004 | O sistema deve suportar no mínimo 1.000 usuários simultâneos     | BAIXA      |
| RNF-005 | A interface deve ser intuitiva e fácil de usar                   | ALTA       |
| RNF-006 | O sistema deve estar disponível 99,9% do tempo                   | ALTA       |
| RNF-007 | Disponibilizar uma plataforma acessível (acessibilidade)         | ALTA       |

### Restrições

São limitações ou condições impostas ao projeto, que afetam o escopo, o desenvolvimento ou a entrega.

| ID  | Restrição                                                             |
| --- | --------------------------------------------------------------------- |
| 01  | O projeto deverá ser entregue até o final do semestre                 |
| 02  | Não será permitido o desenvolvimento de um módulo backend             |
| 03  | O orçamento para marketing digital será limitado a R$ 5.000           |
| 04  | O sistema deve ser implementado usando apenas tecnologias de frontend |
