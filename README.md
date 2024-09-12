# Act5_funciones_5J
Ejemplo de uso de funciones de w3school
print("ejemplo de funciones")

#declarando funciones
def hola():
    print("alguien uso la funcion hola")

def chat(mensa):
    print(f"Chat {mensa}")

def ellacontesta(mensa):
    print(f"chat ella: {mensa}")

def escribenombre(ap,n):
    print(f"Tu nombre completo es: {n}{ap}")
    def suma(a,b):
        s=a+b
        return s

    #llamadas de funciones
    hola()
    chat("Que bonito estas bangchan")
    ellacontesta("graciaas")
    escribenombre("Villar","Daniel")
    print("Operacion suma")
    c1=int("ingresa un numero")
    c2=int("ingresa un numero")
    damesuma=suma(c1,c2)
    print(f"la suma de {c1}+{c2}={damesuma}")
