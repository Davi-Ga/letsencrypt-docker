# letsencrypt-docker

Exemplo de Gerador de Certificados SSL usando Docker e CertiBot

## Introdução

Este projeto visa simplificar a geração de certificados SSL usando Docker e CertiBot. Ele fornece um processo simplificado para obter e gerenciar certificados SSL com o Let's Encrypt.

## Funcionalidades

- Geração automatizada de certificados SSL.
- Utiliza Docker para fácil configuração e implantação.
- Integra-se com CertiBot para gerenciamento eficiente de certificados.

## Começando

### Pré-requisitos

- Docker instalado na sua máquina.
- Docker Compose (se você estiver usando um arquivo `docker-compose.yml`).

### Instalação

1. Clone o repositório:
   ```sh
   git clone https://github.com/Davi-Ga/letsencrypt-docker.git
   cd letsencrypt-docker
   ```

2. Construa e execute os contêineres Docker:
   ```sh
   docker-compose up -d
   ```

### Uso

1. Modifique os arquivos de configuração conforme necessário (por exemplo, `docker-compose.yml`, configurações do CertiBot).
2. Inicie o processo de geração de certificados:
   ```sh
   docker-compose run
   ```

## Estrutura do Repositório

- `docker-compose.yml`: Arquivo de configuração do Docker Compose.
- `nginx`: Pasta para configuração do Nginx

## Contribuindo

Contribuições são bem-vindas! Por favor, faça um fork do repositório e envie pull requests para revisão.

## Licença

Este projeto está licenciado sob a Licença MIT.

## Contato

Para quaisquer perguntas ou feedback, entre em contato com o proprietário do repositório [Davi-Ga](https://github.com/Davi-Ga).
