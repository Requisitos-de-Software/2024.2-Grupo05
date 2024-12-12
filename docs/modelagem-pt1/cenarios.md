# Cenários

## Introdução

Um cenário é uma narrativa concreta, rica em detalhes contextuais, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais (Barbosa et al., 2021). Para o desenvolvimento desse projetos, os cenários serão utilizados para entender as interações entre ambientes e sistemas e o fluxo do software.

## Metodologia

Para a elaboração desses cenários, iremos utilizar um modelo de construção, descrito na tabela 1.

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 1:</strong> Modelo de criação dos cenários.</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Modelo de Cenário</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Título do cenário</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Efeitos na situação que motivam as ações realizadas pelos atores</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>Detalhes da situação que motivam ou explicam os objetivos, ações e reações dos atores do cenário</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>Pessoas que irão interagir com o aplicativo do tesouro direto</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>Ferramentas utilizadas no cenário</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>Ações realizadas pelos atores divididas em etapas</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>Limitações do cenário</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>Planos ou procedimentos para lidar com situações extraordinárias ou erros inesperados durante o cenário</td>
        </tr>
    </tbody>
</table>
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autor: <a href="https://github.com/MariaCHelena" target="blank">Maria Helena</a></p>

Inicialmente serão definidos os cenários das tarefas principais, que descrevem as tarefas de uso diário dos usuários, descrevendo as ações que são realizadas com mais frequência.

## Cenários Identificados

Os cenários listados nas tabelas 2 a 11 foram elaborados com base na análise dos requisitos elicitados, disponíveis na seção de [Requisitos](../elicitacao/grupo5/requisitos.md).

### Cenário 1 - Simulação de compra de titulos - <a href="../../elicitacao/grupo5/requisitos/#anchor_RF02">RF02</a>

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 2:</strong> Cenário 1</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Simulação de compra de titulos <a href="../../elicitacao/grupo5/requisitos/#anchor_RF02">[RF02]</a></td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Simular a compra de titulos para avaliar rentabilidade, custos e prazos</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>
                <ul>
                    <li>Local: Tela de "Simulação"</li>
                    <li>Tempo: Aproximadamente 3 minutos.</li>
                    <li>Pré-condição: Possuir cadastro ativo no sistema e o sistema possuir títulos cadastrados</li>
                </ul>           
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>
                <ul>
                    <li>Usuário do tesouro direto</li>
                    <li>Sistema do tesouro direto</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>
                <ul>
                    <li>Aplicativo do tesouro direto instalado</li>
                    <li>Conexão com a internet</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>Acessar aplicativo</li>
                    <li>Realizar autenticação no sistema</li>
                    <li>Navegar para a tela de simulação</li>
                    <li>Realizar simulação</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>As informações apresentadas dependem de dados atualizados sobre os títulos e taxas</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li> Erro de conexão à internet
                        <ul>
                            <li>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</li>
                        </ul>
                    </li>   
                    <li> Erro de usuário não autenticado
                        <ul>
                            <li>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</li>
                        </ul>
                    </li>
                    <li> Erro de simulação
                        <ul>
                            <li>Caso não haja títulos para os parâmetros estabelecidos pelo usuário, o sistema deve apresentar uma mensagem de falta de títulos para os parâmetros entregues</li>
                        </ul>
                    </li>             
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autores: <a href="https://github.com/MariaCHelena" target="blank">Maria Helena</a> e <a href="https://github.com/ViictorHugoo" target="blank">Victor Rodrigues</a></p>


