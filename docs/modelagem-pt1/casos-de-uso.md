# Casos de Uso

## Introdução

Um caso de uso é uma representação detalhada de como o sistema será utilizado em um contexto ou situação específica. Ele descreve as interações entre os usuários e o sistema, destacando os passos necessários para alcançar um objetivo definido. 

Seu principal objetivo é apoiar o desenvolvimento do sistema, proporcionando uma visão clara dos requisitos funcionais. Além disso, os casos de uso especificam as ações que os usuários podem realizar e como o sistema deve responder a essas ações.


## Metodologia
O diagrama de caso de uso é uma ferramenta visual que resume as interações entre os usuários e um sistema, destacando suas funcionalidades e comportamentos principais. Ele é composto por **atores**, que representam os usuários ou outros sistemas que interagem com o sistema em questão, e **casos de uso**, que descrevem as ações realizadas pelos usuários e as respostas do sistema a essas ações.

Para criar casos de uso que atendam melhor às necessidades dos usuários, utilizamos a persona [Gustavo Ribeiro](../../elicitacao/grupo5/personas/#persona1). Essa abordagem ajuda a compreender as expectativas, desejos e desafios enfrentados pelos usuários finais do sistema. A inclusão dessa persona no processo permite modelar cenários realistas de uso, considerando as diferentes metas e necessidades do tipo de usuário que ela representa.

Voltando ao foco nos diagramas de caso de uso, a **Tabela 1** apresenta os principais elementos que compõem o diagrama, oferecendo uma visão clara e estruturada de suas partes fundamentais.

<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Elementos do diagrama de casos de uso</p></font>

| Nome | Função | Elemento
|------|------|:-------:
| Ator | Representam os diversos tipos de usuários externos que interagem com o sistema. | <figure style="width: 80%; display: flex; justify-content: center; background-color: white; padding: 5px;"> ![boneco](../assets/modelagem/casos-de-uso/bonecodepalito.png) </figure>
| Elipse (Caso de Uso) | É utilizada para representar os casos de uso em um diagrama, destacando funcionalidades ou ações específicas que o sistema realiza em resposta às interações dos atores. A elipse identifica cada caso de uso, exibindo o nome correspondente em seu interior. | <figure style="width: 80%; display: flex; justify-content: center; background-color: white; padding: 10px;"> ![elipse](../assets/modelagem/casos-de-uso/elipse.png) </figure>
| Retângulo (Sistema) | É utilizado para representar o sistema ou o componente em análise, agrupando os casos de uso e os atores associados a ele. | <figure style="width: 80%; display: flex; justify-content: center; background-color: white; padding: 10px;"> ![retangulo](../assets/modelagem/casos-de-uso/retangulo.png) </figure>
| Flecha (Relações) | As setas são utilizadas para ilustrar as relações ou interações entre os atores e os casos de uso no diagrama. | <figure style="width: 80%; display: flex; justify-content: center; background-color: white; padding: 10px;"> ![flecha](../assets/modelagem/casos-de-uso/flecha.png) </figure>

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a></b></p></font>

Além disso, no diagrama de casos de uso, é possível detalhar:  

- **Requisitos externos do sistema**: as funcionalidades essenciais que o sistema deve fornecer para atender às demandas e expectativas dos usuários.  
- **Funcionalidades do sistema**: as capacidades que o sistema oferece para satisfazer as necessidades dos usuários de maneira eficaz e eficiente.  
- **Requisitos do sistema em relação ao ambiente**: as condições ou restrições impostas pelo sistema ao ambiente onde está inserido, especificando como ele interage com outros elementos para cumprir suas funções.  

## Diagrama de Casos de Uso

A figura 1 demonstra o diagrama de casos de uso.

<font size="3"><p style="text-align: center">Figura 1: Casos de uso do app Tesouro Direto</p></font>

![Diagrama de Caso de Uso](../assets/modelagem/casos-de-uso/diagrama-de-caso-de-uso.png)

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a></b></p></font>

## Especialização dos casos de uso

As tabelas de 2 a 6 mostram a especialização dos casos de uso.

<font size="3"><p style="text-align: center">Tabela 2: Fazer Login </p></font>
<center>

| UC01 | Informações |
| ----- | ---------- |
| **Descrição**          | Permitir que o investidor ou interessado acesse sua conta no aplicativo.      |
| **Ator**              | Investidor ou Interessado                                                    |
| **Pré-condições**      | O aplicativo deve estar instalado e conectado à internet.   |
| **Ação**               | O Investidor ou Interessado realiza login no aplicativo.                     |
| **Fluxo principal**    | <ul><li>O Investidor ou Interessado acessa a tela inicial do app.</li><li>O Investidor ou Interessado insere suas credenciais (usuário e senha).</li><li>O sistema verifica a senha.</li><li>O Investidor ou Interessado é autenticado e acessa sua conta.</li> |
| **Fluxo alternativo**  | <ul><li>O Investidor ou Interessado acessa a tela inicial.</li><li>O sistema detecta erro de login e exibe mensagem de erro.</li></ul> |
| **Fluxo de exceção**   | <ul><li>O sistema detecta ausência de conexão com a internet.</li><li>Exibe uma mensagem informando que não é possível conectar.</li></ul> |
| **Pós-condições**      | O Investidor ou Interessado é autenticado e pode acessar as funcionalidades do aplicativo. |
| **Rastreabilidade**    | [RF33](../../elicitacao/grupo5/requisitos/#anchor_RF33) e [RF34](../../elicitacao/grupo5/requisitos/#anchor_RF34)                                                |
| **Data de Criação**    | 06/12/2024                                                 |

</center>

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a></b></p></font>


<font size="3"><p style="text-align: center">Tabela 3: Simular Investimento </p></font>
<center>

| UC02 | Informações |
| ----- | ---------- |
| **Descrição**          | Permitir que o Investidor ou Interessado realize simulações de investimento no Tesouro Direto. |
| **Ator**              | Investidor ou Interessado                                                    |
| **Pré-condições**      | O Investidor ou Interessado deve estar autenticado no aplicativo e conectado à internet. |
| **Ação**               | O Investidor ou Interessado simula diferentes cenários de investimento.      |
| **Fluxo principal**    | <ul><li>O Investidor ou Interessado acessa a opção "Simular Investimento".</li><li>O Investidor ou Interessado preenche os dados necessários, como valor e período do investimento.</li><li>O sistema apresenta os resultados da simulação.</li></ul> |
| **Fluxo alternativo**  | <ul><li>O Investidor ou Interessado acessa "Simular Investimento".</li><li>O sistema solicita que o Investidor ou Interessado preencha um questionário para personalizar a simulação.</li><li>O questionário é preenchido, e o sistema apresenta os resultados.</li></ul> |
| **Fluxo de exceção**   | <ul><li>O sistema detecta ausência de conexão com a internet.</li><li>Exibe uma mensagem informando que não é possível realizar a simulação no momento.</li></ul> |
| **Pós-condições**      | O Investidor ou Interessado visualiza as opções de investimento com base na simulação realizada. |
| **Rastreabilidade**    | [RF02](../../elicitacao/grupo5/requisitos/#anchor_RF02)                                                  |
| **Data de Criação**    | 06/12/2024                                                 |

</center>
<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a></b></p></font>
 
<font size="3"><p style="text-align: center">Tabela 4: Escolher Investimentos </p></font>
<center>

| UC03 | Informações |
| ----- | ---------- |
| **Descrição**          | O Investidor escolhe o investimento mais adequado para seus objetivos. |
| **Ator**              | Investidor                                                    |
| **Pré-condições**      | O Investidor deve estar autenticado e conectado à internet.   |
| **Ação**               | O Investidor escolhe um ou mais investimentos disponíveis.    |
| **Fluxo principal**    | <ul><li>O Investidor acessa a opção "Escolher Investimentos".</li><li>O sistema apresenta a lista de investimentos disponíveis e o Investidor seleciona os que lhe interessa.</li><li>O Investidor define o valor a ser investido em cada um e escolhe investir agora ou agendar o investimento.</li></ul> |
| **Fluxo alternativo**  | <ul><li>O sistema sugere opções com base no questionário previamente preenchido.</li></ul> |
| **Fluxo de exceção**   | <ul><li>O sistema detecta problemas na conexão com o servidor.</li><li>Exibe uma mensagem informando que os investimentos não podem ser carregados no momento.</li></ul> |
| **Pós-condições**      | O Investidor realizou o investimento. |
| **Rastreabilidade**    | [RF35](../../elicitacao/grupo5/requisitos/#anchor_RF35)                                                  |
| **Data de Criação**    | 06/12/2024                                                 |

</center>
<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a></b></p></font>

<font size="3"><p style="text-align: center">Tabela 5: Verificar Meus Investimentos </p></font>
<center>

| UC06 | Informações |
| ----- | ---------- |
| **Descrição**          | Permitir que o Investidor visualize e acompanhe os investimentos realizados. |
| **Ator**              | Investidor                                                    |
| **Pré-condições**      | O Investidor deve estar autenticado no aplicativo.            |
| **Ação**               | O Investidor verifica o histórico e status dos investimentos. |
| **Fluxo principal**    | <ul><li>O Investidor acessa "Verificar Meus Investimentos".</li><li>O sistema apresenta uma lista com os investimentos ativos e finalizados.</li></ul> |
| **Fluxo alternativo**  | <ul><li>O sistema apresenta os investimentos organizados por categoria ou instituição financeira.</li></ul> |
| **Fluxo de exceção**   | <ul><li>O sistema detecta problemas de carregamento dos dados.</li><li>Exibe uma mensagem informando que os investimentos não podem ser carregados no momento.</li></ul> |
| **Pós-condições**      | O Investidor visualiza os detalhes de seus investimentos.     |
| **Rastreabilidade**    | [RF01](../../elicitacao/grupo5/requisitos/#anchor_RF01)                                                 |
| **Data de Criação**    | 06/12/2024                                                 |

</center>
<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a></b></p></font>

<font size="3"><p style="text-align: center">Tabela 6: Resgatar Investimento </p></font>
<center>

| UC07 | Informações |
| ----- | ---------- |
| **Descrição**          | Permitir que o Investidor resgate investimentos realizados.   |
| **Ator**              | Investidor                                                    |
| **Pré-condições**      | O Investidor deve estar autenticado e ter investimentos disponíveis para resgate. |
| **Ação**               | O Investidor solicita o resgate de um ou mais investimentos.  |
| **Fluxo principal**    | <ul><li>O Investidor acessa "Resgatar Investimento".</li><li>O Investidor seleciona quais investimentos deseja resgatar.</li><li>O sistema confirma o resgate e processa a solicitação.</li></ul> |
| **Fluxo alternativo**  | <ul><li>O sistema solicita que o Investidor escolha a instituição financeira para crédito dos valores resgatados.</li></ul> |
| **Fluxo de exceção**   | <ul><li>O sistema detecta que o investimento selecionado não pode ser resgatado no momento.</li><li>Exibe uma mensagem com detalhes do motivo.</li></ul> |
| **Pós-condições**      | O resgate é processado e os valores são creditados na conta do Investidor. |
| **Rastreabilidade**    | [RF03](../../elicitacao/grupo5/requisitos/#anchor_RF03)                                                 |
| **Data de Criação**    | 06/12/2024                                                 |

</center>

<font size="2"><p style="text-align: center"><b>Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a></b></p></font>

## Bibliografia

> Lucidchart. Diagrama de Caso de Uso UML. Disponível em: <<https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>>. Acesso em: 14 maio 2023.

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

> HENRIQUE, Paulo. Caso de Uso. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: [https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/casouso/](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/casouso/). Acesso em: 15 mai. 2023.

> MACEDO, Lucas. Caso de uso. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/casos_de_uso/](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/casos_de_uso/). Acesso em: 15 mai. 2023.

> REPOSITÓRIO DE REQUISITOS. *Modelagem - Casos de Uso*. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/>. Acesso em: 6 dez. 2024.



## Histórico de Versões

| Versão | Data       | Descrição                                      | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ---------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`    | 06/12/2024 | Criação da página | [Víctor Schmidt](https://github.com/moonshinerd)   | [Victor Rodrigues](https://github.com/ViictorHugoo) |
| `1.1`    | 07/12/2024 | Corrigindo Fonte para Autor | [Thales Euflauzino](https://github.com/thaleseuflauzino)   | [Víctor Schmidt](https://github.com/moonshinerd) |
| `1.2`    | 07/12/2024 | Corrigindo Fonte para Autor | [Thales Euflauzino](https://github.com/thaleseuflauzino)   | [Víctor Schmidt](https://github.com/moonshinerd) |
| `1.3`    | 10/12/2024 | Alterações e correções | [Víctor Schmidt](https://github.com/moonshinerd)   | [Thales Euflauzino](https://github.com/thaleseuflauzino) |
