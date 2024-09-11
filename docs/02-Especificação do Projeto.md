# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
>
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
> Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE` | PARA ... `MOTIVO/VALOR`                |
| -------------------- | ---------------------------------- | -------------------------------------- |
| Usuário do sistema   | Registrar minhas tarefas           | Não esquecer de fazê-las               |
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
| RF-003 | Permitir que os usuários realizem doações                        | ALTA       |
| RF-004 | Oferecer um painel de controle para gerenciar doações            | MÉDIA      |
| RF-005 | Mostrar relatórios detalhados do impacto das doações             | ALTA       |
| RF-006 | Facilitar a busca por oportunidades de voluntariado              | MÉDIA      |
| RF-007 | Notificar os usuários sobre novas oportunidades de voluntariado  | BAIXA      |
| RF-008 | Disponibilizar relatórios financeiros para doadores corporativos | MÉDIA      |
| RF-009 | Permitir que os usuários compartilhem oportunidades nas redes sociais | BAIXA      |

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
| RNF-007 | O sistema deve ser compatível com os principais navegadores (Chrome, Firefox, Edge)  | ALTA       |
| RNF-008 | O consumo de recursos (CPU, memória) deve ser otimizado para não sobrecarregar | MEDIA       |


### Restrições

São limitações ou condições impostas ao projeto, que afetam o escopo, o desenvolvimento ou a entrega.

| ID  | Restrição                                                             |
| --- | --------------------------------------------------------------------- |
| 01  | O projeto deverá ser entregue até o final do semestre                 |
| 02  | Não será permitido o desenvolvimento de um módulo backend             |
| 03  | O orçamento para marketing digital será limitado a R$ 5.000           |
| 04  | O sistema deve ser implementado usando apenas tecnologias de frontend |
| 04  |Todo o conteúdo deve estar disponível em português |
