# Dax Fit v2

PWA personal para registrar y guiar la rutina Full Body A/B.

## Novedades v2
- Ficha de técnica para cada ejercicio: propósito, pasos, claves, errores y adaptación personal.
- Dibujos vectoriales offline con posición inicial/final.
- “Máquina ocupada” ahora permite **dejar para después** o cambiar a una **alternativa de calistenia**.
- Alternativa sin máquina para cada ejercicio de la rutina (esterilla como material base).
- Botón **“Sin peso”** en ejercicios compatibles, como hip thrust/puente de glúteos.
- Los resúmenes distinguen peso corporal, alternativas y ejercicios omitidos.
- Compatible con los datos guardados por Dax Fit v1 (`localStorage` mantiene la misma clave).
- Service worker v2 elimina la caché antigua para facilitar futuras actualizaciones.

## Actualizar desde v1
1. En la app actual: **Ajustes → Exportar datos** (copia de seguridad).
2. Sustituye en GitHub los archivos de la v1 por los de esta carpeta y conserva la estructura `icons/`.
3. Haz commit y espera a que GitHub Pages publique los cambios.
4. Abre Dax Fit. Puede ser necesario cerrarla y volverla a abrir una vez para que el nuevo service worker tome el control.
5. Tus datos deberían seguir ahí porque la clave local no cambia. Si no aparecen, usa **Ajustes → Importar datos**.

> Los dibujos son esquemas orientativos. La guía principal son las instrucciones de técnica y un rango de movimiento sin dolor.
