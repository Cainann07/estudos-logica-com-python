# estudos-logica-com-python
Repositório de estudos de lógica de programação com python

## Introdução à Lógica de Programação com Python
A lógica de programação é a base da programação. Ela envolve a criação de uma sequência de instruções que resolvem um problema ou executam uma tarefa específica. Em Python, a lógica de algoritmos pode ser implementada de maneira clara e concisa devido à simplicidade e legibilidade da linguagem.

### Componentes Básicos de um Algoritmo

1. **Entrada**: Dados que são fornecidos ao algoritmo.
2. **Processamento**: Conjunto de instruções que transformam a entrada em saída.
3. **Saída**: Resultado final após o processamento dos dados.

### Estruturas de Controle

Python oferece várias estruturas de controle que ajudam a definir a lógica de um algoritmo:

1. **Condicionais**: Permitem que o algoritmo tome decisões com base em condições.
    ```python
    if condição:
        # bloco de código se a condição for verdadeira
    elif outra_condição:
        # bloco de código se a outra condição for verdadeira
    else:
        # bloco de código se nenhuma condição for verdadeira
    ```

2. **Laços de Repetição**: Permitem que o algoritmo execute um bloco de código várias vezes.
    - **For**: Usado para iterar sobre uma sequência (como uma lista, tupla ou string).
        ```python
        for item in sequência:
            # bloco de código a ser repetido
        ```
    - **While**: Executa um bloco de código enquanto uma condição for verdadeira.
        ```python
        while condição:
            # bloco de código a ser repetido
        ```

### Exemplo de Algoritmo em Python

Vamos criar um algoritmo simples que soma todos os números de uma lista:

```python
# Entrada: lista de números
numeros = [1, 2, 3, 4, 5]

# Processamento: soma dos números
soma = 0
for numero in numeros:
    soma += numero

# Saída: resultado da soma
print("A soma dos números é:", soma)