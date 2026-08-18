# WebAcademy CI/CD — Laboratório 03

Atividade prática sobre testes automatizados e containers em pipelines de CI/CD.

## Exercícios

- `lab03_01`: função TypeScript testada com Jest e relatório de cobertura.
- `lab03_docker`: aplicação Express empacotada em uma imagem Docker.

## Pipelines

- **Test Pipe** executa o Jest nas versões 16 e 18 do Node.js e envia a cobertura ao Codecov.
- **Build on DockerHub** cria e publica a imagem `webacademy:latest` no Docker Hub.

## Configuração do repositório

Os pipelines usam estes segredos em **Settings > Secrets and variables > Actions**:

- `CODECOV_TOKEN`
- `DOCKERHUB_USERNAME`
- `DOCKERHUB_TOKEN`

Consulte os READMEs de cada exercício para executar os projetos localmente.
