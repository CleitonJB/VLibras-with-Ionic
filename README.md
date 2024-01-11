# VLibras-with-Ionic

Implementação simples do VLibras (Vocabulário Brasileiro de Libras) com um aplicativo desenvolvido com **Ionic**, **Angular** e **Capacitor**.

## Objetivo

Este aplicativo/projeto está sendo criado com o intuito de apresentar a ferramenta VLibras à comunidade como uma opção de ferramenta externa para a implementação de conceitos de acessibilidade em aplicações móveis (mobile app).

## Requisitos

Requisitos mínimos para a criação do projeto:

| Depedências   | Versão |
|---------------|--------|
| Node.js       |v18.17.0|
| npm           |9.6.7   |
| Ionic         |7.0.0   |
| Angular       |^17.0.2 |
| Libras Widget |   -    |

O **Libras Widget** é uma depedência do projeto, mas ele é implementado via javascript. Logo, a sua versão dependerá da fonte oficial da ferramenta. A sua implementação pode ser encontrada no diretório abaixo, da linha 26 até 35.

``` shell
> src/index.html
```

## Executar

#### 1° Instalar as dependências do projeto
``` bash
npm install
```
ou
``` bash
npm i
```

#### 2° Rodar o projeto

Via **Ionic** **(Recomendado)**:
``` bash
ionic serve
```
ou via **Angular**:
``` bash
ng serve -o
```

## Referências

A implementação do **VLibras** foi feita a partir do **VLibras Widget**. Para utilizar a ferramenta no projeto o site oficial do [Manual de Instruções da Ferramenta VLibras Widget]('https://vlibras.gov.br/doc/widget/installation/webpageintegration.html') foi utilizado como fonte de requisitos e documentação da ferramenta.