# Repositorio_While
 testando git

##EXERCICIO 1

carrinho = []

while True:
    produto = input('Digite a porra do produto: ')
    if not produto:
        break
    quantidade = int(input('E a quantidade? '))
    adicionar = [produto, quantidade]
    carrinho.append(adicionar)

print(carrinho)