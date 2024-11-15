# Introspecção da Elicitação de Requisitos

## Introdução

Este artefato tem como objetivo realizar uma introspecção para a elicitação dos requisitos do projeto Tesouro Direto. A técnica de introspecção consiste em uma análise pessoal e aprofundada que busca identificar elementos essenciais para o software. Nesse método, o responsável deve imaginar uma situação hipotética em que uma tarefa específica do sistema é realizada, permitindo a identificação de necessidades e funcionalidades indispensáveis. Dessa forma, os requisitos levantados são apresentados na Tabela 1 e na Tabela 2.

## Metodologia

A técnica de introspecção foi aplicada individualmente por [Víctor Schmidt](https://github.com/moonshinerd) no período de 09/11/2024 a 16/11/2024. Após essa etapa, os requisitos identificados foram organizados em duas tabelas: Tabela 1 para Requisitos Funcionais e Tabela 2 para Requisitos Não-Funcionais. Concluído o levantamento, revisamos o aplicativo do Tesouro Direto selecionado pelo grupo, verificando a presença ou ausência dos requisitos elicitados.

### Introspecção do Autor
Para aplicar essa metodologia, imaginei-me em uma situação onde eu, como usuário, desejasse investir no Tesouro Direto e acessasse o aplicativo para realizar essa tarefa. Sem visualizar o aplicativo, procurei listar todas as funções essenciais que ele deveria oferecer para tornar o processo de investimento mais simples e eficiente. Além disso, considerei as dificuldades comuns que um investidor iniciante poderia enfrentar e como o aplicativo deveria abordar esses desafios, proporcionando soluções intuitivas e funcionais.

Esse processo de introspecção para elicitação de requisitos consiste justamente em colocar-se no lugar do usuário sem a referência visual direta do produto, buscando compreender quais funcionalidades (tanto funcionais quanto não funcionais) são fundamentais. No contexto do aplicativo do Tesouro Direto, essa abordagem me permitiu estruturar uma visão clara dos recursos necessários, levando em conta a experiência do usuário e o conhecimento prévio de funcionalidades encontradas em aplicativos semelhantes.

## Requisitos Elicitados

##### Legenda das Tabelas:
- **RFx**: Requisito Funcional número x;
- **RNFx**: Requisito Não Funcional número x;
- **ITx**: Requisito número x;

Aqui está a elaboração dos requisitos do Tesouro Direto com base nas suas anotações:

---

### **Requisitos Funcionais**

<center>
**Tabela 1** - Requisitos Funcionais.

| Tipo | Descrição | ID   | Elaborado (Sim/Não) | Priorização (MoSCoW) |
|------|-----|------|---------------------|---------------------|
| RF1  | Permitir a consulta de investimentos por instituição financeira.                                  | IT1  | Sim                 | Must Have           |
| RF2  | Permitir a simulação, realização e visualização de detalhes de investimentos nos títulos SELIC, Prefixado e Inflação. | IT2  | Sim                 | Must Have           |
| RF3  | Permitir o resgate de investimentos, considerando a instituição financeira associada.             | IT3  | Sim                 | Must Have           |
| RF4  | Oferecer funcionalidade para salvar metas de investimentos (Sonhos).                             | IT4  | Sim                 | Should Have         |
| RF5  | Permitir simulação e planejamento de aposentadoria indicando o ano esperado de aposentadoria.     | IT5  | Sim                 | Should Have         |
| RF6  | Disponibilizar consulta à taxa de custódia da B3 e taxa de administração da instituição financeira. | IT6  | Sim                 | Must Have           |
| RF7  | Incluir um simulador para ajudar o usuário a encontrar títulos adequados ao perfil dele.          | IT7  | Sim                 | Could Have          |
| RF8  | Permitir a consulta de operações realizadas e agendadas.                                          | IT8  | Sim                 | Must Have           |
| RF9  | Oferecer a funcionalidade de “Fale Conosco”.                                                      | IT9  | Sim                 | Must Have           |
| RF10 | Permitir a visualização de notificações recebidas.| IT10 | Sim                 | Should Have|
| RF11 | Incluir funcionalidades sobre o aplicativo (avaliar, indicar para um amigo ou limpar cache).      | IT11 | Sim| Could Have|
|RF12| Permitir a visualização de dados do usuário. | IT12 | Sim                 | Must Have|
|RF13| Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos.      | IT13 | Não| Should Have|
|RF14| Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos.    | IT14 | Não | Could Have  |
|RF15| Incluir relatórios personalizados para análise detalhada de rentabilidade e evolução de investimentos. | IT16 | Não | Should Have |
| RF16| Disponibilizar um recurso educativo com vídeos e artigos sobre como investir no Tesouro Direto.      | IT17 | Não | Should Have |
| RF17| Oferecer integração com carteiras digitais para pagamento direto de investimentos.                     | IT18 | Não | Could Have|
| RF18| Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação.                         | IT19 | Não | Must Have |
| RF19| Adicionar gamificação, como conquistas ou recompensas simbólicas ao atingir metas financeiras.         | IT20 | Não | Could Have|

_Autor: [Víctor Schmidt](https://github.com/moonshinerd), 2024_
</center>
---

### **Requisitos Não Funcionais**

<center>
**Tabela 2** - Requisitos Não Funcionais.

| Tipo   | Descrição                                                                 | ID   | Elaborado (Sim/Não) | Priorização (MoSCoW) |
|--------|---------------------------------------------------------------------------|------|---------------------|---------------------|
| RNF1   | O sistema deve ter tempo de resposta inferior a 2 segundos para consultas básicas. | IT13 | Não        | Must Have           |
| RNF2   | Garantir a segurança dos dados sensíveis do usuário conforme a LGPD.      | IT14 | Sim                 | Must Have           |
| RNF3   | O aplicativo deve ser responsivo para dispositivos móveis e tablets.      | IT15 | Sim                 | Must Have           |
| RNF4   | A interface deve ser intuitiva e seguir as diretrizes de acessibilidade.  | IT16 | Não                 | Should Have         |
| RNF5   | O sistema deve permitir integrações seguras com APIs de instituições financeiras. | IT5 | Sim          | Must Have           |
| RNF6   | Disponibilizar suporte para múltiplos idiomas (português como padrão).    | IT17 | Não                 | Could Have          |

_Autor: [Víctor Schmidt](https://github.com/moonshinerd), 2024_
</center>

---

#### Bibliografia

> Bilheteria Digital - Instrospecção. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/introspeccao/>. Acesso em 15 de novembro de 2024

> SERRANO, Milene; SERRANO, Maurício. Apresentação Elicitação de Requisitos - Técnicas - Priorização. Brasília: UnB Gama, s.d. 1 apresentação em slides.

| Versão | Data       | Descrição | Autor     |       Revisor         |
| ------ | ---------- | --------- | --------- | --------------------- |
| `1.0` | 15/11/2024  | Estruturação Inicial | [Víctor Schmidt](https://github.com/moonshinerd) | [Thales Euflauzino](https://github.com/thaleseuflauzino) |