### Cenário 2 - Resgate Antecipado de Títulos - <a href="../../elicitacao/grupo5/requisitos/#anchor_RF03">RF03</a>

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 3:</strong> Cenário 2</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Resgate Antecipado de Títulos <a href="../../elicitacao/grupo5/requisitos/#anchor_RF03">[RF03]</a></td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Permitir que o usuário realize o resgate antecipado de seus investimentos em títulos</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>
                <ul>
                    <li>Local: Tela de "Meus Investimentos"</li>
                    <li>Tempo: Aproximadamente 3 minutos.</li>
                    <li>Pré-condição: O usuário possuir cadastro ativo no sistema e títulos de investimeto</li>
                </ul>  
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>
                <ul>
                    <li>Usuário do tesouro direto</li>
                    <li>Sistema do tesouro direto</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>
                <ul>
                    <li>Aplicativo do tesouro direto instalado</li>
                    <li>Conexão com a internet</li>
                    <li>Dados de rentabilidade</li>
                    <li>Valores líquidos dos titulos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>Acessar aplicativo</li>
                    <li>Realizar autenticação no sistema</li>
                    <li>Navegar para a tela meus investimentos</li>
                    <li>Realizar resgate antecipado</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>o resgate antecipado está sujeito a disponibilidade de liquidez e às condições impostas pelo Tesouro Nacional</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li> Erro de conexão à internet
                        <ul>
                            <li>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</li>
                        </ul>
                    </li>   
                    <li> Erro de usuário não autenticado
                        <ul>
                            <li>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</li>
                        </ul>
                    </li>
                    <li> Erro de calculo ou resgate
                        <ul>
                            <li>Caso o sistema não consiga calcular ou processar o resgate, o usuário deve ser notificado e instruído a entrar em contato com o suporte técnico</li>
                        </ul>
                    </li>             
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autores: <a href="https://github.com/MariaCHelena" target="blank">Maria Helena</a> e <a href="https://github.com/ViictorHugoo" target="blank">Victor Rodrigues</a></p>


### Cenário 3 - Planejamento de Metas de Investimento - <a href="../../elicitacao/grupo5/requisitos/#anchor_RF04">RF04</a>

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 4:</strong> Cenário 3</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Planejamento de Metas de Investimento <a href="../../elicitacao/grupo5/requisitos/#anchor_RF04">[RF04]</a></td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Realizar o cadastro e o acompanhamento de metas fincanceiras</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>
                <ul>
                    <li>Local: Tela de "Meus Sonhos"</li>
                    <li>Tempo: Aproximadamente 2 minutos.</li>
                    <li>Pré-condição: O usuário possuir cadastro ativo no sistema e o sistema deve ter títulos de investimeto</li>
                </ul>  
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>
                <ul>
                    <li>Usuário do tesouro direto</li>
                    <li>Sistema do tesouro direto</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>
                <ul>
                    <li>Aplicativo do tesouro direto instalado</li>
                    <li>Conexão com a internet</li>
                    <li>Dados de rentabilidade</li>
                    <li>Valores líquidos dos titulos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>Acessar aplicativo</li>
                    <li>Realizar autenticação no sistema</li>
                    <li>Navegar para a tela meus sonho</li>
                    <li>Cadastrar sonho</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td> O planejamento depende de títulos disponíveis e compatíveis com a meta estabelecida</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li> Erro de conexão à internet
                        <ul>
                            <li>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</li>
                        </ul>
                    </li>   
                    <li> Erro de usuário não autenticado
                        <ul>
                            <li>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</li>
                        </ul>
                    </li>
                    <li> Erro de sugestões
                        <ul>
                            <li>Caso o sistema não consiga sugerir títulos, o usuário deve ser notificado e orientado a ajudar prazos e valores</li>
                        </ul>
                    </li>             
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autores: <a href="https://github.com/MariaCHelena" target="blank">Maria Helena</a> e <a href="https://github.com/ViictorHugoo" target="blank">Victor Rodrigues</a></p>


### Cenário 4 - Planejamento de Aposentadoria - <a href="../../elicitacao/grupo5/requisitos/#anchor_RF05">RF05</a>

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 5:</strong> Cenário 4</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário 4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Planejamento de Aposentadoria <a href="../../elicitacao/grupo5/requisitos/#anchor_RF05">[RF05]</a></td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Planejar a aposentadoria, definindo montante necessário e simulando investimentos</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>
                <ul>
                    <li>Local: Tela de "Meus Sonhos"</li>
                    <li>Tempo: Aproximadamente 5 minutos.</li>
                    <li>Pré-condição: O usuário possuir cadastro ativo no sistema e ter idade e ano de aposentadoria definidos</li>
                </ul>  
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>
                <ul>
                    <li>Usuário do tesouro direto</li>
                    <li>Sistema do tesouro direto</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>
                <ul>
                    <li>Aplicativo do tesouro direto instalado</li>
                    <li>Conexão com a internet</li>
                    <li>Dados de rentabilidade</li>
                    <li>Valores líquidos dos titulos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>Acessar aplicativo</li>
                    <li>Realizar autenticação no sistema</li>
                    <li>Navegar para a tela meus sonhos</li>
                    <li>Selecionar para cadastar novo sonho</li>
                    <li>Escolher aposentadoria como opção</li>
                    <li>Definir de parâmetros de aposentadoria</li>
                    <li>Escolher os titulos</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td> O planejamento depende de títulos disponíveis e compatíveis, condições de mercado e regularidade dos aportes do usuário.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li> Erro de conexão à internet
                        <ul>
                            <li>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</li>
                        </ul>
                    </li>   
                    <li> Erro de usuário não autenticado
                        <ul>
                            <li>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</li>
                        </ul>
                    </li>
                    <li> Erro de completude
                        <ul>
                            <li>Caso o sistema não consiga sugerir títulos compatíveis ou o usuário não possua saldo suficiente com os prazos desejados, o sistema deve sugerir mudanças no ano da aposentadoria ou no investimento mensal</li>
                        </ul>
                    </li>             
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autores: <a href="https://github.com/MariaCHelena" target="blank">Maria Helena</a> e <a href="https://github.com/ViictorHugoo" target="blank">Victor Rodrigues</a></p>

