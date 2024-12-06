# Verificação dos artefatos

## Introdução

Após o planejamento, realiza-se a inspeção dos artefatos. Este documento apresenta os objetivos da verificação, a metodologia utilizada e a lista de verificação para a avaliação. Além disso, os problemas encontrados poderão conter observações e serão sumarizados e analisados, fornecendo informações valiosas para auxiliar na sua correção.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca dos artefatos produzidos pelo [grupo](https://github.com/Requisitos-de-Software/2024.2-TesouroDireto) durante a etapa 3.

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir da lista de verificação elaborada na página de [planejamento](../entrega3/planej-verificacao-e3-gp5.md) Para responder às perguntas apresentadas na lista de verificação, o avaliador usará as opções **Sim**, **Não** ou **Incompleto**. O avaliador poderá, também, escrever observações em cada pergunta, detalhando pontos que achar necessários.

### Cronograma e Participantes

Os participantes da verificação são todos integrantes do grupo. [Víctor Schmidt](https://github.com/moonshinerd), que irá verificar e corrigir possíveis problemas com os outros integrantes do grupo. E o integrante do grupo [Thales Euflauzino](https://github.com/thaleseuflauzino) realizará a revisão da avaliação. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../entrega3/planej-verificacao-e3-gp5.md).

<center>

**Tabela 1** - Lista de Verificação.

|        ID        | Descrição                                                                                                                                                                  | Avaliação   | Autor            | Data e Hora         |
| :--------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | ----------------- | ------------------- |
| **Itens do Desenvolvimento do Projeto** |                                                                                                                                                        |             |                   |                     |
|        1         | As especificações dos cenários para o projeto. <br> <a href="../referencias_png/especificacaocenarios.png" target="_blank">Exemplo de especificação dos cenários?</a> <a id="anchor_2" href="#REF2"><sup>2</sup></a>       | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|        2         | Os cenários possuem os elementos básicos de um cenário (Título, Metas/Objetivo, Contexto, Atores, Recursos, Exceção e Episódios). <br> <a href="../referencias_png/elementoscenarios.png" target="_blank">Quais elementos dos cenários?</a> <a id="anchor_2" href="#REF2"><sup>2</sup></a>     | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|        3         | As especificações dos léxicos. <br> <a href="../referencias_png/oqsaolexicos.png" target="_blank">O que são léxicos?</a> <a id="anchor_1" href="#REF1"><sup>1</sup></a>                                          | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|        4         | A definição do usuário nos léxicos.                                                                                                                                        | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|        5         | Os léxicos possuem ligações entre si (hiperlinks).                                                                                                                         | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|        6         | Os léxicos utilizam a estrutura de dicionário (verbo, objeto, estado). <br> <a href="../referencias_png/tiposlexicos.png" target="_blank">O que é o dicionário dos léxicos?</a><a id="anchor_1" href="#REF1"><sup>1</sup></a>       | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|        7         | A especificação do caso de uso.                                                                                                                                             | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|        8         | Os atores principais e secundários no diagrama de caso de uso. <br> <a id="anchor_3" href="#REF3">3 [min. 3:27]</a>.                            | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|        9         | O ator principal está do lado esquerdo do sistema no diagrama de caso de uso. <br> <a id="anchor_3" href="#REF3">3 [min. 3:57]</a>             | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       10         | Os atores estão fora da caixa de limite do sistema no diagrama de caso de uso. <br> <a id="anchor_3" href="#REF3">3 [min. 2:55]</a>            | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       11         | A especificação do diagrama de caso de uso (com Nome, Descrição, Atores, Pré-Condição, Pós-Condição, Fluxo Principal, Fluxo Alternativo e Fluxo de Exceção etc.).           | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       12         | No diagrama de caso de uso há ao menos um caso de uso com pontos de extensão? <br> <a id="anchor_3" href="#REF3">3 [min. 8:35]</a>   | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       13         | A participação do cliente e/ou persona na validação do diagrama de caso de uso.                                                                                            | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       14         | A especificação suplementar. <br> <a href="../referencias_png/oqesuplementar.png" target="_blank">O que é especificação suplementar?</a> <a id="anchor_2" href="#REF2"><sup>2</sup></a>                                      | **RESPOSTA** | André Barros      | **DATA/HORA**       | 
|       15         | O artefato segue o modelo FURPS+.                                                                                                                                          | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       16         | O documento especifica o tempo de resposta, no desempenho?                                                                                                                 | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       17         | O documento especifica qual plataforma o aplicativo pode ser executado?                                                                                                    | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       18         | Todos os requisitos podem ser testados (RF e RNF)? <br> **Identificar quais requisitos não são testáveis/verificáveis.**                                                    | **RESPOSTA** | André Barros      | **DATA/HORA**       |
|       **Itens do Conteúdo da Disciplina** (a foto referente ao texto está no ID)         |   |  |  |  |
|       <a id="anchor_3" href="#REF3">P1</a>         | Todos os elementos necessários no diagrama de caso de uso estão presentes? (atores, relacionamentos, sistemas e casos de uso) <a id="anchor_3" href="#REF3">3 [min. 1:37]. </a>                                                    | **RESPOSTA** | Thales Euflauzino | **DATA/HORA**       |
|       <a id="REF7" href="#anchor_8">P2</a>         | Víctor Schmidt                                                    | **RESPOSTA** | Víctor Schmidt      | **DATA/HORA**       |
|       <a id="REF8" href="#anchor_8">P3</a>         | Victor Rodrigues                                                  | **RESPOSTA** | Victor Rodrigues      | **DATA/HORA**       |
|       <a id="REF9" href="#anchor_9">P4</a>         | Maria Helena                                                   | **RESPOSTA** | Maria Helena      | **DATA/HORA**       |
|       <a id="REF10" href="#anchor_10">P5</a>         | Júlia Takaki                                                   | **RESPOSTA** | Júlia Takaki      | **DATA/HORA**       |

_Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024._

</center>

## Vídeo da Verificação

<center>

[**Vídeo 1:** Requisitos - Verificação Entrega 2](COLOQUE AQUI O LINK DO VIDEO!!!!!!!!!!!!!!!!!!!!!!!!!!!!)

<iframe width="560" height="315" src="COLOQUE AQUI O LINK DO VIDEO!!!!!!!!!!!!!!!!!!!!!!!!!!!!" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

_Autor: NOME E LINK GITHUB, 2024_

</center>

---
## Bibliografia

> <a id="REF1" href="#anchor_1">1.</a> SERRANO, Milene; SERRANO, Maurício. Apresentação Modelagem de Requisitos - Cenários, Léxicos e Ferramenta C&L. Brasília: UnB Gama, s.d. 1 apresentação em slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf).
>
> <a id="REF2" href="#anchor_2">2.</a> SERRANO, Milene; SERRANO, Maurício. Apresentação Modelagem de Requisitos - Casos de Uso e Especificação Suplementar. Brasília: UnB Gama, s.d. 1 apresentação em slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf)
>
> <a id="REF3" href="#anchor_3">3.</a> LUCID SOFTWARE PORTUGUÊS. Tutorial de Caso de Uso UML. YouTube, 25 abr. 2019. Disponível em: [https://youtu.be/ab6eDdwS3rA](https://youtu.be/ab6eDdwS3rA). Acesso em: 28 nov. 2024.
>
> SALES, André Barros. Plano de Ensino. Aprender 3. Distrito Federal, 2024. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/51/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf](https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/51/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf). Acesso em 04 dez. 2024.
>
><a id="anchor_7" href="#REF7"><sup>P2</sup></a><br>![Referencia 2](./p2.png)     SCHMIDT   ADICIONE SE HOUVER REFERENCIA DE IMAGEM, SE NAO TIRE!!!!!!! COLOQUE TAMBÉM NO PLANEJAMENTO
>****
><a id="anchor_8" href="#REF8"><sup>P3</sup></a><br>![Referência 3](./p3.png)       RODRIGUES    ADICIONE SE HOUVER REFERENCIA DE IMAGEM, SE NAO TIRE!!!!!!! COLOQUE TAMBÉM NO PLANEJAMENTO
>****
> <a id="anchor_9" href="#REF9"><sup>P4</sup></a><br>![Referência 4](./p3.png)        HELENA   ADICIONE SE HOUVER REFERENCIA DE IMAGEM, SE NAO TIRE!!!!!!! COLOQUE TAMBÉM NO PLANEJAMENTO
>****
> <a id="anchor_10" href="#REF10"><sup>P5</sup></a><br>![Referência 5](./p5.png)       TAKAKI   ADICIONE SE HOUVER REFERENCIA DE IMAGEM, SE NAO TIRE!!!!!!! COLOQUE TAMBÉM NO PLANEJAMENTO


## Histórico de Versões

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| -------- | ------ | ------ | ---------- | ---------- |
| `1.0` | 04/12/2024 | Criação do documento  | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Victor Rodrigues](https://github.com/ViictorHugoo) |
