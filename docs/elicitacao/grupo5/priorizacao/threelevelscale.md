# Three Level Scale

## Introdução

A técnica de priorização Three Levels Scale é uma abordagem simples e eficiente para classificar requisitos com base em sua prioridade relativa. Essa técnica categoriza os requisitos em três níveis: alta, média e baixa prioridade, facilitando a organização e o planejamento do projeto. No contexto deste trabalho, a técnica foi aplicada com a colaboração de um desenvolvedor, que atuou como mediador, e de um usuário, responsável por avaliar os requisitos.

## Participantes

A tabela 1 apresenta os participantes da atividade de priorização

<div style="text-align: center">
<font size="3"><p> Tabela 1: Participantes 2024 </font></p>

<table>
  <tr>
    <th>Nome</th>
    <th>Função</th>
  </tr>
  <tr>
    <td>Victor Rodrigues</td>
    <td>Mediador</td>
  </tr>
  <tr>
    <td> Kauan Dias </td>
    <td> Usuário </td>
  </tr>
</table>

<font size="3"><p><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>

## Metodologia

Os requisitos foram apresentados ao usuário, que os classificou em uma das três categorias de prioridade com base em sua importância e urgência. Durante o processo, o mediador explicou os critérios de cada nível e esclareceu dúvidas para garantir uma avaliação consistente. Não foram atribuídos valores numéricos, mas considerou-se a relevância de cada requisito para os objetivos do projeto e as necessidades do usuário.

## Requisitos priorizados

Os requisitos foram organizados em duas tabelas: a Tabela 2 apresenta os Requisitos Funcionais, enquanto a Tabela 3 lista os Requisitos Não Funcionais.

_Legenda das Tabelas:_

- RFx: Requisito Funcional número x;
- RNFx: Requisito Não Funcional número x;
- ITx: Requisito da Introspecção número x;
- BFx: Requisito Funcional do Brainstorm número x;
- BFNx: Requisito Não Funcional do Brainstorm número x;
- GFx: Requisito do Grupo de Foco número x;
- GLOx: Requisito do Glossário número x;

### Funcionais

<div>
<font size="3"><p style="text-align: center"> Tabela 2 - Requisitos Funcionais </a></font></p>
</div>


| Identificador | Descrição	| ID | Priorização |
|---------------|-----------|-----|-------------|
| RF01 | Permitir a consulta de investimentos por instituição financeira. | IT1 | Alta prioridade |  
| RF02 | Permitir a simulação, realização e visualização de detalhes de investimentos nos títulos SELIC, Prefixado e Inflação. | IT2 | Alta prioridade |  
| RF03 | O sistema deve permitir o resgate antecipado de títulos, com cálculo automático do valor líquido baseado na data de resgate e na rentabilidade acumulada. | IT3, GLO07 | Média prioridade |  
| RF04 | Oferecer funcionalidade para salvar metas de investimentos (Sonhos). | IT4 | Média prioridade |  
| RF05 | Permitir simulação e planejamento de aposentadoria indicando o ano esperado de aposentadoria. | IT5 | Alta prioridade |  
| RF06 | Disponibilizar consulta à taxa de custódia da B3 e taxa de administração da instituição financeira. | IT6 | Alta prioridade |  
| RF07 | Incluir um simulador para ajudar o usuário a encontrar títulos adequados ao perfil dele. | IT7 | Méida prioridade |  
| RF08 | Permitir a consulta de operações realizadas e agendadas. | IT8 | Média prioridade |  
| RF09 | Oferecer a funcionalidade de “Fale Conosco”. | IT9 | Alta prioridade |  
| RF10 | Permitir a visualização de notificações recebidas. | IT10 | Alta prioridade |  
| RF11 | Incluir funcionalidades sobre o aplicativo (avaliar, indicar para um amigo ou limpar cache). | IT11, GF05 | Baixa prioridade |  
| RF12 | Permitir a visualização de dados do usuário. | IT12 | Alta prioridade |  
| RF13 | Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos. | IT13, GLO07 | Média prioridade |  
| RF14 | Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos. | IT14 | Média prioridade |  
| RF15 | Incluir relatórios personalizados para análise detalhada de rentabilidade e evolução de investimentos. | IT15 | Alta prioridade |  
| RF16 | Disponibilizar um recurso educativo com vídeos e artigos sobre como investir no Tesouro Direto. | IT16, BF10 | Média prioridade |  
| RF17 | Oferecer integração com carteiras digitais para pagamento direto de investimentos. | IT17 | Alta prioridade |  
| RF18 | Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação. | IT18 | Média prioridade |  
| RF19 | Adicionar gamificação, como conquistas ou recompensas simbólicas ao atingir metas financeiras. | IT19 | Média prioridade |  
| RF20 | O aplicativo deve permitir que o usuário faça uma autodeclaração de expertise (novo, médio, experiente). | BF1 | Média prioridade |  
| RF21 | O aplicativo deve oferecer um tutorial para guiar o usuário no uso das funcionalidades. | BF2 | Média prioridade |  
| RF22 | O sistema deve disponibilizar um maior leque de opções para simulações financeiras. | BF3, GF03 | Média prioridade |  
| RF23 | O aplicativo deve exibir a liquidez dos títulos do Tesouro Nacional na simulação. | BF4 | Alta prioridade |  
| RF24 | O sistema deve permitir a comparação de títulos de diferentes origens na simulação. | BF5, GF04 | Média prioridade |  
| RF25 | O sistema deve integrar a funcionalidade de simulação com a aba "Meus Sonhos". | BF7 | Alta prioridade |  
| RF26 | O aplicativo deve apresentar um dashboard inicial com informações relevantes para o usuário. | BF10 | Alta prioridade |  
| RF27 | O sistema deve incluir uma barra de progresso na aba "Meus Sonhos". | BF12 | Alta prioridade |  
| RF28 | O aplicativo deve permitir a comparação da simulação com os padrões do INSS na aposentadoria. | BF14 | Média prioridade |  
| RF29 | O sistema deve exibir sugestões personalizadas na página inicial do "Meu Investimento". | BF15 | Média prioridade |  
| RF30 | O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis, incluindo suas características principais. | GLO01 | Alta prioridade |  
| RF31 | O sistema deve possibilitar a compra de títulos públicos por meio de diferentes métodos de pagamento, garantindo segurança na transação. | GLO02 | Alta prioridade |  
| RF32 | O sistema deve exibir a rentabilidade acumulada de cada título na carteira do usuário, de forma clara e atualizada. | GLO03 | Alta prioridade |  
| RF33 | O aplicativo deverá permitir que o usuário faça login criando uma conta própria no sistema | GF02 | Alta prioridade |
| RF34 | O aplicativo deverá possuir uma tela de login integrado com o gov.br | GF01 | Média prioridade |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>


