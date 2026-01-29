# 💱 Conversor de Moedas (BRL → USD / EUR)

Projeto **front-end** desenvolvido com **JavaScript**, que converte valores em **Reais (BRL)** para **Dólar Americano (USD)** ou **Euro (EUR)** utilizando **cotações em tempo real**.

---

## 🚀 Funcionalidades

- ✅ Converter **BRL → USD**
- ✅ Converter **BRL → EUR**
- ✅ Consumo de API externa com `fetch`
- ✅ Atualização dinâmica:
  - Nome da moeda
  - Bandeira da moeda selecionada
- ✅ Formatação correta de moedas:
  - Real → `pt-BR`
  - Dólar → `en-US`
  - Euro → `de-DE`

---

## 🌐 API Utilizada

As cotações são obtidas através da **AwesomeAPI**:

https://economia.awesomeapi.com.br/last/USD-BRL,EUR-BRL


Campos utilizados no projeto:
- `USDBRL.high` → cotação do dólar
- `EURBRL.high` → cotação do euro

---

## 🧠 Como o projeto funciona

### 🔄 Conversão de Moedas
Ao clicar no botão **Converter**, o sistema:
1. Busca as cotações atualizadas da API
2. Lê o valor digitado em reais
3. Converte o valor para a moeda selecionada
4. Exibe o resultado formatado corretamente

## 🛠️ Tecnologias Utilizadas

HTML5

CSS3

JavaScript (Vanilla)

Fetch API

AwesomeAPI (cotações em tempo real)
