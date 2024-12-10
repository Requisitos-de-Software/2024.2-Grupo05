# Requisitos Elicitados

## Introdução 

Esta página reúne todos os requisitos elicitados pela equipe do projeto. As técnicas utilizadas foram [brainstorming](./brainstorm.md), [glossário](./glossario.md), [grupo de foco](./grupo-de-foco.md) e [introspecção](./introspeccao.md).

## Requisitos

Os requisitos foram organizados em duas tabelas: a Tabela 1 apresenta os Requisitos Funcionais, enquanto a Tabela 2 lista os Requisitos Não Funcionais.

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
<font size="3"><p style="text-align: center"> Tabela 1 - Requisitos Funcionais </a></font></p>
</div>


| Identificador | Descrição	| ID | Implementado |
|---------------|-----------|-----|-------------|
| <a id="anchor_RF01" style="visibility: hidden"></a>RF01 | Permitir a consulta de investimentos por instituição financeira. | IT1 | Sim |  
| <a id="anchor_RF02" style="visibility: hidden"></a>RF02 | Permitir a simulação, realização e visualização de detalhes de investimentos nos títulos SELIC, Prefixado e Inflação. | IT2 | Sim |  
| <a id="anchor_RF03" style="visibility: hidden"></a>RF03 | O sistema deve permitir o resgate antecipado de títulos, com cálculo automático do valor líquido baseado na data de resgate e na rentabilidade acumulada. | IT3, GLO07 | Sim |  
| <a id="anchor_RF04" style="visibility: hidden"></a>RF04 | Oferecer funcionalidade para salvar metas de investimentos (Sonhos). | IT4 | Sim |  
| <a id="anchor_RF05" style="visibility: hidden"></a>RF05 | Permitir simulação e planejamento de aposentadoria indicando o ano esperado de aposentadoria. | IT5 | Sim |  
| <a id="anchor_RF06" style="visibility: hidden"></a>RF06 | Disponibilizar consulta à taxa de custódia da B3 e taxa de administração da instituição financeira. | IT6 | Sim |  
| <a id="anchor_RF07" style="visibility: hidden"></a>RF07 | Incluir um simulador para ajudar o usuário a encontrar títulos adequados ao perfil dele. | IT7 | Sim |  
| <a id="anchor_RF08" style="visibility: hidden"></a>RF08 | Permitir a consulta de operações realizadas e agendadas. | IT8 | Sim |  
| <a id="anchor_RF09" style="visibility: hidden"></a>RF09 | Oferecer a funcionalidade de “Fale Conosco”. | IT9 | Sim |  
| <a id="anchor_RF10" style="visibility: hidden"></a>RF10 | Permitir a visualização de notificações recebidas. | IT10 | Sim |  
| <a id="anchor_RF11" style="visibility: hidden"></a>RF11 | Incluir funcionalidades sobre o aplicativo (avaliar, indicar para um amigo ou limpar cache). | IT11, GF05 | Sim |  
| <a id="anchor_RF12" style="visibility: hidden"></a>RF12 | Permitir a visualização de dados do usuário. | IT12 | Sim |  
| <a id="anchor_RF13" style="visibility: hidden"></a>RF13 | Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos. | IT13, GLO07 | Não |  
| <a id="anchor_RF14" style="visibility: hidden"></a>RF14 | Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos. | IT14 | Não |  
| <a id="anchor_RF15" style="visibility: hidden"></a>RF15 | Incluir relatórios personalizados para análise detalhada de rentabilidade e evolução de investimentos. | IT15 | Não |  
| <a id="anchor_RF16" style="visibility: hidden"></a>RF16 | Disponibilizar um recurso educativo com vídeos e artigos sobre como investir no Tesouro Direto. | IT16, BF10 | Não |  
| <a id="anchor_RF17" style="visibility: hidden"></a>RF17 | Oferecer integração com carteiras digitais para pagamento direto de investimentos. | IT17 | Não |  
| <a id="anchor_RF18" style="visibility: hidden"></a>RF18 | Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação. | IT18 | Não |  
| <a id="anchor_RF19" style="visibility: hidden"></a>RF19 | Adicionar gamificação, como conquistas ou recompensas simbólicas ao atingir metas financeiras. | IT19 | Não |  
| <a id="anchor_RF20" style="visibility: hidden"></a>RF20 | O aplicativo deve permitir que o usuário faça uma autodeclaração de expertise (novo, médio, experiente). | BF1 | Não |  
| <a id="anchor_RF21" style="visibility: hidden"></a>RF21 | O aplicativo deve oferecer um tutorial para guiar o usuário no uso das funcionalidades. | BF2 | Não |  
| <a id="anchor_RF22" style="visibility: hidden"></a>RF22 | O sistema deve disponibilizar um maior leque de opções para simulações financeiras. | BF3, GF03 | Não |  
| <a id="anchor_RF23" style="visibility: hidden"></a>RF23 | O aplicativo deve exibir a liquidez dos títulos do Tesouro Nacional na simulação. | BF4 | Não |  
| <a id="anchor_RF24" style="visibility: hidden"></a>RF24 | O sistema deve permitir a comparação de títulos de diferentes origens na simulação. | BF5, GF04 | Não |  
| <a id="anchor_RF25" style="visibility: hidden"></a>RF25 | O sistema deve integrar a funcionalidade de simulação com a aba "Meus Sonhos". | BF7 | Não |  
| <a id="anchor_RF26" style="visibility: hidden"></a>RF26 | O aplicativo deve apresentar um dashboard inicial com informações relevantes para o usuário. | BF10 | Não |  
| <a id="anchor_RF27" style="visibility: hidden"></a>RF27 | O sistema deve incluir uma barra de progresso na aba "Meus Sonhos". | BF12 | Não |  
| <a id="anchor_RF28" style="visibility: hidden"></a>RF28 | O aplicativo deve permitir a comparação da simulação com os padrões do INSS na aposentadoria. | BF14 | Não |  
| <a id="anchor_RF29" style="visibility: hidden"></a>RF29 | O sistema deve exibir sugestões personalizadas na página inicial do "Meu Investimento". | BF15 | Não |  
| <a id="anchor_RF30" style="visibility: hidden"></a>RF30 | O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis, incluindo suas características principais. | GLO01 | Sim |  
| <a id="anchor_RF31" style="visibility: hidden"></a>RF31 | O sistema deve possibilitar a compra de títulos públicos por meio de diferentes métodos de pagamento, garantindo segurança na transação. | GLO02 | Sim |  
| <a id="anchor_RF32" style="visibility: hidden"></a>RF32 | O sistema deve exibir a rentabilidade acumulada de cada título na carteira do usuário, de forma clara e atualizada. | GLO03 | Sim |  
| <a id="anchor_RF33" style="visibility: hidden"></a>RF33 | O aplicativo deverá permitir que o usuário faça login criando uma conta própria no sistema | GF02 | Não |
| <a id="anchor_RF34" style="visibility: hidden"></a>RF34 | O aplicativo deverá possuir uma tela de login integrado com o gov.br | GF01 | Sim |
|<a id="anchor_RF35" style="visibility: hidden"></a>RF35|Escolher meus investimentos, definir um valor para cada investimento e escolher entre investir agora ou investir depois|IT21|Sim|

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>


