# 🧠 CC2632 - Desenvolvimento de Algoritmos (C)

## 📌 Descrição

Este repositório reúne todos os exercícios práticos desenvolvidos ao longo das **7 semanas** da disciplina **CC2632 - Desenvolvimento de Algoritmos** (graduação).  
Cada semana contém de 6 a 12 programas independentes, que exploram progressivamente os fundamentos da linguagem C e do raciocínio algorítmico.

Os arquivos estão organizados por semana:

- 📁 Semana1.c
- 📁 Semana2.c
- 📁 Semana3.c
- 📁 Semana4.c
- 📁 Semana5.c
- 📁 Semana6.c
- 📁 Semana7.c

> Cada arquivo contém múltiplos programas (separados por comentários). Para executar um exercício específico, copie o bloco de código desejado para um arquivo `.c` separado.

## 🧱 Conteúdos abordados (por semana)

### 🔹 Semana 1 – Primeiros passos
- ✅ Entrada e saída com `scanf` / `printf`
- ✅ Operações aritméticas básicas
- ✅ Conversão de tipos (segundos → horas, minutos, segundos)
- ✅ Cálculo de média ponderada
- ✅ Decomposição de um valor em cédulas
- ✅ Geração de dígito de controle com operações de resto

### 🔹 Semana 2 – Estruturas condicionais e repetições
- ✅ Ordenação de 2 e 3 números inteiros
- ✅ Verificação de formação de triângulos (desigualdade triangular)
- ✅ Seleção de três varetas entre quatro para formar um triângulo
- ✅ Laços `for` e `while`
- ✅ Geração de múltiplos em um intervalo
- ✅ Sequência de Fibonacci (recursiva)
- ✅ Cálculo do MDC (Máximo Divisor Comum)

### 🔹 Semana 3 – Funções e matemática computacional
- ✅ Definição e chamada de funções
- ✅ Distância entre pontos em R² e R³
- ✅ Produto escalar de vetores em R³
- ✅ Funções trigonométricas (cosseno, arccos)
- ✅ Conversão radianos ↔ graus
- ✅ Módulo de vetor em R³
- ✅ Ângulo entre dois vetores (via cosseno)
- ✅ Média e desvio padrão amostral
- ✅ Regressão linear simples (coeficiente de correlação, estimativa)

### 🔹 Semana 4 – Vetores
- ✅ Cálculo da média e do índice do maior elemento
- ✅ Inversão de vetor in-place
- ✅ Desvio padrão e variância amostral
- ✅ Módulo e produto escalar de vetores
- ✅ Produto vetorial (em R³)
- ✅ Menor e maior distância entre componentes de dois vetores
- ✅ Busca linear (retorna índice ou -1)

### 🔹 Semana 5 – Matrizes e criptografia
- ✅ Multiplicação de matriz por vetor
- ✅ Multiplicação de matrizes (com validação de dimensões)
- ✅ **Cifra de Hill**:
  - Codificação: conversão de string para ASCII, multiplicação por matriz 2×2
  - Decodificação: uso da matriz inversa para recuperar a mensagem original

### 🔹 Semana 6 – Ponteiros
- ✅ Cálculo do módulo de um vetor usando ponteiros
- ✅ Produto escalar de dois vetores usando ponteiros

### 🔹 Semana 7 – Structs e tipos compostos
- ✅ Uso de `struct` para representar datas
- ✅ Ordenação de três números reais com struct
- ✅ Cálculo do perímetro de um polígono (vértices em struct)
- ✅ Números complexos:
  - Representação com `struct Ponto { double R, I; }`
  - Menu interativo (soma, multiplicação, divisão, módulo, conjugado)

## 🖥️ Como compilar e executar (exemplo)

Compile um programa individual. Lembre-se da flag `-lm` para funções matemáticas:

    gcc programa.c -o programa -lm
    ./programa

⚠️ **Importante:** os arquivos `.c` contêm várias funções `main()`. Para compilar um exercício específico, copie seu bloco para um arquivo separado.

## 🛠️ Ferramentas e ambiente

- **Linguagem:** C (padrão C99)
- **Compilador:** GCC (ou qualquer compatível)
- **Bibliotecas usadas:** `stdio.h`, `stdlib.h`, `math.h`, `string.h`

## 👨‍🎓 Autoria

- **Disciplina:** CC2632 - DESENVOLVIMENTO DE ALGORITMOS
- **Instituição:** Centro Universitário FEI
- **Período:** Graduação
- **Linguagem:** C
- **Ano:** 2022
