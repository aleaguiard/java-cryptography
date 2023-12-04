# Aplicación de Criptografía en Java

## Descripción

Este proyecto Java implementa una aplicación de criptografía que incluye funcionalidades como inicio de sesión, cifrado y descifrado de mensajes. La aplicación utiliza algoritmos de hash y cifrado para garantizar la seguridad de la información.

## Funcionalidades

### 1. Inicio de Sesión

- La aplicación permite a los usuarios iniciar sesión ingresando un nombre de usuario y una contraseña.
- Se proporcionan tres cuentas de usuario predefinidas: administrador (Pepe, contraseña: 0000), usuario2 (Elena, contraseña: 1111) y usuario3 (Alberto, contraseña: 2222).
- Se implementa un mecanismo de bloqueo después de tres intentos fallidos de inicio de sesión.

### 2. Cifrado de Mensajes

- Utiliza el algoritmo de cifrado DES (Data Encryption Standard) para cifrar mensajes.
- Genera una clave secreta (paloEspartano) para el cifrado.
- Permite al usuario introducir una frase para ser cifrada y muestra el mensaje cifrado.

### 3. Descifrado de Mensajes

- Permite descifrar un mensaje previamente cifrado utilizando la clave secreta generada durante el cifrado.
- Muestra tanto el mensaje cifrado como el mensaje descifrado.

### 4. Hashing de Credenciales

- Utiliza el algoritmo de hash SHA-512 para generar un resumen hash a partir del nombre de usuario y la contraseña.
- Almacena los resúmenes hash de las cuentas de usuario predefinidas para la verificación durante el inicio de sesión.





