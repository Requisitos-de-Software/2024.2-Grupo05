# Especificação Suplementar

## Introdução

A Especificação Suplementar objetiva descrever requisitos adicionais do aplicativo, incluindo características relacionadas à usabilidade, confiabilidade, desempenho e capacidade de suporte. Ele complementa os Casos de Uso ao especificar pontos que não foram tratados diretamente neles.

## Metodologia

O modelo adotado para definir os requisitos do aplicativo Tesouro Direto foi o FURPS+. Essa abordagem organiza os requisitos do sistema em categorias como funcionalidade, usabilidade, confiabilidade, desempenho e capacidade de suporte.

## Definições da Especificação Suplementar

## Funcionalidades

As funcionalidades foram elicitadas e podem ser encontradas em Elicitação de requisitos e nos Casos de usos levantados.

- [Elicitação de Requisitos(priorização)](../priorizacao.md)
- [Casos de Uso](casos_de_uso.md)

## Usabilidade

Este tópico aborda os requisitos que influenciam a facilidade de uso da aplicação pelo usuário.

### Capacidade de customização

O sistema não apresenta uma boa capacidade de customização, possui apenas um tema (tema claro).

### Visibilidade do sistema

O sistema exibe informações de forma clara e organizada para o usuário.

### Fácil aprendizagem

O sistema possui uma interface padronizada, garantindo conforto ao usuário e facilitando o acesso a informações de forma clara e objetiva.

## Confiabilidade

Esse tópico diz respeito a quanto o aplicativo é confiável

### Disponibilidade

Os servidores devem permanecer acessíveis ao usuário em tempo integral. Em casos de manutenção ou falhas no sistema, o usuário deve ser notificado com a maior antecedência possível.

### Segurança das informações

O sistema apresenta uma conta vinculada ao Gov.br, que traz mais segurança para o usuário por já ser utilizado em outros aplicativos do governo.

## Suportabilidade

Multiplataforma(versão mobile, versão web, versão desktop) e responsividade.

### Web

O sistema do Tesouro Direto é acessível através de navegadores em desktops, tablets ou smartphones, sendo necessário apenas uma conexão com a internet.

Caminho: [Tesouro Direto Web](https://www.tesourodireto.com.br/)

### IOs

A aplicação mobile destinada a dispositivos Apple está disponível nos sistemas iOS 10.0 ou posterior.

Caminho: [Tesouro Direto Apple Store](https://apps.apple.com/br/app/tesouro-direto/id1356012706)

### Android

A aplicação mobile destinada a dispositivos Android está disponível nos sistemas Android 10.0 ou posterior.

Caminho: [Tesouro Direto Google Play](https://play.google.com/store/apps/details?id=br.gov.b3.tesourodireto)

## Performance

Esse tópico diz respeito a questões relacionadas ao desempenho do software

### Economia de dados

Economia de dados (modo hibernar, boa experiência offline), tempo de resposta(otimização de requisições), economia de bateria (Escurecer a tela, modo hibernar).

### Tempo de resposta

Otimização das requisições do aplicativo

### Economia de bateria

É possível escurecer a tela, ativar o modo hibernar.

## Referências

[1] SERRANO M., SERRANO M. Requisitos - Aula 13. Disponível na plataforma Aprender3. Aceso em 06 de dez. de 2024.
[2] ROCHA, Samily. Especificação Suplementar - Aula 13. Material de apoio, disponível na plataforma Aprender 3. Aceso em 06 de dez. de 2024.
[3] SILVA, Davi. Especificação Suplementar, dispovível em: https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/especificacao_suplementar/. Acesso em 06 de dez. de 2024.

## Histórico de Versão

| Versão | Data  | Descrição                     | Autor(es)     | Revisor(es)   |
| ------ | ----- | ----------------------------- |-------------- | -------       |
| `1.0`  | 06/12 |  Criação do documento         | Júlia Takaki  | Maria Helena  |