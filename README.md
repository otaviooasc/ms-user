# Projeto User

## Descrição

O Projeto User é uma aplicação web projetada para automatizar a comunicação de boas-vindas aos clientes recém-cadastrados. Ao realizar o cadastro de um cliente na plataforma, o sistema envia automaticamente uma mensagem para um broker. Esse broker, por sua vez, encaminha uma requisição para outra API responsável por enviar um email de boas-vindas ao cliente.

## Funcionalidades Principais

1. **Cadastro de Clientes:** Permita que novos clientes se cadastrem na plataforma.

2. **Comunicação com Broker:** Após o cadastro, uma mensagem é enviada para um broker para acionar a próxima etapa do processo.

3. **Requisição à API Externa:** O broker envia uma requisição para uma API externa responsável pelo envio de emails de boas-vindas.

4. **Email de Boas-Vindas:** A API externa processa a requisição e envia um email personalizado de boas-vindas ao cliente cadastrado.


## Ambiente de Desenvolvimento
* Linguagem: Java
* Framework: Spring Boot
* Banco de Dados: PostgreSQL
* Comunicação assíncrona: RabbitMQ
* Cloud: CloudAMQP

<img width="672" alt="image" src="https://github.com/otaviooasc/ms-user/assets/52991335/d456ea8e-dbef-4733-9f65-5adf59eae0c5">

