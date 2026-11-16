# Portafolio — José Armando Brito Realpe

Portafolio académico y personal de José Armando Brito Realpe, estudiante de **Ingeniería Civil** y de una **subespecialización en Ciencias de la Computación**.

## Sitio web

El portafolio está construido como una página estática de una sola página con **HTML, CSS y JavaScript**, sin frameworks ni procesos de compilación. El diseño usa una estética urbana inspirada en pósters y cultura musical: fondo oscuro, acentos fucsia, violeta y verde ácido, tipografía de gran formato y detalles gráficos. Es adaptable a pantallas móviles.

**Publicación prevista con GitHub Pages:** https://nexiqu.github.io/portafolio/

Para activarla, abre **Settings → Pages** en este repositorio, selecciona **Deploy from a branch**, elige la rama `main` y la carpeta `/(root)`, y guarda. Después GitHub Pages publicará el archivo `index.html`.

## Sobre mí e intereses

Me interesa seguir aprendiendo sobre mi carrera, descubrir cómo se crean los videojuegos y probar nuevas herramientas.

- **Música — Young Miko:** me gusta su música, su propuesta y su identidad visual.
- **Videojuegos:** me interesa conocer sus mecánicas y cómo se construyen experiencias interactivas.
- **Automovilismo:** me atraen la velocidad, la estrategia y la tecnología del motorsport.

## Proyectos

### Proyecto 1 — Control de Tráfico

Juego de gestión de tráfico en el que el jugador coordina los semáforos para mantener el flujo vehicular, evitar congestión y prevenir colisiones. El segundo nivel conecta dos intersecciones que se controlan por separado.

- **Versión publicada:** https://nexiqu.github.io/proyecto1/
- **Repositorio:** https://github.com/nexiqu/proyecto1
- **Tecnologías:** HTML, CSS y JavaScript.
- **Publicación y ejecución:** GitHub Pages sirve los archivos estáticos; la lógica del juego corre en el navegador.
- **Datos:** no usa base de datos. La partida y la mejor puntuación se mantienen durante la sesión y pueden reiniciarse al recargar.

### Proyecto 2 — City Caos

Juego multijugador en el que varias personas construyen y modifican una ciudad compartida de 12 × 12 casillas.

- **Versión publicada:** https://proyecto22-gamma.vercel.app/
- **Repositorio:** https://github.com/nexiqu/Proyecto2
- **Tecnologías:** HTML, CSS, JavaScript y Vite.
- **Publicación y ejecución:** Vercel publica la aplicación; la lógica de `app.js` corre en el navegador y se comunica con Supabase mediante su API REST.
- **Datos:** Supabase Authentication gestiona el inicio de sesión. La tabla `city_tiles` guarda objetos por sala y casilla; `city_presence` registra jugadores presentes.
- **Sincronización:** el mapa se consulta aproximadamente cada 800 ms y la lista de jugadores cada 3 segundos. Esta versión usa consultas periódicas, no Supabase Realtime ni WebSockets.

## Sobre el diseño

Elegí una estética urbana con fondo oscuro, acentos fucsia, violeta y verde ácido, tipografía grande y gráficos inspirados en pósters y stickers. Quería conectar la energía de la música que me gusta con los mundos interactivos que me interesa crear, sin quitar protagonismo a los proyectos.

---

*Portafolio en desarrollo continuo.*
