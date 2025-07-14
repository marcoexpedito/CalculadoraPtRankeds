# 🧮 Calculadora de Partidas Rankeadas

Projeto prático desenvolvido durante um desafio da DIO, com o objetivo de reforçar conceitos fundamentais de JavaScript como:

- Variáveis
- Operadores
- Funções
- Estruturas de decisão
- Lógica de programação

---

## 💡 Descrição

A função principal deste projeto é calcular o saldo de partidas ranqueadas (vitórias - derrotas) de um jogador e determinar seu nível com base na **quantidade total de vitórias**, conforme a tabela abaixo:

| Vitórias       | Nível      |
|----------------|------------|
| 0 - 10         | Ferro      |
| 11 - 20        | Bronze     |
| 21 - 50        | Prata      |
| 51 - 80        | Ouro       |
| 81 - 90        | Diamante   |
| 91 - 100       | Lendário   |
| 101 ou mais    | Imortal    |

---

## 🧠 Lógica

- O saldo é calculado apenas para exibição.
- O nível é determinado unicamente com base na **quantidade de vitórias**, e **não** no saldo.

Exemplo de chamada da função:

``javascript
calcularRank(35, 10); // O Herói tem 35 vitórias e 10 derrotas (saldo de 25) e está no nível de Prata
