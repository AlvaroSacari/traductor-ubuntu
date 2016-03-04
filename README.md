# traductor-ubuntu

traductor que usa la api del traductor de google | para ubuntu

##Dependencias:

- **xsel** *(capturador de la selección actual para poder manipularla)*

  ```sudo apt-get install xsel```
  
- **libnotify-bin** *(sistema de notificaciones de Ubuntu)*

  ```sudo apt-get install libnotify-bin```
  
- **wget** *(para utilizar la traducción de Google)*

  ```sudo apt-get install wget```

##Instalación

1. dar permisos permisos de ejecución al archivo `traductor_alv` y copiarlo al directorio `/usr/bin`

  ```
  chmod +x traductor_alv
  sudo cp traductor_alv /usr/bin
  ```

2. Por último crea un atajo para el traductor en `Configuración del sistema > Teclado`

##Uso

selecciona el texto de cualquier parte, puede ser de un archivo .pdf, de un archivo de texto, del navegador, etc, y presiona la combinación de teclas para lanzar el traductor.