### Cenário 5 - Consultar operações agendadas - <a href="../../elicitacao/grupo5/requisitos/#anchor_RF08">RF08</a>

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 6:</strong> Cenário 5</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário 5</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Consultar operações agendadas <a href="../../elicitacao/grupo5/requisitos/#anchor_RF08">[RF08]</a></td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Consultar as operações de investimento em tesouros públicos que foram agendadas pelo aplicativo</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>
                <p>Local: <i>Tela de "Meus Investimentos" do aplicativo.</i></p>
                <p>Tempo: <i>Aproximadamente 1 minuto.</i></p>
                <p>Pré-condição: <i>Possuir um cadastro ativo no sistema e possuir agendamentos realizados.</i></p>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>
                <ul>
                    <li>Usuários do tesouro direto</li>
                    <li>Sistema do tesouro direto</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>
                <ul>
                    <li>Aplicativo do tesouro direto instalado no celular</li>
                    <li>Conexão com a internet</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>Acessar o aplicativo</li>
                    <li>Realizar a autenticação no sistema</li>
                    <li>Acessar a tela principal do aplicativo</li>
                    <li>Navegar para a tela de meus investimentos</li>
                    <li>Visualizar seus agendamentos em formato de lista</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>
                <ul>
                    <li>O usuário só deverá poder visualizar os agendamentos que ele mesmo realizar</li>
                    <li>Somente usuários cadastrados e autenticados no aplicativo poderão realizar agendamentos</li>
                    <li>O sistema deverá realizar uma diferenciação entre agendamentos e compras que ainda não foram realizadas</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li>Erro de conexão à internet <p><i>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</i></p></li>
                    <li>Erro de obtenção de usuário não autenticado <p><i>Caso o usuário não esteja mais autenticado na aplicação e ele tente acessar os agendamentos o aplicativo deverá gerar uma mensagem de erro de "sessão expirada" e redirecioná-lo a tela de login</i></p></li>
                    <li>Erro de obtenção de agendamentos <p><i>Caso o usuário não tenha nenhum agendamento o sistema deverá exibir um texto de aviso de nenhum investimento, com uma mensagem guiando o usuário a como realizar agendamentos no aplicativo.</i></p></li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autores: <a href="https://github.com/MariaCHelena" target="blank">Maria Helena</a> e <a href="https://github.com/ViictorHugoo" target="blank">Victor Rodrigues</a></p>

### Cenário 6 - Visualizar lista de títulos públicos disponíveis - <a href="../../elicitacao/grupo5/requisitos/#anchor_RF30">RF30</a>

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 7:</strong> Cenário 6</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário 6</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Visualizar lista de títulos públicos disponíveis <a href="../../elicitacao/grupo5/requisitos/#anchor_RF30">[RF30]</a></td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Visualizar os títulos públicos disponíveis para a compra dentro da aplicação em formato de lista.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>
                <p>Local: <i>Tela "Investir" do aplicativo.</i></p>
                <p>Tempo: <i>Aproximadamente 1 minuto.</i></p>
                <p>Pré-condição: <i>Possuir um cadastro ativo no sistema e o sistema possuir títulos cadastrados disponíveis para a visualização.</i></p>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>
                <ul>
                    <li>Usuários do tesouro direto</li>
                    <li>Sistema do tesouro direto</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>
                <ul>
                    <li>Aplicativo do tesouro direto instalado no celular</li>
                    <li>Conexão com a internet</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>Acessar o aplicativo</li>
                    <li>Realizar a autenticação no sistema</li>
                    <li>Acessar a tela principal do aplicativo</li>
                    <li>Navegar para a tela de investimentos</li>
                    <li>Visualizar os investimentos disponíveis em formato de lista</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>
                <ul>
                    <li>Os investimentos deverão estar cadastrados no banco de dados no sistema</li>
                    <li>Os investimentos deverão ser acessíveis para os usuários do sistema</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li>Erro de conexão à internet <p><i>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</i></p></li>
                    <li>Erro de usuário não autenticado <p><i>Caso o usuário não esteja mais autenticado na aplicação e ele tente acessar a tela de investimentos o aplicativo deverá gerar uma mensagem de erro de "sessão expirada" e redirecioná-lo a tela de login</i></p></li>
                    <li>Erro de obtenção de investimentos <p><i>Caso não seja possível obter nenhum título na tela de investimentos, o sistema deverá retornar ao usuário uma mensagem de erro de investimentos não disponíveis.</i></p></li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autores: <a href="https://github.com/MariaCHelena" target="blank">Maria Helena</a> e <a href="https://github.com/ViictorHugoo" target="blank">Victor Rodrigues</a></p>

