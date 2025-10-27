# ✨ Calculadora Modular Avançada em C 🔢

Este projeto implementa uma calculadora robusta e modular em linguagem C, desenvolvida para cumprir diversos requisitos de programação estruturada. O código contém **mais de 25 funções**, manipulação de **arrays**, **matrizes ($3 \times 3$)**, uso de **estruturas (`struct`)** e **persistência de dados** (salvamento em arquivo CSV).

---

## ⚙️ Funcionalidades Principais

O programa opera através de um menu interativo e é dividido nos seguintes módulos:

### Módulo I: Operações Básicas
| Operação | Detalhes |
| :--- | :--- |
| **Aritméticas** | Soma, Subtração, Multiplicação e Divisão (com tratamento de erro para `/ 0`). |

### Módulo II: Operações Avançadas, Logaritmos e Trigonometria
Este módulo é o mais extenso e utiliza uma função unária centralizada para funções da biblioteca `math.h`.

| Categoria | Funções Implementadas (Exemplos) |
| :--- | :--- |
| **Especiais** | Potência ($a^b$), Fatorial ($n!$), MDC, MMC. |
| **Trigonometria** | Seno, Cosseno, Tangente, ArcSen, ArcCos, ArcTan (*Ângulos em Graus*). |
| **Cálculo** | Raiz Quadrada, Raiz Cúbica, Logaritmo Natural ($\ln$), Log Base 10, Exponenciais ($e^x$, $2^x$, $10^x$). |
| **Estatística** | Média e Mediana (para arrays de até 10 elementos). |

### Módulo III: Operações com Matrizes ($3 \times 3$)
* Soma de Matrizes.
* Multiplicação de Matrizes.

### 💾 Histórico e Persistência
* **Histórico Circular:** Armazena as últimas 10 operações (`struct Operacao`).
* **Exportação:** Salva o histórico em um arquivo **`historico_calculadora.csv`**.

---

## 🚀 Como Compilar e Executar

Este projeto requer o compilador GCC e a linkagem com a biblioteca matemática.

### 1. Salvar o Código
Salve todo o código-fonte (que contém todas as funções, definições e o `main`) no arquivo **`calculadora_completa.c`**.

### 2. Compilação
Use o terminal e inclua a flag `-lm` para linkar a biblioteca matemática:

```bash
# Compila o arquivo e cria um executável chamado 'calculadora'
gcc calculadora-cientifica.c -o calculadora -lm
