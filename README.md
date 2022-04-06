## **CodePix**

> O Codepix é uma aplicação para simular o envio de Pix. O projeto foi desenvolvido utilizando as tecnologias Go, Apache Kafka, Microserviços e o modelo de comunicação gRPC.

## **Como Executar**

### /codepix

- Instale o Docker e o Docker Compose;
- Entre no diretório do serviço codepix:
```bash
cd codepix
```
- Execute:
```bash
docker-compose up -d
```
- Acesse o container da aplicação:
```bash
docker exec -it codepix_app bash
```
- Rode o comando do Go:
```bash
go run cmd/codepix/main.go
```

## Techs

- gRPC
- Apache Kafka
- Go
- Docker

## **Creditos**

- [Imersão Full Stack && Full Cycle](https://imersao.fullcycle.com.br)