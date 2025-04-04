# 1. ord() em Python
# A função ord() retorna o valor Unicode (código numérico) de um caractere específico.
# Exemplo:

print(ord('A'))  # Saída: 65
print(ord('a'))  # Saída: 97


# 2. chr() em Python
# A função chr() faz o inverso do ord(): converte um código Unicode de volta para o caractere correspondente.
# Exemplo:

print(chr(65))  # Saída: 'A'
print(chr(97))  # Saída: 'a'
# 3. Transformar uma string em lista de letras
# Use list() para dividir uma string em caracteres individuais:

lista_letras = list("texto")
print(lista_letras)  # Saída: ['t', 'e', 'x', 't', 'o']


# 4. f-strings (formatação de strings)
# F-strings permitem inserir variáveis diretamente em strings usando {var}.
# Exemplo:


nome = "Alice"
idade = 25
print(f"Olá, {nome}! Você tem {idade} anos.")  
# Saída: "Olá, Alice! Você tem 25 anos."


# 5. Acessar letras específicas por índice
# Strings são sequências indexadas (começando em 0):

palavra = "Python"
print(palavra[0])  # Saída: 'P'
print(palavra[3])  # Saída: 'h'
# 6. Acessar um índice inexistente
# Se tentar acessar um índice fora do intervalo, ocorre um erro IndexError:

palavra = "casa"
print(palavra[6])  # IndexError: string index out of range


# 7. Tabela ASCII
# É um padrão que mapeia caracteres (letras, números, símbolos) para códigos numéricos (0 a 127).
# Exemplos:

# A → 65
# a → 97
# 0 → 48
# ! → 33
# Observação: Python usa Unicode (que estende a ASCII), suportando mais caracteres (como emojis e acentos).
