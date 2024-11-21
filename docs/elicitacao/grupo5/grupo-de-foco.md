# Grupo de Foco: Avaliação do Aplicativo Tesouro Direto

## Introdução

A técnica de grupo de foco foi utilizada para coletar insights qualitativos sobre a experiência dos usuários do aplicativo [Tesouro Direto](https://www.tesourodireto.com.br/). O objetivo principal foi entender as percepções, dificuldades e sugestões de melhoria diretamente dos usuários, permitindo uma análise mais rica para subsidiar futuras atualizações no aplicativo.

## Metodologia

A técnica do Grupo de Foco foi empregada para conduzir a análise. A reunião contou com três participantes, listados na Tabela 1, que compartilharam suas experiências e opiniões sobre o uso do aplicativo. O roteiro do grupo de foco foi elaborado por [Thales Euflauzino](https://github.com/thaleseuflauzino), disponível [nesse link](https://docs.google.com/document/d/1U2ujh2tgV2MimwFtCYiGocC-mi5pKNCLk3nGenzlyDg/edit?tab=t.0). Foi conduzido por [Maria Helena](https://github.com/MariaCHelena) e teve a revisão presencial do [Víctor Schmidt](https://github.com/moonshinerd), e a gravação está disponível no [Vídeo 1](https://youtu.be/lIt-R5LL7wU). O grupo de foco teve a intenção de abranger tópicos como experiência do usuário, funcionalidades, acompanhamento de investimentos, segurança e sugestões de melhorias.

<br>
<center>
**Tabela 1** - Nome completo e idade dos participantes.

| Nome   | Idade |
|--------|-------|
| Manoela Silvestre Garcia Chaves   | 20 |
| Victor Hugo dos Santos Bernardes | 23 |
| Marcos Augusto Oliveira Goulart | 20 |

_Autor: Elaborado por [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024_

</center>

## Resultados

### 1. Experiência do Usuário

- **Manoela:** O login foi considerado pouco atraente. Usou o aplicativo apenas algumas vezes.
- **Victor:** Achou o simulador interativo e bem projetado.
- **Marcos:** Considerou as funcionalidades desconexas, dificultando a navegação.

### 2. Funcionalidades Essenciais

- **Manoela:** Utilizou os recursos de investimento e sonhos, relatando que o aplicativo atendeu às suas necessidades básicas.
- **Victor:** Concentrou-se no simulador e destacou a ausência de um modo escuro funcional.
- **Marcos:** Recomendou a inclusão de uma tela comparativa para diferentes investimentos.

### 3. Acompanhamento e Notificações

- **Manoela:** Acompanha o andamento dos investimentos manualmente, sem utilizar as notificações.
- **Marcos e Victor:** Não mencionaram o uso de notificações como prioridade.

### 4. Segurança

- **Manoela:** Sente-se segura devido à sua organização pessoal, pois anota as senhas.
- **Victor:** Confia no aplicativo pela intuição e design, mas buscaria reviews antes de usar para transações críticas.
- **Marcos:** Confia por ser um produto do Tesouro Nacional e da B3, mas tem dúvidas sobre o login pelo Gov.br.

### 5. Melhorias e Sugestões

- **Manoela:** Não sugeriu grandes mudanças, afirmando que o aplicativo atende às suas necessidades.
- **Victor:** Apontou falhas na responsividade e sugeriu melhorias no design de login e modo escuro.
- **Marcos:** Sugeriu uma interface mais intuitiva para novos usuários e maior conectividade entre funcionalidades.

## Conclusão

O grupo de foco revelou que:

- O simulador de investimentos é amplamente valorizado pelos usuários, mas melhorias na interface geral são necessárias.
- A ausência de um modo escuro adequado é um ponto negativo destacado.
- Segurança é percebida como satisfatória devido à confiança na marca, embora o login pelo Gov.br tenha gerado dúvidas.
- Há sugestões para aprimorar a navegação, conectividade das funcionalidades e inclusão de novas telas comparativas.

## Recomendações

1. Melhorar a usabilidade e o design do login, incluindo opções modernas como biometria.
2. Implementar um modo escuro funcional e melhorias na responsividade para dispositivos móveis.
3. Adicionar funcionalidades de comparação de investimentos e uma interface mais intuitiva para usuários novos.

## Vídeo do Grupo de Foco

<center>

[**Vídeo 1:** Elicitação de Requisitos - Grupo de Foco](https://youtu.be/lIt-R5LL7wU)

<iframe width="560" height="315" src="https://www.youtube.com/embed/lIt-R5LL7wU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>

_Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2024_

</center>

## Termo de Consentimento

O termo de consentimento utilizado neste grupo de foco permite o uso de imagem, áudio e dados fornecidos pelos participantes exclusivamente para fins educativos e de pesquisa.

Para abrir o documento completo do termo de consentimento, <button id="open-pdf-btn" class="btn btn-primary">clique aqui.</button>

<div id="pdf-container" style="display: none; margin-top: 20px;">
    <iframe
        src="/termo_de_consentimento_grupofocal.pdf"
        width="100%"
        height="600px"
        style="border: none;">
    </iframe>
</div>

<script>
    document.getElementById("open-pdf-btn").addEventListener("click", function() {
        var pdfContainer = document.getElementById("pdf-container");
        if (pdfContainer.style.display === "none") {
            pdfContainer.style.display = "block";
        } else {
            pdfContainer.style.display = "none";
        }
    });
</script>

## Requisitos coletados

##### Legenda das Tabelas:
- **RFx**: Requisito Funcional número x;
- **RNFx**: Requisito Não Funcional número x;
- **GFx**: Requisito do grupo de foco número x;

### Requisitos Funcionais

| Tipo   | Descrição                                                                 | ID   | Elaborado (Sim/Não) |
|--------|---------------------------------------------------------------------------|------|---------------------|
| RF1   | O aplicativo devverá possuir uma tela de login integrado com o Gov Br | GF01 | Sim  |
| RF2   | O aplicativo deverá permitir que o usuário faça login criando uma conta própria no sistema      | GF02 | Sim   |
| RF3   | O aplicativo deverá possuir uma ferramenta de simulação de evolução dos investimentos.      | GF03 | Sim   |
| RF4   | O aplicativo deverá possuir uma ferramenta para comparar o investimento escolhido com outros tipos de investimento.  | GF04 | Não   |
| RF5   | O aplicativo deverá possuir a funcionalidade de alternar entre modo claro e escuro. | GF05 | Não   |

### Requisitos não funcionais

| Tipo   | Descrição                                                                 | ID   | Elaborado (Sim/Não) |
|--------|---------------------------------------------------------------------------|------|---------------------|
| RNF1   | O aplicativo deverá garantir a segurança dos dados cadastrais dos usuários de acordo com a LGPD. | GF06 | Sim  |
| RNF2   | O aplicativo deverá ser responsivo para todos os dispositivos mobile. | GF07 | Não   |
| RNF3   | A navegação no aplicativo deverá ser focada em integrar as funcionalidades do aplicativo de modo intuitivo e compreensivo. | GF08 | Não   |


## Bibliografia
> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) **Interação Humano-Computador e Experiência do usuário.** Cap 7. Autopublicação. ISBN: 978-65-00-19677-1.
>
> Economia DF - Grupo de Foco. Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/elicitacao/tecnicas-perfil-usuario/grupo_de_foco/. Acesso em 19 de novembro de 2024

| Versão | Data       | Descrição | Autor     |       Revisor         |
| ------ | ---------- | --------- | --------- | --------------------- |
| `1.0` | 19/11/2024  | Estruturação Inicial | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Victor Rodrigues](https://github.com/ViictorHugoo)   |
| `1.2` | 21/11/2024  | Elicitação de Requisitos | [Maria Helena](https://github.com/MariaCHelena) |  |
