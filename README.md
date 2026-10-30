# Memory

Juego de memoria desarrollado en Python con Turtle y Free Python Games, basado en el código original de Grant Jenks.

## Objetivo

Encontrar las parejas de tarjetas iguales hasta descubrir todo el tablero. Al encontrar una pareja, sus cuadros desaparecen y revelan parte de la imagen de fondo.

## Requisitos

- Python 3.
- Turtle disponible en la instalación de Python.
- Biblioteca Free Python Games.

## Instalación y ejecución

Desde la carpeta del repositorio, crear y activar un ambiente virtual en Windows:

```bat
py -m venv .venv
.venv\Scripts\activate
python -m pip install freegames
python memory.py
```

La imagen de fondo se obtiene de los recursos incluidos en Free Python Games.

## Controles

Hacer clic sobre las tarjetas para seleccionar y comparar sus contenidos.

## Modificaciones

### Santiago Román Villalobos Bolaños

- Agregó un contador de taps dentro del tablero.
- Mostró el contador en la ventana y en la consola.
- Incorporó una validación para ignorar clics fuera del tablero.
- Implementó la detección de todas las parejas encontradas mediante `not any(hide)`.
- Agregó un mensaje de victoria.
- Detuvo el registro de taps después de completar el juego.
- Amplió la ventana para mostrar el contador y el mensaje final.

### Compañera de equipo

- Centró el contenido de las tarjetas.
- Sustituyó los números por contenido alternativo para ejercitar la memoria mediante asociaciones visuales.

## Comprobación del funcionamiento

- Hacer clic dentro del tablero y comprobar que aumente el contador.
- Hacer clic fuera del tablero y verificar que el contador no cambie.
- Encontrar parejas y comprobar que permanezcan descubiertas.
- Completar el tablero y verificar que aparezca el mensaje de victoria.
- Comprobar que el contador deje de aumentar al terminar.

## Trabajo colaborativo

Se utilizó un repositorio principal y un fork, sin acceso de colaborador. Cada integrante registró sus aportaciones mediante commits y los cambios se integraron mediante pull requests.

## Código de referencia

Grant Jenks, Free Python Games:
https://grantjenks.com/docs/freegames/memory.html