### Cenário 7 - Consultar as informações de liquidez dos títulos disponíveis - <a href="../../elicitacao/grupo5/requisitos/#anchor_RF23">RF23</a>

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 8:</strong> Cenário 7</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário 7</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Consultar as informações de liquidez dos títulos disponíveis <a href="../../elicitacao/grupo5/requisitos/#anchor_RF23">[RF23]</a></td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Permitir que o usuário visualize as informações de liquidez referentes a cada título cadastrado no sistema</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>
                <p>Local: <i>Tela de "Simulador" referente a cada título do aplicativo.</i></p>
                <p>Tempo: <i>Aproximadamente 2 minutos.</i></p>
                <p>Pré-condição: <i>Possuir um cadastro ativo no sistema e possuir títulos disponíveis no sistema com informações de liquidez.</i></p>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>
                <ul>
                    <li>Usuários do tesouro direto</li>
                    <li>Sistema do tesouro direto</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>
                <ul>
                    <li>Aplicativo do tesouro direto instalado no celular</li>
                    <li>Conexão com a internet</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>Acessar o aplicativo</li>
                    <li>Realizar a autenticação no sistema</li>
                    <li>Acessar a tela principal do aplicativo</li>
                    <li>Navegar para a tela de meus investimentos</li>
                    <li>Visualizar os títulos disponíveis</li>
                    <li>Clicar em "ver detalhes e simular" no título que deseja obter mais informações</li>
                    <li>Visualizar a tela de simulação com as informações detalhadas a respeito do título</li>
                    <li>Navegar até a seção de "Tempo de liquidação"</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>
                <ul>
                    <li>Os títulos disponíveis no sistema deverão possuir também os detalhes a respeito de liquidez associados a ele cadastrados no sistema</li>
                    <li>Somente usuários cadastrados e autenticados no aplicativo poderão visualizar informações a respeito da liquidez dos títulos</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li>Erro de conexão à internet <p><i>Caso o usuário não tenha acesso a internet, o aplicativo deverá gerar uma mensagem de erro de conexão</i></p></li>
                    <li>Erro de usuário não autenticado <p><i>Caso o usuário não esteja mais autenticado na aplicação e ele tente acessar as informações do título, o aplicativo deverá gerar uma mensagem de erro de "sessão expirada" e redirecioná-lo a tela de login</i></p></li>
                    <li>Erro de obtenção de dados do título <p><i>Caso o título cadastrado não possua dados de liquidez associados a ele, o sistema deverá gerar uma mensagem de obtenção de dados interna para o usuário.</i></p></li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autores: <a href="https://github.com/MariaCHelena" target="blank">Maria Helena</a> e <a href="https://github.com/ViictorHugoo" target="blank">Victor Rodrigues</a></p>