### Não Funcionais

<div>
<font size="3"><p style="text-align: center"> Tabela 2 - Requisitos Não Funcionais </a></font></p>
</div>

| Identificador | Descrição	| ID | Implementado |
|---------------|-----------|-----|-------------|
| <a id="anchor_RNF01" style="visibility: hidden"></a>RNF01 | O sistema deve ter tempo de resposta inferior a 2 segundos para consultas básicas. | IT20 | Não |
| <a id="anchor_RNF02" style="visibility: hidden"></a>RNF02 | Garantir a segurança dos dados sensíveis do usuário conforme a LGPD. | IT21, GF06 | Sim |
| <a id="anchor_RNF03" style="visibility: hidden"></a>RNF03 | O aplicativo deve ser responsivo para dispositivos móveis e tablets. | IT22, GF07, GLO08 | Sim |
| <a id="anchor_RNF04" style="visibility: hidden"></a>RNF04 | A interface deve ser intuitiva e seguir as diretrizes de acessibilidade. | IT23, BFN11, GF08, GLO04 | Não |
| <a id="anchor_RNF05" style="visibility: hidden"></a>RNF05 | O sistema deve permitir integrações seguras com APIs de instituições financeiras. | IT24, GLO06 | Sim |
| <a id="anchor_RNF06" style="visibility: hidden"></a>RNF06 | Disponibilizar suporte para múltiplos idiomas (português como padrão). | IT25 | Não |
| <a id="anchor_RNF07" style="visibility: hidden"></a>RNF07 | O sistema deve oferecer controle ampliado para simulações de aposentadoria. | BFN6 | Não |
| <a id="anchor_RNF08" style="visibility: hidden"></a>RNF08 | O perfil de recomendação de investimentos deve ser mais visível e acessível no aplicativo. | BFN9 | Não |
| <a id="anchor_RNF09" style="visibility: hidden"></a>RNF09 | O aplicativo deve incluir uma opção de tema escuro para melhorar a experiência do usuário. | BFN13 | Não |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>

## Histórico de Versões

| Versão | Data       | Descrição | Autor     |       Revisor         |
| ------ | ---------- | --------- | --------- | --------------------- |
| `1.0`  | 21/11/2024 | Lista de requisitos | [Víctor Rodrigues](https://github.com/ViictorHugoo) | [Thales Euflauzino](https://github.com/thaleseuflauzino) |
