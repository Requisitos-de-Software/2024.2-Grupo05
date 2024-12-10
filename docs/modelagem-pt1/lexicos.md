## Introdução

O Léxico é uma notação que, por meio da descrição de termos, tem como objetivo descrever os símbolos de uma linguagem. No entanto, seu principal objetivo na Engenharia de Requisitos é o reconhecimento de palavras ou frases peculiares ao contexto social aplicado no estudo. Cada símbolo possui sua noção e seu impacto. Noção é o que o símbolo denota, já impacto é a conotação de um símbolos, ou seja, o efeito real que ele causa quando executado. O responsável pela criação dos léxicos foi o integrante: [Thales Euflauzino](https://github.com/thaleseuflauzino).

## Metodologia

Para a confecção dos léxicos, utilizamos a notação do Léxico Ampliado da Linguagem (LAL)<a id="anchor_1" href="#REF1"><sup>1</sup></a>, com os conceitos explicitados na Tabela 1, já o template utilizado está presente na Tabela 2:
<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Léxicos do tipo LAL</p></font>

| Tipo do símbolo <br> (Sujeito) | Noção <br> (Quem é o sujeito?) | Impacto<br>(Quais ações executa?) |
|-----------------|-------|-------|
| Verbo | Quem realiza, quando acontece e quais os procedimentos envolvidos | Quais os reflexos das ações no ambiente (outras ações que devem ocorrer) e quais os novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que significa e quais ações levaram a esse estado | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve  |

<font size="2"><p style="text-align: center">Fonte: SERRANO, Maurício e SERRANO, Milene<a id="anchor_1" href="#REF1"><sup>1</sup></a>.</p></font>

<br>

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Template Léxicos</p></font>
<center>

| ID | Descrição |
|-----------------|-------|
| Descrição | Explicação do que é o léxico e/ou o contexto em que ele é usado |
| Classificação | Verbo/Objeto/Estado |
| Noção | Símbolo |
| Impacto | Descrição de ações e de seus efeitos |
| Dicionário | Sinônimos |

</center>
<font size="2"><p style="text-align: center">Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024</p></font>

_Legenda das Tabelas:_

- RFx: Requisito Funcional número x;
- RNFx: Requisito Não Funcional número x;
- ITx: Requisito da Introspecção número x;
- BFx: Requisito Funcional do Brainstorm número x;
- BFNx: Requisito Não Funcional do Brainstorm número x;
- GFx: Requisito do Grupo de Foco número x;
- GLOx: Requisito do Glossário número x;
<br><br>

# Léxicos

## <a id="anchor_L01" style="visibility: hidden"></a>Léxico 01: Simular Investimentos

O primerio léxico, apresentado na Tabela 2, faz o uso dos seguintes requisitos:

- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF02">IT2</a>** - Permitir a simulação, realização e visualização de detalhes de investimentos nos títulos SELIC, Prefixado e Inflação.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF07">IT7</a>** - Incluir um simulador para ajudar o usuário a encontrar títulos adequados ao perfil dele.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF22">BF3, GF03</a>** - O sistema deve disponibilizar um maior leque de opções para simulações financeiras.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF30">GLO01</a>** - O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis, incluindo suas características principais.
<center>

**Tabela 2 - Léxico de Verbo: Simular Investimentos (L01)**
</center>

| **Identificador** | **L01** |
|--------------------|---------|
| **Descrição**      | Os títulos disponíveis são listados após a simulação  |
| **Classificação**  | Verbo |
| **Impacto**        | O <a href="#anchor_L02">investidor/interessado</a> está interessado em simular um investimento.<br>O <a href="#anchor_L02">investidor/interessado</a> escolhe o que quer conquistar, o tempo de investimento e a prioridade (quanto vai ganhar ou preservar o poder de compra).<br>O <a href="#anchor_L02">investidor/interessado</a> realiza a simulação baseada nas escolhas feitas anteriormente. |
| **Noção**          | Calcular projeções, definir metas e avaliar possibilidades. |
| **Dicionário**     | Calcular projeções, definir metas e avaliar possibilidades. |

<font size="2"><p style="text-align: center">Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024</p></font>

---
## <a id="anchor_L02" style="visibility: hidden"></a>Léxico 02: Investidor

O segundo léxico, apresentado na Tabela 3, faz o uso dos seguintes requisitos: 

- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF01">IT1</a>**- Permitir a consulta de investimentos por instituição financeira.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF02">IT2</a>** - Permitir a simulação, realização e visualização de detalhes de investimentos.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF08">IT8</a>** - Permitir a consulta de operações realizadas e agendadas.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF12">IT12</a>** - Permitir a visualização de dados do usuário.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF13">IT13, GLO07</a>** - Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF14">IT14</a>** - Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos.
<center>

**Tabela 3 - Léxico de Objeto: Investidor (L02)**
</center>

| **Identificador** | **L02** |
|--------------------|---------|
| **Descrição**      | O investidor pode realizar simulações de investimento (<a href="#anchor_L01">L01</a>).<br>O investidor pode escolher títulos com base em suas metas financeiras.<br>O investidor pode consultar o histórico de rendimentos de seus investimentos.<br>O investidor pode configurar alertas e notificações sobre títulos de interesse.<br>O investidor pode atualizar suas metas financeiras a qualquer momento. |
| **Classificação**  | Objeto |
| **Impacto**        | O investidor é o <a href="#anchor_L02">usuário</a> principal do aplicativo Tesouro Direto.<br>O investidor pode ser alguém buscando preservar o poder de compra.<br>O investidor pode ser alguém interessado em aumentar seu patrimônio financeiro.<br>O sistema auxilia o investidor a tomar decisões informadas, sugerindo opções adequadas às suas escolhas. |
| **Noção**          | Cliente, Interessado, Aplicador e Cidadão. |
| **Dicionário**     | Cliente, Interessado, Aplicador e Cidadão. |

<font size="2"><p style="text-align: center">Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024</p></font>

---
## <a id="anchor_L03" style="visibility: hidden"></a>Léxico 03: Filtros de Tesouros

O terceiro léxico, apresentado na Tabela 4, faz o uso dos seguintes requisitos: 

- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF02">IT2</a>** - Permitir a simulação, realização e visualização de detalhes de investimentos nos títulos SELIC, Prefixado e Inflação.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF24">BF5, GF04</a>** - O sistema deve permitir a comparação de títulos de diferentes origens na simulação.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF30">GLO01</a>** - O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis, incluindo suas características principais.
  
<center>

**Tabela 4 - Léxico de Estados: Filtros de Tesouros (L03)**
</center>

| **Identificador** | **L03** |
|--------------------|---------|
| **Descrição**      | Exibe os títulos disponíveis de acordo com o tipo de filtro selecionado pelo investidor/interessado.<br>Facilita a busca ao permitir a segmentação por categorias: Selic, Prefixado e Inflação. |
| **Classificação**  | Estado |
| **Impacto**        | O tipo de título é categorizado pelo sistema com base nos parâmetros financeiros.<br>O aplicativo permite ao <a href="#anchor_L02">investidor/interessado</a> aplicar filtros para encontrar títulos específicos. |
| **Noção**          | Títulos Selic, Títulos Prefixados, Títulos de Inflação. |
| **Dicionário**     | Títulos Selic, Títulos Prefixados, Títulos de Inflação. |

<font size="2"><p style="text-align: center">Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024</p></font>

---

## <a id="anchor_L04" style="visibility: hidden"></a>Léxico 04: Relatórios Personalizados

O quarto léxico, apresentado na Tabela 5, faz o uso dos seguintes requisitos:

- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF15">IT15</a>** - Incluir relatórios personalizados para análise detalhada de rentabilidade e evolução de investimentos.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF22">BF3, GF03</a>** - O sistema deve disponibilizar um maior leque de opções para simulações financeiras.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF30">GLO01</a>** - O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis, incluindo suas características principais.

---
<center>

**Tabela 5 - Léxico de Verbo: Relatórios Personalizados (L04)**
</center>

| **Identificador** | **L04** |
|--------------------|---------|
| **Descrição**      | Ferramenta que permite a geração de relatórios detalhados sobre rentabilidade, evolução patrimonial e simulações financeiras realizadas. |
| **Classificação**  | Verbo |
| **Impacto**        | O sistema gera relatórios específicos com base nas simulações financeiras realizadas e nos dados de investimentos.<br>Os relatórios podem ser usados pelo <a href="#anchor_L02">investidor/interessado</a> para planejar novas estratégias financeiras. |
| **Noção**          | Ferramenta de análise de dados financeiros. |
| **Dicionário**     | Relatório de Rentabilidade, Relatório de Evolução Patrimonial, Relatórios de Simulação. |

<font size="2"><p style="text-align: center">Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024</p></font>


---
## <a id="anchor_L05" style="visibility: hidden"></a>Léxico 05: Investidor ou Interessado

O quinto, e último, léxico, apresentado na Tabela 6, faz o uso dos seguintes requisitos: 

- **[IT1](../../elicitacao/grupo5/requisitos/#anchor_RF01)** - Permitir a consulta de investimentos por instituição financeira.
- **[IT2](../../elicitacao/grupo5/requisitos/#anchor_RF02)** - Permitir a simulação, realização e visualização de detalhes de investimentos.
- **[IT8](../../elicitacao/grupo5/requisitos/#anchor_RF08)** - Permitir a consulta de operações realizadas e agendadas.
- **[IT12](../../elicitacao/grupo5/requisitos/#anchor_RF12)** - Permitir a visualização de dados do usuário.
- **[IT13, GLO07](../../elicitacao/grupo5/requisitos/#anchor_RF13)** - Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos.
- **[IT14](../../elicitacao/grupo5/requisitos/#anchor_RF14)** - Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos.
- **<a href="../../elicitacao/grupo5/requisitos/#anchor_RF18">IT18</a>** - Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação.
- **[GF01](../../elicitacao/grupo5/requisitos/#anchor_RF34)** - O aplicativo deverá possuir uma tela de login integrado com o [gov.br](https://www.gov.br).

<center>

**Tabela 6 - Léxico de Objeto: Investidor ou Interessado (L05)**
</center>

| **Identificador** | **L05** |
|-------------------|---------|
| **Descrição**     | O investidor pode gerar relatórios personalizados (<a href="#anchor_L04">L04</a>).<br>O investidor pode consultar dados de sua conta e histórico de investimentos.<br>O investidor pode consultar o histórico de rendimentos de seus investimentos.(<a href="#anchor_L02">L02</a>)<br>O investidor pode configurar alertas personalizados sobre metas financeiras.<br>O investidor pode realizar transferências automáticas entre investimentos com base em objetivos definidos.<br>O investidor/interessado pode realizar simulações de investimento com base em seus objetivos financeiros (<a href="#anchor_L01">L01</a>, <a href="#anchor_L03">L03</a>).<br>O sistema permite login integrado com o [gov.br](https://www.gov.br). |
| **Classificação** | Objeto |
| **Impacto**       | O investidor/interessado interage diretamente com as principais funcionalidades do aplicativo.<br>O sistema auxilia na tomada de decisões financeiras com base nas preferências e metas do investidor/interessado.<br>Permite a personalização de notificações e metas financeiras. |
| **Noção**         | Cliente, Explorador, Aplicador, Cidadão. |
| **Dicionário**    | Cliente, Explorador, Aplicador, Cidadão. |

<font size="2"><p style="text-align: center">Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024</p></font>

## Bibliografia
> Bilheteria Digital - Léxicos. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/>. Acesso em 28 de novembro de 2024
>
## Referências Bibliográficas
> <a id="REF1" href="#anchor_1">1.</a> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. **Aprender 3**. Distrito Federal, 2016. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>>. Acesso em: 28 de novembro de 2024.
> 


## Histórico de Versões

| Versão | Data       | Descrição                                    | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 28/11/2024 | Criação dos léxicos.                       | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Maria Helena](https://github.com/MariaCHelena) |
| `1.1`    | 07/12/2024 | Corrigindo Fonte para Autor | [Thales Euflauzino](https://github.com/thaleseuflauzino)   | [Víctor Schmidt](https://github.com/moonshinerd) |
| `1.2`    | 10/12/2024 | Ajustando rastreabilidade e hyperlinks |  [Víctor Schmidt](https://github.com/moonshinerd) | [Thales Euflauzino](https://github.com/thaleseuflauzino)   |
| `1.3`    | 10/12/2024 | Ajustando usuário para investidor |   [Thales Euflauzino](https://github.com/thaleseuflauzino)   | [Víctor Schmidt](https://github.com/moonshinerd) |
