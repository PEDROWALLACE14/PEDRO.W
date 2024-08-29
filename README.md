

num1 = 12

num2 = int(15)

print(num1)
# Exibe em tela o conteúdo da variável num1

print(type(num1))
# Exibe em tela o tipo de dado da variável num1

print(num2)
print(type(num2))

     
12
<class 'int'>
15
<class 'int'>

num1 = 12
# Será automaticamente identificado pelo interpretador como dado do tipo int

num2 = int(15)
# Será manualmente identificado pelo interpretador como dado do tipo int

num3 = str(15)
# Será manualmente identificado pelo interpretador como dado do tipo string

print(type(num1))
print(type(num2))
print(type(num3))

     
<class 'int'>
<class 'int'>
<class 'str'>
Float - Número de ponto flutuante / com casas decimais.


num3 = 12.8
# Ao inserir o ponto demarcador de casa decimal, tal número será
# automaticamente reconhecido pelo interpretador como tipo float

num4 = float(19.0)

print(num3)
print(type(num3))

print(num4)
print(type(num4))

     
12.8
<class 'float'>
19.0
<class 'float'>
String - Texto composto de qualquer caractere alfanumérico.


palavra1 = 'palavra'
# Todo conteúdo contido entre aspas é lido como texto pelo interpretador

palavra2 = "marca d'água"
# Uso de aspas duplas para não gerar conflito com o apóstrofo '

frase1 = 'Uma frase qualquer'

frase3 = 'Ela tinha 8 anos'

frase3 = str('Outra frase qualquer')

print(palavra1)
print(palavra2)

print(frase3)
print(type(frase3))

     
palavra
marca d'água
Outra frase qualquer
<class 'str'>

codigo1 = '887237'
# Apesar de composto apenas por números, o atributo da variável codigo1 por
# conta de sua sintaxe é um texto, tipo de dado string

print(codigo1)
print(type(codigo1))

     
887237
<class 'str'>
Tupla - Conjunto de elementos imutável


# Método simples para guardar mais de um dado/valor atribuído a uma variável.

tupla = ('Ana', 'Fernando', 3, 19.90)
# Cada elemento declarado conforme sua sintaxe.

print(tupla)
print(type(tupla))

     
('Ana', 'Fernando', 3, 19.9)
<class 'tuple'>
List - Listas - Conjunto de elementos indexados e mutáveis


# Basicamente o mesmo tipo de dado array de outras linguagens de programação.

lista = [2, 'Pedro', 15.9]
# Cada elemento possui um número de índice, começando em 0.

lista2 = list([1, 'Maria', 19.99])

print(lista)
print(type(lista))

print(lista2)

     
[2, 'Pedro', 15.9]
<class 'list'>
[1, 'Maria', 19.99]

lista_compras = ['Arroz',
                 'Açúcar',
                 'Café',
                 'Carne',
                 'Frutas',
                 'Pão',
                 'Sabão em pó']
# Apenas por organização, os elementos de uma lista podem ser organizados
# em linhas separadas, desde que mantenham a indentação

print(lista_compras)

     
['Arroz', 'Açúcar', 'Café', 'Carne', 'Frutas', 'Pão', 'Sabão em pó']
Dict - Dicionários - Estrutura de dados baseada em 'chave : valor'


dicionario = {'Nome':'Fernando', 'Idade':32}
# Na primeira entrada, 'Nome' é a chave e 'Fernando' é o valor.

print(dicionario)
print(type(dicionario))

     
{'Nome': 'Fernando', 'Idade': 32}
<class 'dict'>

dicionario = {'Nome':'Fernando',
              'Idade': 32,
              'Altura': 1.90,
              'Peso': '120kg'}
# Por uma questão de organização, os itens de um dicionário podem
# ser dispostos em linhas independentes, desde que respeitando a
# indentação.

print(dicionario)

     
{'Nome': 'Fernando', 'Idade': 32, 'Altura': 1.9, 'Peso': '120kg'}
Bool - Booleano (True / False)


condicao1 = True
# Tipo de dado usado em expressões/proposições lógicas, onde o retorno é True
# ou False, referente a Verdadeiro ou Falso, válido ou inválido, ligado ou
# desligado, etc... de acordo com a proposição.

print(condicao1)
print(type(condicao1))

     
True
<class 'bool'>
