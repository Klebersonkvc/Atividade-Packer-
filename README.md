# Laboratório Packer + Docker

Imagens Docker criadas com HashiCorp Packer (HCL2).

| Pasta | Imagem gerada | Descrição |
|---|---|---|
| atividade1-apache | meu-apache-packer:latest | Apache com index.html local |
| atividade2-python | ambiente-dev-python:v1 | Python 3, pip e Flask, WORKDIR /app |
| atividade3-node | ambiente-node:v1 | Node.js e npm, package.json em /app |

## Como executar

Em cada pasta:

    packer init .
    packer fmt .
    packer validate .
    packer build .
