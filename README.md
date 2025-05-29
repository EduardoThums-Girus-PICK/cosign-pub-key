# Imagem pública de assinatura do Cosign

Nesse repositório se encontra a parte pública da chave utilizada para assinar as imagens através do Cosign utilizado por essa organização.

## Como verificar uma imagem

```bash
cosign verify --key https://raw.githubusercontent.com/EduardoThums-Girus-PICK/cosign-pub-key/refs/heads/main/cosign.pub my-image:latest
```
