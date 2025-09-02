# Anotações Sobre Python 🐍
📚 Todas as minhas anotações feitas no curso de Python do [@gustavoguanabara](https://github.com/gustavoguanabara) 📝

---
## Python 3 - Módulo 1
![Python](https://img.shields.io/badge/Python-3.13-green)

> ### Aula 2-5

**Python é:**
- Linguagem de propósito geral
- Fácil e intuitiva
- Multiplataforma
- Batteries included (Batérias incluidas, vem com muita coisa instalada)
- Livre
- Organizada

---
O PEP 8 é o "Python Enhancement Proposal 8", que é um guia de estilo para a escrita de código python.
O PEP 8 recomenda o uso de espaços em branco de maneira de consistente, incluindo a indentação de 4 espaços (não tabulações).

- Usar **nomes descritivos minúsculos para variáveis e funções** (por exemplo, **minha_variável**);
- Usar **letras maiúsculas separadas por sublinhados para nomes de classes** (por exemplo, **Minha_Classe**);
- Recomenda-se manter linhas de código com até 79 caracteres de comprimento;
- Importações devem ser organizadas de forma ordenada e agrupadas em seções.

---
## Variáveis e Tipos de Dados
O interpretador Python consegue **estabelecer o tipo de dado da variável observando seu valor.** Confira alguns exemplos:

- x = 10
- nome = 'aluno'
- nota = 8.75
- fez_inscricao = True

**Observe que x=um número inteiro, nome=string, nota=um número decimal e fez_inscricao=booleano.** Será que Python é capaz de definir o tipo de variável somente com base no valor fornecido em cada variável?

Utilizaremos a função print() e type().

print(type(x))

print(type(nome))

print(type(nota))

print(type(fez_inscricao))

<class 'int'>
<class 'str'>
<class 'float'>
<class 'bool'>

Como esperado, o Python acertou todos os tipos de variáveis. Note, também, que em Python tudo é objeto. Sendo assim, os tipos de dados aparecem com a palavra “class”, que é uma classe.

---
## Operadores Relacionais

**Operação** x **Significado**

- "**<**" | Estritamente menor que
- "**<=**" | Menor ou igual que
- "**>**" | Estritamente maior que
- "**>=**" | Maior ou igual que
- "**==**" | Igual
- "**!=**" | Diferente
- "**is**" | Identidade do objeto
- "**is not**" | Negação da identidade do objeto

Além dos operadores relacionais, que comparam valores, também utilizamos operadores booleanos para construir decisões mais complexas em programação. Os operadores booleanos ajudam a combinar diferentes condições e a orientar o fluxo do programa de acordo com a lógica desejada.

- **Operador “E” (and)** - O operador “E” (and) permite a realização da operação lógica “E”. Isso significa que, ao usar a expressão (a and b), o resultado será “Verdadeiro” somente quando ambos os argumentos, “a” e “b”, forem verdadeiros. Caso contrário, o resultado será “Falso”.
- **Operador “OU” (or)** - O operador “OU” (or) realiza a operação lógica “OU”. Ao utilizar a expressão (a or b), o resultado será “Verdadeiro” se pelo menos um dos argumentos, “a” ou “b”, for verdadeiro. A expressão será “Falsa” apenas quando ambos os argumentos forem falsos.
- **Operador “NÃO” (not)** - O operador “NÃO” (not) é responsável por inverter o valor do argumento. Ao aplicarmos a expressão (not a), ela transformará “Verdadeiro” em “Falso”, e vice-versa. Ou seja, se o argumento for verdadeiro, a operação o tornará falso, e, se for falso, a operação o tornará verdadeiro.

Operadores booleanos são usados para controlar o fluxo de execução com base em condições complexas e, assim, tornam viável a elaboração de programas que tomam decisões de acordo com critérios específicos.
