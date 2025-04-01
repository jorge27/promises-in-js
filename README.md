# Proyecto de Solicitud de Datos y Despliegue en Tabla

Este repositorio se utiliza para evaluar la comprensión y aplicación de peticiones POST en JavaScript, junto con la manipulación del DOM para desplegar datos en una tabla. El objetivo es demostrar el uso efectivo de ``fetch()`` para realizar peticiones POST y la integración de la respuesta en una interfaz web.

El siguiente es un ejemplo de como se usa el método ``fetch()`` para la solicitud de datos a través de una petición POST

    ```bash
    fetch("https://ejemplo-api.com/usuarios", {
        method: "POST",
        headers: {
            "Content-Type": "application/json"
        },
        body: JSON.stringify(datosEnvio)
    })


## Instrucciones para Clonar el Repositorio

1. Abre tu terminal o línea de comandos.
2. Navega al directorio donde deseas clonar el repositorio.
3. Ejecuta el siguiente comando 

   ```bash
   git clone https://github.com/jorge27/promises-in-js.git

4. Ingresa al directorio del repositorio clonado:
    ````bash
    cd promises-in-js
    
## Requisitos del Proyecto
El proyecto debe cumplir con los siguientes requisitos:
- Uso del constructor ``Promise()``
- Uso de ``.then()``, ``.catch()`` y ``.finally()``
- Despliegue de datos: Procesar la respuesta de la API y mostrar los datos en una tabla HTML.
- Pruebas Unitarias: Incluir pruebas unitarias que verifiquen el correcto funcionamiento de la petición y la actualización de la tabla.
- Tiempo de Ejecución: El proyecto debe completarse en un máximo de 1 hora.