### Cenário 8 - Simulação da Evolução de Metas/Sonhos - [RF25](../../elicitacao/grupo5/requisitos/#anchor_RF25)

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 9:</strong> Cenário 8</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário: Simulação da Evolução de Metas/Sonhos</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Simulação da Evolução de uma Meta ou Sonho Financeiro</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Permitir que o Investidor ou Interessado visualize, de forma projetada, o progresso financeiro de suas metas ou sonhos, auxiliando no planejamento e tomada de decisões sobre investimentos.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>O Investidor ou Interessado deseja verificar como suas metas financeiras podem evoluir ao longo do tempo com base em diferentes cenários de aportes e rendimentos, usando o aplicativo do Tesouro Direto para realizar a análise.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>Investidor ou Interessado</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>Aplicativo do Tesouro Direto, dados financeiros das metas cadastradas, simulador de evolução de investimentos.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>O Investidor ou Interessado acessa a seção "Meus Sonhos" no aplicativo.</li>
                    <li>Seleciona uma meta ou sonho existente na lista.</li>
                    <li>Insere dados para simulação, como valor adicional a ser investido, período de tempo e expectativa de retorno.</li>
                    <li>O sistema processa os dados e exibe projeções em gráficos e tabelas.</li>
                    <li>O Investidor ou Interessado avalia os cenários apresentados e pode ajustar os parâmetros da simulação para realizar novas análises.</li>
                    <li>Após finalizar a análise, o usuário encerra o processo, sem necessidade de salvar a simulação.</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>
                <ul>
                    <li>O usuário deve estar autenticado para acessar a funcionalidade.</li>
                    <li>O sistema requer que a meta ou sonho já esteja cadastrada para realizar a simulação.</li>
                    <li>Os dados de rendimento projetado são baseados em taxas históricas e não garantem retorno futuro.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li>Se algum campo necessário para a simulação estiver vazio ou preenchido incorretamente, o sistema exibe uma mensagem de erro e solicita a correção.</li>
                    <li>Se houver falha na comunicação com o servidor, o sistema exibe uma mensagem de indisponibilidade e orienta o usuário a tentar novamente mais tarde.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
