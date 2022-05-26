Nome = input("Digite Seu Nome :")
Nota1 = int(input("Digite Sua Primeira Nota :"))
Nota2 = int(input("Digite Sua Segunda Nota:"))
Nota3 = int(input("Digite Sua Terceira Nota: "))
Media= (Nota1+Nota2+Nota3)/3
if Media >= 7:
    print("{} EM APROVADO".format(Nome))
else:
    if Media <= 5:
        print("{} EM REPROVADO".format(Nome))
    else:
        if Media > 5.1 and Media < 6.9:
             print("{} EM RECUPERAÇÃO".format(Nome))
