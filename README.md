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
