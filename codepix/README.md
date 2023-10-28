# Codepix Microservice

`````bash
.
├── Dockerfile
├── README.md
├── application
│   ├── factory
│   ├── grpc
│   ├── kafka
│   ├── model
│   └── usecase
├── cmd
├── docker-compose.yaml
├── domain
│   └── model
└── infraestructure
    ├── db
    └── repository

`````
## Description
    - servidor grpc
    - consumir e publicar mensagens kafka
    - operações simultaneas ao executar serviço
    - Domain driven design