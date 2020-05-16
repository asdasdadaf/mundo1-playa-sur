# mundo1-playa-sur
me_aburro = True
import random
vida1=120
vida2 = 60
ve1= 20
partida1 = False
while not vida1 == 0 or ve1 == 0:
    if partida1 == False:

        atake = input("Con quien quieres atacar?Con red o con red?")
        if atake == "red":
            print("Y a quien atacas? A cerdo con palo,con " + str(ve1) + "puntos de vida,.")
            atake2 = input("")
            if atake2 == "cerdo con palo":
                ve1 = ve1 - 26
                if ve1 >0:
                    atake3 = random.randint("1,1")
                    if atake3 == 1:
                        vida1 = vida1 - 7
                elif vida1 <0:
                    print("Perdiste...")
                    partida1 = True
                else:
                    print("Ganaste!!")
                    partida1 = True
                    vida1 = 120
                    ve1 = 20
                    ve2 = 40
                    partida2 = False
                    while not vida1 < 0 or ve1 < 0 and ve2 < 0:
                        if partida2 == False:

                            atake = input("Con quien quieres atacar?Con red o con red?")
                            if atake == "red":
                                print("Y a quien atacas? A cerdo con palo,con " + str(
                                    ve1) + "puntos de vida,o a bandido, con " + str(ve2) + " puntos de vida?")
                                atake2 = input("")
                                if atake2 == "cerdo con palo":
                                    ve1 = ve1 - 26
                                if atake2 == "bandido":
                                    ve2 = ve2 - 26
                                if ve1 > 0:
                                    vida1 = vida1 - 7
                                if ve2 > 0:


                                    vida1 = vida1 - 10
                                if vida1 > 0 and ve1 > 0 or ve2 > 0:
                                    print("Al primer enemigo le queda " + str(
                                        ve1) + " puntos de vida, y al segundo le queda " + str(
                                        ve2) + " puntos de vida")
                                    print("Y a red le quedan " + str(vida1) + "puntos de vida")
                                elif vida1 < 0:
                                    print("Perdiste...")
                                    partida2 = True

                                elif ve1 < 0 and ve2 < 0:
                                    print("Ganaste!!!")
                                    partida2 = True
                                    vida1 = 120
                                    ve1 = 125
                                    turnos_de_carga =3
                                    partida3 = False
                                    while not vida1 < 0 or ve1 < 0:
                                        if partida3 == False:

                                            atake = input("Con quien quieres atacar?Con red o con red?")
                                            if atake == "red":
                                                print("Y a quien atacas? A la bestia,con " + str(ve1) + "puntos de vida.")
                                                ataque=input("")
                                                if ataque=="la bestia":
                                                    ve1 = ve1 - 26
                                                turnos_de_carga = turnos_de_carga - 1
                                                if turnos_de_carga == 0:
                                                    vida1 = vida1 - 48
                                                    turnos_de_carga = 3
                                                if vida1 > 0 and ve1 > 0 or ve2 > 0:
                                                    print("Al primer enemigo le queda " + str(
                                                        ve1) + " puntos de vida, y le quedan " + str(turnos_de_carga) + " turnos para atacar.")
                                                    print("Y a red le quedan " + str(vida1) + "puntos de vida")
                                                elif vida1 < 0:
                                                    print("Perdiste...")
                                                    partida3 = True

                                                elif ve1 < 0 and ve2 < 0:
                                                    print("Ganaste!!!")
                                                    partida3 = True
                                                    vida1 = 120
                                                    ve1 = 20
                                                    turnos = 3
                                                    ve2 = 125
                                                    partida4 = False
                                                    while not vida1 < 0 or ve1 < 0 and ve2 < 0:
                                                        if partida4 == False:

                                                            atake = input("Con quien quieres atacar?Con red o con red?")
                                                            if atake == "red":
                                                                print("Y a quien atacas? A cerdo con palo,con " + str(
                                                                    ve1) + "puntos de vida,o a la bestia, con " + str(
                                                                    ve2) + " puntos de vida?")
                                                                atake2 = input("")
                                                                if atake2 == "cerdo con palo":
                                                                    ve1 = ve1 - 26
                                                                if atake2 == "la bestia":
                                                                    ve2 = ve2 - 26

                                                                if ve1 > 0:
                                                                        vida1 = vida1 - 7
                                                                if ve2 > 0:
                                                                        turnos = turnos - 1
                                                                        if turnos == 0:
                                                                            vida1 = vida1 -48
                                                                            turnos = 3

                                                                if vida1 > 0 and ve1 > 0 or ve2 > 0:
                                                                    print("Al primer enemigo le queda " + str(
                                                                        ve1) + " puntos de vida, y al segundo le queda " + str(
                                                                        ve2) + " puntos de vida. A la bestia le quedan\n " + str(turnos) + " turnos para atacar.")
                                                                    print("Y a red le quedan " + str(
                                                                        vida1) + "puntos de vida")
                                                                elif vida1 < 0:
                                                                    print("Perdiste...")
                                                                    partida4 = True

                                                                elif ve1 < 0 and ve2 < 0:
                                                                    print("Ganaste!!!")
                                                                    partida4 = True
                                                                    vida1 = 120
                                                                    partida5 = False
                                                                    vida2 = 60
                                                                    ve1 = 54


                                                                    while not vida1 < 0 or ve1 < 0:

                                                                        if partida5 == False:

                                                                            atake = input(
                                                                                "Con quien quieres atacar?Con red o con red?")
                                                                            if atake == "red":
                                                                                print(
                                                                                    "Y a quien atacas? A el guardia real,con " + str(
                                                                                        ve1) + "puntos de vida.")
                                                                                ataque = input("")
                                                                                if ataque == "guardia real":
                                                                                    ve1 = ve1 - 26
                                                                                    vida1 = vida1 - 6
                                                                                if vida1 > 0 and ve1 > 0 or ve2 > 0:
                                                                                    print(
                                                                                        "Al primer enemigo le queda " + str(
                                                                                            ve1) + " puntos de vida.")
                                                                                    print("Y a red le quedan " + str(
                                                                                        vida1) + "puntos de vida")
                                                                                elif vida1 < 0:
                                                                                    print("Perdiste...")
                                                                                    partida3 = True

                                                                                elif ve1 < 0:

                                                                                    print("Pasas de oleada!!")
                                                                                    partida5 = True
                                                                                    partida6 = False
                                                                                    ve1 = 54




                                                                                    while not vida1 < 0 or ve1 < 0:

                                                                                        if partida6 == False:

                                                                                            atake = input(
                                                                                                "Con quien quieres atacar?Con red o con red?")
                                                                                            if atake == "red":
                                                                                                print(
                                                                                                    "Y a quien atacas? A el guardia real,con " + str(
                                                                                                        ve1) + "puntos de vida.")
                                                                                                ataque = input("")
                                                                                                if ataque == "guardia real":
                                                                                                    ve1 = ve1 - 26
                                                                                                    vida1 = vida1 - 6
                                                                                                if vida1 > 0 and ve1 > 0 or ve2 > 0:
                                                                                                    print(
                                                                                                        "Al primer enemigo le queda " + str(
                                                                                                            ve1) + " puntos de vida.")
                                                                                                    print(
                                                                                                        "Y a red le quedan " + str(
                                                                                                            vida1) + "puntos de vida")
                                                                                                elif vida1 < 0:
                                                                                                    print("Perdiste...")
                                                                                                    partida3 = True

                                                                                                elif ve1 < 0:

                                                                                                    print("Pasas de oleada!!")
                                                                                                    partida6 = True
                                                                                                    partida7 = False
                                                                                                    ve1 = 53
                                                                                                    ve2 = 53
                                                                                                    ve3 = 240
                                                                                                    ve4 =54

                                                                                                    while not vida1 < 0 or ve1 < 0 and ve2 < 0 and ve3 <0 and ve4 <0:
                                                                                                        if partida7 == False:

                                                                                                            atake = input(
                                                                                                                "Con quien quieres atacar?Con red o con red?")
                                                                                                            if atake == "red":
                                                                                                                print(
                                                                                                                    "Y a quien atacas?A el guardia real,con " + str(
                                                                                                                        ve1) + "puntos de vida,a el guardia real 2, con " + str(
                                                                                                                        ve2) + " puntos de vida, a el caballero,\n con " + str(ve3) + " o a la bomba nuclear,\n"
                                                                                                                                                                                      
                                                                                                                                                                                      "con" + str(ve4) + " puntos de vida?")

                                                                                                                atake2 = input("")
                                                                                                                if atake2 == "guardia real":
                                                                                                                    ve1 = ve1 - 26
                                                                                                                if atake2 == "guardia real 2":
                                                                                                                    ve2 = ve2 - 26
                                                                                                                if atake2 == "caballero":
                                                                                                                    ve3 = ve3 - 26
                                                                                                                if atake2 == "bomba nuclear":
                                                                                                                    ve4 = ve4 - 26
                                                                                                                if ve1 > 0:
                                                                                                                    vida1 = vida1 - 6
                                                                                                                if ve2 > 0:
                                                                                                                    vida1 = vida1 - 6
                                                                                                                if ve3 > 0:
                                                                                                                    vida1 = vida1 - 15
                                                                                                                if ve4 < 0:
                                                                                                                    print("La bomba explotó!!")
                                                                                                                    vida1 = 128
                                                                                                                    ve1 = -1
                                                                                                                    ve2 = -1
                                                                                                                    ve3 = -1
                                                                                                                    ve4 = -1
                                                                                                                if vida1 > 0 and ve1 > 0 or ve2 > 0 or ve3 >0:
                                                                                                                    print(
                                                                                                                        "Al primer enemigo le queda " + str(ve1)
                                                                                                                             + " puntos de vida, al segundo le queda " + str(ve2)
                                                                                                                             + " puntos de vida, al tercero le queda " + str(ve3) + " de vida, y a la bomba nuclear le faltan " + str(ve4) + "para explotar")
                                                                                                                    print(
                                                                                                                        "Y a red le quedan " + str(
                                                                                                                            vida1) + "puntos de vida")
                                                                                                                elif vida1 < 0:
                                                                                                                    print(
                                                                                                                        "Perdiste...")
                                                                                                                    partida7 = True

                                                                                                                elif ve1 < 1 and ve2 < 1 and ve3 <0 and ve4 <1:

                                                                                                                    partida7 = True
                                                                                                                    print("Ganaste!!")
                                                                                                                    partida8 = False
                                                                                                                    penis = False


                                                                                                                    while not partida8:



                                                                                                                        print("Has derrotado a la caballería!!")
                                                                                                                        while me_aburro:


                                                                                                                            print("Conseguiste a Chuck!!")
                                                                                                                            while me_aburro:

                                                                                                                                while penis == False:


                                                                                                                                   print("Chuck es un poderoso mago que ataca a todos los enemigos a la vez!!!")
                                                                                                                                   while penis == False:

                                                                                                                                       print("No hace falta escribir a su objetivo, ataca automaticamente.")
                                                                                                                                       while penis == False:

                                                                                                                                           print("Has completado el primer mundo: Playa sur.")
                                                                                                                                           while penis == False:




                                                                                                                                                print("Has empezado el mundo 2, Meseta de Cobalto!")
                                                                                                                                                print("Memorizate el nombre, porque sino,  no podrás entrar\n al siguiente mundo. Ve al otro link")

                                                                                                                                                penis = True

