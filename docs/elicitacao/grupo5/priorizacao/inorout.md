# In or Out

## Introdução

Durante o desenvolvimento de software, é comum que haja uma quantidade significativa de requisitos elicitados, tornando necessário definir quais deles devem ser priorizados para a primeira etapa de implementação. Nesse contexto, a técnica In or Out é uma abordagem prática e direta para essa priorização.


## Metodologia

A técnica consiste em realizar uma escolha binária para cada requisito: In (dentro) ou Out (fora), indicando, respectivamente, se o requisito será implementado na próxima release ou não. Aqueles marcados como Out permanecem na lista de requisitos para serem reavaliados em futuras etapas do projeto.

Neste trabalho, um dos integrantes do grupo reuniu-se com um usuário externo ao projeto, que foi orientado a aplicar a técnica. A dinâmica envolveu a análise de cada requisito, seguida pela decisão sobre sua inclusão ou exclusão na próxima fase de desenvolvimento, com base em sua relevância e urgência.


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
    <td> - </td>
    <td> Usuário </td>
  </tr>
</table>

<font size="3"><p><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>

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
| RF01 | Permitir a consulta de investimentos por instituição financeira. | IT1 |  |  |
| RF02 | Permitir a simulação, realização e visualização de detalhes de investimentos nos títulos SELIC, Prefixado e Inflação. | IT2 |  |  |
| RF03 | O sistema deve permitir o resgate antecipado de títulos, com cálculo automático do valor líquido baseado na data de resgate e na rentabilidade acumulada. | IT3, GLO07 |  |  |
| RF04 | Oferecer funcionalidade para salvar metas de investimentos (Sonhos). | IT4 |  |  |
| RF05 | Permitir simulação e planejamento de aposentadoria indicando o ano esperado de aposentadoria. | IT5 |  |  |
| RF06 | Disponibilizar consulta à taxa de custódia da B3 e taxa de administração da instituição financeira. | IT6 |  |  |
| RF07 | Incluir um simulador para ajudar o usuário a encontrar títulos adequados ao perfil dele. | IT7 |  |  |
| RF08 | Permitir a consulta de operações realizadas e agendadas. | IT8 |  |  |
| RF09 | Oferecer a funcionalidade de “Fale Conosco”. | IT9 |  |  |
| RF10 | Permitir a visualização de notificações recebidas. | IT10 |  |  |
| RF11 | Incluir funcionalidades sobre o aplicativo (avaliar, indicar para um amigo ou limpar cache). | IT11, GF05 |  |  |
| RF12 | Permitir a visualização de dados do usuário. | IT12 |  |  |
| RF13 | Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos. | IT13, GLO07 |  |  |
| RF14 | Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos. | IT14 |  |  |
| RF15 | Incluir relatórios personalizados para análise detalhada de rentabilidade e evolução de investimentos. | IT15 |  |  |
| RF16 | Disponibilizar um recurso educativo com vídeos e artigos sobre como investir no Tesouro Direto. | IT16, BF10 |  |  |
| RF17 | Oferecer integração com carteiras digitais para pagamento direto de investimentos. | IT17 |  |  |
| RF18 | Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação. | IT18 |  |  |
| RF19 | Adicionar gamificação, como conquistas ou recompensas simbólicas ao atingir metas financeiras. | IT19 |  |  |
| RF20 | O aplicativo deve permitir que o usuário faça uma autodeclaração de expertise (novo, médio, experiente). | BF1 |  |  |
| RF21 | O aplicativo deve oferecer um tutorial para guiar o usuário no uso das funcionalidades. | BF2 |  |  |
| RF22 | O sistema deve disponibilizar um maior leque de opções para simulações financeiras. | BF3, GF03 |  |  |
| RF23 | O aplicativo deve exibir a liquidez dos títulos do Tesouro Nacional na simulação. | BF4 |  |  |
| RF24 | O sistema deve permitir a comparação de títulos de diferentes origens na simulação. | BF5, GF04 |  |  |
| RF25 | O sistema deve integrar a funcionalidade de simulação com a aba "Meus Sonhos". | BF7 |  |  |
| RF26 | O aplicativo deve apresentar um dashboard inicial com informações relevantes para o usuário. | BF10 |  |  |
| RF27 | O sistema deve incluir uma barra de progresso na aba "Meus Sonhos". | BF12 |  |  |
| RF28 | O aplicativo deve permitir a comparação da simulação com os padrões do INSS na aposentadoria. | BF14 |  |  |
| RF29 | O sistema deve exibir sugestões personalizadas na página inicial do "Meu Investimento". | BF15 |  |  |
| RF30 | O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis, incluindo suas características principais. | GLO01 |  |  |
| RF31 | O sistema deve possibilitar a compra de títulos públicos por meio de diferentes métodos de pagamento, garantindo segurança na transação. | GLO02 |  |  |
| RF32 | O sistema deve exibir a rentabilidade acumulada de cada título na carteira do usuário, de forma clara e atualizada. | GLO03 |  |  |
| RF33 | O aplicativo deverá permitir que o usuário faça login criando uma conta própria no sistema | GF02 | |
| RF34 | O aplicativo deverá possuir uma tela de login integrado com o gov.br | GF01 | |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>


### Não Funcionais

<div>
<font size="3"><p style="text-align: center"> Tabela 3 - Requisitos Não Funcionais </a></font></p>
</div>

| Identificador | Descrição	| ID | Priorização |
|---------------|-----------|-----|-------------|
| RNF01 | O sistema deve ter tempo de resposta inferior a 2 segundos para consultas básicas. | IT20 |  |
| RNF02 | Garantir a segurança dos dados sensíveis do usuário conforme a LGPD. | IT21, GF06 |  |
| RNF03 | O aplicativo deve ser responsivo para dispositivos móveis e tablets. | IT22, GF07, GLO08 |  |
| RNF04 | A interface deve ser intuitiva e seguir as diretrizes de acessibilidade. | IT23, BFN11, GF08, GLO04 |  |
| RNF05 | O sistema deve permitir integrações seguras com APIs de instituições financeiras. | IT24, GLO06 |  |
| RNF06 | Disponibilizar suporte para múltiplos idiomas (português como padrão). | IT25 |  |
| RNF07 | O sistema deve oferecer controle ampliado para simulações de aposentadoria. | BFN6 |  |
| RNF08 | O perfil de recomendação de investimentos deve ser mais visível e acessível no aplicativo. | BFN9 |  |
| RNF09 | O aplicativo deve incluir uma opção de tema escuro para melhorar a experiência do usuário. | BFN13 |  |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>



## Referências Bibliográficas

> REQUISTOS DE SOFTWARE. In our Out. Disponível em: https://requisitos-de-software.github.io/2022.2-Grasshopper/elicitacao/priorizacao/in-or-out/. Acesso em: 21 nov. 2024.
>


## Histórico de Versões

| Versão | Data       | Descrição | Autor     |       Revisor         |
| ------ | ---------- | --------- | --------- | --------------------- |
| `1.0`  | 21/11/2024 | Lista de requisitos | [Víctor Rodrigues](https://github.com/ViictorHugoo) | [Thales Euflauzino](https://github.com/thaleseuflauzino) |
| `1.1`  | 21/11/2024 | Inclusão de Introdução e Metodologia | [Víctor Rodrigues](https://github.com/ViictorHugoo) |  |
