# Banco Digital em Java

Este projeto simula um banco digital utilizando os principais conceitos da Programação Orientada a Objetos (POO) em Java: abstração, encapsulamento, herança e polimorfismo.

## 💡 Funcionalidades

- Criação de contas do tipo **Corrente** e **Poupança**.
- Realização de **depósitos**, **saques** e **transferências** entre contas.
- Impressão de extrato com as informações da conta.

## 📦 Estrutura do Projeto

- `Banco.java`: Representa o banco e armazena os clientes.
- `Cliente.java`: Contém informações do cliente.
- `Conta.java`: Classe abstrata com atributos e métodos comuns a todas as contas.
- `ContaCorrente.java` e `ContaPoupanca.java`: Especializações da classe `Conta`.
- `Main.java`: Ponto de entrada do programa para simulação das operações.

## 🛠️ Tecnologias Utilizadas

- Java 17+
- IntelliJ IDEA ou outro IDE compatível

## ▶️ Como Executar

1. Compile todos os arquivos `.java` no diretório do projeto.
2. Execute a classe `Main` para ver a simulação das operações bancárias.

## 📁 Exemplo de saída

```
=== Extrato Conta Corrente ===
Titular: João
Agência: 0001
Número: 1
Saldo: R$ 500.0

=== Extrato Conta Poupança ===
Titular: Maria
Agência: 0001
Número: 2
Saldo: R$ 300.0
```

