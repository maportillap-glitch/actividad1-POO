# actividad1-POO

class Edades:
    def calcular_edalber(edjuan):
        return 2 * edjuan / 3

    def calcular_edana(edjuan):
        return 4 * edjuan / 3

    def calcular_edmama(edjuan, edalber, edana):
        return edjuan + edalber + edana


class Main:
    def main():
        edjuan = float(input("Ingrese la edad de juan: "))

        edalber = Edades.calcular_edalber(edjuan)
        edana = Edades.calcular_edana(edjuan)
        edmama = Edades.calcular_edmama(edjuan, edalber, edana)

        print("Edad de Juan:", edjuan)
        print("Edad de Alberto:", edalber)
        print("Edad de Ana:", edana)
        print("Edad de mama:", edmama)

Main.main()
