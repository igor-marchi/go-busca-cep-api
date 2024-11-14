# Busca CEP API

Este projeto é uma API para busca de CEPs utilizando Go.

## Instalação

1. Clone o repositório:

```sh
git clone https://github.com/igor-marchi/go-busca-cep-api
cd go-busca-cep-api
```

2. Instale as dependências:

```sh
go mod tidy
```

## Utilização

### Live Reload com Air

Este projeto utiliza o [Air](https://github.com/cosmtrek/air) para live reload durante o desenvolvimento. Siga os passos abaixo para configurar o Air:

1. Instale o Air:

```sh
go install github.com/air-verse/air@latest
```

2. Execute o Air:

```sh
air
```

O Air irá monitorar as mudanças no código e recarregar automaticamente a aplicação.

## Endpoints

- `GET /?cep={cep}`: Retorna informações sobre o CEP fornecido.
