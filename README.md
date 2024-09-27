# treinamentoPython 
1. Instalação e configuração VSCode
    Baixar e instalar Python
    Vá ao site oficial do Python: https://www.python.org/downloads/Links to an external site. 
    Certifique-se de marcar a opção "Add Python to PATH" durante o processo de instalação no Windows. Isso permitirá que você execute Python a partir da linha de comando.
Conceitos básicos da sintaxe em Python
Antes de mergulharmos em conceitos mais avançados, é importante familiarizar-se com alguns aspectos básicos da sintaxe do Python.

Indentação
No Python, a indentação (espaços ou tabulações no início de uma linha) é utilizada para delimitar blocos de código. Diferente de outras linguagens que utilizam chaves ou palavras-chave, o Python utiliza a indentação para determinar o escopo das declarações. Por exemplo: 

if condition:

    # Bloco de código se a condição for verdadeira

    instrucao1
    instrucao2

else:

    # Bloco de código se a condição for falsa

    instrucao3
    instrucao4
 

SOA_LID_Importante-1.png	
Importante
É fundamental manter uma indentação consistente em todo o código para evitar erros de sintaxe.
 

Comentários
Os comentários são linhas de texto no código que são ignoradas pelo interpretador do Python. Eles são utilizados para explicar ou documentar o código. No Python, os comentários de uma única linha começam com o símbolo #, enquanto os comentários de várias linhas são delimitados por três aspas """ . Por exemplo:

# Este é um comentário de uma única linha

"""
Este é um comentário
de várias linhas
"""
 

Sensibilidade a maiúsculas e minúsculas
Python distingue entre maiúsculas e minúsculas. Portanto, variável, Variável e VARIÁVEL são consideradas variáveis diferentes.

 

Ponto e vírgula
Diferente de outras linguagens, o Python não requer o uso de ponto e vírgula (;) ao final de cada instrução. No entanto, se você desejar escrever várias instruções em uma única linha, pode separá-las com um ponto e vírgula. Por exemplo:

instrucao1; instrucao2; instrucao3
 

Uso de parênteses
Os parênteses são utilizados para agrupar expressões, definir funções e realizar chamadas a funções. Por exemplo:

resultado = (a + b) * c

Tipos de dados básicos
Em Python, os tipos de dados básicos são as categorias nas quais podemos classificar os valores que utilizamos em nossos programas. Compreender os diferentes tipos de dados é fundamental para trabalhar com variáveis e realizar operações em Python. Os tipos de dados básicos incluem:

Inteiros (int)
Os números inteiros são aqueles que não têm parte decimal. Em Python, são representados simplesmente escrevendo o número sem aspas nem pontos decimais. Por exemplo:

idade = 25
quantidade = 100
 

Flutuantes (float)
Os números flutuantes, também conhecidos como números de ponto flutuante, são aqueles que têm uma parte decimal. Em Python, são representados utilizando um ponto para separar a parte inteira da parte decimal. Por exemplo:

preço = 9.99
altura = 1.75
 

Cadeias de texto (strings)
As cadeias de texto, ou simplesmente cadeias, são sequências de caracteres encerradas entre aspas simples ('...') ou duplas ("..."). São utilizadas para representar texto em Python. Por exemplo:

nome = "Juan"
mensagem = '¡Hola, mundo!'
Você pode incluir caracteres especiais nas cadeias utilizando o caractere de escape \. Por exemplo, para incluir aspas dentro de uma cadeia, você pode usar \' ou \". Também pode utilizar a notação de tripla aspa ('''...''' ou """...""") para criar cadeias de várias linhas.

 

Booleanos
Os valores booleanos representam os valores de verdade: True (verdadeiro) e False (falso). São comumente utilizados em expressões condicionais e operações lógicas. Por exemplo:

é_maior_de_idade = True
tem_desconto = False
 

SOA_LID_Ten en cuenta-1.png	
Tenha em mente
Os valores booleanos em Python começam com uma letra maiúscula: True e False.
 

Estes são os tipos de dados básicos em Python. Ao longo deste módulo, você aprenderá a trabalhar com esses tipos de dados, realizar operações e utilizá-los em diferentes contextos.