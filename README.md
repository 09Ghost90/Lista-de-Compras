# Lista-de-Compras

import os

lista = []

while True:
  print("Escolha um das opções:")
  opcao = input("[i]nserir, [a]pagar, [l]istar")

  if opcao == "a"
    os.system("cls")
    valor = input("Digite o valor")
    lista.append(valor)

  elif opcao == 'a'
    os.system("cls")
    indice_str = input("Digite o indice para apagar: ")

  try:
    indice = int(indice_str)
    del lista[indice]

  except ValueError:
    print("Digite apenas número INT")

  except IndexError:
    print("Esse valor indicado não está na Lista!")

  except Exception:
    print("Erro Desconhecido")

  elif opcao == "i"
    os.system("cls")

  for i, valor in enumerate(lista):
    print(i, valor)

else:
  print("Selecione uma opção válida!")

