# Guía para resolver el EPIC Challenge

## Introducción
Este documento proporciona instrucciones paso a paso para resolver el EPIC Challenge, un ejercicio tipo CTF (Capture The Flag) que implica navegación por directorios, búsqueda de archivos clave, descifrado de contraseñas, y desencriptación de archivos.

## Objetivos del Challenge
Según la información proporcionada, tu misión es:
1. Navegar por una compleja estructura de directorios
2. Encontrar una contraseña cifrada con el cifrado César
3. Encontrar un archivo objetivo encriptado
4. Desencriptar el archivo objetivo usando la contraseña encontrada

## Acceso al Entorno
```
URL: http://shortline.proxy.rlwy.net:53282/
Usuario: epic_guest
Contraseña: epic_guest
```

### Alternativa en local
Alternativamente, puedes acceder vía SSH:
```
https://drive.google.com/drive/u/0/folders/1gY8ZtA_0j8u8SzFG6WW-2v7EmTt2oMSS
```

```
ssh epic_guest@localhost -p 2222
Contraseña: epic_guest
```

## Estructura del Entorno
El script configura el siguiente entorno:
- 20 directorios principales (dir1 a dir20)
- Cada directorio principal contiene 5 subdirectorios (maybehere1 a maybehere5)
- Cada subdirectorio contiene 5 archivos (file1.txt a file5.txt)