Esse cenário foi feito baseado nas [Instruções do Professor](../../elicitacao/grupo5/requisitos/#requisitos-por-integrante) sobre os requisitos a serem desenvolvidos no projeto.
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autor: <a href="https://github.com/moonshinerd" target="blank">Víctor Schmidt</a></p>

### Cenário 9 - Relatórios Mensais de Evolução de Rendimentos - [RF15](../../elicitacao/grupo5/requisitos/#anchor_RF15)

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 10:</strong> Cenário 9</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário: Relatórios Mensais de Evolução de Rendimentos</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Geração de Relatórios Mensais de Evolução de Rendimentos</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Fornecer ao usuário uma visão consolidada da evolução mensal dos rendimentos de seus títulos adquiridos que estão ativos, auxiliando na análise de desempenho dos investimentos.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>O usuário deseja verificar como os rendimentos de seus títulos têm evoluído ao longo dos meses, usando os relatórios gerados pelo sistema para acompanhamento financeiro.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>Sistema e Usuário</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>Base de dados dos rendimentos dos títulos adquiridos, módulo de geração de relatórios, interface do sistema.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>O sistema gera automaticamente o relatório mensal ao final de cada mês.</li>
                    <li>O relatório consolida os rendimentos mensais de todos os títulos adquiridos ativos pelo usuário.</li>
                    <li>Os dados são organizados em gráficos e/ou tabelas comparando o mês atual com os 3 meses anteriores.</li>
                    <li>O sistema notifica o usuário sobre a disponibilidade do relatório na seção "Meus Relatórios".</li>
                    <li>O usuário acessa o relatório, visualiza os dados e faz o download, se desejar.</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>
                <ul>
                    <li>O usuário deve estar autenticado para acessar os relatórios.</li>
                    <li>Os dados dos rendimentos dos títulos devem estar atualizados no sistema.</li>
                    <li>Os relatórios são baseados em dados históricos e não apresentam projeções futuras.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li>Se houver falha na geração do relatório, o sistema exibe uma mensagem de erro e agenda uma nova tentativa automática.</li>
                    <li>Se o usuário tentar acessar o relatório durante uma indisponibilidade do servidor, o sistema exibe uma mensagem e sugere tentar novamente mais tarde.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

Esse cenário foi feito baseado nas [Instruções do Professor](../../elicitacao/grupo5/requisitos/#requisitos-por-integrante) sobre os requisitos a serem desenvolvidos no projeto.
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autor: <a href="https://github.com/thaleseuflauzino" target="blank">Thales Euflauzino</a></p>


### Cenário 10 - Dashboard com Dados de Rentabilidade e Inflação - [RF26](../../elicitacao/grupo5/requisitos/#anchor_RF26)

<p style="font-size: 13px; text-align: center; margin: 0px auto"><strong>Tabela 11:</strong> Cenário 10</p>
<table border="1">
    <thead>
        <tr>
            <th colspan="2" style="text-align: center;">Cenário 10</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold;">Título</td>
            <td>Visualização do Dashboard com Dados de Rentabilidade e Inflação [RF26]</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Objetivo</td>
            <td>Permitir que o investidor visualize, na página inicial, informações consolidadas sobre a rentabilidade dos títulos adquiridos e a taxa de inflação atual.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Contexto</td>
            <td>
                <ul>
                    <li><strong>Local:</strong> Página inicial do aplicativo Tesouro Direto.</li>
                    <li><strong>Tempo Estimado:</strong> Menos de 5 segundos para carregar as informações.</li>
                    <li><strong>Pré-condições:</strong> O usuário deve estar autenticado no aplicativo e o sistema deve possuir dados atualizados.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Atores</td>
            <td>Investidor e Sistema do Tesouro Direto.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Recursos</td>
            <td>Aplicativo Tesouro Direto e conexão com a base de dados do Tesouro Direto.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Episódios</td>
            <td>
                <ol>
                    <li>O investidor acessa o aplicativo e é direcionado à página inicial.</li>
                    <li>O sistema carrega automaticamente os dados de rentabilidade dos títulos adquiridos.</li>
                    <li>A taxa de inflação atual e sua variação são exibidas no dashboard.</li>
                    <li>O investidor visualiza um resumo claro e direto das informações financeiras relevantes.</li>
                    <li>Se necessário, o investidor interage com gráficos para detalhar informações específicas.</li>
                </ol>
            </td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Restrições</td>
            <td>O sistema pode apresentar limitações caso não haja conexão com a internet ou se os dados estiverem indisponíveis.</td>
        </tr>
        <tr>
            <td style="font-weight: bold;">Exceção</td>
            <td>
                <ul>
                    <li>O sistema não consegue acessar os dados do servidor e exibe uma mensagem informando que os dados estão temporariamente indisponíveis.</li>
                    <li>O investidor não possui títulos adquiridos, e o sistema exibe uma mensagem sugerindo a aquisição de títulos para visualizar dados no dashboard.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>


Esse cenário foi feito baseado nas [Instruções do Professor](../../elicitacao/grupo5/requisitos/#requisitos-por-integrante) sobre os requisitos a serem desenvolvidos no projeto.
<p style="font-size: 13px; margin: 0px; text-align: center; margin-top: -14px">Autor: <a href="https://github.com/ViictorHugoo" target="blank">Victor Rodrigues</a></p>

## Bibliografia

> Bilheteria Digital - Cenários. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/>. Acesso em 01 de dezembro de 2024
> 
> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf.

## Referências Bibliográficas

> BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. *Interação Humano-Computador e Experiência do Usuário.* Autopublicação, 2021. ISBN: 978-65-00-19677-1.



## Histórico de Versões

| Versão | Data       | Descrição                                    | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 01/12/2024 | Estrutura inical do documento                |  [Maria Helena](https://github.com/MariaCHelena) | [Victor Rodrigues](https://github.com/ViictorHugoo) |
| `1.1`  | 01/12/2024 | Inicio da criação dos Cenários               |  [Victor Rodrigues](https://github.com/ViictorHugoo) | [Maria Helena](https://github.com/MariaCHelena) |
| `1.2` | 10/12/2024 | Colocando titulos nos cenarios  | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Victor Schmidt](https://github.com/moonshinerd)  |
| `1.3` | 10/12/2024 | Adicionando rastreabilidade  | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Victor Schmidt](https://github.com/moonshinerd)  |
| `1.4`  | 10/12/2024 |  Ajustando referencias/bibliografia        | [Thales Euflauzino](https://github.com/thaleseuflauzino)  | [Víctor Schmidt](https://github.com/moonshinerd)  |
| `1.5`    | 11/12/2024 | Adicionando Cenário baseado nas [Instruções do Professor](../../elicitacao/grupo5/requisitos/#requisitos-por-integrante)| [Víctor Schmidt](https://github.com/moonshinerd)   | [Thales Euflauzino](https://github.com/thaleseuflauzino) |
| `1.6`    | 11/12/2024 | Adicionando Cenário baseado nas [Instruções do Professor](../../elicitacao/grupo5/requisitos/#requisitos-por-integrante)   | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Víctor Schmidt](https://github.com/moonshinerd) |
| `1.7`    | 12/12/2024 | Adicionando Cenário baseado nas [Instruções do Professor](../../elicitacao/grupo5/requisitos/#requisitos-por-integrante)   | [Victor Rodrigues](https://github.com/ViictorHugoo) |[Thales Euflauzino](https://github.com/thaleseuflauzino) |
