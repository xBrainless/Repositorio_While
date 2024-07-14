# Repositorio_While
 testando git

##EXERCICIO 1

carrinho = []

while True:
    produto = input('Digite o nome do produto: ')
    if not produto:
        break
    quantidade = int(input('E também a quantidade? '))
    adicionar = [produto, quantidade]
    carrinho.append(adicionar)

print(carrinho)
