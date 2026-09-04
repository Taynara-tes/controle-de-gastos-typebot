# Controle de Gastos com Typebot

Sistema conversacional para registrar, organizar e acompanhar despesas pessoais de forma simples e automatizada.

O projeto usa o **Typebot** como interface de conversa e o **Google Sheets** como base de dados e painel financeiro. Durante o atendimento, o usuário informa os dados da despesa, revisa o lançamento e confirma o envio para a planilha.

## Demonstração

[Acessar o fluxo no Typebot](https://typebot.co/projeto-controle-de-gastos-xx8bfms)

## Funcionalidades

- Registro de despesas por meio de uma conversa guiada
- Classificação por categoria de gasto
- Seleção da forma de pagamento
- Tratamento de data e identificação automática do mês
- Conferência dos dados antes do envio
- Edição, cancelamento e reinício do lançamento
- Integração automática com o Google Sheets
- Cálculo de totais mensais
- Resumo de gastos por categoria
- Visão anual das despesas
- Identificação da categoria com maior gasto

## Como funciona

```text
Usuário
   ↓
Tipo de gasto
   ↓
Valor e forma de pagamento
   ↓
Data e identificação do mês
   ↓
Conferência dos dados
   ↓
Registro no Google Sheets
   ↓
Resumo financeiro
```

## Tecnologias utilizadas

- **Typebot:** criação do fluxo conversacional
- **Google Sheets:** armazenamento e análise dos lançamentos
- **JavaScript:** tratamento de datas e identificação do mês
- **Lógica condicional:** validação, edição e confirmação dos dados

## Galeria

<p align="center">
  <img src="https://raw.githubusercontent.com/Taynara-tes/controle-de-gastos-typebot/main/Captura%20de%20Tela%202026-08-16%20a%CC%80s%2021.52.07.png" width="45%" alt="Início do fluxo de controle de gastos">
  <img src="https://raw.githubusercontent.com/Taynara-tes/controle-de-gastos-typebot/main/Captura%20de%20Tela%202026-08-16%20a%CC%80s%2021.52.43.png" width="45%" alt="Registro de uma despesa">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Taynara-tes/controle-de-gastos-typebot/main/Captura%20de%20Tela%202026-08-16%20a%CC%80s%2021.53.25.png" width="45%" alt="Conferência do lançamento">
  <img src="https://raw.githubusercontent.com/Taynara-tes/controle-de-gastos-typebot/main/Captura%20de%20Tela%202026-08-16%20a%CC%80s%2021.53.41.png" width="45%" alt="Resumo financeiro no Google Sheets">
</p>

## Objetivo do projeto

Este projeto foi desenvolvido para tornar o controle financeiro pessoal mais acessível. Em vez de preencher uma planilha manualmente, o usuário registra cada gasto por meio de perguntas simples e recebe uma visão organizada das suas despesas.

## Autora

Desenvolvido por [Taynara](https://github.com/Taynara-tes).
