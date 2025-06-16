# Avaliação de Expressões Numéricas

> Projeto acadêmico de implementação de avaliador de expressões matemáticas com conversão entre notação infixa e pós-fixa, desenvolvido em linguagem C.

![C](https://img.shields.io/badge/C-Language-blue)
![Estruturas de Dados](https://img.shields.io/badge/Data%20Structures-Stacks-orange)
![Projeto Acadêmico](https://img.shields.io/badge/Projeto-Acadêmico-green)

---

## 📖 Sobre o projeto

Este trabalho foi desenvolvido como atividade avaliativa prática para a disciplina de **Estruturas de Dados** no curso de **Engenharia de Software - Universidade Católica de Brasília (UCB)**, sob orientação do professor Marcelo Eustáquio.

O objetivo principal do projeto é:

- Construir um sistema em **linguagem C** capaz de avaliar expressões matemáticas;
- Realizar a conversão entre notação **infixa e pós-fixa**;
- Avaliar as expressões com suporte a:

### Operações binárias:
- `+` adição
- `-` subtração
- `*` multiplicação
- `/` divisão
- `%` resto (mod)
- `^` exponenciação

### Funções unárias:
- `raiz` (raiz quadrada)
- `sen` (seno)
- `cos` (cosseno)
- `tg` (tangente)
- `log` (logaritmo de base 10)

> As funções trigonométricas utilizam ângulos em graus.

---

## 🧠 Objetivos de aprendizado

- Aplicação prática de **estruturas de dados: pilhas**;
- Implementação de algoritmos de conversão de notação infixa para pós-fixa e vice-versa;
- Manipulação de expressões algébricas;
- Modularização de código em C utilizando múltiplos arquivos fonte e cabeçalho.

---

## 🚀 Estrutura do projeto

- `main.c` — Interface principal de entrada do usuário.
- `expressao.c` — Implementação dos algoritmos de conversão e avaliação.
- `expressao.h` — Declaração da estrutura de dados e protótipos de funções.

---

## ⚙️ Como compilar e executar

### Compilação (via terminal com GCC):

```bash
gcc expressao.c main.c -o expressao
```

### Execução:

```bash
./expressao
```

---

## 📚 Contexto acadêmico

- Universidade Católica de Brasília – UCB  
- Estruturas de Dados — 3º semestre de 2025  
- Professor: Marcelo Eustáquio

---

## 📝 Licença

Projeto desenvolvido exclusivamente para fins acadêmicos e avaliação na disciplina de Estruturas de Dados.
