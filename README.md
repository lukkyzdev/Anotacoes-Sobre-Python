# Anotações Sobre Python 🐍
📚 Todas as minhas anotações feitas na faculdade de ADS e no curso de Python do [@gustavoguanabara](https://github.com/gustavoguanabara) 📝

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

O PEP 8 é o "Python Enhancement Proposal 8", que é um guia de estilo para a escrita de código python.
O PEP 8 recomenda o uso de espaços em branco de maneira de consistente, incluindo a indentação de 4 espaços (não tabulações).

- Usar **nomes descritivos minúsculos para variáveis e funções** (por exemplo, **minha_variável**);
- Usar **letras maiúsculas separadas por sublinhados para nomes de classes** (por exemplo, **Minha_Classe**);
- Recomenda-se manter linhas de código com até 79 caracteres de comprimento;
- Importações devem ser organizadas de forma ordenada e agrupadas em seções.

---
## Variáveis e Tipos de Dados 🔠
O interpretador Python consegue **estabelecer o tipo de dado da variável observando seu valor.** Confira alguns exemplos:

- x = 10
- nome = 'aluno'
- nota = 8.75
- fez_inscricao = True

**Observe que x=um número inteiro, nome=string, nota=um número decimal e fez_inscricao=booleano.** Será que Python é capaz de definir o tipo de variável somente com base no valor fornecido em cada variável?

Utilizaremos a função print() e type().

![Função Print e Type](./images/funçãoprintetype.png)

Como esperado, o Python acertou todos os tipos de variáveis. Note, também, que em Python tudo é objeto. Sendo assim, os tipos de dados aparecem com a palavra “class”, que é uma classe.

---
## Operadores Relacionais 🌐

![Operação x Significado](./images/operaçãoxsignificado.png)

Além dos operadores relacionais, que comparam valores, também utilizamos operadores booleanos para construir decisões mais complexas em programação. Os operadores booleanos ajudam a combinar diferentes condições e a orientar o fluxo do programa de acordo com a lógica desejada.

- **Operador “E” (and)** - O operador “E” (and) permite a realização da operação lógica “E”. Isso significa que, ao usar a expressão (a and b), o resultado será “Verdadeiro” somente quando ambos os argumentos, “a” e “b”, forem verdadeiros. Caso contrário, o resultado será “Falso”.
- **Operador “OU” (or)** - O operador “OU” (or) realiza a operação lógica “OU”. Ao utilizar a expressão (a or b), o resultado será “Verdadeiro” se pelo menos um dos argumentos, “a” ou “b”, for verdadeiro. A expressão será “Falsa” apenas quando ambos os argumentos forem falsos.
- **Operador “NÃO” (not)** - O operador “NÃO” (not) é responsável por inverter o valor do argumento. Ao aplicarmos a expressão (not a), ela transformará “Verdadeiro” em “Falso”, e vice-versa. Ou seja, se o argumento for verdadeiro, a operação o tornará falso, e, se for falso, a operação o tornará verdadeiro.

Operadores booleanos são usados para controlar o fluxo de execução com base em condições complexas e, assim, tornam viável a elaboração de programas que tomam decisões de acordo com critérios específicos.

---
## Estruturas condicionais if, else e elif 🔃

- A condição “se o semáforo estiver verde” é satisfeita (verdadeira), então você segue em frente (if).
- A condição “se o semáforo estiver vermelho” não é satisfeita (falsa), então você para (else).

Resumindo:
- **if = se** (exemplo: se estiver verde, siga em frente)
- **else = ao contrário** (exemplo: caso contrário de verde, vermelho, pare)

O comando elif, em Python, é uma abreviação de “else if”, sendo usado em estruturas condicionais para avaliar **múltiplas condições em sequência.**

**1- Avaliação em sequência:** quando um bloco if é usado, a condição é avaliada. Se a condição for verdadeira, o bloco de código dentro desse if é executado. No entanto, em muitos cenários, você deseja avaliar uma série de condições em sequência, e o elif permite esse processo.

**2- Verificação múltipla:** após o bloco if, você pode usar um ou mais blocos elif, cada um com sua própria condição. O Python avalia essas condições em ordem, do topo para baixo. Assim que uma condição for verdadeira, o bloco de código associado a essa condição será executado e as condições subsequentes serão ignoradas.

**3- Flexibilidade:** o elif é flexível porque permite que você trate de múltiplos casos sem precisar aninhar uma série de blocos if. Isso torna o código mais legível e eficiente.

**Vamos verificar o exemplo de código a seguir:**

idade = 25


if idade < 18:

    print(“Menor de idade”)

elif idade >= 18 and idade < 65:

    print(“Adulto”)

else:

    print(“Idoso”)

Repare na estrutura do if, elif e else. Ao final, definimos o que será feito com “:”. Além disso, utilizamos operadores relacionais e o “and” para combinar duas condições.
