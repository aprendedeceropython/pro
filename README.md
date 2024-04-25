# Práctica para Pros de Python  

### Como participar en la práctica

- Haga un fork a su cuenta GitHub
- Para subir cambios al repositorio de la práctica solicite una PR(1)

La práctica para el nivel pro consiste en lo siguiente:

### Condiciones  

- Elaborar una aplicación que pueda almacenar MFA de las distintas cuentas y generar el código de autenticación
  en función a la cuenta solicitada
- Debe ser capaz de añadir nuevas cuentas a través de dos medios:
      - Escaneando un código QR
      - Secret Key
- Los datos se almacenaran en una BBDD(2) SQLite
- Posibilidad de hacer respaldo de todas las claves MFA(3) en archivo plano
- Posibilidad de recuperar todas las claves MFA(3) exportadas (Esto puede generar duplicados, pero es valido)
- La funcionalidad de exportación de los datos debe tener la posibilidad de ser cifrada con una contraseña que se solicitara al momento de la exportación,
  esta contraseña no será almacenada en ningún lugar.
- La importación debe validar que la contraseña ingresada es válida para poder desencriptar los datos e importarlos a la BD(3)
- Debe tener una opción para activar la solicitud de contraseña para mostrar Código MFA(3)
- Se recomienda trabajar en equipo

## Opcionales

- Poder subir un respaldo a la nube (Google Drive, DropBox, OneDrive, etc.)

## Obligatorio

- Todo el código debe estar en Python
- Posibilidad de llamar a rutinas o CO-rutinas en otro lenguaje de programación

## Notas finales

- En caso de trabajar el proyecto de forma no colaborativa, abra una nueva branch con el nombre PRO\_<NOMBRE>  
  El nombre puede ser un alias, su cuenta de GitHub, etc.
- No Cambiar el archivo README.md, podeis añadir uno o mas archivos con la tormenta de ideas
- Es muy importante que os pongais en contacto y discutan las bases del proyecto. Podeis solicitar un canal en Telegram para la dicusion del mismo.
- La practica esta sujeta a sugerencias

### ❤ HAPPY CODING ❤

(1) Pull Request  
(2) Base(s) de dato(s)  
(3) Multi factor de Autenticación
