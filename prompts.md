# Historial de Prompts

## Prompt 1 

Crea el HTML básico de una página con un contenedor principal.
Dentro debe haber 2 filas y cada fila 2 grupos.
Cada grupo tiene dos figuras: un cuadrado y un círculo.
No pongas estilos todavía, solo la estructura.


---

## Prompt 2 
Luego le pedí:

Ahora crea el CSS.
El contenedor debe medir 400px x 300px.
Pon fondo azul al contenedor.
Las figuras deben medir aproximadamente 65-70px.
El círculo debe hacerse usando border-radius: 50%.
El fondo de la página debe ser oscuro.

Recuerda:
- width y height sirven para medir tamaños
- el fondo general se cambia en body
- border-radius: 50% convierte un cuadrado en círculo

---

## Prompt 3
Después:

Necesito centrar el contenedor exactamente en el medio de la pantalla
(vertical y horizontal).

Recuérdame cómo centrar algo:

height: 100vh
display: flex
justify-content: center
align-items: center

Eso centra un elemento en toda la pantalla.

---

## Prompt 4 
Luego le pedí:
Separa la fila superior de la inferior y separa cada par de figuras.

Recuérdame:
- flex-direction: column separa arriba y abajo
- justify-content: space-between empuja a los extremos
- gap separa elementos sin usar márgenes

---

## Prompt 5 
Finalmente:

Ajusta los espacios internos para que las figuras no queden pegadas al borde.

Recuérdame:
padding = espacio dentro del contenedor  
margin = mueve el elemento completo