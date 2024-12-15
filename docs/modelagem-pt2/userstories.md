# Histórias de Usuário

## Introdução

Histórias de usuários são usadas para capturar as necessidades e expectativas dos usuários finais de forma clara, simples e centrada no valor que será entregue. Elas são descrições breves que comunicam o que um usuário deseja alcançar ao interagir com o sistema.

## Metodologia

Para realizar a criação das histórias de usuário, foi utilizado o seguinte modelo estabelecido pelo SWEBOK <a href="REF1">[1]</a>:

"Como [tipo de usuário], eu quero [ação ou necessidade], para que [benefício ou propósito].".

Não somente isso, mas tendo como base o modelo de documentação de histórias de usuário definido pelo ministério da agricultura e pecuária <a href="REF2">[2]</a>, as histórias de usuário serão definidas com base no modelo descrito na tabela 1:

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td>Exemplo de história 1</td>
          <td>Épico 1</td>
          <td>
            <ol>
              <li>Critério 1</li>
              <li>Critério 2</li>
            </ol>
          </td>
          <td>Alta</td>
          <td>001</td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: [Maria Helena](https://github.com/MariaCHelena), 2024</p></font>

## Histórias de Usuário

### US01 - Visualizar a lista de títulos públicos disponíveis

<details>
<summary>Tabela 2 - US01 - Visualizar a lista de títulos públicos disponíveis</summary>
<font size="2"><p style="text-align: center"><bol>Tabela 2</bol> - História de Usuário Visualizar a lista de títulos públicos disponíveis</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> Eu, como usuário, desejo visualizar a lista de títulos públicos disponíveis e suas características principais como nome, título, rentabilidade, valor mínimo e vencimento para conhecer mais sobre os títulos e realizar investimentos. </td>
          <td> <a href="../backlog/#ec01-visualizacao-de-titulos-publicos">EC01</a> - Visualização de Títulos Públicos </td>
          <td>
            <ol>
              <li> Os Títulos deverão ser exibidos de ordem do mais recente para o mais antigo </li>
              <li> Os títulos devem ser agrupados de acordo com o seu tipo, ou seja, agrupados por títulos vinculados a Selic, vinculados à inflação e pré-fixados. </li>
            </ol>
          </td>
          <td> Alta </td>
          <td> US01 </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### US02 - 	Simulação de investimento nos títulos

<details>
<summary>Tabela 3 - US02 - 	Simulação de investimento nos títulos SELIC, Prefixado e Inflação.</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - História de Usuário Simulação de investimento nos títulos SELIC, Prefixado e Inflação.</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> Eu, como usuário, desejo realizar a simulação da evolução do meu título para planejar os meus investimentos. </td>
          <td> <a href="../backlog/#ec03-simulacoes-de-investimentos">EC03</a> - Simulações de investimentos </td>
          <td>
            <ol>
              <li> A simulação deverá estar disponível para todos os títulos listados no aplicativo </li>
            </ol>
          </td>
          <td> Alta </td>
          <td> US02 </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### US03 - Resgate antecipado de títulos

<details>
<summary>Tabela 4 - US03 - Resgate antecipado de títulos</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - História de Usuário Resgate antecipado de títulos</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> Eu, como usuário, desejo realizar o resgate antecipado dos títulos, para obter imediatamente o valor investido nesse título. </td>
          <td> <a href="../backlog/#ec07-processo-de-compra-de-titulos">EC07</a> - Processo de Compra de Títulos </td>
          <td>
            <ol>
              <li> O cálculo do valor líquido que será obtido no resgate deverá ser realizado automaticamente com base na data de resgate e rentabilidade acumulada </li>
              <li> O resgate antecipado deve estar disponível em todos os títulos do aplicativo </li>
            </ol>
          </td>
          <td> Alta </td>
          <td> US03 </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### US04 - Salvar metas de investimentos (Sonhos).

<details>
<summary>Tabela 5 - US04 - Salvar metas de investimentos (Sonhos)</summary>
<font size="2"><p style="text-align: center"><b>Tabela 5</b> - História de Usuário Salvar metas de investimentos (Sonhos)</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> Eu, como usuário, desejo salvar as minhas metas de investimento no aplicativo. </td>
          <td> <a href="../backlog/#ec09-personalizacao-de-metas-e-planejamento-financeiro">EC09</a> - Personalização de Metas e Planejamento Financeiro </td>
          <td>
            <ol>
              <li> O usuário deve poder criar quantas metas quiser </li>
              <li> O usuário deve ser capaz de customizar as metas definindo um nome para a meta e quantidade de dinheiro que deseja investir </li>
            </ol>
          </td>
          <td> Baixa </td>
          <td> US04 </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### US05 - Simulação e planejamento de aposentadoria

<details>
<summary>Tabela 6 - US05 - Simulação e planejamento de aposentadoria</summary>
<font size="2"><p style="text-align: center"><b>Tabela 6</b> - História de Usuário Simulação e planejamento de aposentadoria</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> Eu, como usuário, desejo realizar a simulação e o planejamento financeiro da minha aposentadoria para obter esses dados com base nos títulos do tesouro nacional </td>
          <td> <a href="../backlog/#ec10-simuladores-avancados">EC10</a> - Simuladores Avançados </td>
          <td>
            <ol>
              <li> Para realizar a simulação o usuário deve indicar o ano esperado de aposentadoria </li>
              <li> A simulação de aposentadoria deve estar disponível para todos os títulos públicos </li>
            </ol>
          </td>
          <td> Alta </td>
          <td> US05 </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### US06 - Consulta à taxa de custódia da B3 e taxa de administração da instituição financeira.

<details>
<summary>Tabela 7 - US06 - Consulta à taxa de custódia da B3 e taxa de administração da instituição financeira.</summary>
<font size="2"><p style="text-align: center"><b>Tabela 7</b> História de Usuário Consulta à taxa de custódia da B3 e taxa de administração da instituição financeira</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> Eu, como usuário, desejo realizar a consulta à taxa de custódia da B3 e a taxa de administração da instituição financeira na qual o título será adquirido, para entender os custos relacionados ao meu investimento de interesse </td>
          <td> <a href="../backlog/#ec04-painel-de-controle-e-relatorios">EC04</a> - Painel de Controle e Relatórios </td>
          <td>
            <ol>
              <li> Deve estar disponível as taxas administrativas de todas as instituições vinculadas ao aplicativo do tesouro direto. </li>
            </ol>
          </td>
          <td> Alta </td>
          <td> US06 </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### US07 - Consulta de operações de compra realizadas e agendadas

<details>
<summary>Tabela 8 - US07 - Consulta de operações de compra realizadas e agendadas</summary>
<font size="2"><p style="text-align: center"><b>Tabela 8</b> - História de Usuário Consulta de operações de compra realizadas e agendadas</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> Eu, como usuário, desejo realizar a consulta de compras realizadas e agendadas na aplicação para me atualizar da situação dos meus investimentos. </td>
          <td> <a href="../backlog/#ec07-processo-de-compra-de-titulos">EC07</a> - Processo de Compra de Títulos - Processo de Compra de Títulos </td>
          <td>
            <ol>
              <li> Todos os títulos que foram adiquiridos através do aplicativo deverão exibir o seu status de compra </li>
            </ol>
          </td>
          <td> Alta </td>
          <td> US07 </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### US08 - O aplicativo deverá possuir uma tela intitulada “Fale Conosco” com informações de contato e perguntas frequentes dos usuários.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US09 - Permitir a visualização dos dados cadastrais do usuário (nome, cpf, email, celular).

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US10 - Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US11 - Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US12 - O sistema deve fornecer relatórios mensais contendo a evolução dos rendimentos dos títulos adquiridos pelo usuário com base nos meses anteriores.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US13 - Disponibilizar um recurso educativo com vídeos e artigos sobre como investir no Tesouro Direto.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US14 - Oferecer integração com carteiras digitais de outros bancos digitais para pagamento direto de investimentos. Atualmente as instituições financeiras integradas são “INTER DTVM LTDA”, “NU INVEST CORRETORA DE VALORES S.A” e “XP INVESTIMENTOS CCTVM S/A”

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US15 - Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US16 - O aplicativo deve permitir que o usuário faça uma autodeclaração de expertise (novo, médio, experiente) durante o seu cadastro no sistema.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US17 - O aplicativo deve oferecer um tutorial para guiar o usuário no uso das funcionalidades.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US18 - O aplicativo deve exibir a liquidez dos títulos do Tesouro Nacional na simulação.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US19 - O sistema deverá disponibilizar uma ferramenta para simular a evolução do investimento em um título do tesouro nacional em comparação com outras opções de investimento como a poupança, LCI (Letra de Crédito Imobiliário) e LCA (Letra de Crédito do Agronegócio), Fundo de Renda Fixa Referenciado ID e CDB (Certificado de Depósito Bancário).

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US20 - A tela de metas e sonhos deverá ser capaz de simular a evolução das metas

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US21 - O aplicativo deve apresentar um dashboard com dados de rentabilidade dos títulos adquiridos e taxa de inflação.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US22 - O sistema deve incluir uma barra de progresso na aba "Meus Sonhos".

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US23 - O aplicativo deve permitir a comparação da simulação com os padrões do INSS na aposentadoria.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US24 - O sistema deve exibir sugestões personalizadas com base na expertise declarada pelo usuário na página inicial do "Meu Investimento".

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US25 - O sistema deve possibilitar a compra de títulos públicos por meio de diferentes métodos de pagamento.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US26 - O sistema deve exibir a rentabilidade acumulada de cada título na carteira do usuário.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US27 - O aplicativo deverá permitir que o usuário faça cadastro na aplicação criando uma conta própria no sistema.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US28 - O aplicativo deverá possuir a opção de realizar o login e cadastro a partir do sistema gov.br

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US29 - Escolher meus investimentos, definir um valor para cada investimento e escolher entre investir agora ou investir depois

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US30 - O sistema deverá armazenar (preço unitário, rentabilidade, valor mínimo para investir, data de vencimento do título, pagamento de juros, taxa da BR, imposto de renda previsto sobre o rendimento, taxa de IOF) bem como informações a respeito do horário de funcionamento do mercado e tempo de liquidação dos juros.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US31 - O sistema deverá possuir um simulador da evolução de um título do tesouro direto com base em um determinado período de tempo

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US32 - O simulador deverá possuir um questionário para obter do usuário as informações necessárias para gerar o simulador.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US33 - O simulador deverá possuir as informações de: título do tesouro nacional que será usado, tempo de investimento e valor que será resgatado no futuro ou valor que será investido agora.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US34 - Cada meta deve possuir uma barra de progresso representando o progresso individual de conclusão da meta.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

### US35 - As contas cadastradas na aplicação deverão possuir os dados de nome, cpf, email e celular do dono da conta.

<details>
<summary>Tabela 4 - US03</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - Template Histórias de Usuário</p></font>
<table border="1">
  <thead>
      <tr>
          <th>História de Usuário</th>
          <th>Épico</th>
          <th>Critérios de Aceitação</th>
          <th>Prioridade</th>
          <th>ID</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td> - </td>
          <td> - </td>
          <td>
            <ol>
              <li> - </li>
              <li> - </li>
            </ol>
          </td>
          <td> - </td>
          <td> - </td>
      </tr>
  </tbody>
</table>
<font size="2"><p style="text-align: center">Autor: <a href=""> - </a>, 2024</p></font>
</details>

## Referência Bibliográfica
> <span id="REF1">1.</span> Washizaki, Hironori. Guide to the Software Engineering Body of Knowledge, Version 4.0. SWEBOK. IEEE Computer Society, 2024. Disponível em: https://www.computer.org/education/bodies-of-knowledge/software-engineering. p. 54.
>
> <span id="REF1">1.</span> BRASIL. História de usuário. Disponível em: https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view. Acesso em: 14 dez. 2024.

## Bibliografia

> 1. Bilheteria Digital - Histórias de Usuário. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/introspeccao/>. Acesso em 14 de dezembro de 2024
>
> 2. SERRANO, Milene; SERRANO, Mauricio. Requisitos - Aula 15. Apresentação de slides. FCTE (Faculdade de Ciências e Tecnologias em Engenharia): UnB, s.d.. Acesso em: 11 de dezembro 2024.


## Histórico de Versões

| Versão | Data       | Descrição | Autor     |       Revisor         |
| ------ | ---------- | --------- | --------- | --------------------- |
| `1.0`  | 13/12/2024 | Criação do documento | [Maria Helena](https://github.com/MariaCHelena) |  |