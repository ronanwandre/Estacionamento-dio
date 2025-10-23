# Sistema de Estacionamento em C#

Este projeto é um sistema simples de estacionamento feito em **C#** para rodar no console.  
O objetivo é cadastrar veículos, remover veículos e listar os que estão estacionados.

## Descrição

O programa pede ao usuário dois valores:

- **Preço inicial**
- **Preço por hora**

Com esses dados, o sistema exibe um menu com as opções:

1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar

- **Cadastrar veículo:** o usuário informa a placa, e ela é adicionada à lista.
- **Remover veículo:** o usuário informa a placa e o tempo de permanência. O sistema calcula o valor total usando a fórmula:
  valorTotal = precoInicial + (precoPorHora \* horas).
  Depois, o veículo é removido da lista.
- **Listar veículos:** mostra todas as placas cadastradas.
- **Encerrar:** finaliza o programa
