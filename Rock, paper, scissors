rejouer = 'oui'
while rejouer == 'oui' :
    print('Nous allons jouer à pierre/feuille/ciseaux !')
    jeu = input('Pierre, feuille ou ciseaux ? ')
    score = 0
    from random import randint
    jeu1: int = randint(1, 3)
    if jeu1 == 1:
            jeu1 = 'feuille'
    elif jeu1 == 2:
            jeu1 = 'pierre'
    elif jeu1 == 3:
            jeu1 = 'ciseaux'
    if jeu == 'pierre':
            if jeu1 == 'pierre':
                print('L\'ordinateur a joué pierre, égalité !')
    elif jeu1 == 'feuille':
                print('L\'ordinateur a joué feuille, vous avez perdu !')
    elif jeu1 == 'ciseaux':
                print('L\'ordinateur a joué ciseaux, vous avez gagné !')
                score = score + 1
    elif jeu == 'feuille':
            if jeu1 == 'pierre':
                print('L\'ordinateur a joué pierre, vous avez gagné !')
                score = score + 1
    elif jeu1 == 'feuille':
                print('L\'ordinateur a joué feuille, égalité !')
    elif jeu1 == 'ciseaux':
            print('L\'ordinateur a joué ciseaux, vous avez perdu !')
    elif jeu == 'ciseaux':
            if jeu1 == 'pierre':
                print('L\'ordinateur a joué pierre, vous avez perdu !')
    elif jeu1 == 'feuille':
            print('L\'ordinateur a joué feuille, vous avez gagné !')
            score = score + 1
    elif jeu1 == 'ciseaux':
            print('L\'ordinateur a joué ciseaux, égalité !')
    print('Ton score est de ' + str(score) + ' point(s).')
