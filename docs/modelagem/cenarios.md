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

Os cenários listados nas tabelas 2 a X foram elaborados com base na análise dos requisitos elicitados, disponíveis na seção de [Requisitos](../elicitacao/grupo5/requisitos.md).


### Cenário 1

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
            <td>Simulação de compra de titulos [RF02]</td>
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


### Cenário 2

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
            <td>Resgate Antecipado de Títulos [RF03]</td>
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


### Cenário 3

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
            <td>Planejamento de Metas de Investimento [RF04]</td>
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


### Cenário 4

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
            <td>Planejamento de Aposentadoria [RF05]</td>
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

### Cenário 5

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
            <td>Consultar operações agendadas [RF08]</td>
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

### Cenário 6

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
            <td>Visualizar lista de títulos públicos disponíveis [RF30]</td>
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

### Cenário 7

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
            <td>Consultar as informações de liquidez dos títulos disponíveis [RF23]</td>
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



## Bibliografia

> Bilheteria Digital - Cenários. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/>. Acesso em 01 de dezembro de 2024

## Referências Bibliográficas

> BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. *Interação Humano-Computador e Experiência do Usuário.* Autopublicação, 2021. ISBN: 978-65-00-19677-1.]
>
> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf.


## Histórico de Versões

| Versão | Data       | Descrição                                    | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 01/12/2024 | Estrutura inical do documento                |  [Maria Helena](https://github.com/MariaCHelena) | [Victor Rodrigues](https://github.com/ViictorHugoo) |
| `1.1`  | 01/12/2024 | Inicio da criação dos Cenários               |  [Victor Rodrigues](https://github.com/ViictorHugoo) | [Maria Helena](https://github.com/MariaCHelena) |
