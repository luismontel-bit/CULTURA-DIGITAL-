# CULTURA-DIGITAL-
Tareas semana 13

Python
# Creamos una variable para controlar que el menú siga activo
opcion = 0  # Inicializamos la variable opcion en 0

# Mientras el usuario no seleccione la opción 3, el menú seguirá mostrando
while opcion != 3:  # Ciclo while para repetir el menú
    # Mostramos el menú al usuario
    print("---- MENÚ ----")
    print("1. Saludar")
    print("2. Mostrar mensaje")
    print("3. Salir")

    # Pedimos al usuario que ingrese una opción
    opcion = int(input("Selecciona una opción: "))  # Convertimos la respuesta a número entero

    # Si la opción es 1, pedimos el nombre y saludamos
    if opcion == 1:  
        nombre = input("Escribe tu nombre: ")  # Pedimos el nombre del usuario
        print("Hola", nombre, "¡Mucho gusto!")  # Mostramos saludo con su nombre

    # Si la opción es 2, mostramos un mensaje personalizado
    elif opcion == 2:
        print("¡Sigue adelante! Eres capaz de grandes cosas.")  # Mensaje personalizado

    # Si la opción es 3, despedimos al usuario
    elif opcion == 3:
        print("Gracias por usar el programa. ¡Hasta luego!")  # Mensaje de salida

    # Si elige cualquier otra opción, mostramos mensaje de error
    else:
        print("Opción no válida, intenta de nuevo.")  # Mensaje cuando no es una opción correcta
