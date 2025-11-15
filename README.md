# 🧩 Projeto Tetris – Gerenciamento de Peças com Fila e Pilha

Este projeto implementa um sistema simplificado inspirado na mecânica de jogos como Tetris, utilizando **fila circular** e **pilha** para gerenciar peças, reservas e trocas.

---

## 📌 Funcionalidades

* Jogar peça da frente da fila
* Enviar peça da fila para a pilha de reserva
* Usar peça do topo da pilha
* Trocar a peça da frente da fila com o topo da pilha
* Trocar as 3 primeiras peças da fila com as 3 do topo da pilha

---

## 🧱 Estruturas Utilizadas

### **Peça (`struct Peca`)**

* `nome` — tipo da peça (I, O, T, L)
* `id` — identificador único

### **Fila Circular (`Fila`)**

* Armazena até 5 peças
* Remoção e inserção usando índices circulares

### **Pilha (`Pilha`)**

* Armazena até 3 peças
* Funcionamento LIFO (último a entrar, primeiro a sair)

---

## 🖥️ Exibição

O programa mostra:

* Peças na fila
* Peças na pilha (do topo para a base)
* Menu interativo para operações

---

## 🚀 Como Executar

### **Compilar**

```bash
gcc main.c -o tetris
```

### **Executar**

```bash
./tetris
```

---

## 🎯 Objetivo

Projeto focado em:

* Estruturas de dados
* Lógica de manipulação de filas e pilhas
* Simulação de mecânica de jogo
* Ambiente interativo em console


