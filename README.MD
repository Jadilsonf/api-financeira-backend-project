# Simulador de transações financeiras (back end)
>Clique no vídeo abaixo para saber como utilizar junto ao Insomnia e instalar

[Vídeo](https://youtu.be/C9juIW9U4VE)

Para rodar a aplicação:
```sh
npm install
```

### Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário de um cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário de um cliente por data
- [x] Deve ser possível atualizar dados da conta de um cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [x] Deve ser possível retornar o balance

## Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível buscar extrato de uma conta não existente
- [x] Não deve ser possível fazer saque de uma conta não existente
- [x] Não deve ser possível excluir uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
