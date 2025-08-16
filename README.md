[README.md](https://github.com/user-attachments/files/21815712/README.md)
# Conversor de Monedas 

Este es un proyecto simple de conversión de monedas desarrollado en Java 17. Utiliza una API externa para obtener tasas 
de cambio en tiempo real y la biblioteca Gson para analizar las respuestas en formato JSON, convirtiéndolas en objetos Java.

## Tecnologías Utilizadas 

- **Java 17** – Lenguaje de programación principal.
- **Gson** – Biblioteca de Google para el manejo de JSON en Java.
- **HttpClient** (Java 11+) – Para realizar peticiones HTTP a la API de tasas de cambio.

## Clases y Funcionalidades 

### Calculos.java

Esta clase es responsable de manejar la lógica relacionada con las conversiones de moneda. Aquí se definen métodos para
almacenar valores de moneda, realizar conversiones y obtener mensajes de respuesta.

### ConsultaConversion.java

Clase responsable de realizar consultas a una API externa para obtener las tasas de cambio entre diferentes monedas.

### GeneradorDeArchivos.java

Esta clase se encarga de guardar el historial de consultas en un archivo de texto.

### Principal.java

Este es el punto de entrada principal del programa. En esta clase se gestiona la interacción con el usuario a través 
de la consola. Muestra un menú de opciones y maneja las conversiones de moneda, permitiendo al usuario ingresar 
la moneda base, la moneda de destino y el monto a convertir. Además, ofrece la posibilidad de realizar múltiples 
conversiones de manera consecutiva hasta que el usuario decida finalizar.

##  Desarrollado por
- CCC

## Instrucciones de Uso 

1. Clona este repositorio en tu máquina local.
2. Abre el proyecto en IntelliJ IDEA u otro IDE de tu elección.
3. Importa la libreria Gson en el proyecto.
4. Ejecuta la clase Principal.java para iniciar el programa.
5. Sigue las instrucciones en pantalla para realizar conversiones de moneda.

Enjoy!


