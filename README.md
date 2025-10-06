    # Calculadora Científica em C

Uma aplicação de console simples, escrita em **C**, que simula uma calculadora científica, oferecendo diversas operações matemáticas básicas e avançadas.

---

## Funcionalidades

A calculadora opera em um **loop infinito** até que o usuário escolha a opção de sair (`0`). Ela suporta as seguintes operações:

### Operações com Dois Números (Opções 1 a 5)

1.  **Adição** (`+`)
2.  **Subtração** (`-`)
3.  **Multiplicação** (`*`)
4.  **Divisão** (`/`) - *Inclui tratamento para divisão por zero.*
5.  **Potência** (`x^y`)

### Operações com Um Número (Opções 6 a 25)

| Opção | Operação | Função `math.h` |
| :---: | :--- | :--- |
| **6** | Raiz Quadrada (`sqrt(x)`) | `sqrt()` |
| **7** | Seno (`sin(x)`) | `sin()` |
| **8** | Cosseno (`cos(x)`) | `cos()` |
| **9** | Tangente (`tan(x)`) | `tan()` |
| **10** | Arcoseno (`asin(x)`) | `asin()` |
| **11** | Arcocosseno (`acos(x)`) | `acos()` |
| **12** | Arcotangente (`atan(x)`) | `atan()` |
| **13** | Logaritmo Natural (`ln(x)`) | `log()` |
| **14** | Logaritmo Base 10 (`log10(x)`) | `log10()` |
| **15** | Exponencial (`e^x`) | `exp()` |
| **16** | Valor Absoluto (`|x|`) | `fabs()` |
| **17** | Ceil (Arredonda para cima) | `ceil()` |
| **18** | Floor (Arredonda para baixo) | `floor()` |
| **19** | Seno Hiperbólico (`sinh(x)`) | `sinh()` |
| **20** | Cosseno Hiperbólico (`cosh(x)`) | `cosh()` |
| **21** | Tangente Hiperbólica (`tanh(x)`) | `tanh()` |
| **22** | Potência de 2 (`2^x`) | `pow(2, x)` |
| **23** | Raiz Cúbica (`cbrt(x)`) | `cbrt()` |
| **24** | Exponencial de 10 (`10^x`) | `pow(10, x)` |
| **25** | Fatorial (`x!`) - *Implementação própria para números inteiros não-negativos.* | - |

---

## Tecnologias Utilizadas

* **Linguagem:** C
* **Bibliotecas Padrão:**
    * `stdio.h` (Entrada/Saída)
    * `math.h` (Funções matemáticas avançadas)
    * `stdlib.h` (Funções de utilidade geral)

---

## Como Compilar e Executar

### Pré-requisitos

Você precisará de um compilador C (como **GCC** ou **Clang**) instalado no seu sistema.

### Compilação

Para compilar o código, salve-o como um arquivo, por exemplo, `calculadora.c`, e use o comando de compilação, **incluindo a flag `-lm`** para linkar a biblioteca matemática (`math.h`):

```bash
gcc calculadora.c -o calculadora -lm
