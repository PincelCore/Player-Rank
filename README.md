# Calculadora de Partidas Rankeadas

Este projeto implementa uma **Calculadora de Partidas Rankeadas** que classifica o nível de um jogador com base no número de vitórias e derrotas. O projeto foi desenvolvido em **Node.js** e faz uso de funções, laços de repetição e estruturas de decisão para calcular o saldo de vitórias e o nível do jogador.

## Objetivo

Criar uma função que receba a quantidade de vitórias e derrotas de um jogador e calcule o saldo de partidas ranqueadas. O nível do jogador é determinado pela quantidade de vitórias.

### Critérios de Classificação

- Vitórias < 10: Ferro
- Vitórias entre 11 e 20: Bronze
- Vitórias entre 21 e 50: Prata
- Vitórias entre 51 e 80: Ouro
- Vitórias entre 81 e 90: Diamante
- Vitórias entre 91 e 100: Lendário
- Vitórias ≥ 101: Imortal

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução para JavaScript no servidor.
- **readline**: Biblioteca nativa do Node.js para receber entrada do usuário via terminal.

## Funcionalidades

A aplicação pede ao usuário para inserir a quantidade de vitórias e derrotas. Com base nesses valores, ela calcula o saldo de vitórias (vitórias - derrotas) e classifica o jogador em um dos níveis listados acima. 



