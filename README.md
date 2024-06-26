# Ruby on Rails Application with Docker

Este repositório contém uma aplicação Ruby on Rails configurada para ser executada com Docker, utilizando um contêiner para a aplicação Rails e outro para o banco de dados PostgreSQL.

## Pré-requisitos

Para executar esta aplicação localmente, você precisa ter instalado:

- Docker
- Docker Compose

Certifique-se de ter esses requisitos instalados antes de prosseguir.

## Configuração do Ambiente

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio

Crie o arquivo .env:

Crie um arquivo .env na raiz do projeto com as seguintes variáveis de ambiente:

POSTGRES_USER=app_user
POSTGRES_PASSWORD=123456
POSTGRES_HOST=postgres

Altere as variáveis conforme necessário para o seu ambiente.

Iniciando a Aplicação

Para iniciar a aplicação, execute o seguinte comando:

docker-compose up

Isso criará os contêineres necessários para a aplicação Rails e o banco de dados PostgreSQL, e iniciará a aplicação na porta 3000.

Acessando a Aplicação
Após iniciar a aplicação, você pode acessá-la em seu navegador através do seguinte URL:
http://localhost:3000

