# Dax Fit v2.1 — versión completa corregida

PWA personal para registrar y guiar la rutina Full Body A/B.

## Incluye
- Día A, Día B y día opcional.
- Registro de peso, repeticiones y dificultad percibida.
- Temporizador automático de descansos.
- Historial local y exportación/importación de datos.
- Ficha de técnica de cada ejercicio.
- Dibujos vectoriales offline con posición inicial/final.
- “Máquina ocupada” con:
  - Dejar para después.
  - Alternativa de calistenia.
- Alternativa sin máquina para cada ejercicio.
- Botón “Sin peso” para ejercicios compatibles.
- Iconos PWA incluidos en `icons/`.
- Manifest corregido para Android.
- Caché `dax-fit-v4` para forzar la actualización.
- Compatible con los datos locales de versiones anteriores.

## Cómo actualizar en GitHub
1. En Dax Fit actual: Ajustes → Exportar datos.
2. Descomprime este ZIP.
3. En tu repositorio, sustituye los archivos antiguos por TODO el contenido de esta carpeta:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `README.md`
   - carpeta `icons/` completa
4. Haz commit.
5. Espera a que GitHub Pages publique.
6. Comprueba que esta URL muestra el icono:
   `https://TU-USUARIO.github.io/TU-REPOSITORIO/icons/icon-512.png`
7. Abre después la URL normal de Dax Fit en Chrome.
8. Cierra y vuelve a abrir la PWA instalada. Si Android sigue mostrando el icono antiguo, exporta datos, desinstala la PWA y vuelve a instalarla desde Chrome.

Los datos se guardan localmente en el dispositivo. La copia exportada es la red de seguridad.
