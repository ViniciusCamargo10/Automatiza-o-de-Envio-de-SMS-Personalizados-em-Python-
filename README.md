# Envio de SMS para Clientes via Twilio

Este projeto tem como objetivo automatizar o envio de SMS para clientes, agradecendo pela compra e pedindo feedback sobre a experiência. O script lê uma planilha Excel contendo informações dos clientes, como nome e número de telefone, formata o número corretamente para o Brasil e envia o SMS usando a API Twilio.

## Objetivos

- **Automatizar o envio de SMS**: Enviar mensagens SMS personalizadas para clientes, agradecendo pela compra e pedindo feedback.
- **Integração com a API Twilio**: Utilizar a API Twilio para enviar SMS de forma fácil e rápida.
- **Validação de números de telefone**: Garantir que os números de telefone sejam válidos e corretamente formatados.
- **Prevenção de envios duplicados**: Evitar o envio de SMS para o mesmo número de telefone mais de uma vez.

## Tecnologias Utilizadas

- **Python 3.x**
- **Biblioteca `pandas`**: Para leitura e manipulação da planilha Excel.
- **Biblioteca `re`**: Para validar e formatar números de telefone.
- **Biblioteca `twilio`**: Para enviar os SMS através da API Twilio.

## Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/envio-sms-clientes.git
   cd envio-sms-clientes
