## Boas vindas
print('Olá você esta no chat do ifood')

# para digitar o nome
nome = input('Digite seu nome: ')

# aparece o nome e pede para escolher uma opção
print(f'\n{nome}, Digite o numero de uma opção desejada:\n')

# mostra que e o menu principal
print('Menu pricipal:')

opcao = 0

# Menu pricipal
def menuPrincipal():
    opcao = float(input("\n1 - Pedidos.\n2 - Estabelecimento.\n3 - Área de risco .\n4 - Problemas com a máquina Gertec.\n5 - Sair do atendimento.\n\nOpção: "))
    if opcao == 2:
        escolhadois()
    


def escolhadois():
        print('\n2estabelecinemto:')
        opcao = float(input("\n1 - Estabelecimento fechado,nao consigo escanear o qrcode no estabelecimento .\n2 - Estabecimento fechado .\n3 - Pedido cancelado na tela .\n4 - Retorna ao menu principal \n\nOpção: "))
        if opcao==1:

             Atendimento_Ifood=input("Tira uma foto")
             print("Estamos realocando sua corrida, a taxa de relocação.Estará disponível em até 2 dias úteis.")

             Atendimento_Ifood=input("Mais alguma duvida(sim ou não)")
             entregador_Ifood="não"

             print("O IFOOD agradece o contato. Até a próxima!")



        if opcao==2:

             Atendimento_Ifood=input("Tira uma foto")
             print("Estamos realocando sua corrida, a taxa de relocação.Estará disponível em até 2 dias úteis.")

             Atendimento_Ifood=input("Mais alguma duvida(sim ou não)")
             entregador_Ifood="não"

             print("O IFOOD agradece o contato. Até a próxima!")


        if opcao==3:
             
             entregador_Ifood=input("Nome do Funcionario")        
             print("Estamos realocandosua corrida, ataxa de relocação.Estará disponívelem até 2 dias úteis.")
             
             Atendimento_Ifood=input("Seu problema foi resolvido?(sim ou não)")
             entregador_Ifood="sim"

             print("O IFOOD agradece o contato. Até a próxima!")

        if opcao == 4:
             menuPrincipal()  
