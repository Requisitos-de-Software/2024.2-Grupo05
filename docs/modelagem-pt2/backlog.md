# Product Backlog
## Introdução  

O *Product Backlog* do aplicativo do Tesouro Direto será uma lista dinâmica contendo todas as funcionalidades desejadas para o produto. Ele será gerenciado pelo *Product Owner* — um usuário do próprio aplicativo —, garantindo a entrega incremental de valor ao longo do tempo <a id="anchor_1" href="#REF1">[Mauricio e Milene]</a>. Este documento apresenta a metodologia utilizada para a construção e priorização do *Backlog*.  

## Metodologia  

A construção do *Product Backlog* seguirá os passos descritos abaixo:  

1 - **Definição de perguntas:**  

   - [Thales Euflauzino](https://github.com/thaleseuflauzino) será responsável por criar um roteiro de perguntas baseado nas histórias de usuário já existentes. 
   - Esse roteiro servirá para explorar as necessidades e expectativas dos usuários em maior profundidade.  

2 - **Entrevistas com o *Product Owner*:**  

   - [Víctor Schmidt](https://github.com/moonshinerd) realizará entrevistas com o *Product Owner*, utilizando o roteiro elaborado, para coletar informações detalhadas sobre as funcionalidades desejadas.  

3 - **Construção do *Backlog*:**  

   - Com base nas respostas obtidas nas entrevistas, será criado um *backlog* inicial contendo todas as funcionalidades identificadas.  
   - Cada funcionalidade será descrita de forma clara e objetiva, empregando a técnica de histórias de usuário.  

4 - **Priorização do *Backlog*:**  

   - A priorização será feita com base no critério DEEP (<a id="anchor_2" href="#REF2">Duarte, 2020</a>), que considera os seguintes aspectos:  
     - **Detalhado:** As funcionalidades mais próximas de implementação terão descrições mais detalhadas.  
     - **Estimável:** Cada funcionalidade será avaliada quanto ao esforço necessário para sua implementação.  
     - **Emergente:** O *backlog* será atualizado continuamente para refletir novas demandas ou mudanças.  
     - **Priorizado:** As funcionalidades que geram maior valor para o cliente terão prioridade.  

### Definição das Perguntas  

A construção do *Product Backlog* será realizada antes da elaboração das histórias de usuário, permitindo uma visão ampla das funcionalidades e necessidades do produto. O roteiro de perguntas será organizado em tópicos principais, com um link para o documento completo contendo todas as perguntas detalhadas.  

- [Acesse aqui o PDF com as perguntas completas](../assets/modelagem/backlog/Perguntas%20BACKLOG.pdf)  

#### Tópicos Principais  

**Específicas** 

   - Quais tipos de títulos e informações serão exibidos?  
   - Como o aplicativo lidará com diferentes prazos de vencimento?  

**Processo de Compra**  

   - Quais serão as etapas e limites do processo de compra?  
   - Como o aplicativo lidará com agendamentos e pagamentos?  

**Usabilidade**  

   - Haverá recursos de personalização ou suporte educativo?  
   - Como o app ajudará na escolha e acompanhamento de investimentos?  

**Segurança**  

   - Quais medidas serão tomadas para proteger dados e garantir a privacidade?  
   - Como será a autenticação e segurança nas transações?  

**Acessibilidade**  

* O aplicativo terá suporte a leitores de tela e temas acessíveis?  
* Quais outras funcionalidades de acessibilidade serão implementadas?  

## Gravação do Vídeo

## Backlog
### Respostas do _Product Owner_ às Perguntas
- [Acesse aqui o PDF com as respostas completas](../assets/modelagem/backlog/Respostas%20BACKLOG.pdf)  

### Épicos
Para reduzir o nível de abstração presente nos temas e detalhar melhor as funcionalidades, foram registrados os épicos, que representam grandes blocos de trabalho organizados com base nas respostas do Product Owner. Cada épico descreve um objetivo geral que pode ser dividido em tarefas menores, conhecidas como histórias de usuário (user stories) ou simplesmente "histórias".

Os épicos servem como um contêiner para agrupar funcionalidades relacionadas, permitindo uma visão de alto nível do trabalho a ser realizado e facilitando a leitura e o entendimento da tabela de backlog. Após a tabela 1, estão os épicos que foram elaborados com base nas necessidades e requisitos identificados.

### Tabela dos épicos
A tabela 1 resume os épicos, organizando-os em features e os requisitos relacionados. Além disso, o restante deste documento detalha o processo de definição dos temas, épicos e features, bem como o significado de cada um desses termos.

<center>
<table>
<thead>
  <tr>
    <th>Épico</th>
    <th>Feature</th>
    <th>Rastreabilidade</th>
    <th>Priorização</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">
         <a href="#ec01-visualizacao-de-titulos-publicos">EC01 - Visualização de Títulos Públicos</a>
    </td>
    <td rowspan="1">Feature 1 - Listar Títulos</td>
    <td><a href=""> RFXX </a> - Descrição</td>
    <td>-</td>
  </tr>
  <tr>
      <td rowspan="1">Feature 2 - Filtros de Prazo</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
  </tr>

  <tr>
      <td rowspan="2">
         <a href="#ec02-gerenciamento-de-investimentos">EC02 - Gerenciamento de Investimentos</a>
      </td>
      <td rowspan="1">Feature 3 - Agendamento de Compras</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
  </tr>
  <tr>
      <td rowspan="1">Feature 4 - Transferência Automática entre Investimentos</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
  </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec03-simulacoes-de-investimentos">EC03 - Simulações de Investimentos</a>
      </td>
      <td rowspan="1">Feature 5 - Simulação de Metas</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 6 - Dashboard de Metas</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec04-painel-de-controle-e-relatorios">EC04 - Painel de Controle e Relatórios</a>
      </td>
      <td rowspan="1">Feature 7 - Relatórios de Rentabilidade</td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RF15"> RF15 </a> - O sistema deve fornecer relatórios mensais contendo a evolução dos rendimentos dos títulos adquiridos pelo usuário com base nos meses anteriores.</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 8 - Dashboard</td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RF26"> RF26 </a> - O aplicativo deve apresentar um dashboard com dados de rentabilidade dos títulos adquiridos e taxa de inflação.</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="3">
         <a href="#ec05-cadastro-e-personalizacao-de-usuario">EC05 - Cadastro e Personalização de Usuário</a>
      </td>
      <td rowspan="1">Feature 9 - Cadastro de Usuário</td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RF20"> RF20 </a> - O aplicativo deve permitir que o usuário faça uma autodeclaração de expertise (novo, médio, experiente) durante o seu cadastro no sistema.</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 10 - Personalização de Tema</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 11 - Sugestões Personalizadas com Base na Expertise</td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RF29"> RF29 </a> - O sistema deve exibir sugestões personalizadas com base na expertise declarada pelo usuário na página inicial do "Meu Investimento".</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec06-seguranca-e-acessibilidade">EC06 - Segurança e Acessibilidade</a>
      </td>
      <td rowspan="1">Feature 11 - Autenticação Segura</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 12 - Acessibilidade Visual</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec07-processo-de-compra-de-titulos">EC07 - Processo de Compra de Títulos</a>
      </td>
      <td rowspan="1">Feature 13 - Fluxo de Compra</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 14 - Notificações de Status</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec08-recursos-educativos">EC08 - Recursos Educativos</a>
      </td>
      <td rowspan="1">Feature 15 - Artigos e Notícias</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 16 - Víeos e Tutoriais</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="3">
         <a href="#ec09-personalizacao-de-metas-e-planejamento-financeiro">EC09 - Personalização de Metas e Planejamento Financeiro</a>
      </td>
      <td rowspan="1">Feature 17 - Definição de Metas</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="2">Feature 18 - Acompanhamento de Metas</td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RF25"> RF25 </a> - A tela de metas e sonhos deverá ser capaz de simular a evolução das metas</td>
      <td>-</td>
   </tr>
   <tr>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RF40"> RF40 </a> - Cada meta deve possuir uma barra de progresso representando o progresso individual de conclusão da meta.</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec10-simuladores-avancados">EC10 - Simuladores Avançados</a>
      </td>
      <td rowspan="1">Feature 19 - Simulação de Aposentadoria</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 20 - Comparação com INSS</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="4">
         <a href="#ec11-gerenciamento-de-dados-do-usuario">EC11 - Gerenciamento de Dados do Usuário</a>
      </td>
      <td rowspan="1">Feature 21 - Validação de Dados</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 22 - Alteração de Informações Pessoais</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="2">Feature 23 - Acessibilidade ao Perfil de Recomendação de Investimentos </td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RNF08"> RNF08 </a> - O perfil de recomendação de investimentos deve ser acessível a partir de 3 cliques de qualquer parte do aplicativo.</td>
      <td>-</td>
   </tr>
   <tr>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RNF04"> RNF04 </a> - A interface do aplicativo deve seguir as diretrizes de acessibilidade da norma técnica NBR 17060:2022.</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec12-integracao-com-canais-de-atendimento">EC12 - Integração com Canais de Atendimento</a>
      </td>
      <td rowspan="1">Feature 24 - Canal de Suporte</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 25 - Notificações de Suporte</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec13-funcionalidades-de-acessibilidade">EC13 - Funcionalidades de Acessibilidade</a>
      </td>
      <td rowspan="1">Feature 26 - Temas de Alto Contraste</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 27 - Ajuste de Velocidade de Áudio</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec14-multilingue-e-inclusao">EC14 - Multilíngue e Inclusão</a>
      </td>
      <td rowspan="1">Feature 28 - Tradução Multilíngue</td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RNF06"> RNF06 </a> - O aplicativo deverá disponibilizar suporte para múltiplos idiomas (português como padrão).	</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 29 - Troca Dinâmica de Idioma</td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RNF01"> RNF01 </a>- O sistema deve ter tempo de resposta inferior a 2 segundos para consultas básicas.</td>
      <td>-</td>
   </tr>

   <tr>
      <td rowspan="2">
         <a href="#ec15-atualizacoes-e-notificacoes-automaticas">EC15 - Atualizações e Notificações Automáticas</a>
      </td>
      <td rowspan="1">Feature 30 - Notificações de Taxas e Inflação</td>
      <td><a href="../../elicitacao/grupo5/requisitos/#anchor_RF18"> RF18 </a> - Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação.</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1">Feature 31 - Alertas de Feriados e Indisponibilidade</td>
      <td><a href=""> RFXX </a> - Descrição</td>
      <td>-</td>
   </tr>

</tbody>
</table>



_Autor: [Thales Euflauzino](https://www.github.com/thaleseuflauzino) e [Víctor Schmidt](https://www.github.com/moonshinerd), 2024_

</center>

#### **EC01. Visualização de Títulos Públicos**
- **Descrição**: Implementar funcionalidades para listar e exibir detalhes dos títulos do Tesouro Nacional, categorizados por prazo de vencimento.
- **Histórias Relacionadas**:
      - Exibir lista de títulos (Tesouro Prefixado, Tesouro IPCA+, Tesouro Selic).
      - Implementar filtros para curto, médio e longo prazo.
      - Detalhar informações como preço unitário, rentabilidade, vencimento, taxas aplicáveis e liquidez.


#### **EC02. Gerenciamento de Investimentos**
- **Descrição**: Desenvolver funcionalidades para agendamento e execução de investimentos, integrando APIs bancárias com segurança avançada.
- **Histórias Relacionadas**:
      - Implementar agendamento de compras com notificações automáticas.
      - Gerenciar transferências automáticas entre investimentos com base em metas e cenários.
      - Cancelar agendamentos automaticamente caso não haja saldo suficiente, com notificação ao usuário.


#### **EC03. Simulações de Investimentos**
- **Descrição**: Criar simuladores interativos para planejamento financeiro e comparações de rentabilidade.
- **Histórias Relacionadas**:
      - Simular metas financeiras personalizadas (ex.: aposentadoria).
      - Comparar títulos com outras opções de investimento (LCI, LCA, poupança, etc.).
      - Exibir impacto das variáveis como prazo e valor nos objetivos financeiros.


#### **EC04. Painel de Controle e Relatórios**
- **Descrição**: Fornecer relatórios e dashboards interativos para acompanhamento de investimentos.
- **Histórias Relacionadas**:
      - Exibir evolução dos rendimentos com base em taxas atualizadas do BACEN.
      - Apresentar dashboards com rentabilidade e comparativos com a inflação.
      - Mostrar progresso de metas e sonhos financeiros com barras de progresso interativas.


#### **EC05. Cadastro e Personalização de Usuário**
- **Descrição**: Permitir cadastro de contas com autenticação segura e personalização de perfis.
- **Histórias Relacionadas**:
      - Implementar cadastro de usuários com dados pessoais obrigatórios (CPF, nome, data de nascimento, etc.).
      - Oferecer temas personalizáveis (claro, escuro ou conforme configuração do dispositivo).
      - Ajustar sugestões e conteúdos com base na expertise declarada pelo usuário.


#### **EC06. Segurança e Acessibilidade**
- **Descrição**: Garantir a proteção de dados e acessibilidade universal no aplicativo.
- **Histórias Relacionadas**:
      - Implementar autenticação por biometria e dois fatores.
      - Garantir conformidade com a LGPD.
      - Oferecer suporte a leitores de tela, temas de alto contraste, ajuste de fontes e descrições de áudio.


#### **EC07. Processo de Compra de Títulos**
- **Descrição**: Estruturar as etapas do processo de compra, com foco em clareza e eficiência.
- **Histórias Relacionadas**:
      - Criar fluxo de compra com carrinho para múltiplos títulos.
      - Notificar o usuário sobre agendamentos e status das transações.
      - Oferecer tutorial reutilizável sobre o processo de compra.


#### **EC08. Recursos Educativos**
- **Descrição**: Fornecer conteúdos e ferramentas educativas para os usuários.
- **Histórias Relacionadas**:
      - Incluir artigos e notícias sobre investimentos.
      - Oferecer vídeos e tutoriais interativos.
      - Criar uma FAQ abrangente para dúvidas comuns.

#### **EC09. Personalização de Metas e Planejamento Financeiro**
- **Descrição**: Oferecer ferramentas para o usuário definir, acompanhar e personalizar metas financeiras e sonhos.
- **Histórias Relacionadas**:
      - Permitir que os usuários criem metas e sonhos personalizados com valores, prazos e preferências.
      - Exibir barras de progresso interativas para cada meta.
      - Oferecer notificações sobre o status das metas e sugestões de ajustes.


#### **EC10. Simuladores Avançados**
- **Descrição**: Desenvolver simuladores para planejamento de aposentadoria e outras metas financeiras específicas.
- **Histórias Relacionadas**:
      - Incluir questionários para coleta de informações do usuário para simulação (idade, renda, objetivos, etc.).
      - Permitir comparações interativas entre padrões de investimento e INSS.
      - Exibir projeções detalhadas com títulos do Tesouro e outras opções de investimento.


#### **EC11. Gerenciamento de Dados do Usuário**
- **Descrição**: Criar fluxos robustos para validação e gerenciamento de informações pessoais e de perfil.
- **Histórias Relacionadas**:
      - Validar automaticamente dados cadastrais (CPF, e-mail, etc.).
      - Oferecer suporte para alteração de informações pessoais pelo usuário.
      - Ajustar sugestões baseadas no perfil de expertise do usuário.


#### **EC12. Integração com Canais de Atendimento**
- **Descrição**: Oferecer múltiplos canais de suporte ao usuário.
- **Histórias Relacionadas**:
      - Desenvolver uma aba "Fale Conosco" com opções de chat, FAQ e suporte por e-mail.
      - Implementar notificações para informar status de suporte ou consultas.


#### **EC13. Funcionalidades de Acessibilidade**
- **Descrição**: Tornar o aplicativo inclusivo e acessível para todos os usuários.
- **Histórias Relacionadas**:
      - Implementar temas de alto contraste e ajuste de fontes.
      - Oferecer suporte para leitores de tela e descrições de áudio.
      - Permitir ajustes na velocidade de reprodução de áudio.


#### **EC14. Multilíngue e Inclusão**
- **Descrição**: Suportar múltiplos idiomas para aumentar a acessibilidade do aplicativo.
- **Histórias Relacionadas**:
      - Implementar tradução completa para os idiomas mais usados por usuários estrangeiros no Brasil.
      - Permitir a troca dinâmica de idioma no aplicativo.


#### **EC15. Atualizações e Notificações Automáticas**
- **Descrição**: Enviar informações relevantes em tempo real para os usuários.
- **Histórias Relacionadas**:
      - Notificar o usuário sobre alterações nas taxas de juros ou inflação.
      - Enviar lembretes sobre vencimentos, agendamentos ou novas ofertas.
      - Informar feriados bancários e datas de indisponibilidade do sistema.

### Priorização das Listas de Funcionalidade

## Referências Bibliográficas
> <a id="REF1" href="#anchor_1">1.</a> SERRANO, Milene; SERRANO, Mauricio. Requisitos - Aula 15. Apresentação de slides. FCTE (Faculdade de Ciências e Tecnologias em Engenharia): UnB, s.d.. Acesso em: 11 de dezembro 2024.
> 
> <a id="REF2" href="#anchor_2">2.</a> DUARTE, Luiz. Product Backlog - Introdução. LuizTools - Canal no Youtube, 2020. Disponível em: [Product Backlog - Introdução](https://www.youtube.com/watch?v=z4ubaBwjCsU). Acesso em: 11 de dezembro 2024.

## Bibliografia
> Lichess - Backlog do Produto. Disponível em: <https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>. Acesso em 12 de dezembro de 2024

## Histórico de Versões

| Versão | Data       | Descrição                    | Autor(es)                                        | Revisor(es)                                              |
| ------ | ---------- | ---------------------------- | ------------------------------------------------ | -------------------------------------------------------- |
| `1.0`  | 11/12/2024 | Criação do Documento Inicial | [Víctor Schmidt](https://github.com/moonshinerd) | [Thales Euflauzino](https://github.com/thaleseuflauzino) |