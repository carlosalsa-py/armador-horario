# Armador de horario

Aplicación web para armar el horario universitario del semestre. Muestra las materias con sus secciones y bloques de clase en una grilla semanal, y ayuda a encontrar combinaciones de secciones que no choquen entre sí.

Es un único archivo (`index.html`) sin dependencias ni servidor: funciona en cualquier navegador, en computadora o teléfono.

**Abrir la app:** _URL pendiente_

## Cómo usarla

1. **Elegir secciones.** Marca «Inscribir» en las materias que vas a cursar y selecciona una sección de cada una. El horario se dibuja en la grilla a medida que eliges.
2. **Buscar combinaciones sin choque.** Pulsa «Buscar combinaciones sin choque» para ver todas las combinaciones de secciones compatibles. Recórrelas con «Anterior» y «Siguiente» y pulsa «Usar esta combinación» para aplicarla.
3. **Editar materias.** Con «Editar materias» puedes agregar o eliminar materias, secciones y bloques de horario. Pulsa «Guardar cambios» al terminar, o «Restaurar datos originales» para volver al estado inicial.

## Tus datos

Todo se guarda **solo en el navegador de cada usuario** (localStorage). No hay servidor ni cuentas: nadie más ve tu horario, y si cambias de navegador o de dispositivo, o borras los datos del sitio, empiezas de cero.

Para pasar tu horario a otro dispositivo, usa «Editar materias» y luego «Respaldo (texto)»: copia el texto en un dispositivo y cárgalo con «Cargar texto» en el otro.
