# RabbitMQ_Basic

![version](https://img.shields.io/static/v1?label=version&message=1.0.0&color=blue)
![status](https://img.shields.io/badge/status-em_funcionamento-green)
![release-date](https://img.shields.io/badge/release%20date-04--2023-green)
 ![GitHub Org's stars](https://img.shields.io/github/stars/FernandoStrijeskiLinx?style=social)

Projeto básico demonstrando o uso do RabbitMQ para enviar e ler mensagens em um determinado canal.

# 📄**Documentação do Projeto**
O projeto foi construído utilizando Visual Studio 2022 .NET 8 em C#, utilizando a ferramenta RabbitMQ em container Docker.

# 🗂️**Acesso ao projeto**

Você pode [acessar o código fonte do projeto](https://github.com/FernandoStrijeskiLinx/RabbitMQ_Basic) ou [baixá-lo](https://github.com/FernandoStrijeskiLinx/RabbitMQ_Basic/archive/refs/heads/main.zip).

## Abrir e rodar o projeto

Após baixar o projeto, você pode abrir com o `Visual Studio 2022`.
<br>

# ⚙️**Configurações**

Para utilizar esse projeto utilizando o Docker você precisa ter uma conta e de preferência baixar o Docker Desktop:<br>
[Docker](https://www.docker.com/)<br><br>

Após isso, executar pelo CMD o comando abaixo que irá criar seu container, com o RabbitMQ já instalado e em uso.<br>
```
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.13-management
```
<br><br>
> [!TIP]
> O comando acima foi obtido da documentação do próprio site do RabbitMQ, que ensina a utilizar com ou sem Docker:<br>
[RabbitMQ](https://www.rabbitmq.com/docs/download)<br><br>


# 📸**Preview**
<img src="https://github.com/FernandoStrijeskiLinx/RabbitMQ_Basic/blob/main/Preview.png">


# 💻**Autor**

- [@FernandoStrijeski](https://github.com/FernandoStrijeskiLinx)

Nos vemos no próximo projeto! 👋✌️