### Não Funcionais

<div>
<font size="3"><p style="text-align: center"> Tabela 3 - Requisitos Não Funcionais </a></font></p>
</div>

| Identificador | Descrição	| ID | Priorização |
|---------------|-----------|-----|-------------|
| RNF01 | O sistema deve ter tempo de resposta inferior a 2 segundos para consultas básicas. | IT20 | Alta prioridade |
| RNF02 | Garantir a segurança dos dados sensíveis do usuário conforme a LGPD. | IT21, GF06 | Alta prioridade |
| RNF03 | O aplicativo deve ser responsivo para dispositivos móveis e tablets. | IT22, GF07, GLO08 | Alta prioridade |
| RNF04 | A interface deve ser intuitiva e seguir as diretrizes de acessibilidade. | IT23, BFN11, GF08, GLO04 | Alta prioridade |
| RNF05 | O sistema deve permitir integrações seguras com APIs de instituições financeiras. | IT24, GLO06 | Alta prioridade |
| RNF06 | Disponibilizar suporte para múltiplos idiomas (português como padrão). | IT25 | Média prioridade |
| RNF07 | O sistema deve oferecer controle ampliado para simulações de aposentadoria. | BFN6 | Alta prioridade |
| RNF08 | O perfil de recomendação de investimentos deve ser mais visível e acessível no aplicativo. | BFN9 | Média prioridade |
| RNF09 | O aplicativo deve incluir uma opção de tema escuro para melhorar a experiência do usuário. | BFN13 | Baixa prioridade |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>

## Reunião de priorização 

A gravação da reunião de priorização pode ser encontrada no video 1.

<div>
<font size="3"><p style="text-align: center"> Video 1 - Reunião de Priorização $100 </a></font></p>
</div>

<div style="display: flex; justify-content: center; margin: 20px 0;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/fxQMHT1a_eQ?si=6McpdKge4oBjqJUg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<div>
<font size="3"><p style="text-align: center"><b>Autores:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues</a> e <a href="https://github.com/thaleseuflauzino">Thales Euflauzino</a>, 2024</font></p>
</div>
## Bibliografia

> WIEGERS Karl E. First Things First: Prioritizing Requirements. Setembro de 1999. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf. Acesso em: 21 nov. 2024
>
> REQUISTOS DE SOFTWARE. Three Levels Scale. Disponível em: https://requisitos-de-software.github.io/2022.2-Grasshopper/elicitacao/priorizacao/threeLevel-Scale/. Acesso em: 21 nov. 2024.
>
> REQUISTOS DE SOFTWARE. Three Levels Scale. Disponível em: https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/priorizacao/#escala-de-tres-niveis. Acesso em: 21 nov. 2024.
>
> REQUISTOS DE SOFTWARE. Three Levels Scale. Disponível em: https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/priorizacao/threeLvlScale/. Acesso em: 21 nov. 2024.
>

## Histórico de Versões

| Versão | Data       | Descrição | Autor     |       Revisor         |
| ------ | ---------- | --------- | --------- | --------------------- |
| `1.0`  | 21/11/2024 | Lista de requisitos | [Víctor Rodrigues](https://github.com/ViictorHugoo) | [Thales Euflauzino](https://github.com/thaleseuflauzino) |
| `1.1`  | 21/11/2024 | Inclusão de Introdução e Metodologia | [Víctor Rodrigues](https://github.com/ViictorHugoo) | [Thales Euflauzino](https://github.com/thaleseuflauzino) |
| `1.2`  | 22/11/2024 | Priorização | [Víctor Rodrigues](https://github.com/ViictorHugoo) | [Thales Euflauzino](https://github.com/thaleseuflauzino) |

