# Para Ashanty

Un juego 3D low poly (estilo PlayStation 1) hecho para el cumpleaños de Ashanty.
Se juega en el navegador, en computadora o celular. No necesita instalar nada.

## Cómo se juega
- Computadora: moverse con **WASD** o flechas, examinar con **E** o **Espacio**.
- Celular: joystick a la izquierda y botón **A** a la derecha. Para avanzar un diálogo, tocar la pantalla.
- Recorrido: jardín, casa, habitación rosada y una sorpresa final. El código del baúl lo da el calendario de la habitación.

## Publicarlo con GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `para-ashanty`). Debe ser **público** en el plan gratuito.
2. Sube `index.html` y este `README.md` (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
4. Espera uno o dos minutos. El enlace será `https://TU-USUARIO.github.io/para-ashanty/`.

El juego carga Three.js y la fuente desde internet (cdnjs y Google Fonts), así que necesita conexión.

## Cambiar textos
Todo lo editable está al inicio del script de `index.html`, en el bloque `CONFIG`:
nombres de los regalos, el código del baúl (`code`, ahora `1010`) y el texto de la carta (`letter`).

## Ojo con la privacidad
Un repositorio público deja la carta visible en el código para quien lo busque. Si quieres que
sea sorpresa, no compartas el enlace con nadie más y usa un nombre de repositorio poco obvio.
