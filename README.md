# 100 Argentinos Dicen - El Juego

![fondo_menu2](https://github.com/user-attachments/assets/c9add263-9cf1-4ca0-9f97-977e6d0b3bcb)

¡Vení a vivir la emoción de competir en el clásico programa de preguntas y respuestas de Argentina!🌟 Sumergite en la adrenalina de adivinar qué piensa la mayoría y enfrentá preguntas que pondrán a prueba tu intuición y conocimiento. En este juego, sos el participante que debe pensar rápido y decidir con precisión. ¿Podrás alcanzar el puntaje máximo y llevarte el premio mayor? ¡Probá tu habilidad y convertite en el próximo ganador!

<div align="center">
  <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="icon" width="50" height="50" />
</div>

## Desarrollo del juego
"En este juego esta inspirado en el clásico 100 Argentinos Dicen, tu misión es adivinar las respuestas más populares de una serie de preguntas que se hicieron a 100 personas. En cada ronda, tendrás que poner a prueba tus conocimientos sobre lo que piensa la mayoría en temáticas variadas: desde cantantes hasta deportistas y aspectos culturales. Con cada respuesta correcta, vas sumando puntos, y si alcanzás los 500 puntos en cinco rondas, ¡te llevás el premio mayor de $1,000,000! ¿Tenés lo necesario para pensar como el resto y llevarte el gran premio?"

## Características

- **Selección Aleatoria de Preguntas**: El juego selecciona aleatoriamente una pregunta de una temática específica para cada ronda.
- **Respuestas de Usuarios**: Los jugadores ingresan sus respuestas utilizando el teclado.
- **Sistema de Puntuación y Oportunidades**: El jugador gana puntos basados en la popularidad de su respuesta. Tiene tres oportunidades por ronda y puede ganar oportunidades extra por cada 50 puntos acumulados.
- **Comodines**: Los jugadores pueden usar comodines como tiempo extra, mostrar la respuesta menos votada o multiplicar sus puntos.
- **Interfaz Gráfica**: El juego cuenta con una interfaz gráfica interactiva, con imágenes de fondo para el menú y las preguntas.

## Requisitos

Para ejecutar el juego, necesitas tener instalados los siguientes paquetes de Python. Puedes instalar las dependencias usando el archivo `requirements.txt`:

**pip install -r requirements.txt **

### Requisitos del Sistema

**Python 3.7 o superior**
**Pygame 2.0.0 o superior**

## Instalación

### Clona el repositorio:

**git clone https://github.com/tu_usuario/100-argentinos-dicen.git**

### Navega al directorio del proyecto:

**cd 100-argentinos-dicen**

## Instala las dependencias:

**pip install -r requirements.txt**

## Ejecuta el juego:

**python game.py**

Estructura del Proyecto

```markdown
100-argentinos-dicen/
│
├── assets/ # Imágenes y otros archivos de medios
│ ├── fondo_menu.jpg # Imagen de fondo para el menú
│ └── fondo_preguntas.jpg # Imagen de fondo para las preguntas
│
├── config.py # Configuraciones y constantes globales
├── preguntas.py # Archivo que contiene las preguntas y respuestas del juego
├── game.py # Lógica principal del juego
├── main.py # Archivo principal para ejecutar el menú y el juego
└── requirements.txt # Dependencias necesarias para ejecutar el juego
```

## Controles

**Teclado:** Ingresar la respuesta a las preguntas.
**Enter:** Confirmar la respuesta.
**Esc:** Salir del juego.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles.
