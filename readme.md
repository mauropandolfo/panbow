# Panbow
Panbow es una aplicación en Go que convierte la salida de texto en un efecto de arcoíris. La aplicación toma el texto de entrada y lo imprime en colores para crear un efecto visual interesante.

## Instalación
Asegúrate de tener Go instalado en tu sistema. Luego, puedes compilar y ejecutar el programa usando los siguientes comandos:

```bash
go build -o panbow
```
```bash
go install panbow
```
## Uso
La aplicación Panbow está diseñada para funcionar con pipes. Puedes usarla de la siguiente manera:

```bash
fortune | panbow
```
Esto tomará la salida del comando fortune (o cualquier otro flujo de texto) y la pasará a panbow para que la salida de texto se presente en colores arcoíris.

## Demo
```bash
fortune| cowsay | panbow
```
![democowsay](https://i.imgur.com/eidczDM.png)

### Disclaimer.
El codigo esta basado en el proyecto presentado en la siguiente [URL](https://flaviocopes.com/go-tutorial-lolcat/), con una vuelta de tuerca para darle un valor agregado.

